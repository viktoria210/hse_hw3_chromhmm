# hse_hw3_chromhmm
Решение задачи сегментации генома человека посредством запуска ChromHMM и анализа выдачи программы. . 

## Ссылка на google colab ноутбук
Ссылка 

## Список 10-ти гистоновых меток
Для анализа была выбрана клеточная линия **A549** (вместо **MCF-7**, для которой не нашлись необходимые *.bam* файлы )

*Контрольный эксперимент(файл)*: wgEncodeBroadHistoneA549ControlDex100nmAlnRep1.bam 

*Название после скачивания*: Control.bam

|Гистоновая метка|Файл с гистоновой меткой                            |Название .bam файла (После скачивания)|
|:---------------|:---------------------------------------------------|:-------------------------------------|
|H4k20me1        |wgEncodeBroadHistoneA549H4k20me1Etoh02AlnRep1.bam   |H4k20me1.bam                          |
|H3k79me2        |wgEncodeBroadHistoneA549H3k79me2Dex100nmAlnRep1.bam |H3k79me2.bam                          |
|H3k36me3        |wgEncodeBroadHistoneA549H4k20me1Etoh02AlnRep1.bam   |H3k36me3.bam                          |
|H3k27me3        |wgEncodeBroadHistoneA549H3k27me3Dex100nmAlnRep1.bam |H3k27me3.bam                          |
|H3k27ac         |wgEncodeBroadHistoneA549H3k27acDex100nmAlnRep1.bam  |H3k27ac.bam                           |
|H3k9me3         |wgEncodeBroadHistoneA549H3k09acEtoh02AlnRep1.bam    |H3k9me3.bam                           |
|H3k4me3         |wgEncodeBroadHistoneA549H3k04me3Dex100nmAlnRep1.bam |H3k4me3.bam                           |
|H3k4me2         |wgEncodeBroadHistoneA549H3k04me2Dex100nmAlnRep1.bam |H3k4me2.bam                           |
|H3k4me1         |wgEncodeBroadHistoneA549H3k04me1Dex100nmAlnRep1.bam |H3k4me1.bam                           |
|Ctcf            |wgEncodeBroadHistoneA549CtcfDex100nmAlnRep1.bam     |Ctcf.bam                              |

## cellmarkfiletable.txt
|Клеточная линия| Гистоновая метка | Файл с гистоновой меткой| Файл с контролем|
|:--|:----------|:------------|:------------|
|A549|	H4k20me1|	H4k20me1.bam|	Control.bam|
|A549|	H3k79me2|	H3k79me2.bam|	Control.bam|
|A549|	H3k36me3|	H3k36me3.bam|	Control.bam|
|A549|	H3k27me3|	H3k27me3.bam|	Control.bam|
|A549|	H3k27ac|	H3k27ac.bam|	Control.bam|
|A549|	H3k9me3|	H3k9me3.bam|	Control.bam|
|A549|	H3k4me3|	H3k4me3.bam|	Control.bam|
|A549|	H3k4me2|	H3k4me2.bam|	Control.bam|
|A549|	H3k4me1|	H3k4me1.bam|	Control.bam|
|A549|	Ctcf|	Ctcf.bam|	Control.bam|

## Картинки из выдачи ChromHMM

![Emission_Parameters](https://user-images.githubusercontent.com/60792064/161400551-c95b828a-dab0-4172-a2fd-26b15e7f4fde.png)

![Transition_Parameters](https://user-images.githubusercontent.com/60792064/161400557-35a9a9b7-c546-4f45-a6ac-8f582d5e4f98.png)

![Overlap](https://user-images.githubusercontent.com/60792064/161400561-b7e86bc9-8300-4ada-b86e-b8f73a097a94.png)

![RefSeqTSS](https://user-images.githubusercontent.com/60792064/161400565-abd9e9d8-b341-4278-bc96-1a6d2a436a2e.png)

![RefSeqTES](https://user-images.githubusercontent.com/60792064/161400575-144dc141-f333-484b-b538-8bf597971a76.png)

## Картинки из браузера

![Br_1](https://user-images.githubusercontent.com/60792064/161401769-6ba4ea35-484e-4139-b228-abc550f922dd.png)

![Br_2](https://user-images.githubusercontent.com/60792064/161401773-d3240f5d-3252-465f-be56-4b1b8e0aec7a.png)

![Br_3](https://user-images.githubusercontent.com/60792064/161401778-5d4c5a62-b5d4-43c3-bfd9-b15e1a4bbe43.png)

## Бонусное задание: 

Файл с добавленной аннотацией: *"A549_10_dense_new.bed"*

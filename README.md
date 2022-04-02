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

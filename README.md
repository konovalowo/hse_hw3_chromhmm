# hse_hw3_chromhmm

код: https://colab.research.google.com/drive/1LrLHZmcCRAiZx_rxL-4vLcDnHFACFH0t?usp=sharing

## Таблица гистоновых меток 
| Гистоновая метка | Имя файла                                      |
|------------------|------------------------------------------------|
| H2AFZ            | wgEncodeBroadHistoneNhlfH2azAlnRep1.bam        |
| H3K27ac          | wgEncodeBroadHistoneNhlfH3k27acStdAlnRep1.bam  |
| H3K27me3         | wgEncodeBroadHistoneNhlfH3k27me3StdAlnRep1.bam |
| H3K36me3         | wgEncodeBroadHistoneNhlfH3k36me3StdAlnRep1.bam |
| H3K4me1          | wgEncodeBroadHistoneNhlfH3k4me1StdAlnRep1.bam  |
| H3K4me2          | wgEncodeBroadHistoneNhlfH3k4me2StdAlnRep1.bam  |
| H3K4me3          | wgEncodeBroadHistoneNhlfH3k4me3StdAlnRep1.bam  |
| H3K79me2         | wgEncodeBroadHistoneNhlfH3k79me2AlnRep1.bam    |
| H3K9ac           | wgEncodeBroadHistoneNhlfH3k9acStdAlnRep1.bam   |
| H3K9me3          | wgEncodeBroadHistoneNhlfH3k09me3AlnRep1.bam    |

## ChromHMM
![image](https://user-images.githubusercontent.com/20297250/160242703-383df96b-feaa-4bca-9a36-57e0a5bff698.png)

![image](https://user-images.githubusercontent.com/20297250/160242707-7032c99c-c3c5-4d15-a16d-ba30715ae3c7.png)

![image](https://user-images.githubusercontent.com/20297250/160242715-349d3d1b-ece0-4cfe-bb3f-fcf15683d5eb.png)

![image](https://user-images.githubusercontent.com/20297250/160242719-a52771ed-bf36-4ad0-9bbd-e1c91ecf5b5e.png)

![image](https://user-images.githubusercontent.com/20297250/160242722-3fde0ae3-7cda-4ae4-8ddd-a9de35ffba94.png)


## Эпигенетические типы
| #  | название        | описание                                                                                            |
|----|-----------------|-----------------------------------------------------------------------------------------------------|
| 1  | heterochromatin | Активность в H3K27me3                                                                               |
| 2  | heterochromatin | Ассоциируется с % genome и Lamina                                                                   |
| 3  | heterochromatin | Активность в H3K9me3                                                                                |
| 4  | enchancer       | Находится в участках транскрипции                                                                   |
| 5  | transcribed     | Ассоциируется с RefSeqGene, активен в H3K79m2                                                       |
| 6  | transcribed     | Ассоциируется с RefSeqGene                                                                          |
| 7  | promoter        | Ассоциируется с RefSeqTSS, RefSeqTSS2kb, CpGIsland. Располагается в начале генов, активен в H3K4me3 |
| 8  | promoter        | Ассоциируется с RefSeqTSS, RefSeqTSS2kb, CpGIsland. Активен в H3K4me3                               |
| 9  | heterochromatin | Ассоциируется с % genome и Lamina                                                                   |
| 10 | enchancer       | Активен в H3K4me1                                                                                   |

## UCSC GenomeBrowser

Тип 3:

<img width="422" alt="3" src="https://user-images.githubusercontent.com/20297250/160242850-c317c1c8-8c8a-4a7b-b316-e90a10ba040c.png">

Тип 5:

<img width="780" alt="5" src="https://user-images.githubusercontent.com/20297250/160242862-e2921058-9a94-45f8-8da6-33852e3e36ed.png">

Тип 7:

<img width="367" alt="7" src="https://user-images.githubusercontent.com/20297250/160242878-578b75d3-b340-44eb-a134-d498a66a9f93.png">

Тип 8:

<img width="473" alt="8" src="https://user-images.githubusercontent.com/20297250/160242884-bbc4dbf4-ddc6-40e2-b713-185604b215fd.png">

Тип 10:

<img width="530" alt="10" src="https://user-images.githubusercontent.com/20297250/160242897-6a9a2ace-d79d-4805-bbdc-68d951865877.png">

## Список запущенных команд
Есть ссылка на колаб сверху.

## Бонус
Реализация замены номеров типов на названия есть в колабе.

Результат:

![image](https://user-images.githubusercontent.com/20297250/160244868-be056c44-c9e6-4143-9f1f-6de0870fb799.png)


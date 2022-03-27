# Домашнее задание 2.3 по БиоИнформатике (2 год)

![Colab тетрадка](https://colab.research.google.com/drive/1MswHuv45z_HzwXJzdwDs1ZU4T3NSL61p?usp=sharing)

## Информация о данных 

Клеточная линия | Имя при обработке | Гистоновая метка | Файл с гистоновой меткой  
--- | --- | --- | ---
A549 | H3K04me2.bam | H3K4me2   | wgEncodeBroadHistoneA549H3k04me2Dex100nmAlnRep1.bam 
A549 | H3K79me2.bam | H3K79me2  | wgEncodeBroadHistoneA549H3k79me2Dex100nmAlnRep1.bam 
A549 | H3K36me3.bam | H3K36me3  | wgEncodeBroadHistoneA549H3k36me3Dex100nmAlnRep1.bam
A549 | H4K20me1.bam | H4K20me1  | wgEncodeBroadHistoneA549H4k20me1Etoh02AlnRep1.bam
A549 | H3K09me3.bam | H3K9me    | wgEncodeBroadHistoneA549H3k09me3Etoh02AlnRep1.bam
A549 | H3K04me1.bam | H3K4me1   | wgEncodeBroadHistoneA549H3k04me1Dex100nmAlnRep1.bam
A549 | H3K27ac.bam  | H3K27ac   | wgEncodeBroadHistoneA549H3k27acDex100nmAlnRep1.bam
A549 | H3K09ac.bam  | H3K9ac    | wgEncodeBroadHistoneA549H3k09acEtoh02AlnRep1.bam
A549 | H3K04me3.bam | H3K4me3   | wgEncodeBroadHistoneA549H3k04me3Dex100nmAlnRep1.bam
A549 | H3K27me3.bam | H3K27me3  | wgEncodeBroadHistoneA549H3k27me3Dex100nmAlnRep1.bam

## ChromHMM

### RefSeqTSS
![](/data/A549_10_RefSeqTSS_neighborhood.png)

### RefSeqTES
![](/data/A549_10_RefSeqTES_neighborhood.png)

### Emission
![](/data/emissions_10.png)

### Overlap
![](/data/A549_10_overlap.png)

### Transition
![](/data/transitions_10.png)

## Гистоновые модификации

По этим графикам для каждого из типов можно предположить характерную гистоновую модификацию

![](/data/graph.png)

![](/data/graph2.png)

![](/data/graph3.png)

## Список команд см. в colab

## Бонус см. в colab

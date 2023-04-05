# hse_hw3_chromhmm

## Colab
[colab](https://colab.research.google.com/drive/1GdsVmVo6jLau76amKugonuoXS5fLi9W3?usp=sharing)

## Гистоновые Метки
Name | File
--- | ---
H3K4me2 | wgEncodeBroadHistoneA549H3k04me2Dex100nmAlnRep1.bam
H3K79me2 | wgEncodeBroadHistoneA549H3k79me2Dex100nmAlnRep1.bam
H3K36me3 | wgEncodeBroadHistoneA549H3k36me3Dex100nmAlnRep1.bam
H4K20me1 | wgEncodeBroadHistoneA549H4k20me1Etoh02AlnRep1.bam
H3K9me3 | wgEncodeBroadHistoneA549H3k09me3Etoh02AlnRep1.bam
H3K4me1 | wgEncodeBroadHistoneA549H3k04me1Dex100nmAlnRep1.bam
H3K27ac | wgEncodeBroadHistoneA549H3k27acDex100nmAlnRep1.bam
H3K9ac | wgEncodeBroadHistoneA549H3k09acEtoh02AlnRep1.bam
H3K4me3 | wgEncodeBroadHistoneA549H3k04me3Dex100nmAlnRep1.bam
H3K27me3 | wgEncodeBroadHistoneA549H3k27me3Dex100nmAlnRep1.bam


## cellmarkfiletable.txt

Клеточная линия | Гистоновая метка | Файл с гистоновой меткой | Файл с контролем
--- | --- | --- | ---
A549 | H3K4me2 | H3K4me2.bam | Control.bam
A549 | H3K79me2 | H3K79me2.bam | Control.bam
A549 | H3K36me3 | H3K36me3.bam | Control.bam
A549 | H4K20me1 | H4K20me1.bam | Control.bam
A549 | H3K9me | H3K9me.bam | Control.bam
A549 | H3K4me1 | H3K4me1.bam | Control.bam
A549 | H3K27ac | H3K27ac.bam | Control.bam
A549 | H3K9ac | H3K9ac.bam | Control.bam
A549 | H3K4me3 | H3K4me3.bam | Control.bam
A549 | H3K27me3 | H3K27me3.bam | Control.bam

## Папка с выдачей ChromHMM
[папка](https://github.com/dpaleyev/hse_hw3_chromhmm/tree/main/%20ChromHMM)

## ChromHMM
### Emission
![Image](/%20ChromHMM/emissions_15.png)
### Transition
![Image](/%20ChromHMM/transitions_15.png)
### Overlap
![Image](/%20ChromHMM/A549_15_overlap.png)
### RefSeqTSS
![Image](/%20ChromHMM/A549_15_RefSeqTSS_neighborhood.png)
### RefSeqTES
![Image](/%20ChromHMM/A549_15_RefSeqTES_neighborhood.png)

## Эпигенетические типы

### Active Promoter 
![Image](/GenomeBrowser/state_1.png)
Выражен в H3K27me3, H3K4me3, H3K4me2. Попадает на интрон или экзон.
### Weak enhancer/Weak transcribed 
![Image](/GenomeBrowser/state_2.png)
Выражен в H3K4me2, H3K4me1. Попадает на интрон. 
### Strong enhancer/Transcriptional elogation 
![Image](/GenomeBrowser/state_3.png)
Выражен в H3K9ac, H3K27ac, H3K4me3, H3K4me2, H3K4me1. Попадает на интрон. 
### Active Promoter 
![Image](/GenomeBrowser/state_4.png)
Выражен в H3K9ac, H3K27ac, H3K4me3, H3K4me2. Попадает на интрон или экзон. 
### Active Promoter 
![Image](/GenomeBrowser/state_5.png)
Выражен в H3K9ac, H3K27ac, H3K4me3, H3K4me2. Попадает на интрон или экзон.
### Weak enhancer 
![Image](/GenomeBrowser/state_6.png)
Выражен в H3K79me2, H3K9ac, H3K27ac, H3K4me3, H3K4me2. Попадает на интрон.
### Weak enhancer
![Image](/GenomeBrowser/state_7.png)
Выражен в H3K9ac, H3K27ac, H3K4me1. Попадает на интрон.
### Weak enhancer 
![Image](/GenomeBrowser/state_8.png)
Выражен в H3K4me1. Попадает на интрон. 
### Weak enhancer 
![Image](/GenomeBrowser/state_9.png)
Выражен в H3K79me2, H3K4me1. Попадает на интрон.
### Weak transcribed 
![Image](/GenomeBrowser/state_10.png)
Выражен в H3K79me2. Попадает на экзон или интрон. 
### Weak transcribed
![Image](/GenomeBrowser/state_11.png)
Выражен в H3K36me3, H3K79me2. Попадает на экзон или интрон. 
### Weak transcribed 
![Image](/GenomeBrowser/state_12.png)
Выражен в H3K36me3. Попадает на экзон или интрон.
### Repressed 
![Image](/GenomeBrowser/state_13.png)
Не попадает на ген.
### Heterochromatin 
![Image](/GenomeBrowser/state_14.png)
Выражен в H3K27me3. Не попадает на ген. 
### Heterochromatin 
![Image](/GenomeBrowser/state_15.png)
Выражен в H3K9me3. Не попадает на ген. 








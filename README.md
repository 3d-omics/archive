# 3D'omics archive
Repository logging archiving of 3D'omics data.

## 15-12-2025

### MSEB0042_MSEB0045 (ongoing)

```{sh}
screen -S MSEB0042_MSEB0045
conda activate arch3d
cd MSEB0042_MSEB0045
arch3d microsample -m MSEB0042_MSEB0045.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### MSEB0046_MSEB0053 (ongoing)

```{sh}
screen -S MSEB0046_MSEB0053
conda activate arch3d
cd MSEB0046_MSEB0053
arch3d microsample -m MSEB0046_MSEB0053.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

## 10-12-2025

### MSEB0016_MSEB0023

```{sh}
screen -S MSEB0016_MSEB0023
conda activate arch3d
cd MSEB0016_MSEB0023
arch3d microsample -m MSEB0016_MSEB0023.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### MSEB0024_MSEB0031

```{sh}
screen -S MSEB0024_MSEB0031
conda activate arch3d
cd MSEB0024_MSEB0031
arch3d microsample -m MSEB0024_MSEB0031.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### MSEB0034_MSEB0041

```{sh}
screen -S MSEB0034_MSEB0041
conda activate arch3d
cd MSEB0034_MSEB0041
arch3d microsample -m MSEB0034_MSEB0041.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

## 09-12-2025

### MSEB0032_MSEB0033

```{sh}
screen -S MSEB0032_33
conda activate arch3d
cd MSEB0032_33
arch3d microsample -m MSEB0032_33.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

## 27-11-2025

### M_MG

```{sh}
screen -S M_MG
conda activate arch3d
cd M_MG
arch3d macrosample -m M_MG.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### H_MG

```{sh}
screen -S H_MG
conda activate arch3d
cd H_MG
arch3d macrosample -m M_MG.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

## 17-11-2025

### F_MG

```{sh}
screen -S F_MG
conda activate arch3d
cd F_MG
arch3d macrosample -m F_MG.csv -d input -o output -u 'Webin-69627' -p '{password}'
```


### K_MG

```{sh}
screen -S K_MG
conda activate arch3d
cd K_MG
arch3d macrosample -m K_MG.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### I_MG

```{sh}
screen -S I_MG
conda activate arch3d
cd I_MG
arch3d macrosample -m I_MG.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

## 14-11-2025

### J_MG

```{sh}
screen -S J_MG
conda activate arch3d
cd J_MG
arch3d macrosample -m J_MG.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### J_MT

```{sh}
screen -S J_MT
conda activate arch3d
cd J_MT
arch3d macrosample -m J_MT.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### J_HT

```{sh}
screen -S J_HT
conda activate arch3d
cd J_HT
arch3d macrosample -m J_HT.csv -d input -o output -u 'Webin-69627' -p '{password}'
```



## 14-11-2025

### MSEB0027

#### G081bI105B, G082bI105B

```{sh}

lmdmap -n G081bI105B \
        -i archive/G081bI105_post.jpg \
        -t archive/G081bI105B/G081bI105B.csv \
        -o archive/G081bI105B/G081bI105B.jpg \
        -m archive/G081bI105B/G081bI105B_marked.jpg

lmdmap -n G081bI105B \
        -s 800 -x -20 -y 5 -d M302722 \
        -i archive/G081bI105_post.jpg \
        -t archive/G081bI105B/G081bI105B.csv \
        -o archive/G081bI105B/G081bI105B.jpg \
        -m archive/G081bI105B/G081bI105B_marked.jpg

lmdmap -n G081bI105B \
        -s 800 -x -20 -y 5 -d M302722 -a \
        -i archive/G081bI105_pre.jpg \
        -t archive/G081bI105B/G081bI105B.csv \
        -o archive/G081bI105B/G081bI105B.jpg \
        -m archive/G081bI105B/G081bI105B_marked.jpg
```

> [!WARNING]
> JGL: Poor point-to-cut coverages, most does not align. Excluded M302722: incorrect coordinate (out of bounce)

#### G082bI105B

```{sh}
lmdmap -n G082bI105B \
        -i archive/G082bI105_post.jpg \
        -t archive/G082bI105B/G082bI105B.csv \
        -o archive/G082bI105B/G082bI105B.jpg \
        -m archive/G082bI105B/G082bI105B_marked.jpg

lmdmap -n G082bI105B \
        -s 1000 -x -22 -w 10 -y -32 -l -4 -d M302770\
        -i archive/G082bI105_post.jpg \
        -t archive/G082bI105B/G082bI105B.csv \
        -o archive/G082bI105B/G082bI105B.jpg \
        -m archive/G082bI105B/G082bI105B_marked.jpg

lmdmap -n G082bI105B \
        -s 1000 -x -22 -w 10 -y -32 -l -4 -d M302770 -a \
        -i archive/G082bI105_pre.jpg \
        -t archive/G082bI105B/G082bI105B.csv \
        -o archive/G082bI105B/G082bI105B.jpg \
        -m archive/G082bI105B/G082bI105B_marked.jpg

```

> [!WARNING]
> JGL: Poor point-to-cut coverages given resolution. Excluded M302770: incorrect coordinate (out of bounce)






## 29-10-2025

### MSEB0044 + MSEB0045

#### M003aI101A

```{sh}
lmdmap -n M003aI101A \
        -i archive/M003aI101_post.jpg \
        -t archive/M003aI101A/M003aI101A.csv \
        -o archive/M003aI101A/M003aI101A.jpg \
        -m archive/M003aI101A/M003aI101A_marked.jpg

lmdmap -n M003aI101A \
        -x -70 -w 9 -y -3\
        -i archive/M003aI101_post.jpg \
        -t archive/M003aI101A/M003aI101A.csv \
        -o archive/M003aI101A/M003aI101A.jpg \
        -m archive/M003aI101A/M003aI101A_marked.jpg

lmdmap -n M003aI101A \
        -x -70 -w 9 -y -3 -a\
        -i archive/M003aI101_pre.jpg \
        -t archive/M003aI101A/M003aI101A.csv \
        -o archive/M003aI101A/M003aI101A.jpg \
        -m archive/M003aI101A/M003aI101A_marked.jpg
```

> [!NOTE]
> JGL:  Good point-to-cut matches - All good.

#### M061aH101A 

```{sh}
lmdmap -n M061aH101A \
        -i archive/M061aH101_post.jpg \
        -t archive/M061aH101A/M061aH101A.csv \
        -o archive/M061aH101A/M061aH101A.jpg \
        -m archive/M061aH101A/M061aH101A_marked.jpg

lmdmap -n M061aH101A \
        -x -150 -w 40 -y -5 -d M304525,M304510\
        -i archive/M061aH101_post.jpg \
        -t archive/M061aH101A/M061aH101A.csv \
        -o archive/M061aH101A/M061aH101A.jpg \
        -m archive/M061aH101A/M061aH101A_marked.jpg

lmdmap -n M061aH101A \
        -x -150 -w 40 -y -5 -d M304525,M304510 -a\
        -i archive/M061aH101_pre.jpg \
        -t archive/M061aH101A/M061aH101A.csv \
        -o archive/M061aH101A/M061aH101A.jpg \
        -m archive/M061aH101A/M061aH101A_marked.jpg

```

> [!CAUTION]
> JGL:  M304525,M304510 excluded: Incorrect coordinate (memebrane control). Very poor point-to-cut match, many coordinate points far off potential cuts, a lot (more than 20) points do not have a close match in vicininity.


### MSEB0042 + MSEB0043

#### M021aI101C 

```{sh}
lmdmap -n M021aI101C \
        -i archive/M021aI101_post.jpg \
        -t archive/M021aI101C/M021aI101C.csv \
        -o archive/M021aI101C/M021aI101C.jpg \
        -m archive/M021aI101C/M021aI101C_marked.jpg

lmdmap -n M021aI101C \
        -x -95 \
        -i archive/M021aI101_post.jpg \
        -t archive/M021aI101C/M021aI101C.csv \
        -o archive/M021aI101C/M021aI101C.jpg \
        -m archive/M021aI101C/M021aI101C_marked.jpg

lmdmap -n M021aI101C \
        -x -95 -a \
        -i archive/M021aI101_pre.jpg \
        -t archive/M021aI101C/M021aI101C.csv \
        -o archive/M021aI101C/M021aI101C.jpg \
        -m archive/M021aI101C/M021aI101C_marked.jpg

```

> [!NOTE]
> JGL: Good point-to-cut match - all good.


#### M042aI101A

```{sh}
lmdmap -n M042aI101A \
        -i archive/M042aI101_post.jpg \
        -t archive/M042aI101A/M042aI101A.csv \
        -o archive/M042aI101A/M042aI101A.jpg \
        -m archive/M042aI101A/M042aI101A_marked.jpg

lmdmap -n M042aI101A \
        -x -95 -w 5 -d M304335 \
        -i archive/M042aI101_post.jpg \
        -t archive/M042aI101A/M042aI101A.csv \
        -o archive/M042aI101A/M042aI101A.jpg \
        -m archive/M042aI101A/M042aI101A_marked.jpg

lmdmap -n M042aI101A \
        -x -95 -w 5 -d M304335 -a \
        -i archive/M042aI101_pre.jpg \
        -t archive/M042aI101A/M042aI101A.csv \
        -o archive/M042aI101A/M042aI101A.jpg \
        -m archive/M042aI101A/M042aI101A_marked.jpg

```

> [!CAUTION]
> JGL:  M304335 excluded: Incorrect coordinate (memebrane control). Good point-to-cut match - all good.



### MSEB0040

#### J018eD104A 

```{sh}
lmdmap -n J018eD104A \
        -i archive/J018eD104_post.jpg \
        -t archive/J018eD104A/J018eD104A.csv \
        -o archive/J018eD104A/J018eD104A.jpg \
        -m archive/J018eD104A/J018eD104A_marked.jpg

lmdmap -n J018eD104A \
        -s 1500 -x -20 -w 5\
        -i archive/J018eD104_post.jpg \
        -t archive/J018eD104A/J018eD104A.csv \
        -o archive/J018eD104A/J018eD104A.jpg \
        -m archive/J018eD104A/J018eD104A_marked.jpg

lmdmap -n J018eD104A \
        -s 1500 -x -20 -w 5 -a\
        -i archive/J018eD104_pre.jpg \
        -t archive/J018eD104A/J018eD104A.csv \
        -o archive/J018eD104A/J018eD104A.jpg \
        -m archive/J018eD104A/J018eD104A_marked.jpg
```

> [!Note]
> JGL: Good point-to-cut match - all good.




### MSEB0041


#### J018eD104B

```{sh}
lmdmap -n J018eD104B \
        -i archive/J018eD104_post.jpg \
        -t archive/J018eD104B/J018eD104B.csv \
        -o archive/J018eD104B/J018eD104B.jpg \
        -m archive/J018eD104B/J018eD104B_marked.jpg

lmdmap -n J018eD104B \
        -s 1400 -x -25 -w 4\
        -i archive/J018eD104_post.jpg \
        -t archive/J018eD104B/J018eD104B.csv \
        -o archive/J018eD104B/J018eD104B.jpg \
        -m archive/J018eD104B/J018eD104B_marked.jpg

lmdmap -n J018eD104B \
        -s 1400 -x -25 -w 4 -a \
        -i archive/J018eD104_pre.jpg \
        -t archive/J018eD104B/J018eD104B.csv \
        -o archive/J018eD104B/J018eD104B.jpg \
        -m archive/J018eD104B/J018eD104B_marked.jpg

```

> [!WARNING]
> JGL: Okay point-to-cut match - some of them inconsistent off-center i arbitrary directions. The section is weirdly stitch together, which some bigger disparities between frames. 


#### J020eD104A

```{sh}
lmdmap -n J020eD104A \
        -i archive/J020eD104_post.jpg \
        -t archive/J020eD104A/J020eD104A.csv \
        -o archive/J020eD104A/J020eD104A.jpg \
        -m archive/J020eD104A/J020eD104A_marked.jpg

lmdmap -n J020eD104A \
        -x -50 -y -10 \
        -i archive/J020eD104_post.jpg \
        -t archive/J020eD104A/J020eD104A.csv \
        -o archive/J020eD104A/J020eD104A.jpg \
        -m archive/J020eD104A/J020eD104A_marked.jpg

lmdmap -n J020eD104A \
        -x -50 -y -10 -a \
        -i archive/J020eD104_pre.jpg \
        -t archive/J020eD104A/J020eD104A.csv \
        -o archive/J020eD104A/J020eD104A.jpg \
        -m archive/J020eD104A/J020eD104A_marked.jpg

```

> [!WARNING]
> JGL: Not great point-to-cut coverages. Best case found, but many misalignments.


### MSEB0039

#### J020eD104B

```{sh}
lmdmap -n J020eD104B \
        -i archive/J020eD104_post.jpg \
        -t archive/J020eD104B/J020eD104B.csv \
        -o archive/J020eD104B/J020eD104B.jpg \
        -m archive/J020eD104B/J020eD104B_marked.jpg

lmdmap -n J020eD104B \
        -x -30 -w 5\
        -i archive/J020eD104_post.jpg \
        -t archive/J020eD104B/J020eD104B.csv \
        -o archive/J020eD104B/J020eD104B.jpg \
        -m archive/J020eD104B/J020eD104B_marked.jpg

lmdmap -n J020eD104B \
        -x -30 -w 5 -a \
        -i archive/J020eD104_pre.jpg \
        -t archive/J020eD104B/J020eD104B.csv \
        -o archive/J020eD104B/J020eD104B.jpg \
        -m archive/J020eD104B/J020eD104B_marked.jpg

```

> [!WARNING]
> JGL: Not great point-to-cut coverages. Best case found, but many misalignments.



## 04-11-2025

### MSEB0034

#### J010eD104A

```{sh}
lmdmap -n J010eD104A \
        -i archive/J010eD104_post.jpg \
        -t archive/J010eD104A/J010eD104A.csv \
        -o archive/J010eD104A/J010eD104A.jpg \
        -m archive/J010eD104A/J010eD104A_marked.jpg

lmdmap -n J010eD104A \
        -x -57 -w 5 \
        -i archive/J010eD104_post.jpg \
        -t archive/J010eD104A/J010eD104A.csv \
        -o archive/J010eD104A/J010eD104A.jpg \
        -m archive/J010eD104A/J010eD104A_marked.jpg

lmdmap -n J010eD104A \
        -x -57 -w 5 -a \
        -i archive/J010eD104_pre.jpg \
        -t archive/J010eD104A/J010eD104A.csv \
        -o archive/J010eD104A/J010eD104A.jpg \
        -m archive/J010eD104A/J010eD104A_marked.jpg

```

> [!NOTE]
> JGL: Good point-to-cut coverages. All good.


#### J005eD104A

```{sh}
lmdmap -n J005eD104A \
        -i archive/J005eD104_post.jpg \
        -t archive/J005eD104A/J005eD104A.csv \
        -o archive/J005eD104A/J005eD104A.jpg \
        -m archive/J005eD104A/J005eD104A_marked.jpg

lmdmap -n J005eD104A \
        -s 1500 -x -22 -w 7 \
        -i archive/J005eD104_post.jpg \
        -t archive/J005eD104A/J005eD104A.csv \
        -o archive/J005eD104A/J005eD104A.jpg \
        -m archive/J005eD104A/J005eD104A_marked.jpg

lmdmap -n J005eD104A \
        -s 1500 -x -22 -w 7 -a \
        -i archive/J005eD104_pre.jpg \
        -t archive/J005eD104A/J005eD104A.csv \
        -o archive/J005eD104A/J005eD104A.jpg \
        -m archive/J005eD104A/J005eD104A_marked.jpg

```

> [!NOTE]
> JGL: Good point-to-cut coverages. All good. 



### MSEB0035

#### J010eD104B

```{sh}
lmdmap -n J010eD104B \
        -i archive/J010eD104_post.jpg \
        -t archive/J010eD104B/J010eD104B.csv \
        -o archive/J010eD104B/J010eD104B.jpg \
        -m archive/J010eD104B/J010eD104B_marked.jpg

lmdmap -n J010eD104B \
        -s 1100 -x -32 -w 7 -d M303490 \
        -i archive/J010eD104_post.jpg \
        -t archive/J010eD104B/J010eD104B.csv \
        -o archive/J010eD104B/J010eD104B.jpg \
        -m archive/J010eD104B/J010eD104B_marked.jpg

lmdmap -n J010eD104B \
        -s 1100 -x -32 -w 7 -d M303490 -a \
        -i archive/J010eD104_pre.jpg \
        -t archive/J010eD104B/J010eD104B.csv \
        -o archive/J010eD104B/J010eD104B.jpg \
        -m archive/J010eD104B/J010eD104B_marked.jpg
```

> [!NOTE]
> JGL: Good point-to-cut coverages. All good. M303490 Excluded: incorrect coordinate (membrane control)



#### J005eD104B

```{sh}
lmdmap -n J005eD104B \
        -i archive/J005eD104_post.jpg \
        -t archive/J005eD104B/J005eD104B.csv \
        -o archive/J005eD104B/J005eD104B.jpg \
        -m archive/J005eD104B/J005eD104B_marked.jpg

lmdmap -n J005eD104B \
        -s 1200 -w 0 -x -20 \
        -i archive/J005eD104_post.jpg \
        -t archive/J005eD104B/J005eD104B.csv \
        -o archive/J005eD104B/J005eD104B.jpg \
        -m archive/J005eD104B/J005eD104B_marked.jpg

lmdmap -n J005eD104B \
        -s 1200 -x -20 -a\
        -i archive/J005eD104_pre.jpg \
        -t archive/J005eD104B/J005eD104B.csv \
        -o archive/J005eD104B/J005eD104B.jpg \
        -m archive/J005eD104B/J005eD104B_marked.jpg
```

> [!WARNING]
> JGL: Poor point-to-cut coverages.


### MSEB0036

#### J011eD104A

```{sh}

lmdmap -n J011eD104A \
        -i archive/J011eD104_post.jpg \
        -t archive/J011eD104A/J011eD104A.csv \
        -o archive/J011eD104A/J011eD104A.jpg \
        -m archive/J011eD104A/J011eD104A_marked.jpg

lmdmap -n J011eD104A \
        -x -35 -w 4 \
        -i archive/J011eD104_post.jpg \
        -t archive/J011eD104A/J011eD104A.csv \
        -o archive/J011eD104A/J011eD104A.jpg \
        -m archive/J011eD104A/J011eD104A_marked.jpg

lmdmap -n J011eD104A \
        -x -35 -w 4 -a \
        -i archive/J011eD104_pre.jpg \
        -t archive/J011eD104A/J011eD104A.csv \
        -o archive/J011eD104A/J011eD104A.jpg \
        -m archive/J011eD104A/J011eD104A_marked.jpg

```

> [!WARNING]
> JGL: Poor point-to-cut coverages.

#### J009eD104A

```{sh}
lmdmap -n J009eD104A \
        -i archive/J009eD104_post.jpg \
        -t archive/J009eD104A/J009eD104A.csv \
        -o archive/J009eD104A/J009eD104A.jpg \
        -m archive/J009eD104A/J009eD104A_marked.jpg

lmdmap -n J009eD104A \
        -s 1500 -x -25 -w 5 -y -5\
        -i archive/J009eD104_post.jpg \
        -t archive/J009eD104A/J009eD104A.csv \
        -o archive/J009eD104A/J009eD104A.jpg \
        -m archive/J009eD104A/J009eD104A_marked.jpg

lmdmap -n J009eD104A \
        -s 1500 -x -25 -w 5 -y -5 -a \
        -i archive/J009eD104_pre.jpg \
        -t archive/J009eD104A/J009eD104A.csv \
        -o archive/J009eD104A/J009eD104A.jpg \
        -m archive/J009eD104A/J009eD104A_marked.jpg

```

> [!NOTE]
> JGL: Okay point-to-cut coverages.


### MSEB0037

#### J011eD104B 

```{sh}
lmdmap -n J011eD104B \
        -i archive/J011eD104_post.jpg \
        -t archive/J011eD104B/J011eD104B.csv \
        -o archive/J011eD104B/J011eD104B.jpg \
        -m archive/J011eD104B/J011eD104B_marked.jpg

lmdmap -n J011eD104B \
        -s 1400 -x -40 -w 6 -d M303685 \
        -i archive/J011eD104_post.jpg \
        -t archive/J011eD104B/J011eD104B.csv \
        -o archive/J011eD104B/J011eD104B.jpg \
        -m archive/J011eD104B/J011eD104B_marked.jpg

lmdmap -n J011eD104B \
        -s 1400 -x -40 -w 6 -d M303685 -a \
        -i archive/J011eD104_pre.jpg \
        -t archive/J011eD104B/J011eD104B.csv \
        -o archive/J011eD104B/J011eD104B.jpg \
        -m archive/J011eD104B/J011eD104B_marked.jpg

``` 

> [!NOTE]
> JGL: Okay point-to-cut coverages. M303685 Excluded: incorrect coordinate (not plotted at 2000 pixels [outside cryosection])


#### J009eD104B

```{sh}
lmdmap -n J009eD104B \
        -i archive/J009eD104_post.jpg \
        -t archive/J009eD104B/J009eD104B.csv \
        -o archive/J009eD104B/J009eD104B.jpg \
        -m archive/J009eD104B/J009eD104B_marked.jpg

lmdmap -n J009eD104B \
        -s 1300 -x -35 -w 7 -l -4\
        -i archive/J009eD104_post.jpg \
        -t archive/J009eD104B/J009eD104B.csv \
        -o archive/J009eD104B/J009eD104B.jpg \
        -m archive/J009eD104B/J009eD104B_marked.jpg

lmdmap -n J009eD104B \
        -s 1300 -x -35 -w 7 -l -4 -a \
        -i archive/J009eD104_pre.jpg \
        -t archive/J009eD104B/J009eD104B.csv \
        -o archive/J009eD104B/J009eD104B.jpg \
        -m archive/J009eD104B/J009eD104B_marked.jpg
```

> [!NOTE]
> JGL: Okay point-to-cut coverages.



### MSEB0032

#### J001eD101A !

```{sh}
lmdmap -n J001eD101A \
        -i archive/J001eD101_post.jpg \
        -t archive/J001eD101A/J001eD101A.csv \
        -o archive/J001eD101A/J001eD101A.jpg \
        -m archive/J001eD101A/J001eD101A_marked.jpg

lmdmap -n J001eD101A \
        -s 2200 -x -100 \
        -i archive/J001eD101_post.jpg \
        -t archive/J001eD101A/J001eD101A.csv \
        -o archive/J001eD101A/J001eD101A.jpg \
        -m archive/J001eD101A/J001eD101A_marked.jpg

lmdmap -n J001eD101A \
        -s 2200 -x -100 -a \
        -i archive/J001eD101_pre.jpg \
        -t archive/J001eD101A/J001eD101A.csv \
        -o archive/J001eD101A/J001eD101A.jpg \
        -m archive/J001eD101A/J001eD101A_marked.jpg

```

> [!WARNING]
> JGL: Poor camera center setting, wasting pixels and resolution on finding the cut. Okay point-to-cut coverages given resolution.

#### J002eD101A

```{sh}
lmdmap -n J002eD101A \
        -i archive/J002eD101_post.jpg \
        -t archive/J002eD101A/J002eD101A.csv \
        -o archive/J002eD101A/J002eD101A.jpg \
        -m archive/J002eD101A/J002eD101A_marked.jpg

lmdmap -n J002eD101A \
        -s 1200 -x -130 -w 5 -y 15 \
        -i archive/J002eD101_post.jpg \
        -t archive/J002eD101A/J002eD101A.csv \
        -o archive/J002eD101A/J002eD101A.jpg \
        -m archive/J002eD101A/J002eD101A_marked.jpg

lmdmap -n J002eD101A \
        -s 1200 -x -130 -w 5 -y 15 -a\
        -i archive/J002eD101_pre.jpg \
        -t archive/J002eD101A/J002eD101A.csv \
        -o archive/J002eD101A/J002eD101A.jpg \
        -m archive/J002eD101A/J002eD101A_marked.jpg
```

> [!NOTE]
> JGL: Reasonable point-to-cut coverages.



### MSEB0033

#### J001eD101B 

```{sh}
lmdmap -n J001eD101B \
        -i archive/J001eD101_post.jpg \
        -t archive/J001eD101B/J001eD101B.csv \
        -o archive/J001eD101B/J001eD101B.jpg \
        -m archive/J001eD101B/J001eD101B_marked.jpg

lmdmap -n J001eD101B \
        -x -100 -w 4 -l 1\
        -i archive/J001eD101_post.jpg \
        -t archive/J001eD101B/J001eD101B.csv \
        -o archive/J001eD101B/J001eD101B.jpg \
        -m archive/J001eD101B/J001eD101B_marked.jpg

lmdmap -n J001eD101B \
        -x -100 -w 4 -l 1 -a\
        -i archive/J001eD101_pre.jpg \
        -t archive/J001eD101B/J001eD101B.csv \
        -o archive/J001eD101B/J001eD101B.jpg \
        -m archive/J001eD101B/J001eD101B_marked.jpg

```

> [!WARNING]
> JGL: Poor point-to-cut coverages.

#### J002eD101B

```{sh}
lmdmap -n J002eD101B \
        -i archive/J002eD101_post.jpg \
        -t archive/J002eD101B/J002eD101B.csv \
        -o archive/J002eD101B/J002eD101B.jpg \
        -m archive/J002eD101B/J002eD101B_marked.jpg

lmdmap -n J002eD101B \
        -x -118 -w 4 -y 20 \
        -i archive/J002eD101_post.jpg \
        -t archive/J002eD101B/J002eD101B.csv \
        -o archive/J002eD101B/J002eD101B.jpg \
        -m archive/J002eD101B/J002eD101B_marked.jpg

lmdmap -n J002eD101B \
        -x -118 -w 4 -y 20 -a \
        -i archive/J002eD101_pre.jpg \
        -t archive/J002eD101B/J002eD101B.csv \
        -o archive/J002eD101B/J002eD101B.jpg \
        -m archive/J002eD101B/J002eD101B_marked.jpg

```

> [!NOTE]
> JGL: Reasonable point-to-cut coverages.






## 23-10-2025

### MSEB0054 

#### M080dI101B

```{sh}
lmdmap -n M080dI101B \
        -i archive/M080dI101_post.jpg \
        -t archive/M080dI101B/M080dI101B.csv \
        -o archive/M080dI101B/M080dI101B.jpg \
        -m archive/M080dI101B/M080dI101B_marked.jpg

lmdmap -n M080dI101B \
        -s 900 -x -90 -w 5 -d M305500 \
        -i archive/M080dI101_post.jpg \
        -t archive/M080dI101B/M080dI101B.csv \
        -o archive/M080dI101B/M080dI101B.jpg \
        -m archive/M080dI101B/M080dI101B_marked.jpg

lmdmap -n M080dI101B \
        -s 900 -x -90 -w 5 -d M305500 -a \
        -i archive/M080dI101_pre.jpg \
        -t archive/M080dI101B/M080dI101B.csv \
        -o archive/M080dI101B/M080dI101B.jpg \
        -m archive/M080dI101B/M080dI101B_marked.jpg
```

> [!WARNING]
> JGL: M305500 excluded: Incorrect coordinate. Some LMD points slightly skewed.





### MSEB0016 

#### G125eI201A

```{sh}
lmdmap -n G125eI201A \
        -i archive/G125eI201_post.jpg \
        -t archive/G125eI201A/G125eI201A.csv \
        -o archive/G125eI201A/G125eI201A.jpg \
        -m archive/G125eI201A/G125eI201A_marked.jpg

lmdmap -n G125eI201A \
        -s 950 -x -10 -y -60 -w 20 -l 10 \
        -i archive/G125eI201_post.jpg \
        -t archive/G125eI201A/G125eI201A.csv \
        -o archive/G125eI201A/G125eI201A.jpg \
        -m archive/G125eI201A/G125eI201A_marked.jpg

lmdmap -n G125eI201A \
        -s 950 -x -10 -y -60 -w 20 -l 10 -a\
        -i archive/G125eI201_pre.jpg \
        -t archive/G125eI201A/G125eI201A.csv \
        -o archive/G125eI201A/G125eI201A.jpg \
        -m archive/G125eI201A/G125eI201A_marked.jpg
```

> [!CAUTION]
> JGL: Some mismatch point-to-cut fitting. 





### MSEB0017 

#### G125eI201B

```{sh}
lmdmap -n G125eI201B \
        -i archive/G125eI201_post.jpg \
        -t archive/G125eI201B/G125eI201B.csv \
        -o archive/G125eI201B/G125eI201B.jpg \
        -m archive/G125eI201B/G125eI201B_marked.jpg

lmdmap -n G125eI201B \
        -s 900 -w 20 -l 10 -x -50 -d M301805 \
        -i archive/G125eI201_post.jpg \
        -t archive/G125eI201B/G125eI201B.csv \
        -o archive/G125eI201B/G125eI201B.jpg \
        -m archive/G125eI201B/G125eI201B_marked.jpg

lmdmap -n G125eI201B \
        -s 900 -w 20 -l 10 -x -50 -d M301805 -a \
        -i archive/G125eI201_pre.jpg \
        -t archive/G125eI201B/G125eI201B.csv \
        -o archive/G125eI201B/G125eI201B.jpg \
        -m archive/G125eI201B/G125eI201B_marked.jpg

```

> [!WARNING]
> JGL: M301805 Excluded: incorrect coordinate. Few connection points between marks and cuts.


### MSEB0058 + MSEB0059

#### I031dD101A

```{sh}
lmdmap -n I031dD101A \
        -i archive/I031dD101_post.jpg \
        -t archive/I031dD101A/I031dD101A.csv \
        -o archive/I031dD101A/I031dD101A.jpg \
        -m archive/I031dD101A/I031dD101A_marked.jpg

lmdmap -n I031dD101A \
        -s 2000 -x -90 -w 7  \
        -i archive/I031dD101_post.jpg \
        -t archive/I031dD101A/I031dD101A.csv \
        -o archive/I031dD101A/I031dD101A.jpg \
        -m archive/I031dD101A/I031dD101A_marked.jpg

lmdmap -n I031dD101A \
        -s 2000 -x -90 -w 7 -a \
        -i archive/I031dD101_pre.jpg \
        -t archive/I031dD101A/I031dD101A.csv \
        -o archive/I031dD101A/I031dD101A.jpg \
        -m archive/I031dD101A/I031dD101A_marked.jpg
```

> [!NOTE]
> JGL: Hard to contrast cuts. Good point-to-cut matches - All good.


#### I057dD101B

```{sh}
lmdmap -n I057dD101B \
        -i archive/I057dD101_post.jpg \
        -t archive/I057dD101B/I057dD101B.csv \
        -o archive/I057dD101B/I057dD101B.jpg \
        -m archive/I057dD101B/I057dD101B_marked.jpg

lmdmap -n I057dD101B \
        -s 1100 -x -93 -w 5 -d M305881 \
        -i archive/I057dD101_post.jpg \
        -t archive/I057dD101B/I057dD101B.csv \
        -o archive/I057dD101B/I057dD101B.jpg \
        -m archive/I057dD101B/I057dD101B_marked.jpg

lmdmap -n I057dD101B \
        -s 1100 -x -93 -w 5 -d M305881 -a \
        -i archive/I057dD101_pre.jpg \
        -t archive/I057dD101B/I057dD101B.csv \
        -o archive/I057dD101B/I057dD101B.jpg \
        -m archive/I057dD101B/I057dD101B_marked.jpg
```

> [!NOTE]
> JGL: M305881 excluded: incorrect coordinate. Good point-to-cut match - All good.



###  MSEB0056 + MSEB0057

#### I009dD101A

```{sh}
lmdmap -n I009dD101A \
        -i archive/I009dD101_post.jpg \
        -t archive/I009dD101A/I009dD101A.csv \
        -o archive/I009dD101A/I009dD101A.jpg \
        -m archive/I009dD101A/I009dD101A_marked.jpg

lmdmap -n I009dD101A \
        -s 1200 -x -95 -w 5 -y -2\
        -i archive/I009dD101_post.jpg \
        -t archive/I009dD101A/I009dD101A.csv \
        -o archive/I009dD101A/I009dD101A.jpg \
        -m archive/I009dD101A/I009dD101A_marked.jpg

lmdmap -n I009dD101A \
        -s 1200 -x -95 -w 5 -y -2 -a \
        -i archive/I009dD101_pre.jpg \
        -t archive/I009dD101A/I009dD101A.csv \
        -o archive/I009dD101A/I009dD101A.jpg \
        -m archive/I009dD101A/I009dD101A_marked.jpg
```

> [!NOTE]
> JGL: Weird ERDA file naming: I009dD101A001. Good point-to-cut match - All good.



#### I021dD101A

```{sh}
lmdmap -n I021dD101A \
        -i archive/I021dD101_post.jpg \
        -t archive/I021dD101A/I021dD101A.csv \
        -o archive/I021dD101A/I021dD101A.jpg \
        -m archive/I021dD101A/I021dD101A_marked.jpg

lmdmap -n I021dD101A \
        -s 2000 -x -92 -w 5 \
        -i archive/I021dD101_post.jpg \
        -t archive/I021dD101A/I021dD101A.csv \
        -o archive/I021dD101A/I021dD101A.jpg \
        -m archive/I021dD101A/I021dD101A_marked.jpg

lmdmap -n I021dD101A \
        -s 2000 -x -92 -w 5 -a \
        -i archive/I021dD101_pre.jpg \
        -t archive/I021dD101A/I021dD101A.csv \
        -o archive/I021dD101A/I021dD101A.jpg \
        -m archive/I021dD101A/I021dD101A_marked.jpg
```

> [!NOTE]
> JGL: Good point-to-cut match - all good.


#### M065aI101A

```{sh}
lmdmap -n M065aI101A \
        -i archive/M065aI101A_post.jpg \
        -t archive/M065aI101A/M065aI101A.csv \
        -o archive/M065aI101A/M065aI101A.jpg \
        -m archive/M065aI101A/M065aI101A_marked.jpg

lmdmap -n M065aI101A \
        -s 1200 -x -82 -w 5 \
        -i archive/M065aI101A_post.jpg \
        -t archive/M065aI101A/M065aI101A.csv \
        -o archive/M065aI101A/M065aI101A.jpg \
        -m archive/M065aI101A/M065aI101A_marked.jpg

lmdmap -n M065aI101A \
        -s 1200 -x -82 -w 5 -a \
        -i archive/M065aI101A_pre.jpg \
        -t archive/M065aI101A/M065aI101A.csv \
        -o archive/M065aI101A/M065aI101A.jpg \
        -m archive/M065aI101A/M065aI101A_marked.jpg
```

> [!NOTE]
> [!WARNING]
> [!CAUTION]
> JGL: Good point-to-cut match - all good.


### MSEB0048

#### M002aI101A

```{sh}

lmdmap -n M002aI101A \
        -i archive/M002aI101_post.jpg \
        -t archive/M002aI101A/M002aI101A.csv \
        -o archive/M002aI101A/M002aI101A.jpg \
        -m archive/M002aI101A/M002aI101A_marked.jpg

lmdmap -n M002aI101A \
        -x -92 -w 4 -y 2\
        -i archive/M002aI101_post.jpg \
        -t archive/M002aI101A/M002aI101A.csv \
        -o archive/M002aI101A/M002aI101A.jpg \
        -m archive/M002aI101A/M002aI101A_marked.jpg

lmdmap -n M002aI101A \
        -x -92 -w 4 -y 2 -a \
        -i archive/M002aI101_pre2.jpg \
        -t archive/M002aI101A/M002aI101A.csv \
        -o archive/M002aI101A/M002aI101A.jpg \
        -m archive/M002aI101A/M002aI101A_marked.jpg
```

> [!NOTE]
> JGL: 2 Pre-files found Pre2 used for analysis - correct overlaying between images. Good point-to-cut match - All good.

#### M022aH102A

```{sh}

lmdmap -n M022aH102A \
        -i archive/M022aH102_post.jpg \
        -t archive/M022aH102A/M022aH102A.csv \
        -o archive/M022aH102A/M022aH102A.jpg \
        -m archive/M022aH102A/M022aH102A_marked.jpg

lmdmap -n M022aH102A \
        -x -90 -w 3 -l -2  \
        -i archive/M022aH102_post.jpg \
        -t archive/M022aH102A/M022aH102A.csv \
        -o archive/M022aH102A/M022aH102A.jpg \
        -m archive/M022aH102A/M022aH102A_marked.jpg

lmdmap -n M022aH102A \
        -x -90 -w 3 -l -2 -a \
        -i archive/M022aH102_pre.jpg \
        -t archive/M022aH102A/M022aH102A.csv \
        -o archive/M022aH102A/M022aH102A.jpg \
        -m archive/M022aH102A/M022aH102A_marked.jpg
```

> [!NoteCAUTION]
> JGL:  Good point-to-cut match. All good. 


### MSEB0049

#### M002aI101B

```{sh}

lmdmap -n M002aI101B \
        -i archive/M002aI101_post.jpg \
        -t archive/M002aI101B/M002aI101B.csv \
        -o archive/M002aI101B/M002aI101B.jpg \
        -m archive/M002aI101B/M002aI101B_marked.jpg

lmdmap -n M002aI101B \
        -x -91 -w 5 -l -1 -y 2 \
        -i archive/M002aI101_post.jpg \
        -t archive/M002aI101B/M002aI101B.csv \
        -o archive/M002aI101B/M002aI101B.jpg \
        -m archive/M002aI101B/M002aI101B_marked.jpg

lmdmap -n M002aI101B \
        -x -91 -w 5 -l -1 -y 2 -a \
        -i archive/M002aI101_pre2.jpg \
        -t archive/M002aI101B/M002aI101B.csv \
        -o archive/M002aI101B/M002aI101B.jpg \
        -m archive/M002aI101B/M002aI101B_marked.jpg
```

> [!NOTE]
> JGL: 2 Pre-files found Pre2 used for analysis - correct overlaying between images. Good point-to-cut match - All good.


#### M022aH102B

```{sh}
lmdmap -n M022aH102B \
        -i archive/M022aH102_post.jpg \
        -t archive/M022aH102B/M022aH102B.csv \
        -o archive/M022aH102B/M022aH102B.jpg \
        -m archive/M022aH102B/M022aH102B_marked.jpg

lmdmap -n M022aH102B \
        -x -97 -w 5 -d M304918,M304924 \
        -i archive/M022aH102_post.jpg \
        -t archive/M022aH102B/M022aH102B.csv \
        -o archive/M022aH102B/M022aH102B.jpg \
        -m archive/M022aH102B/M022aH102B_marked.jpg

lmdmap -n M022aH102B \
        -x -97 -w 5 -d M304918,M304924 -a \
        -i archive/M022aH102_pre.jpg \
        -t archive/M022aH102B/M022aH102B.csv \
        -o archive/M022aH102B/M022aH102B.jpg \
        -m archive/M022aH102B/M022aH102B_marked.jpg
```

> [!CAUTION]
> JGL:  Excluded M304918,M304924 - incorrect coordinate (membrane controls). Reasonable point-to-cut match.


### MSEB0050

#### M039dI101A

```{sh}
lmdmap -n M039dI101A \
        -i archive/M039dI101_post.jpg \
        -t archive/M039dI101A/M039dI101A.csv \
        -o archive/M039dI101A/M039dI101A.jpg \
        -m archive/M039dI101A/M039dI101A_marked.jpg

lmdmap -n M039dI101A \
        -s 1200 -x -84 -w 5 \
        -i archive/M039dI101_post.jpg \
        -t archive/M039dI101A/M039dI101A.csv \
        -o archive/M039dI101A/M039dI101A.jpg \
        -m archive/M039dI101A/M039dI101A_marked.jpg

lmdmap -n M039dI101A \
        -s 1200 -x -84 -w 5 -d M305054,M305041,M305064,M305052 -a \
        -i archive/M039dI101_pre.jpg \
        -t archive/M039dI101A/M039dI101A.csv \
        -o archive/M039dI101A/M039dI101A.jpg \
        -m archive/M039dI101A/M039dI101A_marked.jpg
```

> [!WARNING]
> JGL:  M305054,M305041,M305064,M305052 are membrane controls - incorrect coordinate. Good point-to-cut match.


#### M038dI101A *****

```{sh}
 
lmdmap -n M038dI101A \
        -i archive/M038dI101_post.jpg \
        -t archive/M038dI101A/M038dI101A.csv \
        -o archive/M038dI101A/M038dI101A.jpg \
        -m archive/M038dI101A/M038dI101A_marked.jpg

lmdmap -n M038dI101A \
        -x -95 -w 4 -y 2 \
        -i archive/M038dI101_post.jpg \
        -t archive/M038dI101A/M038dI101A.csv \
        -o archive/M038dI101A/M038dI101A.jpg \
        -m archive/M038dI101A/M038dI101A_marked.jpg

lmdmap -n M038dI101A \
        -x -95 -w 4 -y 2 -a \
        -i archive/M038dI101_pre.jpg \
        -t archive/M038dI101A/M038dI101A.csv \
        -o archive/M038dI101A/M038dI101A.jpg \
        -m archive/M038dI101A/M038dI101A_marked.jpg
```

> [!NOTE]
> JGL:  Good point-to-cut match. Upper and lower half of section slightly misaligned.


## 27-10-2025

## MSEB0052 + MSEB0053

#### M017dI101A *****

```{sh}
lmdmap -n M017dI101A \
        -i archive/M017dI101_post.jpg \
        -t archive/M017dI101A/M017dI101A.csv \
        -o archive/M017dI101A/M017dI101A.jpg \
        -m archive/M017dI101A/M017dI101A_marked.jpg

lmdmap -n M017dI101A \
        -x -95 -w 5 \
        -i archive/M017dI101_post.jpg \
        -t archive/M017dI101A/M017dI101A.csv \
        -o archive/M017dI101A/M017dI101A.jpg \
        -m archive/M017dI101A/M017dI101A_marked.jpg

lmdmap -n M017dI101A \
        -x -95 -w 5 -a \
        -i archive/M017dI101_pre.jpg \
        -t archive/M017dI101A/M017dI101A.csv \
        -o archive/M017dI101A/M017dI101A.jpg \
        -m archive/M017dI101A/M017dI101A_marked.jpg
```

> [!NOTE]
> JGL:  Good point-to-cut match. All good.


#### M078dI101A *****

```{sh}
 
lmdmap -n M078dI101A \
        -i archive/M078dI101_post.jpg \
        -t archive/M078dI101A/M078dI101A.csv \
        -o archive/M078dI101A/M078dI101A.jpg \
        -m archive/M078dI101A/M078dI101A_marked.jpg

lmdmap -n M078dI101A \
        -x -88 -w 5 -d M305275  \
        -i archive/M078dI101_post.jpg \
        -t archive/M078dI101A/M078dI101A.csv \
        -o archive/M078dI101A/M078dI101A.jpg \
        -m archive/M078dI101A/M078dI101A_marked.jpg

lmdmap -n M078dI101A \
        -x -88 -w 5 -d M305275 -a  \
        -i archive/M078dI101_pre.jpg \
        -t archive/M078dI101A/M078dI101A.csv \
        -o archive/M078dI101A/M078dI101A.jpg \
        -m archive/M078dI101A/M078dI101A_marked.jpg
```

> [!NOTE]
> JGL:  Reasonable point-to-cut match. All good. M305275 Excluded: incorrect coordinate (membrane control)


#### M017dI101B *****

```{sh}
 
lmdmap -n M017dI101B \
        -i archive/M017dI101_post.jpg \
        -t archive/M017dI101B/M017dI101B.csv \
        -o archive/M017dI101B/M017dI101B.jpg \
        -m archive/M017dI101B/M017dI101B_marked.jpg

lmdmap -n M017dI101B \
        -x -100 -d M305238\
        -i archive/M017dI101_post.jpg \
        -t archive/M017dI101B/M017dI101B.csv \
        -o archive/M017dI101B/M017dI101B.jpg \
        -m archive/M017dI101B/M017dI101B_marked.jpg
```

```
lmdmap -n M017dI101B \
        -x -100 -d M305238 -a\
        -i archive/M017dI101_pre.jpg \
        -t archive/M017dI101B/M017dI101B.csv \
        -o archive/M017dI101B/M017dI101B.jpg \
        -m archive/M017dI101B/M017dI101B_marked.jpg
```

> [!WARNING]
> JGL:  Okay point-to-cut match, some points far off potential cuts. M305238 Excluded: incorrect coordinate (membrane control)





## 2025-10-21

### MSEB0054

Example used by Antton to show Jonas how to use lmdmap.

#### M018dI101A

```{sh}
lmdmap -n M018dI101A \
        -i image/overview/M018dI101_post.jpg \
        -t image/overview/M018dI101A/M018dI101A.csv \
        -o image/overview/M018dI101A/M018dI101A.jpg \
        -m image/overview/M018dI101A/M018dI101A_marked.jpg

lmdmap -n M018dI101A \
        -s 1400 -x -90 -w 5 \
        -i image/overview/M018dI101_post.jpg \
        -t image/overview/M018dI101A/M018dI101A.csv \
        -o image/overview/M018dI101A/M018dI101A.jpg \
        -m image/overview/M018dI101A/M018dI101A_marked.jpg

lmdmap -n M018dI101A \
        -s 1400 -x -90 -w 5 -a \
        -i image/overview/M018dI101_pre.jpg \
        -t image/overview/M018dI101A/M018dI101A.csv \
        -o image/overview/M018dI101A/M018dI101A.jpg \
        -m image/overview/M018dI101A/M018dI101A_marked.jpg
```
> [!NOTE]
> All good!

## 2025-10-18

### C_HT

```{sh}
screen -S C_HT
conda activate arch3d
cd C_HT
arch3d macrosample -m C_HT.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### C_MT

```{sh}
screen -S C_MT
conda activate arch3d
cd C_MT
arch3d macrosample -m C_MT.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### C_MG

```{sh}
screen -S C_MG
conda activate arch3d
cd C_MG
arch3d macrosample -m C_MG.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### C_HG

```{sh}
screen -S C_HG
conda activate arch3d
cd C_HG
arch3d macrosample -m C_HG.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### G_MG

```{sh}
screen -S G_MG
conda activate arch3d
cd G_MG
arch3d macrosample -m G_MG.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### G_MT

```{sh}
screen -S G_MT
conda activate arch3d
cd G_MT
arch3d macrosample -m G_MT.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

## 2025-09-11

### MSEB0010

#### Sequences

```{sh}
screen -S MSEB0010
conda activate arch3d
cd MSEB0010
arch3d microsample -m MSEB0010.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### MSEB0012

#### Sequences

```{sh}
screen -S MSEB0012
conda activate arch3d
cd MSEB0012
arch3d microsample -m MSEB0012.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### MSEB0014

#### Sequences

```{sh}
screen -S MSEB0014
conda activate arch3d
cd MSEB0014
arch3d microsample -m MSEB0014.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

### MSEB0015

#### Sequences

```{sh}
screen -S MSEB0015
conda activate arch3d
cd MSEB0015
arch3d microsample -m MSEB0015.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

## 2025-09-10

### MSEB0006

#### Sequences

```{sh}
screen -S MSEB0006
conda activate arch3d
cd MSEB0006
arch3d microsample -m MSEB0006.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

## 2025-06-24

### MSEB0010

#### G121eO301A

```{sh}
lmdmap -n G121eO301A \
        -i image/overview/G121eO301_post.jpg \
        -t image/overview/G121eO301A/G121eO301A.csv \
        -o image/overview/G121eO301A/G121eO301A.jpg \
        -m image/overview/G121eO301A/G121eO301A_marked.jpg

lmdmap -n G121eO301A \
        -s 1400 -x -30 -w 5 \
        -i image/overview/G121eO301_post.jpg \
        -t image/overview/G121eO301A/G121eO301A.csv \
        -o image/overview/G121eO301A/G121eO301A.jpg \
        -m image/overview/G121eO301A/G121eO301A_marked.jpg

lmdmap -n G121eO301A \
        -s 1400 -x -30 -w 5 -a \
        -i image/overview/G121eO301_pre.jpg \
        -t image/overview/G121eO301A/G121eO301A.csv \
        -o image/overview/G121eO301A/G121eO301A.jpg \
        -m image/overview/G121eO301A/G121eO301A_marked.jpg
```

### MSEB0016-28

#### G005bI205A

```{sh}
lmdmap -n G005bI205A \
        -i image/overview/G005bI205_post.jpg \
        -t image/overview/G005bI205A/G005bI205A.csv \
        -o image/overview/G005bI205A/G005bI205A.jpg \
        -m image/overview/G005bI205A/G005bI205A_marked.jpg
```

```{sh}
lmdmap -n G005bI205A \
        -s 800 -x -50 -d M302895,M302896,M302897 \
        -i image/overview/G005bI205_post.jpg \
        -t image/overview/G005bI205A/G005bI205A.csv \
        -o image/overview/G005bI205A/G005bI205A.jpg \
        -m image/overview/G005bI205A/G005bI205A_marked.jpg
```

```{sh}
lmdmap -n G005bI205A \
        -s 800 -x -50 -d M302895,M302896,M302897 -a \
        -i image/overview/G005bI205_pre.jpg \
        -t image/overview/G005bI205A/G005bI205A.csv \
        -o image/overview/G005bI205A/G005bI205A.jpg \
        -m image/overview/G005bI205A/G005bI205A_marked.jpg
```

> [!WARNING]
> M302895, M302896, M302897 are membrane controls

#### G005bI205B

```{sh}
lmdmap -n G005bI205B \
        -i image/overview/G005bI205_post.jpg \
        -t image/overview/G005bI205B/G005bI205B.csv \
        -o image/overview/G005bI205B/G005bI205B.jpg \
        -m image/overview/G005bI205B/G005bI205B_marked.jpg
```

```{sh}
lmdmap -n G005bI205B \
        -s 800 -x -15 -w 10 \
        -i image/overview/G005bI205_post.jpg \
        -t image/overview/G005bI205B/G005bI205B.csv \
        -o image/overview/G005bI205B/G005bI205B.jpg \
        -m image/overview/G005bI205B/G005bI205B_marked.jpg
```

```{sh}
lmdmap -n G005bI205B \
        -s 800 -x -15 -w 10 -a \
        -i image/overview/G005bI205_pre.jpg \
        -t image/overview/G005bI205B/G005bI205B.csv \
        -o image/overview/G005bI205B/G005bI205B.jpg \
        -m image/overview/G005bI205B/G005bI205B_marked.jpg
```

> [!NOTE]
> All good!

#### G006bI203A

```{sh}
lmdmap -n G006bI203A \
        -i image/overview/G006bI203_post.jpg \
        -t image/overview/G006bI203A/G006bI203A.csv \
        -o image/overview/G006bI203A/G006bI203A.jpg \
        -m image/overview/G006bI203A/G006bI203A_marked.jpg
```

```{sh}
lmdmap -n G006bI203A \
        -w 10 -x -10 -c -d M303014 \
        -i image/overview/G006bI203_post.jpg \
        -t image/overview/G006bI203A/G006bI203A.csv \
        -o image/overview/G006bI203A/G006bI203A.jpg \
        -m image/overview/G006bI203A/G006bI203A_marked.jpg
```

```{sh}
lmdmap -n G006bI203A \
        -w 10 -x -10 -d M303014 -a \
        -i image/overview/G006bI203_pre.jpg \
        -t image/overview/G006bI203A/G006bI203A.csv \
        -o image/overview/G006bI203A/G006bI203A.jpg \
        -m image/overview/G006bI203A/G006bI203A_marked.jpg
```

> [!WARNING]
> M303014 is a membrane control

#### G006bI203B

```{sh}
lmdmap -n G006bI203B \
        -i image/overview/G006bI203_post.jpg \
        -t image/overview/G006bI203B/G006bI203B.csv \
        -o image/overview/G006bI203B/G006bI203B.jpg \
        -m image/overview/G006bI203B/G006bI203B_marked.jpg
```

```{sh}
lmdmap -n G006bI203B \
        -s 1100 -w 8 -x -20 -d M303110,M303111 -c \
        -i image/overview/G006bI203_post.jpg \
        -t image/overview/G006bI203B/G006bI203B.csv \
        -o image/overview/G006bI203B/G006bI203B.jpg \
        -m image/overview/G006bI203B/G006bI203B_marked.jpg
```

```{sh}
lmdmap -n G006bI203B \
        -s 1100 -w 8 -x -20 -d M303110,M303111 -a \
        -i image/overview/G006bI203_pre.jpg \
        -t image/overview/G006bI203B/G006bI203B.csv \
        -o image/overview/G006bI203B/G006bI203B.jpg \
        -m image/overview/G006bI203B/G006bI203B_marked.jpg
```

> [!WARNING]
> M303110 and M303111 are membrane controls

#### G007bI105A

```{sh}
lmdmap -n G007bI105A \
        -i image/overview/G007bI105_post.jpg \
        -t image/overview/G007bI105A/G007bI105A.csv \
        -o image/overview/G007bI105A/G007bI105A.jpg \
        -m image/overview/G007bI105A/G007bI105A_marked.jpg
```

```{sh}
lmdmap -n G007bI105A \
        -a \
        -i image/overview/G007bI105_pre.jpg \
        -t image/overview/G007bI105A/G007bI105A.csv \
        -o image/overview/G007bI105A/G007bI105A.jpg \
        -m image/overview/G007bI105A/G007bI105A_marked.jpg
```

> [!NOTE]
> All good!

#### G007bI105B

```{sh}
lmdmap -n G007bI105B \
        -i image/overview/G007bI105_post.jpg \
        -t image/overview/G007bI105B/G007bI105B.csv \
        -o image/overview/G007bI105B/G007bI105B.jpg \
        -m image/overview/G007bI105B/G007bI105B_marked.jpg
```

```{sh}
lmdmap -n G007bI105B \
        -s 800 -w 5 -l 2 -x -10 -c -d M303192,M303163,M303172 \
        -i image/overview/G007bI105_post.jpg \
        -t image/overview/G007bI105B/G007bI105B.csv \
        -o image/overview/G007bI105B/G007bI105B.jpg \
        -m image/overview/G007bI105B/G007bI105B_marked.jpg
```

```{sh}
lmdmap -n G007bI105B \
        -s 800 -w 5 -l 2 -x -10 -d M303192,M303163,M303172 -a \
        -i image/overview/G007bI105_pre.jpg \
        -t image/overview/G007bI105B/G007bI105B.csv \
        -o image/overview/G007bI105B/G007bI105B.jpg \
        -m image/overview/G007bI105B/G007bI105B_marked.jpg
```

> [!WARNING]
> M303192, M303163 and M303172 are membrane controls

#### G019eI105A

```{sh}
lmdmap -n G019eI105A \
        -i image/overview/G019eI105_post.jpg \
        -t image/overview/G019eI105A/G019eI105A.csv \
        -o image/overview/G019eI105A/G019eI105A.jpg \
        -m image/overview/G019eI105A/G019eI105A_marked.jpg
```

```{sh}
lmdmap -n G019eI105A \
        -s 1500 -x -85 -w 3 \
        -i image/overview/G019eI105_post.jpg \
        -t image/overview/G019eI105A/G019eI105A.csv \
        -o image/overview/G019eI105A/G019eI105A.jpg \
        -m image/overview/G019eI105A/G019eI105A_marked.jpg
```

```{sh}
lmdmap -n G019eI105A \
        -s 1500 -x -85 -w 3 -a \
        -i image/overview/G019eI105_pre.jpg \
        -t image/overview/G019eI105A/G019eI105A.csv \
        -o image/overview/G019eI105A/G019eI105A.jpg \
        -m image/overview/G019eI105A/G019eI105A_marked.jpg
```

> [!NOTE]
> All good!

#### G019eI105B

```{sh}
lmdmap -n G019eI105B \
        -i image/overview/G019eI105_post.jpg \
        -t image/overview/G019eI105B/G019eI105B.csv \
        -o image/overview/G019eI105B/G019eI105B.jpg \
        -m image/overview/G019eI105B/G019eI105B_marked.jpg
```

```{sh}
lmdmap -n G019eI105B \
        -s 1500 -x -90 -w 3 -c -d M302218 \
        -i image/overview/G019eI105_post.jpg \
        -t image/overview/G019eI105B/G019eI105B.csv \
        -o image/overview/G019eI105B/G019eI105B.jpg \
        -m image/overview/G019eI105B/G019eI105B_marked.jpg
```

```{sh}
lmdmap -n G019eI105B \
        -s 1500 -x -90 -w 3 -d M302218 -a \
        -i image/overview/G019eI105_pre.jpg \
        -t image/overview/G019eI105B/G019eI105B.csv \
        -o image/overview/G019eI105B/G019eI105B.jpg \
        -m image/overview/G019eI105B/G019eI105B_marked.jpg
```

> [!WARNING]
> M302218 is a membrane control

#### G020eI205A

```{sh}
lmdmap -n G020eI205A \
        -i image/overview/G020eI205_post.jpg \
        -t image/overview/G020eI205A/G020eI205A.csv \
        -o image/overview/G020eI205A/G020eI205A.jpg \
        -m image/overview/G020eI205A/G020eI205A_marked.jpg
```

```{sh}
lmdmap -n G020eI205A \
        -x -35 -w 4 \
        -i image/overview/G020eI205_post.jpg \
        -t image/overview/G020eI205A/G020eI205A.csv \
        -o image/overview/G020eI205A/G020eI205A.jpg \
        -m image/overview/G020eI205A/G020eI205A_marked.jpg
```

```{sh}
lmdmap -n G020eI205A \
        -x -35 -w 4 -a \
        -i image/overview/G020eI205_pre.jpg \
        -t image/overview/G020eI205A/G020eI205A.csv \
        -o image/overview/G020eI205A/G020eI205A.jpg \
        -m image/overview/G020eI205A/G020eI205A_marked.jpg
```

> [!NOTE]
> All good!

#### G020eI205B

```{sh}
lmdmap -n G020eI205B \
        -i image/overview/G020eI205_post.jpg \
        -t image/overview/G020eI205B/G020eI205B.csv \
        -o image/overview/G020eI205B/G020eI205B.jpg \
        -m image/overview/G020eI205B/G020eI205B_marked.jpg
```

```{sh}
lmdmap -n G020eI205B \
        -x -35 -w 4 \
        -i image/overview/G020eI205_post.jpg \
        -t image/overview/G020eI205B/G020eI205B.csv \
        -o image/overview/G020eI205B/G020eI205B.jpg \
        -m image/overview/G020eI205B/G020eI205B_marked.jpg
```

```{sh}
lmdmap -n G020eI205B \
        -x -35 -w 4 -a \
        -i image/overview/G020eI205_pre.jpg \
        -t image/overview/G020eI205B/G020eI205B.csv \
        -o image/overview/G020eI205B/G020eI205B.jpg \
        -m image/overview/G020eI205B/G020eI205B_marked.jpg
```

> [!NOTE]
> All good!

#### G021eI105A

```{sh}
lmdmap -n G021eI105A \
        -i image/overview/G021eI105_post.jpg \
        -t image/overview/G021eI105A/G021eI105A.csv \
        -o image/overview/G021eI105A/G021eI105A.jpg \
        -m image/overview/G021eI105A/G021eI105A_marked.jpg
```

```{sh}
lmdmap -n G021eI105A \
        -x -30 -w 5 \
        -i image/overview/G021eI105_post.jpg \
        -t image/overview/G021eI105A/G021eI105A.csv \
        -o image/overview/G021eI105A/G021eI105A.jpg \
        -m image/overview/G021eI105A/G021eI105A_marked.jpg
```

```{sh}
lmdmap -n G021eI105A \
        -x -30 -w 5 -a \
        -i image/overview/G021eI105_pre.jpg \
        -t image/overview/G021eI105A/G021eI105A.csv \
        -o image/overview/G021eI105A/G021eI105A.jpg \
        -m image/overview/G021eI105A/G021eI105A_marked.jpg
```

> [!NOTE]
> All good!

#### G021eI105B

```{sh}
lmdmap -n G021eI105B \
        -i image/overview/G021eI105_post.jpg \
        -t image/overview/G021eI105B/G021eI105B.csv \
        -o image/overview/G021eI105B/G021eI105B.jpg \
        -m image/overview/G021eI105B/G021eI105B_marked.jpg
```

```{sh}
lmdmap -n G021eI105B \
        -x -25 -w 2 \
        -i image/overview/G021eI105_post.jpg \
        -t image/overview/G021eI105B/G021eI105B.csv \
        -o image/overview/G021eI105B/G021eI105B.jpg \
        -m image/overview/G021eI105B/G021eI105B_marked.jpg
```

```{sh}
lmdmap -n G021eI105B \
        -x -25 -w 2 -a \
        -i image/overview/G021eI105_pre.jpg \
        -t image/overview/G021eI105B/G021eI105B.csv \
        -o image/overview/G021eI105B/G021eI105B.jpg \
        -m image/overview/G021eI105B/G021eI105B_marked.jpg
```

> [!NOTE]
> All good!

#### G081bI105A

```{sh}
lmdmap -n G081bI105A \
        -i image/overview/G081bI105_post.jpg \
        -t image/overview/G081bI105A/G081bI105A.csv \
        -o image/overview/G081bI105A/G081bI105A.jpg \
        -m image/overview/G081bI105A/G081bI105A_marked.jpg
```

```{sh}
lmdmap -n G081bI105A \
        -x -40 -w 4 -d M302650 \
        -i image/overview/G081bI105_post.jpg \
        -t image/overview/G081bI105A/G081bI105A.csv \
        -o image/overview/G081bI105A/G081bI105A.jpg \
        -m image/overview/G081bI105A/G081bI105A_marked.jpg
```

```{sh}
lmdmap -n G081bI105A \
        -x -40 -w 4 -d M302650 -a \
        -i image/overview/G081bI105_pre.jpg \
        -t image/overview/G081bI105A/G081bI105A.csv \
        -o image/overview/G081bI105A/G081bI105A.jpg \
        -m image/overview/G081bI105A/G081bI105A_marked.jpg
```

> [!WARNING]
> M302650 is a membrane control

#### G081bI105B

```{sh}
lmdmap -n G081bI105B \
        -i image/overview/G081bI105_post.jpg \
        -t image/overview/G081bI105B/G081bI105B.csv \
        -o image/overview/G081bI105B/G081bI105B.jpg \
        -m image/overview/G081bI105B/G081bI105B_marked.jpg
```

> [!WARNING]
> Seems to be quite off

#### G082bI105A

```{sh}
lmdmap -n G082bI105A \
        -i image/overview/G082bI105_post.jpg \
        -t image/overview/G082bI105A/G082bI105A.csv \
        -o image/overview/G082bI105A/G082bI105A.jpg \
        -m image/overview/G082bI105A/G082bI105A_marked.jpg
```

```{sh}
lmdmap -n G082bI105A \
        -x -35 -w 5 \
        -i image/overview/G082bI105_post.jpg \
        -t image/overview/G082bI105A/G082bI105A.csv \
        -o image/overview/G082bI105A/G082bI105A.jpg \
        -m image/overview/G082bI105A/G082bI105A_marked.jpg
```

```{sh}
lmdmap -n G082bI105A \
        -x -35 -w 5 -a \
        -i image/overview/G082bI105_pre.jpg \
        -t image/overview/G082bI105A/G082bI105A.csv \
        -o image/overview/G082bI105A/G082bI105A.jpg \
        -m image/overview/G082bI105A/G082bI105A_marked.jpg
```

> [!NOTE]
> All good!

#### G082bI105B

```{sh}
lmdmap -n G082bI105B \
        -i image/overview/G082bI105_post.jpg \
        -t image/overview/G082bI105B/G082bI105B.csv \
        -o image/overview/G082bI105B/G082bI105B.jpg \
        -m image/overview/G082bI105B/G082bI105B_marked.jpg
```

> [!WARNING]
> Seems to be quite off

#### G084bI105A

```{sh}
lmdmap -n G084bI105A \
        -i image/overview/G084bI105_post.jpg \
        -t image/overview/G084bI105A/G084bI105A.csv \
        -o image/overview/G084bI105A/G084bI105A.jpg \
        -m image/overview/G084bI105A/G084bI105A_marked.jpg
```

```{sh}
lmdmap -n G084bI105A \
        -x -25 \
        -i image/overview/G084bI105_post.jpg \
        -t image/overview/G084bI105A/G084bI105A.csv \
        -o image/overview/G084bI105A/G084bI105A.jpg \
        -m image/overview/G084bI105A/G084bI105A_marked.jpg
```

```{sh}
lmdmap -n G084bI105A \
        -x -25 -a \
        -i image/overview/G084bI105_pre.jpg \
        -t image/overview/G084bI105A/G084bI105A.csv \
        -o image/overview/G084bI105A/G084bI105A.jpg \
        -m image/overview/G084bI105A/G084bI105A_marked.jpg
```

> [!WARNING]
> Some samples are from the central empty space

#### G084bI105B

```{sh}
lmdmap -n G084bI105B \
        -i image/overview/G084bI105_post.jpg \
        -t image/overview/G084bI105B/G084bI105B.csv \
        -o image/overview/G084bI105B/G084bI105B.jpg \
        -m image/overview/G084bI105B/G084bI105B_marked.jpg
```

```{sh}
lmdmap -n G084bI105B \
        -s 1200 -x -30 -d M302954 \
        -i image/overview/G084bI105_post.jpg \
        -t image/overview/G084bI105B/G084bI105B.csv \
        -o image/overview/G084bI105B/G084bI105B.jpg \
        -m image/overview/G084bI105B/G084bI105B_marked.jpg
```

```{sh}
lmdmap -n G084bI105B \
        -x -30 -d M302954 -a \
        -i image/overview/G084bI105_pre.jpg \
        -t image/overview/G084bI105B/G084bI105B.csv \
        -o image/overview/G084bI105B/G084bI105B.jpg \
        -m image/overview/G084bI105B/G084bI105B_marked.jpg
```

#### G095eI108A

```{sh}
lmdmap -n G095eI108A \
        -i image/overview/G095eI108_post.jpg \
        -t image/overview/G095eI108A/G095eI108A.csv \
        -o image/overview/G095eI108A/G095eI108A.jpg \
        -m image/overview/G095eI108A/G095eI108A_marked.jpg
```

```{sh}
lmdmap -n G095eI108A \
        -x -30 -w 2 \
        -i image/overview/G095eI108_post.jpg \
        -t image/overview/G095eI108A/G095eI108A.csv \
        -o image/overview/G095eI108A/G095eI108A.jpg \
        -m image/overview/G095eI108A/G095eI108A_marked.jpg
```

```{sh}
lmdmap -n G095eI108A \
        -x -30 -w 2 -a \
        -i image/overview/G095eI108_pre.jpg \
        -t image/overview/G095eI108A/G095eI108A.csv \
        -o image/overview/G095eI108A/G095eI108A.jpg \
        -m image/overview/G095eI108A/G095eI108A_marked.jpg
```

#### G095eI108B

```{sh}
lmdmap -n G095eI108B \
        -i image/overview/G095eI108_post.jpg \
        -t image/overview/G095eI108B/G095eI108B.csv \
        -o image/overview/G095eI108B/G095eI108B.jpg \
        -m image/overview/G095eI108B/G095eI108B_marked.jpg
```

```{sh}
lmdmap -n G095eI108B \
        -s 1300 -x -20 -w 5 \
        -i image/overview/G095eI108_post.jpg \
        -t image/overview/G095eI108B/G095eI108B.csv \
        -o image/overview/G095eI108B/G095eI108B.jpg \
        -m image/overview/G095eI108B/G095eI108B_marked.jpg
```

```{sh}
lmdmap -n G095eI108B \
        -s 1300 -x -20 -w 5 -a \
        -i image/overview/G095eI108_pre.jpg \
        -t image/overview/G095eI108B/G095eI108B.csv \
        -o image/overview/G095eI108B/G095eI108B.jpg \
        -m image/overview/G095eI108B/G095eI108B_marked.jpg
```

#### G096eI107A

```{sh}
lmdmap -n G096eI107A \
        -i image/overview/G096eI107_post.jpg \
        -t image/overview/G096eI107A/G096eI107A.csv \
        -o image/overview/G096eI107A/G096eI107A.jpg \
        -m image/overview/G096eI107A/G096eI107A_marked.jpg
```

```{sh}
lmdmap -n G096eI107A \
        -s 900 -x -30 -w 5 \
        -i image/overview/G096eI107_post.jpg \
        -t image/overview/G096eI107A/G096eI107A.csv \
        -o image/overview/G096eI107A/G096eI107A.jpg \
        -m image/overview/G096eI107A/G096eI107A_marked.jpg
```

```{sh}
lmdmap -n G096eI107A \
        -s 900 -x -30 -w 5 -a \
        -i image/overview/G096eI107_pre.jpg \
        -t image/overview/G096eI107A/G096eI107A.csv \
        -o image/overview/G096eI107A/G096eI107A.jpg \
        -m image/overview/G096eI107A/G096eI107A_marked.jpg
```

#### G096eI107B

```{sh}
lmdmap -n G096eI107B \
        -i image/overview/G096eI107_post.jpg \
        -t image/overview/G096eI107B/G096eI107B.csv \
        -o image/overview/G096eI107B/G096eI107B.jpg \
        -m image/overview/G096eI107B/G096eI107B_marked.jpg
```

```{sh}
lmdmap -n G096eI107B \
        -s 900 -x -30 -w 5 \
        -i image/overview/G096eI107_post.jpg \
        -t image/overview/G096eI107B/G096eI107B.csv \
        -o image/overview/G096eI107B/G096eI107B.jpg \
        -m image/overview/G096eI107B/G096eI107B_marked.jpg
```

```{sh}
lmdmap -n G096eI107B \
        -s 900 -x -30 -w 5 -a \
        -i image/overview/G096eI107_pre.jpg \
        -t image/overview/G096eI107B/G096eI107B.csv \
        -o image/overview/G096eI107B/G096eI107B.jpg \
        -m image/overview/G096eI107B/G096eI107B_marked.jpg
```
#### G097eI107A

```{sh}
lmdmap -n G097eI107A \
        -i image/overview/G097eI107_post.jpg \
        -t image/overview/G097eI107A/G097eI107A.csv \
        -o image/overview/G097eI107A/G097eI107A.jpg \
        -m image/overview/G097eI107A/G097eI107A_marked.jpg
```

```{sh}
lmdmap -n G097eI107A \
        -s 1400 -x -80 -w 7 \
        -i image/overview/G097eI107_post.jpg \
        -t image/overview/G097eI107A/G097eI107A.csv \
        -o image/overview/G097eI107A/G097eI107A.jpg \
        -m image/overview/G097eI107A/G097eI107A_marked.jpg
```

```{sh}
lmdmap -n G097eI107A \
        -s 1400 -x -80 -w 7 -a \
        -i image/overview/G097eI107_pre.jpg \
        -t image/overview/G097eI107A/G097eI107A.csv \
        -o image/overview/G097eI107A/G097eI107A.jpg \
        -m image/overview/G097eI107A/G097eI107A_marked.jpg
```

#### G097eI107B

```{sh}
lmdmap -n G097eI107B \
        -i image/overview/G097eI107_post.jpg \
        -t image/overview/G097eI107B/G097eI107B.csv \
        -o image/overview/G097eI107B/G097eI107B.jpg \
        -m image/overview/G097eI107B/G097eI107B_marked.jpg
```

```{sh}
lmdmap -n G097eI107B \
        -s 1400 -x -90 -w 5 -d M302172,M302179 \
        -i image/overview/G097eI107_post.jpg \
        -t image/overview/G097eI107B/G097eI107B.csv \
        -o image/overview/G097eI107B/G097eI107B.jpg \
        -m image/overview/G097eI107B/G097eI107B_marked.jpg
```

```{sh}
lmdmap -n G097eI107B \
        -s 1400 -x -90 -w 5 -d M302172,M302179 -a \
        -i image/overview/G097eI107_pre.jpg \
        -t image/overview/G097eI107B/G097eI107B.csv \
        -o image/overview/G097eI107B/G097eI107B.jpg \
        -m image/overview/G097eI107B/G097eI107B_marked.jpg
```

#### G105bI105B

```{sh}
lmdmap -n G105bI105B \
        -i image/overview/G105bI105_post.jpg \
        -t image/overview/G105bI105B/G105bI105B.csv \
        -o image/overview/G105bI105B/G105bI105B.jpg \
        -m image/overview/G105bI105B/G105bI105B_marked.jpg
```

```{sh}
lmdmap -n G105bI105B \
        -s 600 -x -40 \
        -i image/overview/G105bI105_post.jpg \
        -t image/overview/G105bI105B/G105bI105B.csv \
        -o image/overview/G105bI105B/G105bI105B.jpg \
        -m image/overview/G105bI105B/G105bI105B_marked.jpg
```

```{sh}
lmdmap -n G105bI105B \
        -s 600 -x -40 -a \
        -i image/overview/G105bI105_pre.jpg \
        -t image/overview/G105bI105B/G105bI105B.csv \
        -o image/overview/G105bI105B/G105bI105B.jpg \
        -m image/overview/G105bI105B/G105bI105B_marked.jpg
```

#### G105bI105C

```{sh}
lmdmap -n G105bI105C \
        -i image/overview/G105bI105_post.jpg \
        -t image/overview/G105bI105C/G105bI105C.csv \
        -o image/overview/G105bI105C/G105bI105C.jpg \
        -m image/overview/G105bI105C/G105bI105C_marked.jpg
```

```{sh}
lmdmap -n G105bI105C \
        -s 600 -x -30 -d M302570,M302542,M302546 \
        -i image/overview/G105bI105_post.jpg \
        -t image/overview/G105bI105C/G105bI105C.csv \
        -o image/overview/G105bI105C/G105bI105C.jpg \
        -m image/overview/G105bI105C/G105bI105C_marked.jpg
```

```{sh}
lmdmap -n G105bI105C \
        -s 600 -x -30 -d M302570,M302542,M302546 -a \
        -i image/overview/G105bI105_pre.jpg \
        -t image/overview/G105bI105C/G105bI105C.csv \
        -o image/overview/G105bI105C/G105bI105C.jpg \
        -m image/overview/G105bI105C/G105bI105C_marked.jpg
```

#### G107bI305A

```{sh}
lmdmap -n G107bI305A \
        -i image/overview/G107bI305_post.jpg \
        -t image/overview/G107bI305A/G107bI305A.csv \
        -o image/overview/G107bI305A/G107bI305A.jpg \
        -m image/overview/G107bI305A/G107bI305A_marked.jpg
```

```{sh}
lmdmap -n G107bI305A \
        -x -40 -w 5 \
        -i image/overview/G107bI305_post.jpg \
        -t image/overview/G107bI305A/G107bI305A.csv \
        -o image/overview/G107bI305A/G107bI305A.jpg \
        -m image/overview/G107bI305A/G107bI305A_marked.jpg
```

```{sh}
lmdmap -n G107bI305A \
        -x -40 -w 5 -a \
        -i image/overview/G107bI305_pre.jpg \
        -t image/overview/G107bI305A/G107bI305A.csv \
        -o image/overview/G107bI305A/G107bI305A.jpg \
        -m image/overview/G107bI305A/G107bI305A_marked.jpg
```

#### G107bI305B

```{sh}
lmdmap -n G107bI305B \
        -i image/overview/G107bI305_post.jpg \
        -t image/overview/G107bI305B/G107bI305B.csv \
        -o image/overview/G107bI305B/G107bI305B.jpg \
        -m image/overview/G107bI305B/G107bI305B_marked.jpg
```

```{sh}
lmdmap -n G107bI305B \
        -x -40 -w 5 \
        -i image/overview/G107bI305_post.jpg \
        -t image/overview/G107bI305B/G107bI305B.csv \
        -o image/overview/G107bI305B/G107bI305B.jpg \
        -m image/overview/G107bI305B/G107bI305B_marked.jpg
```

```{sh}
lmdmap -n G107bI305B \
        -x -40 -w 5 -a \
        -i image/overview/G107bI305_pre.jpg \
        -t image/overview/G107bI305B/G107bI305B.csv \
        -o image/overview/G107bI305B/G107bI305B.jpg \
        -m image/overview/G107bI305B/G107bI305B_marked.jpg
```

#### G122eI105A

```{sh}
lmdmap -n G122eI105A \
        -i image/overview/G122eI105_post.jpg \
        -t image/overview/G122eI105A/G122eI105A.csv \
        -o image/overview/G122eI105A/G122eI105A.jpg \
        -m image/overview/G122eI105A/G122eI105A_marked.jpg
```

```{sh}
lmdmap -n G122eI105A \
        -s 900 -x -30 -w 5 \
        -i image/overview/G122eI105_post.jpg \
        -t image/overview/G122eI105A/G122eI105A.csv \
        -o image/overview/G122eI105A/G122eI105A.jpg \
        -m image/overview/G122eI105A/G122eI105A_marked.jpg
```

```{sh}
lmdmap -n G122eI105A \
        -s 900 -x -30 -w 5 -a \
        -i image/overview/G122eI105_pre.jpg \
        -t image/overview/G122eI105A/G122eI105A.csv \
        -o image/overview/G122eI105A/G122eI105A.jpg \
        -m image/overview/G122eI105A/G122eI105A_marked.jpg
```

#### G122eI105B

```{sh}
lmdmap -n G122eI105B \
        -i image/overview/G122eI105_post.jpg \
        -t image/overview/G122eI105B/G122eI105B.csv \
        -o image/overview/G122eI105B/G122eI105B.jpg \
        -m image/overview/G122eI105B/G122eI105B_marked.jpg
```

```{sh}
lmdmap -n G122eI105B \
        -s 900 -x -25 -w 6 \
        -i image/overview/G122eI105_post.jpg \
        -t image/overview/G122eI105B/G122eI105B.csv \
        -o image/overview/G122eI105B/G122eI105B.jpg \
        -m image/overview/G122eI105B/G122eI105B_marked.jpg
```

```{sh}
lmdmap -n G122eI105B \
        -s 900 -x -25 -w 6 -a \
        -i image/overview/G122eI105_pre.jpg \
        -t image/overview/G122eI105B/G122eI105B.csv \
        -o image/overview/G122eI105B/G122eI105B.jpg \
        -m image/overview/G122eI105B/G122eI105B_marked.jpg
```

#### G125eI201A

```{sh}
lmdmap -n G125eI201A \
        -i image/overview/G125eI201_post.jpg \
        -t image/overview/G125eI201A/G125eI201A.csv \
        -o image/overview/G125eI201A/G125eI201A.jpg \
        -m image/overview/G125eI201A/G125eI201A_marked.jpg
```

> [!WARNING]
> Seems to be quite off

#### G125eI201B

```{sh}
lmdmap -n G125eI201B \
        -i image/overview/G125eI201_post.jpg \
        -t image/overview/G125eI201B/G125eI201B.csv \
        -o image/overview/G125eI201B/G125eI201B.jpg \
        -m image/overview/G125eI201B/G125eI201B_marked.jpg
```
## 2025-06-23

### MSEB0014

#### G121eI104A

> [!WARNING]
> All spatial information is incorrect. No spatial data was recorded.

#### G121eI104B

> [!WARNING]
> All spatial information is incorrect. No spatial data was recorded.

### MSEB0015

#### G121eI104C

```{sh}
lmdmap -n G121eI104C \
        -i image/overview/G121eI104_post2.jpg \
        -t image/overview/G121eI104C/G121eI104C.csv \
        -o image/overview/G121eI104C/G121eI104C.jpg \
        -m image/overview/G121eI104C/G121eI104C_marked.jpg

lmdmap -n G121eI104C \
        -s 900 -x -45 -w 5 \
        -i image/overview/G121eI104_post2.jpg \
        -t image/overview/G121eI104C/G121eI104C.csv \
        -o image/overview/G121eI104C/G121eI104C.jpg \
        -m image/overview/G121eI104C/G121eI104C_marked.jpg

lmdmap -n G121eI104C \
        -s 900 -x -35 -w 5 -a \
        -i image/overview/G121eI104_pre.jpg \
        -t image/overview/G121eI104C/G121eI104C.csv \
        -o image/overview/G121eI104C/G121eI104C.jpg \
        -m image/overview/G121eI104C/G121eI104C_marked.jpg
```

> [!NOTE]
> All good!

## 2025-06-17

### MSEB0012

#### G121eO302A

```{sh}
lmdmap -n G121eO302A \
        -i image/overview/G121eO302_post.jpg \
        -t image/overview/G121eO302A/G121eO302A.csv \
        -o image/overview/G121eO302A/G121eO302A.jpg \
        -m image/overview/G121eO302A/G121eO302A_marked.jpg

lmdmap -n G121eO302A \
        -s 1300 -x -75 \
        -i image/overview/G121eO302_post.jpg \
        -t image/overview/G121eO302A/G121eO302A.csv \
        -o image/overview/G121eO302A/G121eO302A.jpg \
        -m image/overview/G121eO302A/G121eO302A_marked.jpg

lmdmap -n G121eO302A \
        -s 1300 -x -90 -a \
        -i image/overview/G121eO302_pre.jpg \
        -t image/overview/G121eO302A/G121eO302A.csv \
        -o image/overview/G121eO302A/G121eO302A.jpg \
        -m image/overview/G121eO302A/G121eO302A_marked.jpg
```

> [!WARNING]
> Pre and post images are a bit shifted, so x-axis correction was updated.

#### G121eO302B

```{sh}
lmdmap -n G121eO302B \
        -i image/overview/G121eO302_post.jpg \
        -t image/overview/G121eO302B/G121eO302B.csv \
        -o image/overview/G121eO302B/G121eO302B.jpg \
        -m image/overview/G121eO302B/G121eO302B_marked.jpg

lmdmap -n G121eO302B \
        -s 1500 -x -210 -y 1150 \
        -i image/overview/G121eO302_post.jpg \
        -t image/overview/G121eO302B/G121eO302B.csv \
        -o image/overview/G121eO302B/G121eO302B.jpg \
        -m image/overview/G121eO302B/G121eO302B_marked.jpg

lmdmap -n G121eO302B \
        -s 1500 -x -260 -y 1150 -a \
        -i image/overview/G121eO302_pre.jpg \
        -t image/overview/G121eO302B/G121eO302B.csv \
        -o image/overview/G121eO302B/G121eO302B.jpg \
        -m image/overview/G121eO302B/G121eO302B_marked.jpg
```

> [!WARNING]
> Pre and post images are a bit shifted, so x-axis correction was updated.
> No original PDF created from cutting.

#### G103bO201A

```{sh}
lmdmap -n G103bO201A \
        -i image/overview/G103bO201_post.jpg \
        -t image/overview/G103bO201A/G103bO201A.csv \
        -o image/overview/G103bO201A/G103bO201A.jpg \
        -m image/overview/G103bO201A/G103bO201A_marked.jpg

lmdmap -n G103bO201A \
        -s 750 -x -130 -y 10 \
        -i image/overview/G103bO201_post.jpg \
        -t image/overview/G103bO201A/G103bO201A.csv \
        -o image/overview/G103bO201A/G103bO201A.jpg \
        -m image/overview/G103bO201A/G103bO201A_marked.jpg

lmdmap -n G103bO201A \
        -s 750 -x -130 -y 10 -a \
        -i image/overview/G103bO201_pre.jpg \
        -t image/overview/G103bO201A/G103bO201A.csv \
        -o image/overview/G103bO201A/G103bO201A.jpg \
        -m image/overview/G103bO201A/G103bO201A_marked.jpg
```

> [!NOTE]
> No notes.

#### G103bO202A

```{sh}
lmdmap -n G103bO202A \
        -i image/overview/G103bO202_post.jpg \
        -t image/overview/G103bO202A/G103bO202A.csv \
        -o image/overview/G103bO202A/G103bO202A.jpg \
        -m image/overview/G103bO202A/G103bO202A_marked.jpg

lmdmap -n G103bO202A \
        -s 750 -x -90 \
        -i image/overview/G103bO202_post.jpg \
        -t image/overview/G103bO202A/G103bO202A.csv \
        -o image/overview/G103bO202A/G103bO202A.jpg \
        -m image/overview/G103bO202A/G103bO202A_marked.jpg

lmdmap -n G103bO202A \
        -s 750 -x -90 -a \
        -i image/overview/G103bO202_pre.jpg \
        -t image/overview/G103bO202A/G103bO202A.csv \
        -o image/overview/G103bO202A/G103bO202A.jpg \
        -m image/overview/G103bO202A/G103bO202A_marked.jpg
```

> [!NOTE]
> No notes.

#### G103bO202B

```{sh}
lmdmap -n G103bO202B \
        -i image/overview/G103bO202_post.jpg \
        -t image/overview/G103bO202B/G103bO202B.csv \
        -o image/overview/G103bO202B/G103bO202B.jpg \
        -m image/overview/G103bO202B/G103bO202B_marked.jpg

lmdmap -n G103bO202B \
        -s 750 -x -90 \
        -i image/overview/G103bO202_post.jpg \
        -t image/overview/G103bO202B/G103bO202B.csv \
        -o image/overview/G103bO202B/G103bO202B.jpg \
        -m image/overview/G103bO202B/G103bO202B_marked.jpg

lmdmap -n G103bO202B \
        -s 750 -x -90 -a \
        -i image/overview/G103bO202_pre.jpg \
        -t image/overview/G103bO202B/G103bO202B.csv \
        -o image/overview/G103bO202B/G103bO202B.jpg \
        -m image/overview/G103bO202B/G103bO202B_marked.jpg
```

#### G103bO202C

```{sh}
lmdmap -n G103bO202C \
        -i image/overview/G103bO202_post.jpg \
        -t image/overview/G103bO202C/G103bO202C.csv \
        -o image/overview/G103bO202C/G103bO202C.jpg \
        -m image/overview/G103bO202C/G103bO202C_marked.jpg

lmdmap -n G103bO202C \
        -s 750 -x -100 \
        -i image/overview/G103bO202_post.jpg \
        -t image/overview/G103bO202C/G103bO202C.csv \
        -o image/overview/G103bO202C/G103bO202C.jpg \
        -m image/overview/G103bO202C/G103bO202C_marked.jpg

lmdmap -n G103bO202C \
        -s 750 -x -100 -a \
        -i image/overview/G103bO202_pre.jpg \
        -t image/overview/G103bO202C/G103bO202C.csv \
        -o image/overview/G103bO202C/G103bO202C.jpg \
        -m image/overview/G103bO202C/G103bO202C_marked.jpg
```

#### G103bO201B

```{sh}
lmdmap -n G103bO201B \
        -i image/overview/G103bO201_post.jpg \
        -t image/overview/G103bO201B/G103bO201B.csv \
        -o image/overview/G103bO201B/G103bO201B.jpg \
        -m image/overview/G103bO201B/G103bO201B_marked.jpg

lmdmap -n G103bO201B \
        -s 750 -x -110 -y 10 \
        -i image/overview/G103bO201_post.jpg \
        -t image/overview/G103bO201B/G103bO201B.csv \
        -o image/overview/G103bO201B/G103bO201B.jpg \
        -m image/overview/G103bO201B/G103bO201B_marked.jpg

lmdmap -n G103bO201B \
        -s 750 -x -110 -y 10 -a \
        -i image/overview/G103bO201_pre.jpg \
        -t image/overview/G103bO201B/G103bO201B.csv \
        -o image/overview/G103bO201B/G103bO201B.jpg \
        -m image/overview/G103bO201B/G103bO201B_marked.jpg
```

> [!NOTE]
> No notes.

#### G103bO201C

```{sh}
lmdmap -n G103bO201C \
        -i image/overview/G103bO201_post.jpg \
        -t image/overview/G103bO201C/G103bO201C.csv \
        -o image/overview/G103bO201C/G103bO201C.jpg \
        -m image/overview/G103bO201C/G103bO201C_marked.jpg

lmdmap -n G103bO201C \
        -x -120 -y 40 -w 20 -l 20 -c -e -d M301277,M301270,M301278 \
        -i image/overview/G103bO201_post.jpg \
        -t image/overview/G103bO201C/G103bO201C.csv \
        -o image/overview/G103bO201C/G103bO201C.jpg \
        -m image/overview/G103bO201C/G103bO201C_marked.jpg

lmdmap -n G103bO201C \
        -x -120 -y 40 -w 20 -l 20 -e -d M301277,M301270,M301278 -a \
        -i image/overview/G103bO201_pre.jpg \
        -t image/overview/G103bO201C/G103bO201C.csv \
        -o image/overview/G103bO201C/G103bO201C.jpg \
        -m image/overview/G103bO201C/G103bO201C_marked.jpg
```

> [!NOTE]
> Discarded samples were membrane controls.

## 2025-06-13

### MSEB0011

#### G121eI103A

```{sh}
lmdmap -n G121eI103A \
        -i image/overview/G121eI103_post.jpg \
        -t image/overview/G121eI103A/G121eI103A.csv \
        -o image/overview/G121eI103A/G121eI103A.jpg \
        -m image/overview/G121eI103A/G121eI103A_marked.jpg

lmdmap -n G121eI103A \
        -x -30 -y -2 -w 5 \
        -i image/overview/G121eI103_post.jpg \
        -t image/overview/G121eI103A/G121eI103A.csv \
        -o image/overview/G121eI103A/G121eI103A.jpg \
        -m image/overview/G121eI103A/G121eI103A_marked.jpg

lmdmap -n G121eI103A \
        -x -30 -y -2 -w 5 \
        -i image/overview/G121eI103_pre.jpg \
        -t image/overview/G121eI103A/G121eI103A.csv \
        -o image/overview/G121eI103A/G121eI103A.jpg \
        -m image/overview/G121eI103A/G121eI103A_marked.jpg
```

> [!NOTE]
> No notes.

#### G121eI103B

```{sh}
lmdmap -n G121eI103B \
        -i image/overview/G121eI103_post.jpg \
        -t image/overview/G121eI103B/G121eI103B.csv \
        -o image/overview/G121eI103B/G121eI103B.jpg \
        -m image/overview/G121eI103B/G121eI103B_marked.jpg

lmdmap -n G121eI103B \
        -x -40 -y -10  \
        -i image/overview/G121eI103_post.jpg \
        -t image/overview/G121eI103B/G121eI103B.csv \
        -o image/overview/G121eI103B/G121eI103B.jpg \
        -m image/overview/G121eI103B/G121eI103B_marked.jpg

lmdmap -n G121eI103B \
        -x -40 -y -10  \
        -i image/overview/G121eI103_pre.jpg \
        -t image/overview/G121eI103B/G121eI103B.csv \
        -o image/overview/G121eI103B/G121eI103B.jpg \
        -m image/overview/G121eI103B/G121eI103B_marked.jpg
```

> [!CAUTION]
> Some cuts are not present in the PDF output.

#### G103bI301A

```{sh}
lmdmap -n G103bI301A \
        -i image/overview/G103bI301_post.jpg \
        -t image/overview/G103bI301A/G103bI301A.csv \
        -o image/overview/G103bI301A/G103bI301A.jpg \
        -m image/overview/G103bI301A/G103bI301A_marked.jpg

lmdmap -n G103bI301A \
        -x -82 -w 5 \
        -i image/overview/G103bI301_post.jpg \
        -t image/overview/G103bI301A/G103bI301A.csv \
        -o image/overview/G103bI301A/G103bI301A.jpg \
        -m image/overview/G103bI301A/G103bI301A_marked.jpg

lmdmap -n G103bI301A \
        -x -82 -w 5 \
        -i image/overview/G103bI301_pre.jpg \
        -t image/overview/G103bI301A/G103bI301A.csv \
        -o image/overview/G103bI301A/G103bI301A.jpg \
        -m image/overview/G103bI301A/G103bI301A_marked.jpg
```
> [!WARNING]
> M301068, M301084 and M301085 look like membrane controls, but logged as positive. Pixel coordinates were removed.

#### G103bI301B

```{sh}
lmdmap -n G103bI301B \
        -i image/overview/G103bI301_post.jpg \
        -t image/overview/G103bI301B/G103bI301B.csv \
        -o image/overview/G103bI301B/G103bI301B.jpg \
        -m image/overview/G103bI301B/G103bI301B_marked.jpg

lmdmap -n G103bI301B \
        -x -105 -e \
        -i image/overview/G103bI301_post.jpg \
        -t image/overview/G103bI301B/G103bI301B.csv \
        -o image/overview/G103bI301B/G103bI301B.jpg \
        -m image/overview/G103bI301B/G103bI301B_marked.jpg

lmdmap -n G103bI301B \
        -x -105 -e \
        -i image/overview/G103bI301_pre.jpg \
        -t image/overview/G103bI301B/G103bI301B.csv \
        -o image/overview/G103bI301B/G103bI301B.jpg \
        -m image/overview/G103bI301B/G103bI301B_marked.jpg
```

> [!CAUTION]
> M301144 positive sample had no coordinates recorded
> Some samples that looked negative membrane controls were removed

#### Sequences

```{sh}
screen -S MSEB0011
conda activate arch3d
cd MSEB0011
arch3d microsample -m MSEB0011.csv -d input -o output -u 'Webin-69627' -p '{password}'
```

> [!NOTE]
> No warnings

### MSEB0009

#### G121eI102A

```{sh}
lmdmap -n G121eI102A \
        -i image/overview/G121eI102_pre.jpg \
        -t image/overview/G121eI102A/G121eI102A.csv \
        -o image/overview/G121eI102A/G121eI102A.jpg \
        -m image/overview/G121eI102A/G121eI102A_marked.jpg

lmdmap -n G121eI102A \
        -s 1500 -x -60 -y -50 -w 50 -l 50 \
        -i image/overview/G121eI102_pre.jpg \
        -t image/overview/G121eI102A/G121eI102A.csv \
        -o image/overview/G121eI102A/G121eI102A.jpg \
        -m image/overview/G121eI102A/G121eI102A_marked.jpg
```

> [!WARNING]
> No post-cut image was generated.

#### Sequences

```{sh}
screen -S MSEB0009
conda activate arch3d
cd MSEB0009
arch3d microsample -m MSEB0009.csv -d input -o output -u 'Webin-69627' -p '{password}'
```



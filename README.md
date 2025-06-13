# 3D'omics archive
Repository logging archiving of 3D'omics data.

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
```

> [!CAUTION]
> COORDINATE LOGGING ERROR. PROBABLY MEMBRANE CONTROLS ENTERED AS POSITIVE

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
```

> [!CAUTION]
> TOO BIG DISTORTION TO CORRECT

#### Sequences

```{sh}
arch3d microsample -m data/microsample/MSEB0009.csv -d data/ -o test -u 'Webin-69627' -p '{password}'
```

> [!NOTE]
> No warnings

### MSEB0009

#### G121eI102A

```{sh}
lmdmap -n G121eI102A \
        -i image/overview/G121eI102A/G121eI102_pre.jpg \
        -t image/overview/G121eI102A/G121eI102A.csv \
        -o image/overview/G121eI102A/G121eI102A.jpg \
        -m image/overview/G121eI102A/G121eI102A_marked.jpg

lmdmap -n G121eI102A \
        -x -60 -y -50 -w 50 -l 50 \
        -i image/overview/G121eI102A/G121eI102_pre.jpg \
        -t image/overview/G121eI102A/G121eI102A.csv \
        -o image/overview/G121eI102A/G121eI102A.jpg \
        -m image/overview/G121eI102A/G121eI102A_marked.jpg
```

> [!ERROR]
> Section size is too large for framing in 1000x1000 pixels





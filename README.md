# 3D'omics archive
Repository logging archiving of 3D'omics data.

## 2025-06-13

### G121eI102A

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

### MSEB0009

```{sh}
arch3d microsample -m data/microsample/MSEB0009.csv -d data/ -o test -u 'Webin-69627' -p '{password}'
```

> [!NOTE]
> No warnings



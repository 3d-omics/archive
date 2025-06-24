# 3D'omics archive
Repository logging archiving of 3D'omics data.

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

#### G095eI108A

```{sh}
lmdmap -n G095eI108A \
        -i image/overview/G095eI108_post.jpg \
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

#### G096eI107A

```{sh}
lmdmap -n G096eI107A \
        -i image/overview/G096eI107_post.jpg \
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

#### G097eI107A

```{sh}
lmdmap -n G097eI107A \
        -i image/overview/G097eI107_post.jpg \
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

#### G105bI105B

```{sh}
lmdmap -n G105bI105B \
        -i image/overview/G105bI105_post.jpg \
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

#### G107bI305A

```{sh}
lmdmap -n G107bI305A \
        -i image/overview/G107bI305_post.jpg \
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

#### G122eI105A

```{sh}
lmdmap -n G122eI105A \
        -i image/overview/G122eI105_post.jpg \
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



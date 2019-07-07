# KOI


## UI

[Preview - https://75mm-studio.github.io/koi/](https://75mm-studio.github.io/koi/)


## Folder Structure

```
INPUT (From Client)

S001
    ├─ CIR_01_0010
    |   └─ CIR_01_0010.####.dpx
    └─ CIR_02_0020
        └─ CIR_02_0020.####.dpx
```

```
RESULT
/show/lazypic_190701_circle/scenes/S001/CIR_01_0010/plate/dpx/CIR_01_0010.####.dpx
/show/lazypic_190701_circle/scenes/S001/CIR_02_0020/plate/dpx/CIR_02_0020.####.dpx

show
└─ SHOW_NAME <client>_<create date>_<project name> (ex. lazypic_190701_circle)
    ├─ assets
    ├─ data
    ├─ images
    ├─ input
    ├─ output
    ├─ sourceimages
    └─ scenes
        └─ SEQUENCE_NAME (ex. S001)
            └─ SHOT_NAME <plate_name> (ex. CIR_01_0010)
                └─ plate
                    └─ PLATE_FILE_EXTENTION (ex. dpx)
                        └─  <plate_name>.####.<plate_file_extention> (ex. CIR_01_0010.####.dpx)
```

## CSV FORMAT (DB)
[https://github.com/lazypic/koi/blob/master/data/show/75MM.csv](https://github.com/lazypic/koi/blob/master/data/show/75MM.csv)

## 웹 애플리케이션 튜토리얼

1. HTML
    - [WEB1 - HTML & Internet | 생활코딩](https://opentutorials.org/course/3084) | [Youtube 자동재생](https://www.youtube.com/playlist?list=PLuHgQVnccGMDZP7FJ_ZsUrdCGH68ppvPb)
    - [HTML - Build a Website | Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpMSXUYwxDFOvyxlssug29Fu)

1. CSS
    - [WEB2 - CSS | 생활코딩](https://opentutorials.org/course/3086) | [Youtube 자동재생](https://www.youtube.com/playlist?list=PLuHgQVnccGMAnWgUYiAW2cTzSBywFO75B)
    - [CSS - Style Your Website | Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpNO7ScZFr-WTmtcBY3AN1M7)
    - [Bootstrap](https://getbootstrap.com/)

1. JavaScript
    - [WEB2 - JavaScript | 생활코딩](https://opentutorials.org/course/3085) | [Youtube 자동재생](https://www.youtube.com/playlist?list=PLuHgQVnccGMBB348PWRN0fREzYcYgFybf)
    - [JavaScript for Web Browser (생활코딩)](https://www.youtube.com/playlist?list=PLuHgQVnccGMDTAQ0S_FYxXOi1ZJz4ikaX)
    - [Javascript - Programming Language | Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpPQbcrA-SzALJeFm23tPrAI)


## Golang 튜토리얼

[Introduction to the Go Programming Language](https://pythonprogramming.net/go/introduction-go-language-programming-tutorial/)

## Golang MongoDB Tutorial

[MongoDB programming in Go (golang) - Part 1](https://www.youtube.com/watch?v=WjbeukMQP2E&list=PL0aDKsruoiW2jac2D2flxZofQLfEOc2GU&index=20)
[MongoDB programming in Go (golang) - Part 2](https://www.youtube.com/watch?v=3feOIdbq2LQ&list=PL0aDKsruoiW2jac2D2flxZofQLfEOc2GU&index=22)

## [Build Web Apps with Go Language (golang)](https://www.youtube.com/watch?v=Vlie-srOU8c)

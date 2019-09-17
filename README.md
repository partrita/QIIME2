
# QIIME2 분석용 Repo

언젠가 폴더 정리를 할 것이다.

## QIIME2

![](https://qiime2.org/assets/img/qiime2.svg)

> QIIME 2™ is a next-generation microbiome bioinformatics platform that is extensible, free, open source, and community developed.


# 규칙.1

1. 각 분석은 개별 폴더를 만들어 사용한다.
2. 관련 데이터는 각 폴더안에 들어가야한다.
3. 분석과정은 주피터 노트북(`.ipynb`)안에 명시한다.

# 파일용량이 큰 경우

`Github`은 파일 용량 제한이 있다. `git add` 에서는 문제가 없지만 `push` 하려고하면 파일 업로드 크기(100Mb)에 제한이 있다. 제한을 수정하지 않은 채, 파일을 지우고 새로운 커밋을 push하려고 해도 에러가 난다. 왜냐하면 워킹 트리에서 이전에 (용량이 넘은 파일을) 추가했던 커밋에는 그 파일이 있기 때문이다. 그때는 `git reset HEAD^` 으로 커밋을 되돌려야한다.

## Git-lfs 사용하기

https://git-lfs.github.com/

## 포기하기

`.gitignore`에 해당 파일을 추가한다.

# README.MD 없이 REPO 만드는 명령 순서

## or create a new repository on the command line

1.echo "# minsung" >> README.md
1.git init
1.git add README.md
1.git commit -m "first commit"
1.git remote add origin https://github.com/xmlnsBuzz/minsung.git
1.git push -u origin master

## or push an existing repository from the command line

1.git remote add origin https://github.com/xmlnsBuzz/minsung.git
1.git push -u origin master

## or import code from another repository

1.You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

## git을 clone하면 repository name과 같은 폴더이름이 생기므로 git bash에서 clone한 후에

1.해당 폴더로 이동
>_cd '해당폴더 이름'_

git clone으로 github repository를 '복제'했을 경우에는 

>git init

라는 명령을 따로 할 필요 없다. 탐색기에서 숨김파일 보이기 옵션을 선택하면 '.git' 폴더가 생성되어 숨겨진 것을 볼 수 있다.

## commit message를 수정하고 싶은 경우
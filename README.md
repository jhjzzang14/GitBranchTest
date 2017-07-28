# 간단한 git 사용 방법

### clone

<li> git 홈페이지에서 repository를 만든다.
<li> 터미널(커맨드라인)을 실행시키고 원하는 경로를 설정하고 clone을 한다.
<li> ex) git clone "git repository http url"
<li> 해당 경로에 git에서 받아온 폴더가 생성 될 것이다

### commit
 
<li> commit은 분기를 지정해는것으로 예를 들어 작업 중이던 파일이 문제가 생겼을 때 commit한 지점으로 돌아갈 수 있다
<li> commit을 하기전에 새로 생성되거나 수정된 파일이 있는 경우 git add "파일명" 또는 git add * 를 입력
<li> ex) git commit -m "message"
 
### push

<li> commit을 한 경우 local에 저장되어 있는 상태이므로 remote 저장소에 저장 하려고 하면 push를 해줘야한다
<li> ex) git push origin master
 
### pull

<li> pull은 remote 저장소에서 데이터를 가지고 오는 명령어이다
<li> git pull 
 
## 마지막으로

작업을 하면서 필요할 때 마다 분기를 지정하기를 원하면 commit 하고자 하는 파일을 add 하고 commit 시켜주면 분기점이 생겨
작업을 하다가 문제가 생겨도 해당 분기로 돌아갈수 있어서 일을 효율적으로 할 수 있게 된다


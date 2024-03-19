## WIL 1
file은 Untracked와 Tracked로 나뉜다.<br>Tracked는 Unmodified, Modified, Staged로 다시 나뉜다.
<br>Git의 큰 그림을 그리자면 우선 크게 local과 Remote로 나뉜다.
<br>local의 Working Directory에서 파일을 git add해서 Staging Area로 올린다.<br>파일이 적절히 모여 버전을 만들게 되면 git commit을 해서 local repo에 올린다.<br>이 버전을 git push를 통해 github, gitnavi?와 같은 remote repo에 올리면 Github 사용 성공이다. <br/> git pull을 통해 remote repo의 파일을 working directory로 가져올 수도 있다.
# Git 사용



## 목차

1. Git을 통해 내 repotories에 파일 올리기
2. Git으로 내 repotories 에 팀원 접근 허락하기
3. Git으로 상대 repotories에 접근하기
4. master 이외에 추가 branch  만들기
5. 내 repotory brunch 관리
6. 주의사항



## 1. Git 을 통해 내 repotories에 파일 올리기

> `typora`에서 파일 만들기, `git`에서 repositories 만들기(주소), `git bash`에서 해당 주소 에 파일 올리기

1. `Typora` 에서 문서작성 (README.md 로 작성시에 repotories 열자마자 확인 가능)

2. `git`에서 your repotories 에서 new ,repository name 설정 후 새로 작성

3. 해당 주소를 복사

   ![image-20210317205824464](C:\Users\rn061\AppData\Roaming\Typora\typora-user-images\image-20210317205824464.png)

4. `git bash`에서 `mkdir` 로 파일 생성, `cd [폴더명]`으로 폴더 접근 `git init` 으로 git 관리 시작

5. 해당 폴더에 파일 넣기

6. `git status` 로 상태 확인 `git add [파일명]`,  `git commit -m "변경점"`  으로 로그 생성

7. `git remote add origin [주소]`를 입력 `git push --set-upstream origin master` or `git push origin master` 로 파일 보내기



## 2. Git으로 내 repotories 에 팀원 접근 허락하기

1. git 에서 repositories 중 공유할 repositories 클릭

2. 해당 그림에서 Setttings 클릭![image-20210317211104471](C:\Users\rn061\AppData\Roaming\Typora\typora-user-images\image-20210317211104471.png)

   

3. `Manage access` 란에서 `invite a collaborator` 로 팀원 주소 입력.

4. 해당 주소를 팀원이 수락하면 사용 가능



## 3. Git으로 상대 repotories에 접근하기

1. 팀장이 보낸 허가 메세지 수락

2. 다음에서 주소 복사

   ![image-20210317211457531](C:\Users\rn061\AppData\Roaming\Typora\typora-user-images\image-20210317211457531.png)

3. `git bash` 에서 `git clone [주소]` 입력 `(처음에만 clone 이용 두번째부터는 pull 이용할 것)`

4. `cd [파일명]`으로 접근 `code .`으로 파일 열고 변경 입력

5. `git add` , `git commit -m "변경"`, `git push`로 파일 올리기



## 4.master 이외에 추가 branch  만들기

> - `git branch` : 현재 브랜치 목록 확인
> - `git branch [branch명]` : 브랜치 새로 만들기
> - `git checkout [branch명] `: 브랜치 위치로 Head 이동
> - `git merge [branch명] `: 브랜치와 병합 `(반드시 head는 master에 있을 것)`
> - `git branch -d [branch명]`: 기존의 브랜치 삭제



## 5. open source repositories 가져오기

1. 아래 `fork`클릭

   ![image-20210317215557559](C:\Users\rn061\AppData\Roaming\Typora\typora-user-images\image-20210317215557559.png)

2. `code` 에서 주소 가져오기

   ![image-20210317215750388](C:\Users\rn061\OneDrive\바탕 화면\image-20210317215750388.png)

3. `git clone [주소]`로 가져오기`(처음에만 clone 이용 두번째부터는 pull 이용할 것)`




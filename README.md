# git 명령어 모음집
      - 실행 방법 순서대로 작성되었습니다.
      
참고 사이트
      - https://opentutorials.org/module/2676/15172
      
0. init - 저장소 만들기
      - mkdir <폴더 이름>    : 폴더 만들기
      - cd <폴더 이름>       : 경로 이동
      - git init            : 저장소 만들기
      - rm -r .git : .git 제거



1. commit - 버전 만들기
      - **버전 관리자 정보 입력**
      - git config --list : config 확인
      - git config user.name "이름" : user 이름 등록
      - git config user.email ***@***.com : user 이메일 등록
      - **스테이지 영역(staging area)**
      - 변경 전에 staging area에 저장(
      - git add 특정 파일: 특정 파일만 추가
      - git add . : 변경된 모든 파일 추가
      - **버전 만들기**
      - git commit : 버전 메세지 작성이 생성된다.
      - git commit -m "버전 메세지 작성" : -m ""은 버전 메세지를 바로 작성하고 생성 가능
2. log - 버전 차이 확인
      - git log -p 


3. reset, revert - 과거 버전으로 돌아가기
      - ~ ing

5. remote - 원격 저장소 관리
    - git remote -v : remote 된 이름들을 확인 가능
    - git remote add [remote 이름] [git 주소] : 저장소 추가 
    - git remote rm [remote 이름]
    - git remote rename [remote 이름] [변경할 remote 이름]


4. fetch vs pull 차이점<br/>
    - **fetch**
        - 원격 저장소의 내용을 확인만 하고 로컬 데이터와 병합은 하고 싶지 않은 경우 사용
        - 원격 저장소의 최신 이력을 확인 가능, 이 때 가져온 최신 커밋 이력은 이름 없는 브랜치로 로컬에 가져오게 된다. (아직 여기 부분 이해가 안된다.)
    - **pull**
        - 원격 저장소의 내용을 가져와 자동으로 병합 작업을 실행
        - fetch 후 merge를 수행하면, pulll 명령을 실행 했을 때와 같다. (fetch + merge)


# 리눅스 명령어
0. 현재 디렉토리 폴더 확인
      - ls -al


1. 텍스트 폴더 생성 및 확인
      - **vim** f1.txt : f1 이라는 텍스트 파일 만들기
      - **i** 누르기 : 하단에 INSERT로 변경되며 작성 가능
      - **esc** : 입력 종료, 만약 다시 작성하고 싶으면 다시 i 누르기
      - **:** : 명령어 입력 가능
      - **w** 저장, **q** 종료, **wq** 저장과 종료 동시에
      - **cat f1.txt** : f1.txt 파일 내용 확인하기


2. 복사 
      - cp f1.txt f2.txt : f1을 f2로 복사

3. conda 자동활성화 해제
      - conda config --set auto_activate_base false

4.심볼릭 링크(symbolic link) 란?   
      - 링크를 연결하여 원본 파일을 직접 사용하는 것과 같은 효과를 내는 링크이다.  윈도우의 바로가기와 비슷한 개념   
      - 특정 폴더에 링크를 걸어 NAS, library 원본 파일을 사용하기 위해 심볼릭 링크를 사용한다.   


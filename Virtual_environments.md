# Anaconda_virtual_environments

프로젝트를 진행하다 보면 여러 모델들이 요구하는 환경 및 라이브러리 버전들이 다를 수 있다.<br/>

여기에 대비할 수 있도록 아나콘다 가상 환경 만드는 방법을 공부해보자!!<br/>

참고 사이트<br/>
https://hyunlee103.tistory.com/58<br/>


1. 콘다 가상환경 설정<br/>
  - conda create -n (가상환경 이름) python=(버전)<br/>

  1.1 콘다 파이썬 버전 변경 <br/>
    - condan install python=x.x.x<br/>

  1.2 콘다 가상환경 목록 출력<br/>
    - conda env list


2. 가상환경 접수
  - conda activate (가상환경 이름)

  2-1. 가상환경 나오기
    - conda deactivate


3. 패키지 설치
- conda install (패키지)


4. 현재 activate된 가상환경에 설치된 패키지 목록 출력
- conda list

# 파이썬 venv 가상환경

참고사이트: http://hleecaster.com/python-venv/ <br/>

삭제 방법: 명령어가 따로 존재하지 않음, 폴더 내에서 휴지통으로 보내면 된다.


# 파이참 get from vcs(Version Control)
![image](https://user-images.githubusercontent.com/57121112/120283220-e9c96c80-c2f5-11eb-826c-2553416730a0.png)

git clone을 사용하면 git에 있는 내용들을 폴더에 가져온다. <br/>

파이참 get from vcs 에서  git 주소를 입력하면 **파이참 내** git clone 작업을 실행해준다. <br/>

또한, 가상환경 interpret도 생성이 되어 프로젝트에 맞는 가상환경을 설정할 수 있다. 굿이다~!

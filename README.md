
# Flutter 사용법

**flutter install** 검색 후 설치
**Android Studio** 설치

**Android Studio** 에서 *plugins*에서 **flutter** 검색 후 설치(설치 시 버전 골라서 받을 때 OS 한번더 확인 하고 받을 것)

*SDK Manager*  -> *sdk tools* -> *android sdk command-line tools* 설치


### 환경변수 설정

**Window** 
&nbsp;&nbsp;*path* 추가하기 눌러서 *flutter* 폴더 안의 *bin* 폴더까지 복사해서 추가

**Mac**
&nbsp;&nbsp;**zsh** 기준으로 **terminal** 열어서
&nbsp;&nbsp;*touch ~/zshrc*
&nbsp;&nbsp;*open ~/.zshrc*

*export PATH="$PATH:/[flutter path/bin"*
저장


## Flutter project 생성
**SDK** 위치는 flutter 압축 푼곳

## lint 끄는 방법
**(analysis_options.yaml)**


*rules:
&nbsp;&nbsp;prefer_const_constructors: false
&nbsp;&nbsp;avoid_print: false
&nbsp;&nbsp;prefer_typing_uninitialized_variables: false
&nbsp;&nbsp;prefer_const_constructors_in_immutables: false
&nbsp;&nbsp;prefer_const_literals_to_create_immutables : false*


### 잡다한 시작 기본 문법

**void main MyApp** 밑에 다 삭제 후
**stless** 자동 완성
**위젯** 대문자로 시작, 소괄호 사용

ex)
**TEXT("")**
**Icon(Icons.start)**
**Image.asset(path)** (프로젝트에서 assets 폴더생성)

**(pubspec.yaml)**
flutter:
&nbsp;&nbsp;assets:
&nbsp;&nbsp;&nbsp;&nbsp;- assets/ 
저장 후


### 레이아웃 생성요령
**Materal app** -> 구글, 커스터마이징
**cupetino** -> 애플 너낌

**Scaffold** 사용 하여 레이아웃 기본 3등분
&nbsp;&nbsp;**appbar, body, bottomNavigationBar**

home: Scaffold(
    &nbsp;&nbsp;appBar: AppBar(), 
   &nbsp;&nbsp; body: Container(),  
   &nbsp;&nbsp; bottomNavigationBar: BottomAppBar(),
    )






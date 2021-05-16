# 미니게임 배틀로얄

## 목차
### 1. 소개
### 2. 서버
### 3. 클라이언트

## 1. 소개
![first](https://user-images.githubusercontent.com/79510083/118403882-78f64380-b6ab-11eb-9541-fe3aba79795d.png)

### - php와 kotlin을 이용한 배틀로얄류 실시간 멀티플레이 게임
### - 총 3라운드(카드맞추기, 1to50, 사천성)로 진행되며 4명에서 시작해 한명씩 탈락하여 마지막 한명이 1등을 차지하는 방식
## 2. 서버
### - http통신
#### ㅁ Server/User_management/signup.php
#### ㅁ Server/User_management/login.php

### - Socket.io
#### ㅁ login
#### ㅁ enter
#### ㅁ chat messasge
#### ㅁ requestID
#### ㅁ disconnect
#### ㅁ roomlist
#### ㅁ createroom
#### ㅁ userDelete
#### ㅁ userlist
#### ㅁ gameStart
#### ㅁ gameReady
#### ㅁ requestOpScreen
#### ㅁ sendScreen
#### ㅁ sendAction
#### ㅁ opscreenExit
#### ㅁ mcsendScreen
#### ㅁ gameClear

### - php기반으로 만들어 졌으며 phpsocket.io 라이브러리를 이용하여 실시간으로 양방향 통신이 가능하게 설계
## 3. 클라이언트
### - android studio를 이용한 kotlin 기반의 android 클라이언트

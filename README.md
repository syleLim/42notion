# 42notion

### 01 Libft
#### 목표
c standard library의 일부를 직접 제작해 본다.
<br><br>

#### 요구 지식
1. 기초적인 c compiling
    - Makefile을 다루는 법
2. library in c
    - library란?
    - lib file을 구성하는 방법
3. standard library
    - standard lib의 재구성
    - 각각의 stdandard lib에 있는 함수들의 기능
4. 메모리 관리
    - 메모리 할당과 해제
    - error case에서의 메모리 관리
<br><br>

#### GAIN
1. Makefile을 작성하는 방법
2. standard library에 있는 함수들
<br><br><br>

### 02 get_next_line
#### 목표
static변수를 이용해 주어진 메모리만큼 데이터를 읽고 한줄씩 출력하는 함수를 작성한다.
<br><br>

#### 요구 지식
1. 파일 입출력
    - 2레벨에서의 파일 입출력
2. 메모리 관리
    - 메모리 할당과 해제
    - 메모리 누수 관리
3. static 변수
    - static 변수란?
    - static 변수의 할당과 해제
<br><br>

#### GAIN
1. static 변수를 활용하는 테크닉
2. error case에 메모리를 해제하는 테크닉
3. 포인터를 이차포인터로 함수에 넘기는 테크닉
<br><br><br>

### 03 ft_printf
#### 목표
가변 변수를 활용해서 printf를 재구성한다.
<br><br>

#### 요구 지식
1. 가변 변수
    - stdarg에 대한 이해
    - stdard의 활용법
2. Parsing
    - 입력에 대한 해석
    - 파싱 모델을 구성하는 방법론
3. 자료형
    - 자료형의 크기
    - 자료형의 casting
<br><br>

#### GAIN
1. stdarg의 활용법
2. parsing 모델을 구성하는 테크닉
<br><br><br>

### 04 netwhat
#### 목표
network에 대한 기본 지식을 익힌다.
<br><br>

#### 요구 지식
1. Network
    - Network 용어 정리
    - IP, Netmask, TCP, DNS, routing...
<br><br>

#### GAIN
1. Network 용어 정리
2. NetMask 계산법
<br><br><br>

### 05 ft_server
#### 목표
docker file을 통해 webserver container를 만든다.
<br><br>

#### 요구 지식
1. Docker
    - Docker란?
    - Dockerfile의 구성법
    - Docker 명령어
2. WebServer
    - Nginx란?
    - SSL protocol
    - Nginx의 설정법(configuration 설정)
    - DB, WordPress, phpMyAdmin 연결
<br><br>

#### GAIN
1. Docker 명령어를 사용하는 방법
2. Dockerfile 활용법
3. configuration 파일 설정법
<br><br><br>

### 06 cub3d
#### 목표
간단한 ray casting 화면을 구성한다.
<br><br>

#### 요구 지식
1. Parsing
    - 입력에 대한 해석
    - 파싱에러를 처리하는 방법
    - 파싱 모델을 구성하는 방법론
2. Ray Casting
    - ray casting이란?
    - ray casting 계산법
        - 물체와 광선의 충돌을 계산하는 법
    - ray casting 계산을 실제로 적용하는 방법
<br><br>

#### GAIN
1. Raycasting 연산법
<br><br><br>

### 07 miniRT
#### 목표
간단한 ray tracing model을 만든다.
<br><br>

#### 요구 지식
1. Ray Tracing
    - Ray Tracing이란?
    - Ray Tracing 계산법
        - Vector연산의 기초
        - object의 형태에 따른 광선과 물체의 충돌 계산
        - object의 선후관계 찾기
        - shadow ray계산법
2. Object 구성
    - position
    - orientation
3. Lumination
    - Phong model
    - surface normal에 대한 빛 계산
<br><br>

#### GAIN
1. ray tracing 연산법
2. object orientation 백터화
3. lighting 연산법
<br><br><br>

### 08 libasm
#### 목표
asm을 사용해 linux lib을 작성한다.
<br><br>

#### 요구 지식
1. assembly language(asm)
    - asm이란?
    - 운영체제 버전에 따른 resister
    - resister가 동작하는 방식
<br><br>
#### GAIN
1. asm 작성법 및 complie 방법
2. resister가 동작하는 방식

<br><br><br>

### 09 ft_service
#### 목표
kubernetes와 docker container를 통해 분산서버 서비스를 관리하는 cluster를 만든다.
<br><br>

#### 요구 지식
1. Docker container
    - docker ssh 설정법
    - 각각의 기능을 담당하는 docker container의 구성법
    - nginx
    - ftps
    - mysql, wordpress, phpmyadmin
    - influxDB, grafana, telegraf
2. kubernetes
    - kubernetes cluster란?
    - kubernetes cluster의 구성
    - kubernetes cluster의 volume구성법 with yaml
    - kubernetes의 pod 구성법(service, deployment, ...) with yaml
<br><br>
#### GAIN
1. docker container를 구성하는 방법
2. kubernetes cluster를 통해 분산 서버 서비스를 관리하는 방법

<br><br><br>

### 10 miniShell
#### 목표
간단한 command line프로그램을 process를 활용해 제작한다.
<br><br>

#### 요구지식
1. parsing
    - parsing 모델을 작성하는 방법론
    - parsing을 단위별로 구성하는 방법
2. process
    - process란?
    - process간의 연결, 대기, 실행등을 관리하는 방법
3. command prompt(cmd)
    - cmd가 동작하는 방법
    - cmd의 명령어들(echo, cd, pwd, export ...)
<br><br>
#### GAIN
1. 복잡한 parsing 모델을 구현하는 방법
2. Process를 직접 구성하고 연결하는 테크닉

<br><br><br>

Preview
===
### 11 Philosopers
#### 목표
thread를 활용한 시뮬레이션만들기
<br><br>

#### 요구지식
1. thread
    - thread란?
    - pthread.h를 활용한 thread를 구성하는 법
    - thread로 동시성 프로그램을 만드는법(메모리를 공유하는 법)
2. mutex, semaphore
    - mutex, semaphore란?
    - mutex, semaphore를 통한 동시성 프로그램의 자원을 관리하는 법
<br><br><br>

### 12 CPP Module 00 ~ 08
#### 목표
C++을 익힌다.
<br><br>

#### 요구지식
1. C++에 대한 전반적인 지식
<br><br><br>

### 13 ft_containers 
#### 목표
C++ STL container의 재구성
<br><br>

#### 요구지식
1. C++의 STL container
    - 각각의 container(List, Vector ...)의 동작
    - 각각의 container을 구현하는 법
<br><br><br>

### 14 ft_irc
#### 목표
IRC server을 RFC규격에 맞도록 c++을 이용해서 구성해본다.
<br><br>

#### 요구지식
1. RFC
    - RFC란?
    - RFC규격에 맞추어 server를 구성하는 방법론
2. socket 통신
    - TCP protocol을 실제로 적용하는 방법
    - TLS 보안을 실제로 적용하는 방법
3. IRC
    - IRC란?
    - IRC server를 구성하고 띄우는 방법
<br><br><br>

### 15 webserv
#### 목표
C++을 이용해서 HTTP server를 구성한다.
<br><br>

#### 요구지식
1. HTTP
    - HTTP Protocol의 구성
    - HTTP header, message의 구성
    - HTTP message를 해석하는 법
2. Web Server
    - CGI란?
    - Request와 response
    - 실제 web server가 동작하는 방식
<br><br><br><br>
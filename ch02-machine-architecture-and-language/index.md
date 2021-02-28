# Ch 02. Machine Architecture and Language

## Contents

1. [서론][link1]

## 1. 폰노이만 아키텍처

* input device, output device, memory, central processing unit

## 2. computer architecture 와 language

* 컴퓨터의 중요 부분은 프로그래밍 언어의 6개의 중요한 부분과 일치한다.
* data
  - 메인 메모리, 레지스터, 파일들에 저장된다.
  - elementary data type
    - 한 개의 데이터
    - 언어에 기본적으로 탑재된 데이터 타입
  - structured data
    - 여러 개의 데이터
    - user defined data

* operation
  - 데이터 value 를 바꾸기 위한 것들
  - 연산, 메모리 접근, 장치 제어, 순서 제어(ex: if else)

* sequence control
  - instruction 순서를 제어 하기 위해
  - 다음 명령어를 가리키기 위해 program address register 를 사용
  - branch operation 사용

* instruction level sequence control
  - 음 어떤 명령어를 먼저 실행할지??
  - funA(funB(3)) 이면 뭐부터 실행해야하는지??

* data access
  - 데이터에 접근하고 조작하는 방식
  - serial (직렬) / parallel (병렬)

* storage management
  - data 와 명령어 storage 를 조작하는 방식
  - io device, 메인 메모리, 레지스터 데이터에 접근하는 시간이 다르다.
  - multiprogramming: 입출력 기다리는 동안 다른 프로그램 수행할 수 있게
  - cache memory

* operational environment
  - 외부장치와 comunication 하는 방법

* other factors
  - 시스템 architecture: RISC, MIMD... (폰노이만 vs multi processor)


## Syntax Analysis and Semantics

* Syntax
  - Grammer
    - Terminal: terminal (더이상 변하지 않는 무언가) 들의 유한한 집합
    - Nonterminal: non-termianl 들의 유한한 집합
    - Production: terminal 이나 non-terminal 을 다시 쓰는 규칙들의 집합
    - Start Symbol: 
  - Notations
    - BNF (Backus Naur Form)

* Terminal 과 Nonterminal 합집합은 언어 안의 모든 단어의 집합

## Compilation Language & Compilation Process

* Text editor -> Pre processor -> Compiler -> Assembler -> Linker -> excutable code 가 나온다

* 컴파일 순서 (ex: A = B + C)
  1. source program
  2. Lexical analysis
    - A: id / =: op / B: id / +: op / C: id(identifier)
  3. Syntax analysis
  4. Semantic analysis
  5. Intermediate code
  6. Assembly code
* symbol table manager, error handler 가 전반에 걸쳐 관여
  
## Language Design Issues

* Binding Time
  - programming 요소에 properties 나 characteristic 을 결정하기 위한 시간
    - language definition time
    - language implementation time
    - program translation time by programmer, translator, loader
    - program excution time
  - translation 방식에 따른 언어 분류: compilation vs interpretation

## Chomsky Hierarchy: Concept

* Type 0: 제약없는 문법
  - 어떠한 제한도 적용되지 않음
  - 회귀열거가능 언어
  - turing machine 에 의해 인식가능

[link1]: #user-content-1-프로그래밍-언어

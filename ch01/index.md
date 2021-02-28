# Ch 01

## Contents

1. [서론][link1]

## 1. 프로그래밍 언어
* 기계의 의사소통 도구
* 컴퓨터를 조작하기 위한 프로토콜
  
## 2. formal language
* word 의 집합
* word 는 알파벳이라고 불리는 element 들의 combination
* grammer 라는 rule 로 단어를 만든다.
* 알파벳과 문법으로 set 가 만들어진다.

## 3. 이 수업 왜 배우는가
* 더 효율적인 알고리즘을 만들 수 있다.
  - 재귀나 메모리 관리면에서 더 좋은 코드를 짤 수 있다.
  - 재귀 구현해주는 언어도 있고 i++ vs i += 1 두 개가 다르다.
* 프로젝트에 적합한 언어를 선택할 수 있다.
* 다른 언어를 더 쉽게 배울 수 있다.
* 더 나은 프로그래밍 언어를 만들기 위해
  - 만든다는 것 = grammer 를 만든다. = grammer 를 해석할 수 있는 compiler 를 만든다.

## 4. 좋은 언어의 특징
* orthogonality 직교, 독립성
  - 언어의 다양한 특징들을 결합해 또 다른 특징으로 만들 수 있다.
  - ex) if (q < r) then S1 else S2
  - 비교 연산, if 연산이 독립 돼 있어서 결합해서 쓸 수 있다.
* 추상화를 지원
  - 재사용하는 패턴을 빼낼 수 있다.
* 다양한 분야에 사용 가능 (중립적이어야 한다.)
  - business, sport, game ...
  - 모든 분야를 다 커버할 수 없지만 적어도 한 domain 에서는 natural 해야한다.
  - unity 는 vr 을 위해서, 코볼은 비즈니스를 위해서 이렇게
* 검증과 디버깅에 쉬워야 한다.
* portability (이식성) and translation
  - 모든 컴퓨터 시스템에서 동일한 기능을 보장해야한다.

## 5. 언어의 분류
* application domain 에 따른 분류
  - business processing: cobol, java ...
  - system: c, ada
  - artificial inteligence: LISP, PROLOG
* 실행되는 환경에 따른 분류
  - bach processing language
  - conversational language
  - embedid lanugage
* 데이터를 어떻게 처리하는지에 따라 (data computational model 에 따라)
  - procedural: c
  - object-oriented
  - functional: LISP
  - logical: PROLOG
  - hybrid: python

## 6. imperative language
* 연속된 statement 들로 이루어져있다.
* 각 statement 의 실행은 시스템의 state 를 바꾼다.
* c, foltan, algol, pascal

## 7. object based language
* 모든것을 object 로 생각
* 복잡한 object 는 간단한 object 로 부터 확장되고 상속한다.
* imperative lanugage 의 효율성을 얻기 위해, fliexibility, reliability 를 얻기 위해
* c++, java, smalltalk

## 8. functional language (applicative)
* function 의 결과값이 또 다른 Function 의 argument 가 된다.
* LISP, ML

## 9. logical language (rule based language)
* 특정 조건 만족하면 action 실행됨
* fact, rule, query 로 이루어져있다.
* fact 들을 기반으로 query 에 맞는 값을 찾는다.
* rule 을 이용해서 새로운 패턴을 만든다.

[link1]: #user-content-1-프로그래밍-언어

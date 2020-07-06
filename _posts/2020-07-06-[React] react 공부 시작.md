# React Study - Day1

## React Project를 위한 React Study 시작
- Java Spring 공부와 병행하여 Toy Project를 위한 React 기초 학습

- Velopert React를 다루는 기술 이라는 책을 기본서로 진행 예정

## 진행 상황
- Chap1 ~ Chap7 완료

### Chapter 1

#### 리액트 특징

##### 1. Virtual DOM

1. DOM 이란?
    - Document Object Model의 약어
    - 즉, 객체로 문서 구조를 표현하는 방법(XML이나 HTML로 작성한다)
    - 웹 브라우저는 DOM을 활용하여 객체에 자바스크립트와 CSS를 적용한다.
    - DOM은 트리형태라서 특정 node를 찾거나, 수정하거나, 제거하거나 삽입 할 수 있다.

2. DOM은 과연 느린가?
    - DOM의 치명적인 문제점
        - 동적 UI에 최적화 되어있지 않다.
        - HTML은 자체적으로 정적이지만, 자바스크립트를 사용하여 이를 동적으로 만든다.
    - 규모가 큰 서비스에서 DOM에 직접 접근하여 변화를 주다 보면, 성능 이슈가 발생한다. 즉, 느려진다.
        - 문제점은 DOM 자체는 빠르지만, DOM에 변화가 일어나면 웹 브라우저가 CSS를 다시 연산하고, 레이아웃을 구성하고, 페이지를 리페인트 하는 과정에서 시간이 허비된다.

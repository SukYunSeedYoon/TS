# TypeScript

## 정의

* SuperSet, 프로그래밍 언어
* Compiled Language ==> Transpile

* 컴파일 과정의 타입을 중요시,  타입 검사

* visual studio 혹은 node.js, browser에서 실행 될 수 있음

## 설치

* 로컬 폴더에 설치하기

```sh
npm init -y
npm i typescript
```

* 가급적이면 전역으로 설치하지 말고, 모듈로 들어가서 설치해 주자.

```sh
tsc --init
tslint --init
```

* module 설정
  * 현실적으로 es6를 쓸수 있는 곳이 많지 않다. es5정도로
  * node를 쓴다는 것은 commonjs를 쓴다는 것, target이 es6이면 es6가 디폴트
* module resolution
  * ts 소스에서 모듈을 사용하는 방식을 지정
  * Class 아니면 Node 입니다.
  * CommonJS일때만 Node라고 생각하면 됨
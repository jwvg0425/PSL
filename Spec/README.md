# Spec

확장자 .psl

## 자료형

- `int` : 32비트 정수
- `i64` : 64비트 정수
- `double` : 실수
- `string` : 문자열
- `char` : 문자
- `T[sz]` : 고정 길이 배열
- `vec T` : 가변 배열
- `map K T` : ordered map
- `set K` : ordered set
- `multiset K`: ordered multi set
- `graph`, `tree`?
- custom type(struct)

### struct

## type system

## 변수 선언

```text
(name):(type) [= (init value)];
```

## 모듈

`import (filename)` 을 통해 특정 파일에 있는 내용 import 가능

## interactive

인터랙티브 프로그램 쉽게 풀기 위한 interactor

## test

- input / output 테스트 셋 쉽게 관리하기
- test generator & brute-force 검증기(scaffold)

## big int

big int 지원을 위한 to python(or java?) 컴파일 기능

## control block

## IO

read, write 함수를 이용해 input, output 가능

## string interpolation

## lambda

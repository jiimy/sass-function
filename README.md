# sass-function
sass 함수 정리

#### [Refactoring.scss](https://github.com/jiimy/sass-function/blob/master/Refactoring.scss)
- 기존엔 긴 코드를 scss의 기능돌로 함축시킨걸 모아놓은 곳입니다. 

#### [func.scss](https://github.com/jiimy/sass-function/blob/master/func.scss)
- 실무에서 쓴 함수 모음집

#### [function.scss](https://github.com/jiimy/sass-function/blob/master/function.scss)
- 공부용 함수 

#### [random.scss](https://github.com/jiimy/sass-function/blob/master/random.scss)
- 랜덤 기능 테스트

#### [vw-convert.scss](https://github.com/jiimy/sass-function/blob/master/vw-convert.scss)
- px to vw

#### [darkmode.scss](https://github.com/jiimy/sass-function/blob/master/darkmode.scss)
- 다크모드 처럼 테마 만들기

#### [pratice.scss](https://github.com/jiimy/sass-function/blob/master/pratice.scss)
- 사스 함수 연구소. 여러 시도하고 있는 함수와 mixin 이 있습니다. 

#### [unique-id.scss](https://github.com/jiimy/sass-function/blob/master/unique-id.scss)
- 중복해서 사용하는 부분제거 하는 함수 ( unique-id 대체인 멀티 셀렉터 함수 )

추가 작업할 부분
- [ㅇ]  - .a, .b 클래스 들을 공통으로 묶는 mixin 함수 연구 
ex) @mixin classes ('클래스명1, 클래스명2'){ ... }

@include classes('.a, .b') { color: red; }; 의 결과는 .a, .b { color: red; } 와 같게

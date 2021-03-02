### 질문들
- [ ] 왜 테스트 클래스에 `@Runwith(SpringRunner.class)`가 들어가야 하는가. 역할이 뭔가. `@SpringBootTest`는 또 무슨 역할인가.

### lombok 빌드 관련 에러가 생길 경우
- 플러그인 업데이트 해보기
- Gradle에서 아래와 같이 직접 annotaion processor 옵션을 줄 수 있다.
   ```gradle
   dependencies {
       ...
       annotationProcessor('org.projectlombok:lombok')
       ...
   }
  ```
#### 참고
- https://defacto-standard.tistory.com/445
- https://stackoverflow.com/questions/24006937/lombok-annotations-do-not-compile-under-intellij-idea/30125507#30125507
- https://m.blog.naver.com/light-star/221969272088

### AssertJ가 JUnit의 assertThat 보다 편리한 이유
- http://bit.ly/30vm9Lg


### 인텔리제이 단축키
- [ ] Map에 정리 추가할 것
- https://blog.jetbrains.com/ko/2020/03/11/top-15-intellij-idea-shortcuts_ko/
- 현재 구문 완성은 `Shift + Ctrl + Enter` 

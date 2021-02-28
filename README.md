
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
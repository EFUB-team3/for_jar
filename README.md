## 최종 파일
### cmd창 실행방법 
```
java -jar ebs-final.jar
```

### intelij Gradle jar 파일 생성 방법

build.gradle에 추가하기
```java
bootJar{
   archiveBaseName='-'
   archiveFileName='아무거나.jar'
   archiveVersion="0.0.0"
   jar.enabled=true
}
```

Working with existing builds
============================

Installing Guide
----------------

#### 선제 조건

-	자바 JDK or JRE 7 이상

	<code> > java -version</code>

	Gradle는 자체 Groovy를 사용하고 있으므로 따로 설치 할 필요 없음. 기존 설치된 Groovy는 무시 됩니다. Gradle는 환경변수 JAVA_HOME이 가리키는 JDK를 인식하게 됩니다.

#### 다운로드

-	Link: [Gradle](https://gradle.org/gradle-download/?_ga=1.189349292.625007235.1481683464)

#### Unpacking

Gradle 배포판은 ZIP 파일 형식으로 제공된다. 배포된 내용은 아래와 같습니다.

-	Gradle 바이너리
-	사용자 가이드(HTML and PDF)
-	DSL 레퍼런스 가이드
-	API 문서(javadoc)
-	사용자 가이드에서 언급된 예제와 샘플 및 사용자 빌드시 복잡한 필드가 포함
-	바이너리 소스

#### 환경변수

Gradle 실행을 위해서 추가되는 환경 변수는 *GRADLE_HOME* 이다.

Working with existing builds
============================

Installing Guide
----------------

#### 선제 조건

-	자바 JDK or JRE 7 이상

	<code> > java -version</code>

	Gradle는 자체 Groovy를 사용하고 있으므로 따로 설치 할 필요 없음. 기존 설치된 Groovy는 무시 됩니다. Gradle는 환경변수 JAVA_HOME이 가리키는 JDK를 인식하게 됩니다.

#### 다운로드

-	[Gradle](https://gradle.org/gradle-download/?_ga=1.189349292.625007235.1481683464)

#### Unpacking

Gradle 배포판은 ZIP 파일 형식으로 제공된다. 배포된 내용은 아래와 같습니다.

-	Gradle 바이너리
-	사용자 가이드(HTML and PDF)
-	DSL 레퍼런스 가이드
-	API 문서(javadoc)
-	사용자 가이드에서 언급된 예제와 샘플 및 사용자 빌드시 복잡한 필드가 포함
-	바이너리 소스

#### 환경변수

Gradle 실행을 위해서 추가되는 환경 변수는 **GRADLE_HOME** 이다.**GRADKE_HOME** 은 다운로드 받은 배포판을 Unpacking 한 폴더를 등록 한다.**PATH** 환경 변수에 GRADLE_HOME/bin 를 등록 한다.

#### 설치 테스트 및 실행

```
 command > gradle

 Starting a Gradle Daemon, 1 incompatible and 1 stopped Daemons could not be reused, use --status for details
 :help

 Welcome to Gradle 3.1.

 To run a build, run gradle <task> ...

 To see a list of available tasks, run gradle tasks

 To see a list of command-line options, run gradle --help

 To see more detail about a task, run gradle help --task <task>

 BUILD SUCCESSFUL

 Total time: 9.153 secs`

 command > gradle -v
------------------------------------------------------------
Gradle 3.1
------------------------------------------------------------

Build time:   2016-09-19 10:53:53 UTC
Revision:     13f38ba699afd86d7cdc4ed8fd7dd3960c0b1f97

Groovy:       2.4.7
Ant:          Apache Ant(TM) version 1.9.6 compiled on June 29 2015
JVM:          1.8.0_101 (Oracle Corporation 25.101-b13)
OS:           Windows 10 10.0 amd64

```

#### JVM options

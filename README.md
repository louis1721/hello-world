A. Gradle 빌드 이해 (window 환경)
  1. Chocolatey 다운로드 (https://chocolatey.org/install , Install with cmd.exe 참조)
  2. gradle 설치 ($ choco install gradle)
  3. 설치 확인 ($ gadle -v)
  4. 설치 완료 후 프로젝트 생성을 위한 init ($ gradle init)
    Select type of project to generate:
      1: basic
      2: groovy-application
      3: groovy-library
      4: java-application
      5: java-library
      6: kotlin-application
      7: kotlin-library
      8: scala-library
    Enter selection (default: basic) [1..8] 6

    Select build script DSL:   // DSL = Domain-Specific Language
      1: groovy
      2: kotlin
    Enter selection (default: kotlin) [1..2] 1
    
B. Ubuntu Gradle 빌드
  1. Android-sdk install  (sdk update higher than API level 24 including 24)
  2. curl 설치 -> $ sudo apt install curl
  3. Add node.js PPA(personal package archive) -> $ curl -sL https://deb.nodesource.com/setup_8.x | sudo bash -
 
  
    
  
  


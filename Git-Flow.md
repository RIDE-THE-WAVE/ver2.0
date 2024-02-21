# Branch Strategy

## Git Flow

총 6개의 브랜치를 사용합니다.

✅ main

*  서비스를 배포하는 브랜치

<br><br>

✅ develop
    
* feature 에서 개발된 내용이 머지되는 브랜치

<br><br>

✅ feature

* 각 기능을 개발하는 브랜치

* 브랜치 이름은 `feature/기능` 으로 만든다.
    
- 로그인 기능을 개발한다면 다음과 같이 브랜치를 만든다.
        
    `feature/login`

<br><br>

✅ release

* 배포하기 전 QA 하는 브랜치

* 브랜치 이름은 `release/기능` 으로 만든다.
    
- 로그인 기능을 테스트한다면 다음과 같이 브랜치를 만든다.
        
    `release/login`

<br><br>

✅ hotfix

* main 브랜치에서 배포를 하고 나서 버그가 생겼을 때 신속하게 고치기 위한 브랜치

* 브랜치 이름은 `hotfix/기능` 으로 만든다.
    
- 로그인 기능에 버그만 있다면 다음과 같이 브랜치를 만든다.
        
    `hotfix/login`

<br><br>

✅ refactor

* 리팩토링을 위한 브랜치

* 브랜치 이름은 `refactor/기능` 으로 만든다.
    
- 로그인 코드를 리팩토링한다면 다음과 같이 브랜치를 만든다.
        
    `refactor/login`

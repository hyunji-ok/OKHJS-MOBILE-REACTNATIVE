# MOBILE-REACTNATIVE

## [description]
- react-navigation을 사용해보는 브랜치

## [author]
- 옥현지
    - hyunji-ok(개인 계정)
    - okhj159(회사 계정)

## [caution]
- git 설정
    - 원본 repo(upstream)과 fork repo(origin)의 branch 맞추는 방법 
        - upstream 원격 추가: git remote add upstream <원본 리포지토리 URL>
        - upstream의 변경 사항 가져오기: git fetch upstream
        - 새로운 브랜치 fet를 로컬에서 생성 및 체크아웃: git checkout -b fet upstream/fet
        - 새로운 브랜치를 포크된 리포지토리로 푸시: git push origin fet
- 개발환경
    - node: 18.19.0
    - ruby: 3.1.6
    - jdk: openjdk@11(homebrew 설치)
- zshrc 설정
    ```
        export PATH="/opt/homebrew/opt/openjdk@17/bin:$PATH"
        # export PATH="/opt/homebrew/opt/openjdk@11/bin:$PATH"

        export ANDROID_HOME="$HOME/Library/Android/sdk"
        export PATH="$PATH:$ANDROID_HOME/emulator"
        export PATH="$PATH:$ANDROID_HOME/tools"
        export PATH="$PATH:$ANDROID_HOME/tools/bin"
        export PATH="$PATH:$ANDROID_HOME/platform-tools"
    ```
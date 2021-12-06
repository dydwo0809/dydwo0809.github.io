# OS

Window

## 사전 준비

1. git(git bash) 설치

2. github에 dydwo0809.github.io 저장소 생성 

3. ruby, jekyll 설치

## 로컬, 리모트 저장소 연결

1. dydwo0809.github.io 저장소에서 클론

2. C 밑에 blog 디렉토리 생성

3. git bash에서 blog 디렉토리로 이동

4. blog 디렉토리에서 git clone <클론한거 붙여넣기>

5. blog 밑에 dydwo0809.github.io 디렉토리 생성완료

## 블로그 생성

1. git bash에서 dydwo0809.github.io 디렉토리로 이동

2. jekyll new . --force

3. bundle add webrick

## 테마 적용

1. gitbook 홈페이지에서 클론

2. blog 디렉토리에서 git clone <클론한거 붙여넣기>

3. 새로 생긴 gitbook 디렉토리의 내용물 전부 dydwo0809.github.io 디렉토리에 덮어씌움

4. dydwo0809.github.io로 가서 다시 jekyll new . --force, bundle add webrick

5. _config.yml에서 title, longtitle을 Yongjae's blog로 수정

6. _config.yml에서 author를 Kwon-Yongjae로, email을 dydwo0809@naver.com으로 수정

7. _config.yml에서 url과 baseurl을 'https://dydwo0809.github.io/'로 수정

## 댓글 기능 구현

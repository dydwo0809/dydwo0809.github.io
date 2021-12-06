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

4. git add, commit, push

5. github에서 블로그 생성 확인

## 테마 적용

1. gitbook 홈페이지에서 클론

2. blog 디렉토리에서 git clone <클론한거 붙여넣기>

3. 새로 생긴 gitbook 디렉토리의 내용물 전부 dydwo0809.github.io 디렉토리에 덮어씌움

4. dydwo0809.github.io로 가서 다시 jekyll new . --force, bundle add webrick

5. _config.yml에서 title, longtitle을 Yongjae's blog로 수정

6. _config.yml에서 author를 Kwon-Yongjae로, email을 dydwo0809@naver.com으로 수정

7. _config.yml에서 url과 baseurl을 'https://dydwo0809.github.io/'로 수정

8. git add, commit, push

9. github 블로그에서 테마 적용 확인

## 댓글 기능 구현

1. disqus 회원가입

2. 플랫폼은 jekyll 선택

3. website url은 내 블로그 주소로 설정

4.  _config.yml 파일에 disqus 설정 추가

5. disqus 홈페이지에서 Universal Code 복사

6. 복사해온 코드를 _layouts/post.html에 붙여넣기

7. 주석 해제 후 PAGE_URL, PAGE_IDENTIFIER 설정

8. s.src 내 주소로 되있는거 확인

9. 댓글 기능을 구현할 post파일(임시로 만든 example 파일)에 comments: True 추가

10. github 블로그의 example 포스트에 댓글 기능 구현 확인(구현 되는데 조금 오래걸림)

## 블로그 설정 변경

1. 블로그에 들어가서 왼쪽 위에 A(깃북 테마 기능)를 누름

2. 작은 A와 큰 A를 적절히 눌러 블로그 글씨 크기를 적절히 변경

3. Serif와 Sans 중 Sans를 눌러 글씨체를 각지게 변경

4. White, Sepia, Night중 White를 눌러 배경색은 흰색으로 유지

5. 파비콘은 깃북 테마에서 제공해주는 파비콘 사용

## "What is Git and Github" 포스트 작성

1. git bash에서 dydwo0809.gibhub.io 폴더로 이동

2. _posts 폴더로 이동

3. vi What-is-Git-and-Github.md 명령어 입력

4. 댓글 기능 구현을 위해 comments: True로 설정

5. git과 github에 관한 내용 작성

6. git add, coommit, push

7. github 블로그에서 What is Git and Github 포스트가 생성된 것을 확인

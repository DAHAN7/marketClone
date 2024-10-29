marketclone 프로젝트
1. 개요
이 저장소는 marketclone 이라는 이름의 웹 애플리케이션 프로젝트를 포함하고 있습니다.
사용자 인증 (로그인, 회원가입) 및 상품 등록 기능을  FastAPI 를 이용하여 구현하는 데 중점을 두고 있습니다.
프론트엔드는 HTML, CSS, JavaScript를 사용하여 구현되었으며, 백엔드는 Python의 FastAPI 를 사용하여 RESTful API를 제공합니다. 데이터베이스는 SQLite 를 사용합니다.

3. 구현된 기능
사용자 인증:
frontend/login.html, frontend/login.js: 로그인 페이지 및 관련 기능 구현
frontend/signup.html, frontend/signup.js: 회원가입 페이지 및 관련 기능 구현
상품 등록:
frontend/wirte.html, frontend/write.js: 상품 등록 페이지 및 관련 기능 구현

이미지 처리:
이미지 업로드 및 데이터베이스 저장 기능 (/items 엔드포인트)
이미지 조회 기능 (/images/{item_id} 엔드포인트)

4. 기술 스택
프론트엔드: HTML, CSS, JavaScript
백엔드: Python (FastAPI)
데이터베이스: SQLite (market.db)
기타: fastapi-login (사용자 인증)

5. 폴더 구조 설명
frontend: 프론트엔드 코드 및 정적 파일 저장 폴더
assets: 데이터베이스 파일 등 저장
(root): 백엔드 코드 및 설정 파일 저장
main.py: FastAPI 애플리케이션 메인 파일
package-lock.json: npm 패키지 관리 파일 (프론트엔드 의존성)

6. 실행 방법
main.py 파일을 실행합니다.
웹 브라우저에서 http://127.0.0.1:8000 에 접속합니다.

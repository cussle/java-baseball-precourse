# 카테캠 미니과제 1 - 숫자 야구
## 개요
- 카카오 테크 캠퍼스 1차 미니과제
- 1부터 9까지 서로 다른 수로 이루어진 3자리 숫자를 맞히는 게임
- 사용자는 컴퓨터가 무작위로 선택한 숫자를 맞히기 위해 입력을 반복, 입력 결과에 따른 힌트 부여

## 기술 스택
- 언어: Java 17
- 테스트 라이브러리: JUnit 5, AssertJ

## 기능 목록
- [x] **숫자 생성** - 게임 시작 시 1부터 9까지 서로 다른 수 3개를 무작위로 생성
- [x] **사용자 입력** - 사용자는 3자리 숫자를 입력
- [x] **입력 검증** - 입력받은 숫자가 3자리이며, 각 숫자가 1부터 9까지이고, 중복되지 않는지 확인
- [x] **결과 반환** - 입력받은 숫자와 컴퓨터가 생성한 숫자를 비교하여 힌트/결과 반환
- [ ] **게임 반복** - 사용자는 게임을 새로 시작할지 또는 종료할지 선택

## 개발 규칙 및 스타일 가이드
- **코드 스타일**: Google Java Style Guide을 기반으로 하되, 들여쓰기는 4 spaces를 사용
- **커밋 메시지**: AngularJS Git Commit Message Conventions을 기
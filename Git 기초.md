# Git 기초
## Git 기본 명령어
```
git init
```
git으로 프로젝트 관리 시작

```
git status
```
현재 관리 상태 확인

```
git add [파일명]
```
commit을 위한 파일 스테이징

```
git commit -m [커밋메시지]
```
커밋하기

```
git log
```
커밋 로그/히스토리 확인
--oneline

## Git 추가 명령어
```
git reset --hard [Branch | ...]
```
위험하니까 알고쓰자, 커밋되지 않은 변경 내용들을 커밋 상태로 되돌리기

## 원격 저장소를 활용한 Git
```
git push
```

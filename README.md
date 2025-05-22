# 프로그래머스 웹 프론트엔드 5기 과제

### Day 1. CLI로 GitHub Push하기

**[기본 개념]**

- `CLI` : Command Line Interface - 터미널 / 콘솔에 명령을 작성하는 방식
- `GUI` : Graphic User Interface - 그래픽을 사용하여 (버튼 등) 응용 프로그램과 상호 통신하는 방식

**[주요 CLI 명령어]**

- 변경 내용 스테이징

```bash
git add <파일> # 특정 파일만
git add . # 변경된 전체 파일
```

- 커밋

```bash
git commit -m '<커밋 이름>'
git commit -am '<커밋 이름>' # 변경 내용 스테이징 & 커밋 동시에
```

- Branch 생성

```bash
git checkout -b <신규 브랜치 이름>
```

- Branch간 이동

```bash
git checkout <이동할 브랜치 이름>
```

- Branch 병합(Merge)

```bash
git merge <병합할 브랜치 이름>
```

- Branch 삭제

```bash
git branch -D <삭제할 브랜치 이름>
```

- Git History 관리

```bash
# 수정 히스토리 확인
# 각 히스토리의 Hashcode 확인 가능
git log # 상세 버전
git log --oneline # 간략 버전

# 리셋
git reset --hard/soft <돌아갈 버전의 해시코드>
```

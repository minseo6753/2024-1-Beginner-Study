### Fork
다른 사람의 Repository를 자신의 계정으로 복사하여 독립적으로 수정,관리

### Star
관심있는 Repository나 프로젝트를 북마크하는 기능

### Issue
Repository에서 작업 계획, 토론 및 추적을 위해 활용

### Branch
+ 기존 브랜치에서 분리되어 생성되는 별도의 작업 공간
+ 같은 Repository에 생성됨
+ Naming Convection:
    "type/issue 번호-간략한 설명"
+ 브랜치 확인
    git branch //현재 브랜치 확인
    git branch -a //모든 브랜치 확인
+ 브랜치 생성
    git branch 브랜치 이름
+ 브랜치 삭제
    git branch -D 브랜치 이름
+ 브랜치 이동
    git checkout 브랜치 이름
+ 브랜치 생성 후 이동
    git checkout -b 브랜치 이름


### Pull Request
+ 분기된 Branch를 다시 병합하기 위한 절차
+ 새로운 변경을 제안하거나 병합 시 발생하는 충돌을 해결
+ Merge에 앞서 코드 리뷰

## Merge

### Merge Commit
+ 두 브랜치를 공통 부모로 하는 새로운 commit을 만든다.
+ 브랜치의 커밋들이 그대로 main브랜치로 병합된다.

### Sqush and Merge
+ 브랜치의 커밋들을 'squash'해서 하나의 커밋으로 main 브랜치에 병합

### Rebase and Merge
+ 브랜치의 커밋들의 base를 main브랜치로 재설정한다.
+ 모두 새로운 커밋으로 변경된다.
+ commit hash가 변경되어 무수한 충돌을 경험할 수 있으니 주의


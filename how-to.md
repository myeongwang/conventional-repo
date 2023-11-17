# git 사용법을 알아봅시다.

## repo clone하기

- github에서 repo를 생성한다.
- repo url을 복사한다.
- `$ git clone repo-url` 하여 로컬에 복제한다.

## add, commit, push

- 새 파일을 생성한다 or 이미 존재하는 파일에 작업을 실시한다.
- `$ git status` 로 현재 상황을 파악한다.
- `$ git add filename`으로 대상 파일을 staging한다.
- `$ git commit` 으로 메타데이터를 작성한다.(`$ git commit -m "message"`도 사용가능)
- `$ git push origin main`으로 원격저장소(github)에 push 한다.

## branch

- `$ git branch branchname`으로 새 브랜치를 생성한다.
- `$ git switch branchname`으로 새 브랜치로 이동한다.
- 작업하여 add, commit을 실시한다.
- 작업이 끝나면, `$ git switch main` 으로 기본 브랜치로 돌아온다.
- `$ git merge branchname`으로 새 브랜치의 작업사항을 기본 브랜치로 합친다.
- 만약, merge conflict가 발생한다면, 해당 상황을 해결한 뒤 add, commit(-m 사용 금지) 하여 merge를 완료한다.

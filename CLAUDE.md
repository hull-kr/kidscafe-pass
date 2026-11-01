# kidscafe-pass 프로젝트 규칙

## git 설정

- 이 저장소의 `user.name` · `user.email` 은 **로컬(`git config --local`)에만** 둔다. 전역 설정은 건드리지 않는다.
- 작성자: `hull-kr` / `www.hull.kr@gmail.com`

## 커밋하면 푸시까지 한다

- 이 폴더에서 커밋을 만들면 **따로 묻지 않고 바로 GitHub 원격(`origin`)에 푸시한다.**
- 푸시 대상은 지금 브랜치의 같은 이름 원격 브랜치다. 처음 푸시하는 브랜치는 `git push -u origin <브랜치>` 로 추적을 건다.
- 강제 푸시(`--force`, `--force-with-lease`)는 이 허가에 포함되지 않는다. 필요하면 먼저 묻는다.
- 푸시가 실패하면(인증 · 원격이 앞서 있음 등) 억지로 밀지 말고 실패 내용을 그대로 알린다.

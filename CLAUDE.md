# MoA Infra 작업 규칙 (Claude용)

규칙, 결정 로그, ADR, 하네스는 모두 Backend 레포(moamarket/Backend)에 있다. 작업 전에 그 레포의 `CLAUDE.md`와 `docs/STATUS.md`를 먼저 읽는다.

- 서버 1대 전제로 시작한다 (ADR-004, 006, 007). 서버를 늘리는 변경은 ADR을 먼저 쓴다.
- 오버엔지니어링 금지: 정한 것과 꼭 필요한 것만 만든다.
- git 규칙은 Backend와 같다: 이슈 → `[type]/#번호` 브랜치(develop에서) → `type : 변경` 커밋 → develop으로 PR. Claude trailer 금지. 이슈, PR, 댓글은 Claude가 만들지 않고 초안만 준다.
- 짧고 쉬운 한국어, 가운뎃점(·) 금지.

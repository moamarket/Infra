# MoA Infra
MoA(인플루언서 댓글 선착순 플리마켓) 배포 설정 레포.

## 레포 구성 (moamarket)
| 레포 | 내용 |
|---|---|
| [Backend](https://github.com/moamarket/Backend) | Spring Boot API, 기획과 설계 문서(`docs/`), 하네스 |
| [Frontend](https://github.com/moamarket/Frontend) | 모바일 웹 화면 |
| Infra (여기) | 배포 설정 |

## 지금 상태
- 아직 배포 전이라 비어 있다. 로컬 MySQL(`compose.yaml`)은 `bootRun`이 쓰므로 Backend 레포에 둔다.
- 배포를 시작할 때 필요한 만큼만 채운다. 배포 전에 할 일은 Backend `docs/STATUS.md` 참고 (Flyway, S3, 도서산간 목록).

## 처음 클론했다면
```
git config core.hooksPath .githooks
```
커밋 메시지 형식(`type : 변경`)과 develop, main 직접 푸시를 검사하는 hook이 켜진다.

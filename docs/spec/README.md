# UDP Specification

이 프로젝트의 UDP 데이터 처리 기준이 되는 공식 명세서 정보이다.

## 명세서

| 항목 | 내용 |
| --- | --- |
| 정식 명칭 | Data Output from F1® 25: 2026 Season Pack |
| 버전 | 1.2 (Season 8 "Sports Update", F2 Driver ID 추가) |
| 대상 게임 | EA SPORTS™ F1® 25: 2026 Season Pack |
| 패킷 포맷 | `m_packetFormat` = 2026 |
| 공식 출처 | EA 공식 포럼 F1 Game Info Hub: https://forums.ea.com/blog/f1-games-game-info-hub-en/ea-sports%E2%84%A2-f1%C2%AE25-udp-specification/12187347 |
| 문의 스레드 | https://forums.ea.com/discussions/f1-25-general-discussion-en/discussion-f1%C2%AE-25-udp-specification/12187351 |
| 로컬 파일명 | `Data_Output_from_F1_25_2026_Season_Pack_Season_8.pdf` |

## 보관 정책

명세서는 "EA의 라이선스 하에 참고 목적으로만 제공"되며 재배포 허락이 확인되지 않았다.
따라서 PDF 원본은 이 저장소에 커밋하지 않는다. `.gitignore`가 `docs/spec/*.pdf`를 추적에서 제외한다.

## 로컬 배치 방법

1. 위 공식 출처에서 명세서 PDF를 내려받는다.
2. 이 폴더(`docs/spec/`)에 위 로컬 파일명으로 저장한다.
3. `git status`에 PDF가 표시되지 않는지 확인한다.

명세서가 갱신되면 이 파일의 버전 정보를 고치고, 적용 버전을 DECISIONS.md에 기록한다.

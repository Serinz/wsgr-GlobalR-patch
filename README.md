# wsgr-GlobalR-patch

전함소녀 R(중국판) 비공식 한국어 패치 배포용 저장소입니다. 첨부 파일은 wsgrGlobalR 앱 전용(암호화)입니다.

- index.json: 언어 목록
- <언어>/manifest.json: 패치 파일 목록
- Releases: 패치 첨부

게임 원저작권: 上海幻娱网络科技有限公司 (Moefantasy). 비영리 팬 번역 패치입니다.

## 구조
| 경로 | 내용 |
|---|---|
| `index.json` | 언어 목록·버전·앱 최소 버전·공지 (앱이 가장 먼저 읽음) |
| `ko/manifest.json` | 한국어 패치 파일 목록 (경로, 원본/패치 해시, 첨부 위치) |
| Releases `ko-<버전>` | 패치 첨부 (WSRE 암호화, 바뀐 파일만 새 릴리스에 올라가고 나머지는 이전 릴리스를 가리킴) |

이 저장소의 내용은 관리자 PC의 `publish_release.ps1`이 갱신합니다. 직접 고치지 마세요.

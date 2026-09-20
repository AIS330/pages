# 앱이소 공개 페이지

브랜드 소개와 앱별 소개·개인정보처리방침을 제공하는 정적 사이트다.
공개 주소: https://ais330.github.io/pages/

| 경로 | 역할 |
|---|---|
| index.html | 브랜드 소개·앱 카드·출시 상태 배지 |
| brand/ | 앱에서도 복사해 쓰는 로고 원본 |
| home/icons/ · home/shots/ | 루트 카드·미리보기 띠의 축소 사본 |
| `<앱>/` | 앱 소개·방침·아이콘·스크린샷 |

앱별 HTML 원본은 각 앱 저장소의 docs/에 있다. 수정 후 그 앱의 `tool/publish_pages.sh` 또는 .ps1로 복사한다.
원본·복사본을 따로 수정하지 않는다. TravelMate 경로의 대소문자를 유지한다.

배포 규칙과 사본 생성법은 [GUIDELINES §6](../AppisoCommon/GUIDELINES.md#6-공개-페이지-ais330pages-저장소),
배지 근거는 [RELEASE-LOG](../AppisoCommon/RELEASE-LOG.md)를 따른다. push는 사용자 요청 때만 한다.
미리보기는 작업 루트 .claude/launch.json의 pages 설정(http://localhost:8765)이다.

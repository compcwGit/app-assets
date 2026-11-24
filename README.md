# app-assets

앱·프로그램의 외부 노출용 이미지(매뉴얼, 소개, 스토어 등록, 설치 안내)를 모아 두는 공개 저장소. 앱마다 `images/앱이름/` 폴더를 쓴다.

| 폴더 | 내용 |
|---|---|
| `images/nurse-duty/` | 간호사 근무표 — `app/` 앱 화면, `kmong/` 크몽 이미지, `install-guide.png` 설치 안내 |
| `images/animalfriends/` | 동물 친구들 — `store/` Play 스토어 등록 이미지(아이콘 512, 대표 그래픽, 폰·7인치·10인치 스크린샷), `icon-1024.png` |
| `images/hangulplay/` `lifeplay/` `numberplay/` `shapeplay/` `stampplay/` | 아이용 앱 — `icon-1024.png` (스토어 등록 때 스크린샷은 `store/` 폴더에 추가) |
| `images/household-ledger/` | 우리집 가계부 — `manual/slideNN-k.png` 사용자 매뉴얼(배포용)의 샘플 화면(슬라이드 번호 순), `icon.png` |
| `images/sosang-tools/` | 소상공인 만능도구 — `app/` 앱 화면(대시보드·마법사·색상 테마 등 33장), `kmong/` 크몽 상세페이지 이미지 12장, `install-guide.png` 설치 안내, `icon-1024.png` |
| `images/comstocktestbot/` | 주식노트 — `icon-512.png` |

## 쓰는 방법
- 노션·크몽·스토어에서는 `https://raw.githubusercontent.com/compcwGit/app-assets/main/images/앱이름/...` 로 링크한다.
- 새 앱의 이미지는 `images/앱이름/` 에 넣고 이 표에 한 줄 추가한다. 앱 소스 저장소에는 두지 않는다.
- 실제 가계부·개인 정보가 보이는 화면은 올리지 않는다 (공개 저장소). 샘플 화면만.
- 설치 파일·자동 업데이트는 앱마다 따로 두는 `앱이름-releases` 저장소를 쓴다.
- 가계부 매뉴얼 원본 PPTX 는 `household-ledger/docs/` 에 있고, 화면이 바뀌면 `scripts/manual/` 로 다시 만든 뒤 `manual/` 이미지를 갈아 끼운다.

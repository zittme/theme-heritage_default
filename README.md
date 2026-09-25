# Heritage (헤리티지)

[Zittme](https://github.com/zittme/zittme) 엔진용 공식 테마입니다. XE 시절 기본 레이아웃(NAVER 제작)의 구조를 물려받아 다시 지었습니다. 상단 2뎁스 메뉴 · 비주얼 슬라이더 · 서브 LNB 같은 원본의 구성은 그대로 두고, 코드는 템플릿 v2로 새로 쓰고 디자인은 지금 기준(반응형 · 다크 모드)으로 다시 해석했습니다.

- 데모: https://heritage-default.zitt.me
- 스토어: https://zitt.me/store/package/31503

## 요구 사항

- Zittme 1.0.0 이상
- 커머스 · 예약 · 짓미페이 · 문의 · 지식질문 스킨은 해당 모듈이 설치된 사이트에서만 적용됩니다. 커머스 스킨은 [commerce](https://github.com/zittme/commerce) 1.1.0 이상에 맞춰져 있습니다.

## 설치

Zittme 설치 경로의 `themes/heritage` 에 이 저장소의 내용을 놓습니다. **폴더 이름은 `heritage`** 입니다.

```bash
cd 설치경로/themes
git clone https://github.com/zittme/theme-heritage_default.git heritage
```

압축 파일로 받았다면 `themes/heritage/` 에 풀면 됩니다. 이후 관리자 > 테마에서 헤리티지를 적용하면 레이아웃과 스킨이 한 번에 바뀝니다.

## 구성

- 레이아웃 `heritage_default`: 2뎁스 GNB, 비주얼 슬라이더, 서브 LNB, 960 그리드
- 모듈 스킨 `heritage_default`: 게시판 · 회원 · 커머스 · 예약 · 짓미페이 · 문의 · 지식질문
- 커머스 스킨: 안내문 HTML, 배너 포인트 이미지 정렬, 주문내역·장바구니 링크와 검색창 표시 설정, 주문 상태 필터를 지원합니다

## 라이선스

[GPL v2](LICENSE)

## 문의

- 홈페이지: https://zitt.me
- 매뉴얼: https://zitt.me/manual

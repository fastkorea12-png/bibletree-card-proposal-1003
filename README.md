# BibleTree 접는 카드 + 모바일 묵상 제안

저·고학년 4면 카드 시안과 모바일 웹 묵상 시연을 한 페이지에서 검토하는 정적 제안 사이트입니다. 이 제안 사이트는 기존 `bibletree-card-demo` 프로토타입 저장소나 운영 바이블트리 저장소와 분리되어 있습니다.

## 미리보기

- 공개 제안 페이지: https://fastkorea12-png.github.io/bibletree-card-proposal-1003/
- 저학년 웹: https://fastkorea12-png.github.io/bibletree-card-proposal-1003/web-demo/?age=lower
- 고학년 웹: https://fastkorea12-png.github.io/bibletree-card-proposal-1003/web-demo/?age=upper
- 로컬: `python3 -m http.server 8940 --bind 0.0.0.0` 뒤 `http://127.0.0.1:8940/`

`index.html` 안의 학년별 미리보기 iframe과 공개 QR은 이 저장소의 `web-demo/` 경로를 가리킵니다. 공개 배포 시 LAN QR은 포함하지 않도록 `.gitignore`에 두었습니다.

## 들어 있는 내용

- 저·고학년 카드 펼침 시안과 네 면별 제안 내용
- 시편 30:3–5 핵심 구절, QR 이후의 웹툰·본문·활동·기도 흐름
- 새싹이 툰이 포함된 저·고학년 정적 웹 시연
- 공개 Pages 웹 화면으로 연결되는 학년별 QR 이미지

## 검토 표시

기존 카드 PNG는 레이아웃 참고용입니다. 그림 속 QR 자리는 빈 칸이고, 핵심 구절 표기가 시편 30:2, 4–5절로 승인 범위인 3–5절과 다릅니다. 해당 그림은 새싹이·복음 문구로 업데이트하지 않았으며, 페이지에 교체 필요사항을 표시했습니다. 개역개정 본문 출처와 대한성서공회 사용 허가, 최종 신학·문안 확인 후 카드 디자인을 갱신해야 합니다. 공개된 사이트도 인쇄용 조판이나 운영 바이블트리 웹 배포본은 아닙니다.

화면 점검 자료는 `review/`에 있습니다. 390×844 모바일과 1440×1100 데스크톱에서 가로 넘침 없이 표시되고, 카드 그림 로드와 학년 선택에 따른 웹 iframe 전환을 확인했습니다.

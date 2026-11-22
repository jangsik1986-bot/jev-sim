# jev-sim — Jev 글감 필터링 시뮬레이션 (모바일 9:16)

매일 아침 07:00 KST에 n8n `0_글감생성기_Jev필터_고정형` 워크플로가 오늘 수집한 시드와 Jev 판정 결과로 이 페이지를 자동 갱신합니다.

- 모바일 보기: https://jangsik1986-bot.github.io/jev-sim/
- 데이터: 그날의 실시간 시드 · Jev 판정(noul · 포맷 확률 · 잠재력 점수) · 소스별 합격률 · 비용
- 갱신 방식: GitHub Contents API(`PUT /contents/index.html`) — 워크플로 노드 `09-10` → `09-11` → `09-12`

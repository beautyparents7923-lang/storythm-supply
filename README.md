# 스토리즘 캠프 비품창고 (PWA)

핸드폰에서 링크만 열면 바로 쓰는 비품 재고 앱. 사진 촬영, 수량 실사, 입출고 기록, 구매 필요 목록.

- 프론트: index.html 하나 (PWA, 홈 화면에 추가 가능)
- 백엔드: Supabase (DB + 사진 저장소 + 공용 로그인)
- 호스팅: GitHub Pages

## 운영
- 비밀번호 바꾸기: Supabase > Authentication > Users > staff 계정 > Reset password
- 사진: Supabase Storage photos 버킷 (무료 1GB)
- 데이터 내보내기: Supabase > Table Editor > items > Export CSV
- 무료 플랜은 1주일간 접속이 없으면 프로젝트가 잠깐 멈춤. 대시보드에서 Restore.

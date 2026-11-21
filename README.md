# 놀이 발자국 리캡 페이지

출구 QR이 여는 정적 페이지예요. 서버·DB 없이 URL 값만 읽어서 보여줘요.

- `recap.html` : 리캡 페이지 / `index.html` : 기본 주소 안내 화면 (같은 파일)
- `images/` : 유형별 공룡 (story=B1, heart=1F, energy=2F, solver=3F, exit=출구)
- `images/exhibits/` : 전시 사진 (선택). `B1-1.jpg`, `B1-2.jpg`, `2F-1.jpg` … 처럼 층-번호.jpg로 넣으면
  '가장 푹 빠져 있던 곳'에 자동으로 나와요. 층마다 최대 3장, 없으면 칸이 숨겨져요.
  팀이 직접 찍은 사진을 쓰세요 (박물관 홈페이지 사진은 저작권 때문에 피하기).

URL 예시: `recap.html?type=energy&sub=heart&top=2F&next=B1&n=3&v=1F,2F,3F&b=100,84,77,89`

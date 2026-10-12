학교 컴퓨터 관리자 PWA - 새 설치본

1. GitHub Pages에 아래 5개 파일을 업로드하세요.
   - index.html
   - manifest.json
   - service-worker.js
   - icon-192.png
   - icon-512.png

2. Google Apps Script의 Code.gs는 함께 제공된 Code.gs로 교체하세요.
   기존 학생 신고 기능을 유지하면서 GitHub Pages 관리자 PWA용 JSONP API가 추가되어 있습니다.

3. Apps Script를 웹 앱으로 다시 배포하세요.
   실행 사용자: 나
   액세스: 모든 사용자

4. index.html의 API 주소가 현재 배포 URL과 같은지 확인하세요.
   현재 설정된 주소:
   https://script.google.com/macros/s/AKfycbyifFoHXBvo0yUq9kWxdRhPRo8-Fw9n9nKrqLhI1YtvJrdD8yhionCtZjK5YEKVcrrig/exec

5. GitHub Pages:
   Settings → Pages → Deploy from a branch → main → /(root)

6. 접속:
   https://dhehhuip-cloud.github.io/my-ai-backen/

주의:
- 이 방식은 GitHub Pages에서 Google Apps Script와 통신하기 위해 JSONP를 사용합니다.
- 관리자 비밀번호는 요청 URL에 포함되므로, 현재처럼 단순한 학교 내부용 시스템에서 사용하는 것을 전제로 합니다.
- 보안이 중요한 실제 서비스라면 별도 인증 방식으로 바꾸는 것을 권장합니다.

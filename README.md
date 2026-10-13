# 신안교회 임직감사예배 모바일 웹 초대장 (GitHub Pages 게시용)

## Github Pages 게시 방법
1. GitHub에서 Public 저장소를 하나 만드세요 (예: sinan-invitation).
2. 이 ZIP을 압축 해제하고 안의 `index.html`, `og-image.png`, `preview.png`, `map.png`, `.nojekyll` 파일을 **저장소 최상위(root)** 에 올리세요. `신안교회_GitHub_Pages_배포용` 폴더 자체를 통째로 중첩 업로드하지 마세요.
3. 저장소 Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main → /(root) → Save.
4. 잠시 후 https://GITHUB사용자명.github.io/sinan-invitation/ 에서 확인하세요.
5. `index.html` 상단 og:image 값 `./og-image.png`를 실제 이미지 절대주소 `https://GITHUB사용자명.github.io/sinan-invitation/og-image.png`로 바꾸고, `og:url`을 공개된 웹주소로 추가하면 카카오톡 등에서 더 안정적으로 미리보기 이미지가 표시됩니다.
6. OG 메타정보를 바꾼 뒤 commit하면 변경 내용이 자동으로 다시 게시됩니다. 카카오톡은 이전 미리보기 이미지가 캐시되어 잠시 남을 수 있습니다.

## 들어 있는 파일
- index.html : 전체 초대장. 약도는 내부에 포함되어 있어 단독 미리보기가 가능합니다.
- og-image.png : SNS/카카오톡용 대표 이미지 (1200 x 630).
- preview.png : 별도 미리보기 이미지 (1200 x 630).
- map.png : 약도 원본 보관용. HTML에 내장된 지도는 별도 파일 없이 표시됩니다.
- .nojekyll : GitHub Pages가 파일을 별도 변환하지 않고 제공하도록 하는 빈 설정 파일.

공개 전 확인: 인명, 행사 정보, 전화번호, 지도 링크. GitHub Pages는 불특정 다수에게 공개됩니다.

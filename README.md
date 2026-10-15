# 박지수 퍼블리싱 포트폴리오

이 저장소에는 GitHub Pages에서 바로 제공할 수 있는 빌드 완료 파일이 들어 있습니다. npm 설치나 빌드 없이 배포할 수 있습니다.

## GitHub 업로드

1. ZIP의 압축을 풉니다.
2. 압축을 푼 폴더를 열고 **그 안의 내용 전체**를 GitHub 저장소의 Add file > Upload files로 업로드합니다.
3. 저장소 Code 첫 화면에 index.html이 바로 보여야 합니다. ZIP 자체나 상위 폴더를 업로드하지 마세요.
4. Settings > Pages > Source: Deploy from a branch / Branch: main / Folder: / (root) > Save.
5. 배포 완료 후 Pages의 Visit site를 누릅니다.

기존 저장소를 업데이트할 때도 이 파일 전체를 같은 위치에 업로드하세요. 기존 파일 교체 후 Commit changes로 저장합니다. assets의 새 파일과 downloads 폴더를 빠뜨리지 마세요. 기존 이름이 다른 assets 파일은 남아 있어도 새 index.html이 새 파일을 참조합니다.

## 파일 역할

- index.html: 포트폴리오 첫 화면
- profile.html: 실제 경력을 반영한 표 형식 이력카드, 인쇄 / PDF 저장 및 Word 다운로드
- assets/: 스타일과 JavaScript. 파일명 변경 금지
- demos/: Vue, React, JavaScript 이벤트, 반응형 브랜드 웹
- downloads/: 편집 가능한 Word 이력카드
- .nojekyll: 정적 파일 배포용 설정. 숨김 파일로 보이지 않더라도 index.html과 assets 등 나머지 파일은 모두 업로드하세요.

## 공개 전 확인

이메일·전화번호·합산 총 경력은 미기재입니다. 이력카드 상단의 '공개 전 확인할 경력 기간 5건' 안내를 검토하세요. 최신 프로젝트 종료월 및 원문 내 기간 불일치·역전 항목을 표시해 두었습니다.

생년월일·성별·주소·병역은 공개용 카드에 포함하지 않았습니다. 실무 이력과 포트폴리오 개인 프로젝트는 구분했습니다. 2019년 TOEIC은 당시 취득 기록입니다.

## 데모 범위

데이터는 가상이며 변경 사항은 새로고침하면 초기화됩니다. 실제 주문·결제·경품·이메일 전송은 없습니다. 외부 CDN을 사용하지 않습니다.

## 확인된 범위

프로덕션 빌드, DOM 기반 주요 기능, 내부 링크·자산 경로 확인 완료. Word 7페이지 렌더링 검수 완료. 실제 브라우저 시각 검수와 인쇄 미리보기는 미실시입니다.

이 ZIP은 업로드 전용입니다. React·Vue·SCSS 수정용 소스는 포함하지 않습니다.

# 박정훈 백엔드 포트폴리오

HTML / CSS / Vanilla JavaScript로 만든 정적 사이트입니다. npm 설치나 빌드가 필요 없습니다.

## 실행

압축을 푼 뒤 index.html을 브라우저로 엽니다. styles.css, script.js, assets 폴더를 같은 위치에 유지하세요.

## GitHub Pages 배포

1. GitHub에서 wjdgns5.github.io 저장소를 만듭니다. 이미 있다면 기존 파일을 확인한 후 업데이트합니다.
2. ZIP을 해제한 내용(index.html, styles.css, script.js, assets 폴더, .nojekyll)을 저장소 최상위에 업로드합니다. ZIP 파일 자체를 올리는 방식이 아닙니다.
3. Settings → Pages → Build and deployment → Source를 Deploy from a branch로 선택합니다.
4. Branch는 main, 폴더는 /(root)를 선택하고 Save를 누릅니다.
5. 배포 완료 후 https://wjdgns5.github.io 에서 확인합니다.

다른 이름의 프로젝트 저장소에 배포해도 모든 로컬 경로가 상대 경로이므로 사용할 수 있습니다.

## 디자인

아이보리와 코발트블루 기반의 작업 노트 스타일입니다. 데스크톱 세로 메뉴, 사진 없는 텍스트 중심 소개, 번호 중심 가로형 프로젝트, 텍스트 기반 기술 목록을 사용합니다. 모바일에서는 메뉴가 상단으로 전환됩니다.

## 수정 위치

- index.html: 소개, 기술, 이력, 프로젝트, 연락처, 프로젝트 상세 대화상자
- styles.css: 색상, 글꼴, 간격, 반응형 레이아웃, 인쇄 레이아웃
- script.js: 테마 전환 및 저장, 상세 대화상자, 메뉴 강조

## 기능

- 아이보리 기본 테마, 슬레이트 어두운 테마 전환 및 저장
- 반응형 레이아웃
- 프로젝트 상세 대화상자: 닫기 버튼, Esc, 바깥 영역 클릭으로 닫기
- 키보드 탐색, 본문 바로가기, 움직임 감소 환경설정 지원

공개 연락처는 이메일과 GitHub입니다. 휴대전화, 생년월일, 상세 주소는 포함하지 않았습니다.
프로젝트 이미지 영역에는 JAM / AMIGO 로고 원본을 비율 변경이나 색상 수정 없이 사용했습니다.
- assets/jam-logo.png: https://github.com/junsoo186/jam 의 static/images/layout/jam.png
- assets/amigo-logo.png: https://github.com/GreenAcademyTeam4/Amigo 의 static/image/logo.png
내용은 첨부 이력서와 Notion '박정훈 이력서'를 바탕으로 구성했습니다.
Notion을 수정해도 자동으로 동기화되지 않습니다.

## 확인 상태

HTML 내부 연결, 로컬 파일 경로, 대화상자 대상 및 JavaScript 구문을 확인했습니다.
현재 환경에 Sites 전용 브라우저 도구가 없어 실제 화면과 브라우저 상호작용은 검증하지 못했습니다.
GitHub Pages 배포는 별도입니다. 제공되는 미리보기는 소유자 전용 비공개 Sites 호스팅입니다.

사진과 전용 인쇄/PDF 저장 버튼은 제거했습니다. 주요 링크는 터치하기 쉬운 테두리 버튼으로 표시됩니다. 연락 영역은 전체 배경과 같은 색을 사용합니다.

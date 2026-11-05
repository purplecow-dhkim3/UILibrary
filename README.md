# UI Library 배포

Git·NAS·로컬 폴더의 Unity UI 리소스를 모아 보고, 목업 보드로 UI를 구성하는 사내 도구입니다.

## 처음 설치
1. **[UILibrary.zip 받기](https://github.com/purplecow-dhkim3/UILibrary/raw/main/bin/UILibrary.zip)** (34MB)
2. 압축을 풀어 `UILibrary.exe`를 원하는 폴더(예: `D:\UILibrary`)에 둡니다. 데이터는 exe 옆 `data\`·`cache\`에 생깁니다.
3. 실행하면 이 리포의 **공용 소스**(Git·NAS)가 자동으로 추가되고, 내 소스도 따로 추가할 수 있습니다.

새 버전이 올라오면 프로그램을 켤 때 업데이트 창이 뜹니다. 업데이트·공용 소스 받기는 로그인 없이 됩니다. 공용 **Git** 소스의 이미지를 받으려면 그 리포를 볼 수 있는 GitHub 로그인과 git이, **NAS** 소스는 사내망이 필요합니다.

## 최신 버전: 0.3.2
게시: 2026-11-05

- 프로젝트 규칙: 소스 > 프로젝트 규칙에서 [학습하기] → 그 프로젝트 UI 프리팹의 이름·구조·버튼 스크립트·글꼴·공용 프리팹을 배움 (5겹 교차 검증 정확도 표시, 팀 채널로 공유)
- Claude 목업이 프로젝트 규칙을 따르고, 공용 프리팹을 그대로 놓음. Unity로 보내면 공용 프리팹은 프리팹 인스턴스로, 버튼은 프로젝트 버튼 스크립트, 글자는 프로젝트 글꼴
- 목업 보드 레이어: 그룹 안 그룹, 버튼 안 글자처럼 요소 안 요소, Unity 앵커 지정, 프리팹을 놓으면 원래 하이어라키 그대로
- [+ 새 보드] 버튼
- Git 소스: 긴 경로 지원, 프리팹 메타도 받음 (업데이트 후 Git 소스를 한 번 재동기화해 주세요)

## 공용 소스 (3개)
- **NAS · 11_PurpleCow** (NAS) — \\nas\Cookapps Project\11_PurpleCow
- **GWPP012_Galaxy** (Git) — https://github.com/cookapps-devops/GWPP012_Galaxy.git @ develop
- **PurpleCow_MadDucks** (Git) — https://github.com/cookapps-devops/PurpleCow_MadDucks.git

_이 파일은 UI Library가 게시할 때 자동으로 만듭니다._

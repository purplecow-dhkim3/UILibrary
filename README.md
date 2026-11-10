# UI Library 배포

Git·NAS·로컬 폴더의 Unity UI 리소스를 모아 보고, 목업 보드로 UI를 구성하는 사내 도구입니다.

## 처음 설치
1. **[UILibrary.zip 받기](https://github.com/purplecow-dhkim3/UILibrary/raw/main/bin/UILibrary.zip)** (34MB)
2. 압축을 풀어 `UILibrary.exe`를 원하는 폴더(예: `D:\UILibrary`)에 둡니다. 데이터는 exe 옆 `data\`·`cache\`에 생깁니다.
3. 실행하면 이 리포의 **공용 소스**(Git·NAS)가 자동으로 추가되고, 내 소스도 따로 추가할 수 있습니다.

새 버전이 올라오면 프로그램을 켤 때 업데이트 창이 뜹니다. 업데이트·공용 소스 받기는 로그인 없이 됩니다. 공용 **Git** 소스의 이미지를 받으려면 그 리포를 볼 수 있는 GitHub 로그인과 git이, **NAS** 소스는 사내망이 필요합니다.

## 최신 버전: 0.3.6
게시: 2026-11-10

- NAS에서 UILibrary.exe를 켜면 내 PC(%LOCALAPPDATA%\UILibrary)에 자동 설치 + 바탕화면·시작 메뉴 바로가기 (NAS에는 아무것도 쓰지 않음)
- 이미 설치돼 있으면 설치본을 켬 (NAS 것이 더 새것일 때만 덮어씀)

## 공용 소스 (4개)
- **NAS · 11_PurpleCow** (NAS) — \\nas\Cookapps Project\11_PurpleCow
- **GWPP012_Galaxy** (Git) — https://github.com/cookapps-devops/GWPP012_Galaxy.git @ develop
- **PurpleCow_MadDucks** (Git) — https://github.com/cookapps-devops/PurpleCow_MadDucks.git
- **PurpleCow_ForgeHero** (Git) — https://github.com/cookapps-devops/PurpleCow_ForgeHero.git

_이 파일은 UI Library가 게시할 때 자동으로 만듭니다._

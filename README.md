# UI Library 배포

Git·NAS·로컬 폴더의 Unity UI 리소스를 모아 보고, 목업 보드로 UI를 구성하는 사내 도구입니다.

## 처음 설치
1. **[UILibrary.zip 받기](https://github.com/purplecow-dhkim3/UILibrary/raw/main/bin/UILibrary.zip)** (34MB)
2. 압축을 풀어 `UILibrary.exe`를 원하는 폴더(예: `D:\UILibrary`)에 둡니다. 데이터는 exe 옆 `data\`·`cache\`에 생깁니다.
3. 실행하면 이 리포의 **공용 소스**(Git·NAS)가 자동으로 추가되고, 내 소스도 따로 추가할 수 있습니다.

새 버전이 올라오면 프로그램을 켤 때 업데이트 창이 뜹니다. 업데이트·공용 소스 받기는 로그인 없이 됩니다. 공용 **Git** 소스의 이미지를 받으려면 그 리포를 볼 수 있는 GitHub 로그인과 git이, **NAS** 소스는 사내망이 필요합니다.

## 최신 버전: 0.3.4
게시: 2026-11-05

- 구조 규칙과 리소스 분리: 고른 프로젝트 규칙은 이름·레이어 구조·앵커·Unity 관례에만 쓰고, 리소스는 기본으로 모든 프로젝트에서 레퍼런스와 가장 비슷한 것을 고름
- Claude 패널: "구조 규칙" 칸과 "리소스: 모든 프로젝트" 칸을 따로 고름

## 공용 소스 (3개)
- **NAS · 11_PurpleCow** (NAS) — \\nas\Cookapps Project\11_PurpleCow
- **GWPP012_Galaxy** (Git) — https://github.com/cookapps-devops/GWPP012_Galaxy.git @ develop
- **PurpleCow_MadDucks** (Git) — https://github.com/cookapps-devops/PurpleCow_MadDucks.git

_이 파일은 UI Library가 게시할 때 자동으로 만듭니다._

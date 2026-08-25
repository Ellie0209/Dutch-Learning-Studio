# Dutch Learning Studio

네덜란드어 A1–C2 학습용 반응형 웹앱입니다.

## 공개 주소 구조

Vercel 배포 후 기본 주소는 자동으로 `/Dutch` 로 이동합니다.

예시:

`https://YOUR-PROJECT.vercel.app/Dutch`

`index.html` 경로를 직접 공유할 필요가 없습니다.

## 자동 배포 설정

1. GitHub에서 새 저장소를 만듭니다. 추천 이름: `Dutch-Learning-Studio`
2. 이 폴더 안의 모든 파일을 저장소의 최상위에 업로드합니다.
3. Vercel → Add New → Project → Import Git Repository에서 해당 GitHub 저장소를 선택합니다.
4. Framework Preset은 `Other` 또는 자동 감지를 사용합니다.
5. Build Command / Output Directory는 비워 둡니다.
6. Deploy를 누릅니다.
7. 이후 GitHub `main` 브랜치에 변경사항을 push할 때마다 Vercel이 자동 Production 배포합니다.

## 포함 기능

- 모바일 / 태블릿 / PC 반응형 레이아웃
- 한국어 / English 전환
- 3D / Amsterdam / Windmill / Modern City 테마
- A1–C2 레벨
- 오늘의 레슨
- 주제별 학습
- 네덜란드어 발음 연습
- Slow Listening
- Writing Lab
- 로컬 프로필 / 진도 저장

## 배포 방식

이 프로젝트는 정적 HTML 앱이라 별도 빌드가 필요하지 않습니다.
이미지는 앱 안에 포함되어 외부 이미지 링크에 의존하지 않습니다.

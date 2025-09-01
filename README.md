# Work Assistant

업무 보조 도구 모음 웹 애플리케이션

## 프로젝트 구성

- `src/ControlAdmin.html` - 사장님 플러스 헬프센터 메인 페이지
- `src/ControlAdmin_backup.html` - 이전 버전 백업

## GitHub Pages로 접속하기

### 1. GitHub Pages 설정 방법

1. GitHub 저장소 페이지로 이동
   - https://github.com/jk-ayaan/work-assistant

2. Settings 탭 클릭

3. 왼쪽 메뉴에서 "Pages" 선택

4. Source 섹션에서:
   - Source: "Deploy from a branch" 선택
   - Branch: "main" 선택
   - Folder: "/ (root)" 선택
   - Save 버튼 클릭

5. 몇 분 후 페이지가 활성화되면 다음 URL로 접속 가능:
   - https://jk-ayaan.github.io/work-assistant/

### 2. 직접 페이지 접속 링크

GitHub Pages가 활성화되면 다음 링크로 직접 접속할 수 있습니다:

- **메인 페이지**: https://jk-ayaan.github.io/work-assistant/src/ControlAdmin.html
- **백업 페이지**: https://jk-ayaan.github.io/work-assistant/src/ControlAdmin_backup.html

### 3. 페이지 업데이트

- `main` 브랜치에 푸시하면 자동으로 GitHub Pages가 업데이트됩니다
- 업데이트 반영까지 약 1-5분 정도 소요될 수 있습니다

## 주요 기능

### 사장님 플러스 헬프센터
- 다국어 지원 (한국어/영어)
- 반응형 디자인
- 검색 기능
- 카테고리별 FAQ
- 다크모드 지원

## 로컬에서 실행하기

```bash
# 저장소 클론
git clone https://github.com/jk-ayaan/work-assistant.git

# 디렉토리 이동
cd work-assistant

# 브라우저에서 HTML 파일 직접 열기
open src/ControlAdmin.html  # macOS
# 또는
start src/ControlAdmin.html  # Windows
```

## 기여하기

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 라이선스

이 프로젝트는 개인 사용을 위한 프로젝트입니다.
# 폴더 구조

이 저장소는 SnapFig의 백엔드와 프론트엔드를 통합 관리합니다.  
최상위 폴더 구조와 각 주요 디렉토리의 역할은 다음과 같습니다.

```
SnapFig/
├── backend/              # 백엔드 서비스 (AI, Gateway 등)
│   ├── ai_task_server/   # OCR 및 AI 요약 마이크로서비스
│   └── gateway_backend/  # PDF 분석, 주석, API 게이트웨이
├── frontend/             # Flutter 기반 모바일 앱 (iOS, Android)
├── reference-mapper/     # PDF 참조 매핑 및 OCR 서비스
├── docs/                 # 문서 및 가이드
└── README.md             # 메인 프로젝트 소개
```

#### backend/
- **ai_task_server/**: OCR 및 AI 요약 기능 제공
- **gateway_backend/**: PDF 분석, 주석 탐지, API 게이트웨이 역할

#### frontend/
- **lib/**: Flutter/Dart 메인 소스 (core, features, shared 등)
- **android/**, **ios/**: 플랫폼별 코드 및 리소스
- **assets/**: 폰트, 아이콘 등 정적 자산

#### reference-mapper/
- **app/**: PDF 참조 매핑, 레이아웃 감지, OCR 핵심 로직
- **main.py**: reference-mapper 서비스 진입점

#### docs/
- 프로젝트 구조, 기여, 라이선스 등 문서

자세한 내용은 각 디렉토리의 README를 참고하세요. 
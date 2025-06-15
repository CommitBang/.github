# 기여 가이드

SnapFig 프로젝트에 관심을 가져주셔서 감사합니다!

## 기여 방법

1. **이슈 확인**
   - 기존 이슈를 확인하거나, 새로운 이슈를 등록하세요.

2. **Fork & 브랜치 생성**
   - 저장소를 포크 후, 기능별 브랜치 생성 (예: `feature/your-feature`)

3. **코드 스타일**
   - 각 하위 프로젝트의 코드 스타일을 준수하세요.
     - **frontend**: Dart/Flutter 스타일, `flutter format .`으로 코드 포매팅, `flutter analyze`로 정적 분석, 테스트는 `flutter test`로 실행. 개발 환경 및 기여 절차는 `frontend/README.md` 참고
     - **backend**: Python PEP8, `black`, `flake8` 사용
     - **reference-mapper**: Python PEP8, `black`, `flake8`, `pytest` 사용. 개발 환경 및 기여 절차는 `reference-mapper/README.md` 참고

4. **커밋 메시지**
   - 명확하고 일관된 커밋 메시지 작성 (예: `feat: OCR 기능 추가`)

5. **Pull Request**
   - 브랜치 푸시 후 PR 생성
   - 관련 이슈를 PR 설명에 명시

6. **리뷰 및 머지**
   - 코드 리뷰에 적극 참여하고, 피드백을 반영하세요.

## 추가 안내

- 상세한 기여 가이드는 각 하위 프로젝트의 `CONTRIBUTING.md` 또는 README를 참고하세요.
- 각 디렉토리의 라이선스 및 코드 오브 컨덕트를 준수해 주세요. 
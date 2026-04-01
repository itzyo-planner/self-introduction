# ✍️ 자기소개서 생성기

AI(Claude)를 활용한 맞춤형 자기소개서 생성 웹 서비스입니다.

## 주요 기능

- 이름, 지원 직무/회사, 경력, 기술 스택 등 개인 정보 입력
- 톤 & 스타일 선택 (공식적 / 친근한 / 창의적 / 간결한)
- 목표 글자 수 선택 (600~2,000자)
- Claude AI가 맞춤형 자기소개서 자동 생성
- 결과 복사 및 텍스트 파일 다운로드

## 사용 방법

1. `index.html`을 브라우저에서 열거나 GitHub Pages로 배포
2. Anthropic API 키 입력 ([console.anthropic.com](https://console.anthropic.com)에서 발급)
3. 개인 정보 입력 후 **자기소개서 생성하기** 클릭

## 기술 스택

- HTML / CSS / JavaScript (순수 프론트엔드, 별도 서버 불필요)
- Anthropic Claude API (`claude-opus-4-6`)

## 배포

GitHub Pages에서 바로 서비스할 수 있습니다:
- Repository Settings → Pages → Source: `main` 브랜치 `/root`

## 주의사항

API 키는 브라우저 localStorage에만 저장되며 외부 서버로 전송되지 않습니다.

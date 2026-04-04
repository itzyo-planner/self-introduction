# ✍️ 자기소개서 AI 생성기

GPT-4o mini 기반 맞춤형 자기소개서 생성 웹 서비스입니다.

## 요금제

| 분량 | 방식 |
|------|------|
| 간략형 600자 | 무료 |
| 표준형 1,000자 | AdSense 광고 1회 시청 |
| 상세형 1,500자 | 유료 결제 (기본 ₩1,000) |
| 심층형 2,000자 | 유료 결제 (기본 ₩1,500) |

## 파일 구조

```
index.html   메인 서비스
admin.html   관리자 페이지 (/admin.html)
```

## 관리자 페이지

`/admin.html` 접속 → 초기 비밀번호 `admin1234`

- **대시보드** — 총 생성 수, 광고 시청 수, 결제 수익, 요금제별 현황, 로그
- **API 설정** — OpenAI API 키, 토스페이먼츠 클라이언트 키
- **광고 설정** — AdSense Publisher ID, 리워드 슬롯 ID, 최소 시청 시간
- **요금제 설정** — 상세형·심층형 가격 변경
- **보안** — 비밀번호 변경, 통계 초기화

> 설정 저장 즉시 서비스에 반영됩니다.

## AdSense 광고 연동

1. 관리자 → 광고 설정에서 `ca-pub-XXXX` 와 리워드 슬롯 ID 입력 후 저장
2. AdSense 미설정 또는 테스트 모드 시 → 카운트다운 모의 광고 자동 표시
3. AdSense 심사 통과 후 실제 리워드 광고 자동 전환

## 배포

- 서비스: https://self-introduction-3q0.pages.dev
- 관리자: https://self-introduction-3q0.pages.dev/admin.html

## 기술 스택

- 순수 HTML/CSS/JavaScript (서버 불필요)
- OpenAI GPT-4o mini API
- 토스페이먼츠 결제
- Google AdSense 리워드 광고 (H5 Ads API)

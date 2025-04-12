# 🎙️ VoiceAppLegacy

React Native 기반 음성 인식 테스트 앱입니다.
`@react-native-voice/voice` 라이브러리를 사용하여 사용자의 음성을 인식하고, 인식된 텍스트를 화면에 출력합니다.

---

## 📦 프로젝트 개요

- **사용 기술**: React Native, TypeScript
- **음성 인식**: `@react-native-voice/voice`
- **대상 플랫폼**: Android (iOS 미지원)
- **권한**: 마이크 권한 요청 포함

---

## ⚙️ 설치 및 실행 방법

### 1. 프로젝트 클론
```bash
git clone https://github.com/your-username/VoiceAppLegacy.git
cd VoiceAppLegacy
```

### 2. 패키지 설치
```bash
npm install
# 또는
yarn
```

### 3. Android SDK 경로 설정
`android/local.properties` 파일을 생성하고 다음 내용을 입력:
```properties
sdk.dir=C:\\Users\\YOUR_NAME\\AppData\\Local\\Android\\Sdk
```
> 자신의 SDK 경로에 맞게 수정하세요.

### 4. 앱 실행
```bash
npx react-native run-android
```

---

## ✅ 필수 조건

- Android Studio 설치 및 환경 구성 완료
- 실제 Android 기기 또는 에뮬레이터 준비
- Google 음성 인식 서비스 활성화 (기기 설정 > 음성 입력)
- Android 10 이상 권장

---

## 📁 폴더 구조 예시
```
VoiceAppLegacy/
├── android/
├── ios/ (미사용)
├── App.tsx
├── index.js
├── app.json
├── package.json
└── ...
```

---

## 🛠 주요 기능

- 🎤 녹음 시작 및 중지 버튼
- 🧠 음성 인식 결과 실시간 출력
- 🔐 마이크 권한 요청
- 🧪 음성 인식 서비스 목록 로깅

---

## ❗ 참고 및 주의사항

- 일부 Android 기기(Galaxy A12 등)는 시스템 설정상 외부에서 Google STT 접근이 제한될 수 있습니다.
- iOS는 현재 지원하지 않습니다.

---

## 📜 라이선스

MIT License

---

## 🙋‍♀️ 기여 & 문의

- Pull Request 및 Issue 환영합니다!
- 개발자: 이희은 (he0960@naver.com)


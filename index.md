---
layout: default
title: Numgye Legal
---

# Numgye (넘겨) — Legal

- [개인정보처리방침 (한국어)](#개인정보처리방침)
- [Privacy Policy (English)](#privacy-policy)

---

## 개인정보처리방침

**넘겨 (Numgye) — 자동 악보 페이지 넘김 앱**

**시행일: 2026년 3월 21일**

**최종 수정일: 2026년 8월 15일**

### 1. 소개

본 개인정보 처리방침은 넘겨(이하 "앱" 또는 "당사")가 모바일 애플리케이션 사용 시 정보를 처리하는 방법을 설명합니다. 당사는 이용자의 개인정보 보호를 위해 최선을 다하고 있습니다.

### 2. 수집하는 정보

#### 2.1 수집하지 않는 정보

넘겨는 개인정보 보호를 기본 원칙으로 설계되었습니다. 당사는 다음 정보를 수집하지 **않습니다**:

- 개인 식별 정보 (이름, 이메일, 전화번호)
- 위치 정보
- 연락처 정보
- 사진, 카메라, 마이크 데이터
- 브라우저 이용 기록
- 금융 또는 결제 정보
- 사용자 계정 또는 로그인 자격 증명

#### 2.2 기기에 저장되는 데이터

다음 데이터는 이용자의 기기에 저장됩니다:

- 앱에 가져온 **PDF 파일**
- **악보 메타데이터** (제목, BPM 설정, 박자표)
- **마디 데이터** (AI 감지 및 수동 편집된 마디 경계)
- **셋리스트 구성**
- **앱 설정** (환경설정, 표시 옵션)
- 이용자가 생성한 **백업 파일** (ZIP 형식으로 기기에 저장)

**가져온 PDF 파일 자체는 어떠한 서버로도 전송되지 않습니다.** 다만 아래 2.4 항에 따라 악보 페이지의 렌더링 이미지와 마디 좌표가 전송될 수 있습니다.

#### 2.3 분석 데이터

분석 기능이 활성화된 경우, 앱 경험 개선을 위해 Firebase Analytics를 통해 익명 사용 통계를 수집할 수 있습니다. 이 데이터에는 다음이 포함될 수 있습니다:

- 앱 실행/종료 이벤트
- 기능 사용 빈도 (예: 재생 시작, AI 감지 실행)
- 기기 유형 및 OS 버전
- 앱 버전
- 충돌 보고서

이 데이터는 **익명**이며 개인을 식별하는 데 사용될 수 없습니다.

#### 2.4 AI 마디 감지 개선을 위한 악보 페이지 수집

AI 마디 감지 기능의 정확도를 높이기 위해, **이용자가 마디를 직접 추가하거나 수정한 페이지에 한해** 다음 데이터를 자동으로 수집합니다:

- **악보 페이지의 렌더링 이미지** (흑백, 축소본)
- **마디 좌표 데이터** — AI가 감지한 결과와 이용자가 수정한 최종 결과
- **악보 메타데이터** — 곡 제목, 파일 식별 해시, 페이지 번호 및 총 페이지 수
- **환경 정보** — 앱 버전, AI 모델 버전, 기기 유형(태블릿·휴대폰 등 대략적 분류), OS 버전, 언어 설정 (기기의 정확한 모델명은 수집하지 않습니다)
- **익명 설치 식별자** — 앱 설치 시 생성되는 무작위 ID (이용자 계정·기기 고유번호·광고 식별자와 무관하며, 이용자를 식별하지 않습니다)

수집 시점 및 조건:

- **이용자가 마디를 직접 추가·이동·크기 조정·삭제한 페이지만** 대상입니다. AI가 감지한 결과를 그대로 두고 수정하지 않은 페이지는 전송되지 않습니다
- 마디 편집을 마치고 편집 모드를 벗어날 때 전송됩니다
- **Wi-Fi 연결 시에만** 전송되며, 셀룰러 데이터는 사용하지 않습니다
- **가져온 PDF 파일 원본은 전송되지 않습니다**

**수집 거부 (옵트아웃):** 앱 내 **설정 → AI 개선 데이터 수집** 에서 언제든지 끌 수 있습니다. 끄는 즉시 전송이 중단됩니다.

본 항목은 iOS/iPadOS 와 Android 양쪽에 동일하게 적용됩니다.

### 3. 정보 이용 목적

당사는 익명 분석 데이터를 다음 목적으로만 사용합니다:

- 버그 및 충돌 식별 및 수정
- 가장 유용한 기능 파악
- 앱 성능 및 사용자 경험 개선

2.4 항의 악보 페이지 데이터는 **AI 마디 감지 모델의 성능 평가 및 개선** 목적으로만 사용하며, 당사 내부에서만 이용합니다. 제3자에게 제공하거나 공개 데이터셋으로 배포하지 않습니다.

당사는 어떠한 데이터도 광고, 마케팅, 프로파일링 또는 제3자 판매에 사용하지 **않습니다**.

### 4. 데이터 저장 및 보안

- 모든 사용자 콘텐츠(PDF, 악보, 마디, 셋리스트)는 이용자의 기기에 로컬로 저장됩니다.
- **AI 마디 감지 자체는 내장 모델로 전적으로 기기에서 실행**되며, 감지 기능을 쓰는 데 인터넷 연결이 필요하지 않습니다. 감지 결과를 서버로 보내 처리하지 않습니다.
- 2.4 항의 수집 데이터는 전송 시 HTTPS/TLS로 암호화되며, 접근 권한이 제한된 당사 저장소에 보관됩니다. 다른 이용자가 열람할 수 없습니다.
- 백업 파일은 로컬에 생성 및 저장되며, 백업 공유는 이용자의 통제 하에 이루어집니다.

### 5. 제3자 서비스

#### Firebase (Google)

Google의 Firebase 서비스를 사용합니다:

- **Firebase Analytics / Crashlytics** — 익명 사용 통계 및 충돌 보고 (2.3 항)
- **Firebase Storage** — 2.4 항의 악보 페이지 데이터 보관

Firebase의 데이터 처리는 [Google 개인정보 처리방침](https://policies.google.com/privacy)에 따릅니다. 그 외 어떠한 제3자 서비스에도 이용자의 데이터가 제공되지 않습니다.

### 6. 아동의 개인정보

넘겨는 만 14세 미만 아동의 개인정보를 고의로 수집하지 않습니다. 앱은 계정을 요구하지 않으며, 광고를 포함하지 않고, 인앱 구매나 소셜 기능이 없습니다.

### 7. 데이터 보관 및 삭제

기기에 저장된 데이터:

- 앱에서 **악보를 삭제**하면 해당 데이터가 기기에서 제거됩니다.
- **앱을 삭제**하면 모든 앱 데이터가 기기에서 제거됩니다.
- 이용자가 생성한 **백업 파일**은 수동으로 삭제할 때까지 기기에 남아 있습니다.

분석 데이터 (2.3 항):

- Firebase Analytics 데이터: 최대 14개월
- Firebase Crashlytics 데이터: 최대 90일

2.4 항에 따라 이미 전송된 데이터:

- AI 마디 감지 개선 목적이 유지되는 동안 보관하며, 목적 달성 시 삭제합니다.
- **앱을 삭제하거나 수집을 끄더라도 이미 전송된 데이터는 자동으로 삭제되지 않습니다.** 삭제를 원하시면 아래 10항의 이메일로 요청해 주세요.
- 삭제 요청 시 해당 설치의 **익명 설치 식별자**에 연결된 데이터 전체를 삭제합니다. 앱 내 **설정 → AI 개선 데이터 수집** 화면에서 본인의 설치 식별자를 확인해 요청에 포함해 주세요.

### 8. 이용자의 권리

이용자는 자신의 데이터에 대해 완전한 통제권을 갖습니다:

- **접근**: 모든 데이터는 앱 내에서 확인할 수 있습니다.
- **내보내기**: 백업 기능을 사용하여 라이브러리를 내보낼 수 있습니다.
- **삭제**: 개별 악보를 삭제하거나 앱을 삭제하여 기기 내 모든 데이터를 제거할 수 있습니다. 전송된 데이터의 삭제는 7항을 참고하세요.
- **수집 거부**: **설정 → AI 개선 데이터 수집** 을 꺼서 2.4 항의 수집을 언제든 중단할 수 있습니다.
- **분석 제한**: 기기의 OS 설정에서 **광고 추적 제한**(iOS) 또는 **광고 개인최적화 사용 중지**(Android)를 활성화하면 2.3 항의 분석 데이터 수집이 제한됩니다.

### 9. 개인정보 처리방침 변경

당사는 수시로 본 개인정보 처리방침을 업데이트할 수 있습니다. 변경 사항이 있을 경우 앱 내에 새로운 개인정보 처리방침을 게시하고 "최종 수정일"을 업데이트하여 알려드리겠습니다.

### 10. 문의

본 개인정보 처리방침에 대한 질문이 있으시면 아래로 연락해 주세요:

- 이메일: <msseodev10@gmail.com>

*본 개인정보 처리방침은 넘겨 버전 1.0.0 이상에 적용됩니다. 2.4 항(AI 개선을 위한 악보 페이지 수집)은 버전 1.0.6 이상에 적용됩니다.*

---

## Privacy Policy

**Numgye (넘겨) — Automatic Sheet Music Page Turner**

**Effective Date: March 21, 2026**

**Last updated: August 15, 2026**

### 1. Introduction

This Privacy Policy describes how Numgye ("we", "our", or "the app") handles information when you use our mobile application. We are committed to protecting your privacy.

### 2. Information We Collect

#### 2.1 Information We Do NOT Collect

Numgye is designed with privacy in mind. We do **not** collect:

- Personal information (name, email, phone number)
- Location data
- Contact information
- Photos, camera, or microphone data
- Browsing history
- Financial or payment information
- User accounts or login credentials

#### 2.2 Locally Stored Data

The following data is stored on your device:

- **PDF files** you import into the app
- **Score metadata** (titles, BPM settings, time signatures)
- **Measure data** (AI-detected and manually edited measure boundaries)
- **Setlist configurations**
- **App settings** (preferences, display options)
- **Backup files** you create (stored locally as ZIP archives)

**The PDF files you import are never transmitted to any server.** However, rendered images of score pages and measure coordinates may be transmitted as described in Section 2.4 below.

#### 2.3 Analytics Data

If analytics are enabled, we may collect anonymous usage statistics through Firebase Analytics to improve the app experience. This data may include:

- App open/close events
- Feature usage frequency (e.g., playback started, AI detection triggered)
- Device type and OS version
- App version
- Crash reports

This data is **anonymous** and cannot be used to identify individual users.

#### 2.4 Score Page Collection for AI Measure Detection Improvement

To improve the accuracy of AI measure detection, **and only for pages where you have added or corrected measures yourself**, the app automatically collects:

- **Rendered images of score pages** (grayscale, downscaled)
- **Measure coordinate data** — both the AI's detection output and your corrected result
- **Score metadata** — title, file identification hash, page number and total page count
- **Environment information** — app version, AI model version, device type (a coarse tablet/phone classification), OS version, language setting (the exact device model is not collected)
- **Anonymous installation identifier** — a random ID generated when the app is installed (unrelated to any account, device serial, or advertising identifier, and not used to identify you)

When and how it is collected:

- **Only pages on which you have added, moved, resized, or deleted a measure yourself.** Pages where you leave the AI's detection result untouched are never transmitted
- Transmitted when you finish editing measures and leave edit mode
- Transmitted **over Wi-Fi only** — cellular data is never used
- **The original PDF files you import are not transmitted**

**Opting out:** You can turn this off at any time in **Settings → AI Improvement Data Collection** in the app. Transmission stops immediately.

This section applies equally to the iOS/iPadOS and Android versions.

### 3. How We Use Information

We use anonymous analytics data solely to:

- Identify and fix bugs and crashes
- Understand which features are most useful
- Improve app performance and user experience

The score page data described in Section 2.4 is used solely to **evaluate and improve our AI measure detection model**, internally. It is not provided to third parties and is not released as a public dataset.

We do **not** use any data for advertising, marketing, profiling, or sale to third parties.

### 4. Data Storage and Security

- All user content (PDFs, scores, measures, setlists) is stored locally on your device.
- **AI measure detection itself runs entirely on-device** using an embedded model — no internet connection is required to use it, and detection is never performed on a server.
- Data collected under Section 2.4 is encrypted in transit via HTTPS/TLS and kept in access-restricted storage that we control. Other users cannot read it.
- Backup files are created and stored locally; sharing backups is under your control.

### 5. Third-Party Services

#### Firebase (Google)

We use Google's Firebase services:

- **Firebase Analytics / Crashlytics** — anonymous usage statistics and crash reports (Section 2.3)
- **Firebase Storage** — storage for the score page data described in Section 2.4

Firebase's data handling is governed by [Google's Privacy Policy](https://policies.google.com/privacy). No other third-party services receive your data.

### 6. Children's Privacy

Numgye does not knowingly collect any personal information from children under 13 (or applicable age in your jurisdiction). The app does not require an account, does not contain ads, and does not include in-app purchases or social features.

### 7. Data Retention and Deletion

Data stored on your device:

- **Deleting a score** from the app removes its data from your device.
- **Uninstalling the app** removes all app data from your device.
- **Backup files** you created remain on your device until you manually delete them.

Analytics data (Section 2.3):

- Firebase Analytics data: up to 14 months
- Firebase Crashlytics data: up to 90 days

Data already transmitted under Section 2.4:

- Retained for as long as it serves the purpose of improving AI measure detection, and deleted once that purpose is fulfilled.
- **Uninstalling the app or turning collection off does not automatically delete data that has already been transmitted.** To have it deleted, email us using the address in Section 10.
- On request, we delete all data associated with that installation's **anonymous installation identifier**. You can find your identifier in **Settings → AI Improvement Data Collection** in the app; please include it in your request.

### 8. Your Rights

You have full control over your data:

- **Access**: All your data is visible within the app.
- **Export**: Use the backup feature to export your library.
- **Delete**: Remove individual scores or uninstall the app to delete all data on your device. For transmitted data, see Section 7.
- **Opt out**: Turn off **Settings → AI Improvement Data Collection** to stop the collection described in Section 2.4 at any time.
- **Limit analytics**: Enable **"Limit Ad Tracking"** (iOS) or **"Opt out of Ads Personalization"** (Android) in your OS settings to restrict the analytics collection described in Section 2.3.

### 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy within the app and updating the "Last Updated" date.

### 10. Contact Us

If you have questions about this Privacy Policy, please contact us at:

- Email: <msseodev10@gmail.com>

*This privacy policy applies to Numgye version 1.0.0 and later. Section 2.4 (Score Page Collection for AI Measure Detection Improvement) applies to version 1.0.6 and later.*

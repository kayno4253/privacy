<style>
:root{color-scheme:light dark;--bg:#f6f7fb;--card:#fff;--ink:#222338;--muted:#62677a;--accent:#6853d8;--line:#e3e5ee}*{box-sizing:border-box}body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.75 system-ui,-apple-system,"Segoe UI",sans-serif}.policy-page{max-width:900px;margin:40px auto;padding:clamp(22px,5vw,56px);background:var(--card);border:1px solid var(--line);border-radius:22px;box-shadow:0 18px 50px #18204a12}.policy-page h1{font-size:clamp(1.7rem,4vw,2.5rem);line-height:1.25;letter-spacing:-.03em}.policy-page h2{margin-top:2.3em;padding-bottom:.35em;border-bottom:1px solid var(--line);font-size:1.45rem}.policy-page h3{margin-top:1.7em;font-size:1.1rem}.policy-page a{color:var(--accent);overflow-wrap:anywhere}.policy-page blockquote{margin:1.2em 0;padding:.2em 1em;border-left:4px solid var(--accent);background:#6853d80c;color:var(--muted)}.policy-page table{display:block;max-width:100%;overflow-x:auto;border-collapse:collapse;font-size:.93em}.policy-page th,.policy-page td{padding:10px 12px;border:1px solid var(--line);vertical-align:top}.policy-page th{background:#6853d80c}.policy-page code{overflow-wrap:anywhere}.policy-page li{padding-left:.18em}.policy-page hr{border:0;border-top:1px solid var(--line);margin:2.5em 0}@media(prefers-color-scheme:dark){:root{--bg:#11121a;--card:#191a24;--ink:#ececf5;--muted:#b4b7c7;--line:#343643}.policy-page{box-shadow:0 18px 50px #0005}}
</style>
<main class="policy-page" markdown="1"># 개인정보처리방침 / Privacy Policy

- 앱: **My Travel Map** (Android, 패키지 `com.elne.travel_map`)
- 시행일 / Effective date: **2026-10-13**
- 문의 / Contact: kayno@naver.com

[English version below](#english)

---

## 한국어

Herion(이하 "운영자")은 My Travel Map(이하 "앱") 이용자의 개인정보를 소중히 다루며,
「개인정보 보호법」 등 관련 법령을 지킵니다. 이 방침은 앱이 어떤 정보를 왜 처리하고, 누구와 공유하며,
이용자가 어떻게 지우거나 거부할 수 있는지 설명합니다.

### 1. 한눈에 보기

- **로그인하지 않아도** 앱의 기본 기능(장소·여행·경로 기록)을 모두 쓸 수 있고, 이때 기록은 **기기 안에만** 저장됩니다.
- 구글로 로그인하면 기기 간 동기화를 위해 여행 기록을 Google Cloud Firestore 에 저장합니다.
- **사진은 기기 밖으로 보내지 않습니다**(직접 공유하거나 백업 파일을 내보낼 때만 이용자가 고른 곳으로 나갑니다).
- 정확한 위치는 **앱을 보고 있을 때** 또는 **이용자가 시작한 경로 기록 중**(상시 알림 표시)에만 씁니다.
- **광고가 없고**, 개인정보를 **판매하지 않으며**, 광고 ID 를 쓰지 않습니다.

### 2. 처리하는 정보와 목적

| 구분 | 항목 | 목적 | 언제 |
|---|---|---|---|
| 계정 | 구글 계정 이름, 이메일, 프로필 사진 주소, Firebase 사용자 ID(uid) | 로그인, 계정 구분, 동기화 | 구글 로그인 시 |
| 여행 기록 | 장소(이름·좌표·나라·지역·방문일·메모·별점·비용·태그·분류), 이동 경로(GPS 좌표·시각), 여행 일정, 예약, 준비물, 경비·멤버 이름, 컬렉션 | 기기 저장·기기 간 동기화·통계 | 로그인 시 Firestore 에 동기화(게스트는 기기에만) |
| 사진 | 이용자가 장소에 붙인 사진 | 장소 기록 표시 | **기기에만 저장**, 서버로 보내지 않음 |
| 위치 | 정확한 위치(GPS) | 지도에 내 위치 표시, 현재 위치로 장소 추가, 이용자가 시작한 경로 기록 | 앱 사용 중 또는 경로 기록 중(상시 알림)만. 백그라운드 위치 권한은 요청하지 않음 |
| 공개 프로필 | 표시 이름, 프로필 사진 주소, 공유 설정 | 친구·커뮤니티에서 이용자 표시 | 소셜 기능 사용 시. **이메일은 공개하지 않음** |
| 커뮤니티 | 피드 글(메모·장소 이름·나라·이모지·방문일·약 1km 단위로 반올림한 좌표, 작성자 표시 이름), 좋아요, 신고(사유), 차단 목록, 친구 관계, 공유 여행(이름·멤버 표시 이름·장소·경비) | 커뮤니티·친구·공유 여행 기능 제공, 신고 검토·운영 | 해당 기능 사용 시. 피드 글에는 사진을 올리지 않음 |
| 오류 진단 | 충돌 기록(스택 추적), 기기 모델, OS·앱 버전, 메모리·디스크 상태, Crashlytics 설치 ID | 오류 수정, 안정성 개선 | 출시 빌드에서 기본 켬, **설정에서 끌 수 있음** |
| 구매 | 구매한 상품, 구매 토큰·상태(Google Play 제공) | 프리미엄 이용 권한 확인·복원 | 구매 시. **카드 정보는 받지 않음**(Google Play 가 처리) |
| 기기 설정 | 언어·테마·단위·기준 통화 등 | 앱 설정 유지 | 기기에만 저장 |

앱은 위 목적 외의 용도로 정보를 쓰지 않으며, 목적이 바뀌면 미리 알리고 필요한 경우 동의를 받습니다.

### 3. 외부 서비스(제3자 제공·처리 위탁·국외 이전)

앱은 기능을 위해 다음 서비스와 통신합니다. 운영자가 이용자 정보를 판매하거나 광고 목적으로 제공하지 않습니다.

| 받는 곳 | 나라 | 보내는 정보 | 목적 | 보유 |
|---|---|---|---|---|
| Google LLC — Firebase Authentication, Cloud Firestore | 미국 등(Google 데이터센터) | 계정 정보, 여행 기록, 커뮤니티 데이터 | 로그인·저장·동기화(처리 위탁) | 계정 삭제 시까지 |
| Google LLC — Firebase Crashlytics | 미국 | 오류 진단 정보 | 오류 분석(처리 위탁) | 최대 90일 |
| Google LLC — Google 로그인, Google Play 결제 | 미국 | 로그인 요청, 구매 정보 | 로그인·결제 | Google 방침에 따름 |
| OpenFreeMap(Hyperknot Software Kft., 타일 서비스 — OpenMapTiles 스키마·OpenStreetMap 데이터, Cloudflare CDN 경유 가능), MapTiler AG(위성 지도, 프리미엄 사용 시) | 헝가리, 스위스 및 CDN 제공 지역 | 보고 있는 지도 영역(타일 요청), 네트워크 메타데이터와 IP 주소(서비스 오류·보안 로그 정책은 [OpenFreeMap 방침](https://openfreemap.org/privacy/) 참고) | 지도 표시 | OpenFreeMap 로그는 보통 7일 이내 삭제. 보안 사고 대응 IP 로그는 최대 30일. Cloudflare·MapTiler 는 각 사 방침에 따름 |
| OpenStreetMap Foundation — Nominatim(또는 설정된 호환 지오코더) | 영국 | 검색어 또는 주소를 찾을 좌표, IP 주소 | 장소 검색·주소 찾기 | 각 사 방침에 따름 |
| Norwegian Meteorological Institute — MET Norway | 노르웨이 | 날씨를 볼 장소의 좌표, IP 주소 | 날씨 예보 | 각 사 방침에 따름 |
| 환율 데이터(currency-api: jsDelivr·Cloudflare, Frankfurter/유럽중앙은행 기준) | 미국·유럽 | IP 주소(개인정보 없음) | 환율 환산 | 각 사 방침에 따름 |

OpenMapTiles 는 기본 지도의 타일 스키마이며 앱 요청을 받는 서비스 제공자가 아닙니다. 지도에는 OpenMapTiles 와 OpenStreetMap 기여자 출처를 표시합니다. ([OpenMapTiles 출처 안내](https://openmaptiles.org/docs/))

- 국외 이전 시기·방법: 해당 기능을 쓸 때 암호화된 인터넷 통신(HTTPS)으로 전송합니다.
- 국외 이전을 원하지 않으면 로그인하지 않고(게스트) 쓰거나, 해당 기능을 쓰지 않거나, 설정에서 오류 보고를 끌 수 있습니다.
  이 경우 동기화·커뮤니티 등 일부 기능을 쓸 수 없습니다.
- 안드로이드 자동 백업을 켠 기기에서는 여행 기록과 앱 설정(사진 제외)이 이용자의 Google 계정 백업에 저장될 수 있습니다
  (기기 설정에서 관리).

### 4. 보유 기간과 파기

- 계정·여행 기록·커뮤니티 데이터: **계정 삭제 시 즉시 삭제**합니다. 서비스 장애 대비 백업에 남은 사본은
  보존 기간(최대 30일)이 지나면 자동으로 지워집니다.
- 로그아웃하면 이 기기에 저장된 계정 데이터를 지웁니다(클라우드의 데이터는 남아 다시 로그인하면 돌아옵니다).
- 계정을 삭제하면 이 기기에 있는 그 계정의 기록과 사진도 지웁니다.
- 오류 진단 정보: Crashlytics 에서 최대 90일 보관 후 삭제됩니다.
- 신고 기록: 검토·조치 후 분쟁 대응을 위해 최대 1년 보관 후 삭제합니다.
- 법령에 따라 보관해야 하는 경우(예: 전자상거래 거래 기록) 해당 기간 동안 분리 보관합니다. 결제 기록은 Google Play 가 보관합니다.
- 전자 파일은 복구할 수 없는 방법으로 지웁니다.

### 5. 이용자의 권리와 행사 방법

- **열람·수정**: 앱에서 언제든 기록을 보고 고칠 수 있습니다.
- **내보내기**: 내 정보 → 백업 및 복원에서 사진을 포함한 백업 파일(ZIP)을 만들 수 있습니다.
- **삭제**: 앱 → 내 정보 → **계정 삭제**. 앱을 쓸 수 없으면 [계정 삭제 안내](https://kayno4253.github.io/privacy/my-travel-map-delete-account.html)나
  kayno@naver.com 로 요청할 수 있습니다(본인 확인 후 처리).
- **처리 정지·동의 철회**: 로그아웃, 위치 권한 해제(기기 설정), 오류 보고 끄기(앱 설정), 공유 설정 끄기.
- 요청은 지체 없이(법정 기한 10일 이내) 처리합니다.

### 6. 위치 정보

- 위치 권한은 "앱 사용 중"만 요청합니다. 경로 기록 중에는 화면을 꺼도 기록이 이어지도록 **상시 알림이 있는
  포그라운드 서비스**를 쓰며, 이용자가 언제든 멈출 수 있습니다.
- 위치는 이용자가 저장한 장소·경로로만 남고, 날씨 조회(MET Norway)·주소 찾기(지오코더) 때 해당 좌표만 보냅니다.
- 다른 이용자에게 **실시간 현재 위치를 공유하지 않습니다**. 친구 공유를 켜면 친구로 추가한 사람에게 다녀온 장소가 보이고,
  피드에 글을 올리면 그 장소의 좌표가 약 1km 단위로 반올림되어 로그인한 이용자에게 보입니다.

### 7. 아동

앱은 만 14세 미만(미국 등은 13세 미만) 아동을 대상으로 하지 않으며, 알면서 아동의 개인정보를 수집하지 않습니다.
아동의 정보가 수집된 사실을 알게 되면 지체 없이 삭제합니다.

### 8. 안전성 확보 조치

- 모든 통신은 HTTPS(평문 통신 차단)로 합니다.
- 클라우드 데이터는 Firebase 보안 규칙으로 본인만 접근하도록 제한합니다(프로필·피드 글은 로그인한 이용자만, 공유한 장소는 친구만 볼 수 있음).
- 기기 데이터는 앱 전용 저장소에 두며, 로그아웃 시 지웁니다.
- 개인정보를 처리하는 사람을 최소화합니다.

### 9. 쿠키 등

앱은 쿠키나 광고 추적 기술을 쓰지 않습니다.

### 10. 개인정보 보호책임자

- 책임자: Herion
- 연락처: kayno@naver.com

개인정보 침해 상담: 개인정보침해신고센터(privacy.kisa.or.kr, 국번 없이 118), 개인정보분쟁조정위원회(www.kopico.go.kr, 1833-6972),
대검찰청(www.spo.go.kr, 1301), 경찰청(ecrm.police.go.kr, 182).

### 11. 변경

방침이 바뀌면 시행 7일 전(이용자에게 불리한 변경은 30일 전) 앱 또는 이 페이지에 알립니다.

---

<a id="english"></a>

## English

Herion ("we") operates My Travel Map (the "App"). This policy explains what the App processes,
why, who it is shared with, and how you can delete it or opt out.

### 1. Summary

- You can use all core features (places, trips, routes) **without signing in**; your records then stay **on your device only**.
- If you sign in with Google, your travel records are stored in Google Cloud Firestore to sync between devices.
- **Photos never leave your device** unless you share them or export a backup yourself.
- Precise location is used **only while the App is open** or **while you record a route** (with an ongoing notification).
- **No ads, no selling of personal data, no advertising ID.**

### 2. Data we process

| Category | Data | Purpose | When |
|---|---|---|---|
| Account | Google account name, email, profile photo URL, Firebase user ID | Sign-in, account separation, sync | When you sign in with Google |
| Travel records | Places (name, coordinates, country, region, visit date, notes, rating, cost, tags, category), routes (GPS points and times), trips, bookings, packing lists, expenses and member names, collections | Storage, sync between devices, statistics | Synced to Firestore when signed in (device only as a guest) |
| Photos | Photos you attach to places | Showing your records | **Stored on device only**, never uploaded |
| Location | Precise location (GPS) | Showing your position, adding a place at your location, recording a route you started | Only while using the App or while recording (ongoing notification). Background location permission is not requested |
| Public profile | Display name, profile photo URL, sharing setting | Showing you to friends and in the community | When you use social features. **Your email is never public** |
| Community | Feed posts (note, place name, country, emoji, visit date, coordinates rounded to about 1 km, your display name), likes, reports (reason), block list, friends, shared trips (name, member display names, places, expenses) | Community, friends and shared trips; reviewing reports | When you use these features. Feed posts contain no photos |
| Diagnostics | Crash stack traces, device model, OS and app version, memory/disk state, Crashlytics installation ID | Fixing bugs, stability | On by default in release builds; **can be turned off in Settings** |
| Purchases | Product, purchase token and state (from Google Play) | Granting and restoring Premium | When you buy. **We never receive card details** (handled by Google Play) |
| Device settings | Language, theme, units, base currency | Keeping your settings | Device only |

### 3. Third parties and international transfers

| Recipient | Country | Data | Purpose | Retention |
|---|---|---|---|---|
| Google LLC — Firebase Authentication, Cloud Firestore | USA and other Google data centers | Account data, travel records, community data | Sign-in, storage, sync (processor) | Until you delete your account |
| Google LLC — Firebase Crashlytics | USA | Diagnostics | Crash analysis (processor) | Up to 90 days |
| Google LLC — Google Sign-In, Google Play Billing | USA | Sign-in request, purchase data | Sign-in, payments | Per Google's policy |
| OpenFreeMap (Hyperknot Software Kft.; tile service using the OpenMapTiles schema and OpenStreetMap data; may be served via Cloudflare CDN), MapTiler AG (satellite map, Premium only) | Hungary, Switzerland, and CDN locations | Map area being viewed (tile requests), network metadata and IP address (see the [OpenFreeMap privacy policy](https://openfreemap.org/privacy/) for error/security logging) | Showing the map | OpenFreeMap logs are usually deleted within 7 days; IP logs for security incidents may be kept up to 30 days. Cloudflare and MapTiler follow their policies |
| OpenStreetMap Foundation — Nominatim (or a configured compatible geocoder) | UK | Search text or coordinates to look up, IP address | Place search and address lookup | Per provider |
| Norwegian Meteorological Institute — MET Norway | Norway | Coordinates of the place you check, IP address | Weather forecasts | Per provider |
| Exchange-rate data (currency-api via jsDelivr/Cloudflare; Frankfurter / European Central Bank data) | USA, EU | IP address only | Currency conversion | Per provider |

OpenMapTiles is the schema used by the default map tiles, not a service that receives app requests. The map credits OpenMapTiles and OpenStreetMap contributors ([OpenMapTiles attribution guidance](https://openmaptiles.org/docs/)).

Data is sent over encrypted connections (HTTPS) when you use the related feature. To avoid transfers, use the App as a guest,
skip the feature, or turn off crash reports — some features (sync, community) will then be unavailable.
If Android Auto Backup is on, your travel records and settings (not photos) may be stored in your own Google account backup.

### 4. Retention and deletion

- Account, travel records and community data are **deleted immediately when you delete your account**. Copies in disaster-recovery
  backups expire within 30 days.
- Signing out removes your account data from that device (cloud data remains and returns when you sign in again).
- Diagnostics are kept by Crashlytics for up to 90 days.
- Reports are kept for up to 1 year after review for dispute handling.
- Where the law requires retention, data is kept separately for that period. Payment records are kept by Google Play.

### 5. Your rights

- **Access and correct** your records in the App at any time.
- **Export**: Me → Backup & restore creates a ZIP backup including photos.
- **Delete**: App → Me → **Delete account**. If you cannot use the App, request deletion at the [account deletion page](https://kayno4253.github.io/privacy/my-travel-map-delete-account.html)
  or kayno@naver.com (we verify your identity first).
- **Withdraw consent**: sign out, revoke location permission (system settings), turn off crash reports, turn off sharing.
- Depending on where you live (e.g., EEA/UK GDPR, California CCPA/CPRA) you may also have rights to portability, restriction
  and objection, and to complain to your data protection authority. We do not sell or "share" personal information for
  cross-context behavioral advertising.

### 6. Location

The App requests "while in use" location only. While you record a route it uses a **foreground service with an ongoing notification**
so recording continues with the screen off; you can stop it at any time. Coordinates are sent only to MET Norway (weather) and
the geocoder (address lookup). The App **never shares your live location** with other users. If you enable sharing, people you added as friends can see
your visited places; if you post to the feed, that place's coordinates are rounded to about 1 km and visible to signed-in users.

### 7. Children

The App is not directed to children under 13 (under 14 in Korea), and we do not knowingly collect their data. If we learn that we have,
we delete it promptly.

### 8. Security

HTTPS only (cleartext traffic blocked); Firebase security rules restrict cloud data to its owner (profiles and feed posts are visible to signed-in users, shared places to friends only);
device data lives in app-private storage and is removed on sign-out.

### 9. Contact and changes

Privacy officer: Herion — kayno@naver.com.
We will announce changes in the App or on this page at least 7 days in advance (30 days for changes unfavorable to you).

</main>

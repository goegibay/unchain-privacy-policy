---
title: UNCHAIN Privacy Policy / 隱私權政策
---

# UNCHAIN 隱私權政策

最後更新日期：2026-10-22

本隱私權政策說明 UNCHAIN（以下稱「本應用程式」）如何收集、使用、儲存與保護您的資料。使用本應用程式即表示您同意本政策的內容。

## iOS 版隱私摘要

iOS 版 UNCHAIN 提供免費的每日行動、簽到與本機反思功能，並可選擇透過 Apple App Store 訂閱 Unchain Core。App 不含廣告、廣告追蹤或 ATT 請求；目前不提供帳號登入或雲端備份。您在 App 輸入的自評、每日行動、反思、私人筆記及照片保存在裝置上的 App 沙盒；本 App 不會主動將這些內容傳送給開發者或應用內第三方服務。您可在「我的 → 資料控制」匯出或清除本機資料。自行匯出、分享及 iOS 系統備份取決於您的操作與裝置設定。

訂閱由 Apple StoreKit 處理付款，RevenueCat 協助驗證購買紀錄與啟用訂閱權益。RevenueCat 會收集購買歷史，用於 App 功能（收據驗證、防詐與權益啟用）及訂閱分析（例如訂戶歷史與統計）。目前 App 使用 RevenueCat 產生的匿名識別碼，不把購買紀錄連結至姓名或電子郵件，也不將其用於跨 App 廣告追蹤。訂閱價格、試用資格與扣款資訊以 Apple 購買畫面為準；取消或管理訂閱可使用 Apple 帳號的訂閱設定。

| iOS 收集的資料 | 收集者與用途 | 身分連結／追蹤 |
| --- | --- | --- |
| 購買歷史 | RevenueCat；驗證收據、啟用訂閱權益及訂閱分析 | 使用匿名識別碼，不連結至可識別個人的身分；不用於廣告追蹤 |

本版本未配置 iOS 的 Supabase 帳號、雲端同步、廣告 SDK 或自家使用事件上傳。以下帳號、Supabase、AdMob、Google Play Billing、雲端備份與一般使用分析的敘述適用於 Android 版。若日後 iOS 的服務或資料處理方式改變，我們會更新本政策及 App Store 隱私標示。

## 1. Android 版收集的資料

Android versionCode 31（版本名稱 1.2.0 的無廣告版本）不包含或初始化 Google AdMob／UMP，不顯示橫幅廣告，也不提供 App 內廣告隱私選項。仍在使用或測試流通中的較早 Android 版本可能繼續依下述方式使用 UMP／AdMob，直到使用者更新至移除廣告的版本。

| 資料類型 | 說明 | 儲存位置 |
| --- | --- | --- |
| 帳號資訊（電子郵件、密碼） | 用於建立帳號、登入與身分驗證 | Supabase（第三方雲端服務），密碼經加密雜湊處理，本應用程式不會明文儲存或讀取您的密碼 |
| 挑戰／習慣資料（名稱、分類、開始時間、重置紀錄、感想、觸發因素等） | 用於提供核心的習慣追蹤與統計功能 | **預設僅儲存於您的裝置本機**（Room 資料庫）。僅在您登入並使用「雲端備份」功能時，才會上傳（見下列「雲端備份資料」） |
| 雲端備份資料（選用；含挑戰／習慣資料、守護者進度、XP、護盾與反思日誌內容） | 用於跨裝置備份與還原您的進度 | Supabase（第三方雲端服務），僅在您**主動點選備份或登入帳號**時上傳；以資料列層級權限（RLS）保護，僅您本人可存取 |
| 使用分析事件（例如：完成 Onboarding、購買 Premium 等操作紀錄） | 用於了解功能使用情況、改善產品體驗 | Supabase（與您的帳號 ID 關聯） |
| 廣告與裝置資料（僅限仍含廣告功能的較早 Android 版本；例如 IP 位址、廣告識別碼、同意狀態、App 互動與診斷資料） | 用於在取得適用的廣告同意後顯示與衡量 Google AdMob 橫幅廣告、分析及防詐；AdMob 可能由 IP 推估大概位置 | 由 Google User Messaging Platform（UMP）與 AdMob 收集與處理 |
| 購買歷史與 SDK 使用者識別資訊（例如 RevenueCat App User ID） | 驗證購買、啟用付費權益與購買分析 | Google Play 處理付款；RevenueCat 處理購買歷史及權益驗證所需資料 |
| V3 結構化進度（自評分數、週期／計畫、結構化活動與課程進度） | 登入後同步支援此功能的紀錄 | Supabase；依功能與紀錄類型同步，不包含 V3 自由文字或進度照片 |

Android versionCode 31 的 App 程式未呼叫 RevenueCat 的廣告裝置識別收集或歸因設定 API，也不會將 RevenueCat 的購買或 SDK 使用者識別資訊用於 App 內廣告。RevenueCat 仍會處理購買歷史、App User ID 與提供購買驗證、權益及相關安全作業所需的技術資料；後台整合與下游接收方另依實際配置揭露，其啟用或變更時，我們會更新本政策與商店揭露。這項版本說明不表示本應用程式或其服務完全不處理任何識別資訊。

您可選擇拍攝或匯入進度照片，並加入備註。照片及備註在本應用程式的私人本機空間處理與儲存；此功能不會自動將它們上傳至 UNCHAIN 的進度同步或雲端備份。拍攝與選圖透過正常系統權限或選取畫面進行，由您決定是否允許或選取。

在「資料控制」手動匯出資料時，匯出檔可能包含照片日期、相關資料與備註，即使您未選擇匯出影像本體。影像本體只有在您明確選擇要匯出的照片時才會加入；透過系統分享時，匯出檔會交給您選擇的接收程式。

本應用程式不要求 Android 位置權限，也不會直接收集您的精確位置、聯絡人或裝置上其他應用程式的資料。仍含廣告功能的較早 Android 版本中，Google AdMob 仍可能處理 IP 位址並推估大概位置，如上所述；這不適用於已移除 AdMob／UMP 的 Android versionCode 31。

## 2. Android 版資料如何被使用

- **帳號資訊**：用於登入驗證、密碼重設、以及識別您的使用分析資料與帳號設定。
- **挑戰／習慣資料**：在本機處理，用於計算連續天數、產生統計圖表與重置歷史。**不登入即可使用核心功能**，此時資料不會離開您的裝置。
- **舊版雲端備份資料（選用）**：在提供舊版備份功能的流程中，若您登入帳號並使用「雲端備份／還原」，本應用程式會將挑戰資料與遊戲化進度（含舊版反思日誌內容）上傳至 Supabase 供日後還原；首次登入時若雲端尚無備份，會自動備份一次。
- **V3 結構化進度同步**：在支援同步的 V3 功能中，登入帳號後，待同步的自評分數、週期／計畫、結構化活動與課程進度可傳送至 Supabase，用於保存與同步進度。這與舊版整份備份不同，V3 同步不包含自由文字、私人筆記或進度照片；並非每種模式或每筆新紀錄都支援同步。
- **使用分析事件**：用於彙整產品使用統計，協助我們了解哪些功能受歡迎、哪裡需要改善；帳號相關的舊版使用事件會與帳號 ID 關聯。
- **廣告與裝置資料**：Android versionCode 31 已移除 AdMob／UMP，不會載入或顯示 AdMob 廣告，也沒有 App 內「廣告隱私選項」。在仍含廣告功能的較早 Android 版本中，Google UMP 用於處理適用的同意要求，廣告請求受 Google SDK 的同意狀態控制；AdMob 可能處理 IP 位址、廣告識別碼、App 互動與診斷資料，以投放／衡量廣告、分析及防詐。使用較早版本時，未看到廣告不表示所有相關 SDK 都停止處理資料；提供「廣告隱私選項」的較早版本可從設定頁開啟。您也可使用裝置系統的廣告隱私設定。
- **購買與權益資料**：Google Play 處理 Android 付款，RevenueCat 處理購買歷史與 SDK 使用者識別資訊，用於驗證購買、啟用權益及購買分析。目前可選購 Unchain Core 月／年自動續訂方案；舊版已售出的 Premium 買斷權益依原購買內容保留。價格、期間與資格以付款畫面為準；管理或取消訂閱請使用 Google Play 的訂閱設定。

## 3. 第三方服務

本應用程式依平台使用以下第三方服務，這些服務有各自的隱私權政策：

**iOS：**

- **RevenueCat**（iOS 訂閱權益驗證與購買分析）：https://www.revenuecat.com/privacy/
- **Apple StoreKit／App Store**（iOS 訂閱付款）：https://www.apple.com/legal/privacy/

**Android：**

- **Supabase**（帳號驗證與雲端資料庫）：https://supabase.com/privacy
- **Google AdMob／Google UMP**（僅適用仍含廣告功能的較早 Android 版本）：https://policies.google.com/privacy
- **Google Play 帳單服務**（應用程式內購買與訂閱付款）：https://policies.google.com/privacy
- **RevenueCat**（Android 購買驗證、權益與購買分析）：https://www.revenuecat.com/privacy/

## 4. Android 版資料安全

- 帳號相關資料、雲端備份與支援的 V3 結構化同步資料透過加密連線（HTTPS/TLS）傳輸至 Supabase。
- 習慣／挑戰資料預設僅儲存在您的裝置本機儲存空間，並受作業系統的應用程式沙盒機制保護。
- 本應用程式已排除 Android 系統自動雲端備份與裝置轉移中的資料庫、偏好與檔案；這不影響上述帳號服務、舊版雲端備份、支援的 V3 同步與第三方 SDK 各自的資料處理。
- 雲端備份以資料列層級安全性（Row Level Security）保護，每位使用者僅能存取自己的備份。
- 我們不會將您的個人資料出售給第三方。

## 5. Android 版帳號與資料刪除

Android 版可從 App 內的帳號刪除入口提出刪除要求。在採用「資料控制」畫面的版本，請前往「我的 → 開啟資料控制 → 刪除帳號與資料」，點選「刪除帳號」並依畫面確認。不同版本的畫面名稱可能不同；若找不到入口或無法使用 App，請依下方「UNCHAIN 帳號與資料刪除頁」的指示提出要求。

帳號刪除流程會要求刪除 Supabase 帳號與相關遠端資料，並處理本機資料清除。遠端刪除是否完成，以流程回報的確認結果為準；若顯示尚待處理或失敗，不能視為遠端資料已刪除。單獨清除本機資料或解除安裝 App 不會刪除遠端帳號。

第三方購買與權益資料的刪除申請，請寄信至 stevenhuang42195@gmail.com。我們可能需要足以確認您本人與相關購買權益的資訊，例如帳號電子郵件或可取得的 App 使用者識別資訊；請勿提供密碼、驗證碼、金鑰或完整付款卡資料。App 內刪帳不代表 RevenueCat 或商店的所有紀錄都已自動清除；Google Play 交易紀錄、退款與訂閱管理仍由 Google 處理，刪帳或刪除資料也不會自動取消訂閱。

此操作**無法復原**。若您僅想登出但保留資料，請使用「登出」功能。

若您在刪除帳號功能無法使用的情況下，仍希望刪除您的資料，請使用 [UNCHAIN 帳號與資料刪除頁](https://gist.github.com/goegibay/a952c6c60166772833c22b40314c95b5) 的指示提出要求。

## 6. 兒童隱私

本應用程式並非針對 13 歲以下兒童設計，我們不會刻意收集兒童的個人資料。若您發現兒童在未經家長同意的情況下提供了個人資料，請與我們聯繫，我們將盡快移除相關資料。

## 7. 健康與安全聲明

UNCHAIN 是協助使用者記錄行為與自我反思的一般健康工具，**不是醫療裝置**，不提供診斷、治療、治癒或預防任何醫療狀況。App 內的內容不能取代專業醫療意見。如需醫療建議、診斷或治療，請諮詢合格醫療專業人員。

## 8. 政策變更

我們可能會不時更新本隱私權政策。若有重大變更，我們會透過應用程式內通知或更新本文件的「最後更新日期」告知您。

## 9. 聯絡我們

若您對本隱私權政策或您的資料有任何問題，請透過以下方式聯絡我們：

stevenhuang42195@gmail.com

---

# UNCHAIN Privacy Policy

Last updated: 2026-10-22

This Privacy Policy explains how UNCHAIN ("the App") collects, uses, stores, and protects your data. By using the App, you agree to this policy.

## iOS Privacy Summary

The iOS version of UNCHAIN offers free daily actions, check-ins and on-device reflection. An optional Unchain Core subscription is available through Apple's App Store. The app has no ads, advertising tracking or App Tracking Transparency prompt. It currently has no account sign-in or cloud backup. Your self-assessments, daily actions, reflections, private notes and photos stay in the app's on-device sandbox. The app does not proactively transmit that content to the developer or in-app third-party services. You can export or erase local data in Profile > Data controls. Sharing, exports and iOS system backups depend on your actions and device settings.

Apple StoreKit handles subscription payments. RevenueCat verifies purchase history and enables subscription access. RevenueCat collects purchase history for app functionality (receipt validation, fraud prevention and entitlements) and subscription analytics (such as customer history and aggregate charts). The app currently uses a RevenueCat-generated anonymous identifier. Purchase history is not linked to your name or email address and is not used to track you across apps for advertising. Subscription prices, trial eligibility and billing details appear in Apple's purchase flow; you can manage or cancel through your Apple account's subscription settings.

| Data collected by the iOS app | Collector and purpose | Identity link / tracking |
| --- | --- | --- |
| Purchase history | RevenueCat; receipt validation, subscription access and subscription analytics | Anonymous identifier, not linked to an identifiable person; not used for advertising tracking |

This iOS version does not configure Supabase accounts, cloud sync, advertising SDKs or uploads of first-party usage events. The account, Supabase, AdMob, Google Play Billing, cloud-backup and general usage analytics descriptions below apply to the Android version. We will update this policy and the App Store privacy disclosure if the iOS app's services or data practices change.

## 1. Data Collected by the Android App

Android versionCode 31 (the ad-free version named 1.2.0) does not include or initialize Google AdMob or UMP, display banner ads, or provide an in-app Ad privacy options entry. Earlier Android versions that remain installed or available to testers may continue to use UMP and AdMob as described below until users update to the ad-free version.

| Data type | Purpose | Where it's stored |
| --- | --- | --- |
| Account info (email, password) | Account creation, login, authentication | Supabase (third-party cloud service); passwords are hashed and never stored or read in plain text by the App |
| Challenge/habit data (name, category, start time, reset records, reflections, triggers) | Core habit-tracking and statistics features | **Stored on your device by default** (local Room database); only uploaded if you sign in and use Cloud Backup (see next row) |
| Cloud backup data (optional; includes challenge/habit data, guardian progress, XP, shields, and reflection journal content) | Backing up and restoring your progress across devices | Supabase (third-party cloud service); uploaded only when you **actively back up or sign in**; protected by row-level security so only you can access it |
| Analytics events (e.g. onboarding completed, Premium purchased) | Understand feature usage and improve the product | Supabase (linked to your account ID) |
| Advertising and device data (only in earlier Android versions that still include ads; such as IP address, advertising ID, consent state, app interactions, and diagnostics) | Showing and measuring Google AdMob banner ads after applicable consent, analytics, and fraud prevention; AdMob may infer approximate location from IP | Collected and processed by Google User Messaging Platform (UMP) and AdMob |
| Purchase history and SDK user identifiers (such as a RevenueCat App User ID) | Purchase validation, paid access and purchase analytics | Google Play handles payment; RevenueCat processes purchase history and data needed for entitlement verification |
| V3 structured progress (assessment scores, cycles/plans, structured activities and lesson progress) | Syncing supported records after sign-in | Supabase; sync depends on the feature and record type and excludes V3 free text and progress photos |

The Android versionCode 31 app code does not call RevenueCat APIs that collect advertising device identifiers or configure attribution, and it does not use RevenueCat purchase or SDK user identifiers for in-app advertising. RevenueCat still processes purchase history, an App User ID, and technical data needed for purchase validation, entitlements, and related security operations. Dashboard integrations and downstream recipients are disclosed according to their actual configuration; if they are enabled or changed, we will update this policy and the store disclosure. This version note does not claim that the App or its services process no identifiers at all.

You may choose to take or import progress photos and add notes. Photos and notes are processed and stored in the App’s private on-device storage; this feature does not automatically upload them to UNCHAIN progress syncing or cloud backup. Taking or selecting photos uses the normal system permission or selection screens, where you decide what to allow or select.

When you manually export data in Data Controls, the export may include photo dates, related information and notes, even if you do not choose to export the image files. Image files are included only when you explicitly select photos for export. When you use system sharing, the export is passed to the receiving app you choose.

The App does not request Android location permission or directly collect your precise location, contacts, or data from other apps on your device. In earlier Android versions that still include ads, Google AdMob may process IP addresses and infer approximate location as described above; this does not apply to Android versionCode 31, which removes AdMob and UMP.

## 2. How the Android App Uses Data

- **Account info**: login authentication, password resets, and linking analytics/settings to your account.
- **Challenge/habit data**: processed on-device to compute streaks, charts, and reset history. **Core features work without signing in**, in which case this data never leaves your device.
- **Legacy cloud backup data (optional)**: in flows that offer legacy backup, signing in and using Cloud Backup/Restore uploads challenge data and gamification progress (including legacy reflection journals) to Supabase for later restore. On first sign-in, if no cloud backup exists, one backup is created automatically.
- **V3 structured progress sync**: in V3 features that support sync, pending assessment scores, cycles/plans, structured activities and lesson progress may be sent to Supabase after sign-in to save and sync progress. This is separate from legacy full backups. V3 sync excludes free text, private notes and progress photos; not every mode or new record supports sync.
- **Analytics events**: product usage statistics to understand which features are popular and where improvements are needed. Account-related legacy usage events are linked to the account ID.
- **Advertising and device data**: Android versionCode 31 removes AdMob and UMP, does not load or display AdMob ads, and has no in-app “Ad privacy options” entry. In earlier Android versions that still include ads, Google UMP handles applicable consent requirements and ad requests are controlled by the Google SDK’s consent state. AdMob may process IP addresses, advertising IDs, app interactions and diagnostics for ad delivery/measurement, analytics and fraud prevention. In those earlier versions, not seeing an ad does not mean every related SDK stops processing data; versions offering “Ad privacy options” provide them in Settings. You can also use the device’s advertising privacy settings.
- **Purchase and access data**: Google Play handles Android payments. RevenueCat processes purchase history and SDK user identifiers for purchase validation, access and purchase analytics. Optional Unchain Core monthly/yearly auto-renewing plans are available; previously sold Premium lifetime access is retained according to the original purchase. Prices, periods and eligibility appear in the purchase flow. Manage or cancel subscriptions in Google Play’s subscription settings.

## 3. Third-Party Services

**iOS:**

- **RevenueCat** (iOS subscription entitlement verification and purchase analytics): https://www.revenuecat.com/privacy/
- **Apple StoreKit / App Store** (iOS subscription payment): https://www.apple.com/legal/privacy/

**Android:**

- **Supabase** (authentication & database): https://supabase.com/privacy
- **Google AdMob / Google UMP** (only in earlier Android versions that still include ads): https://policies.google.com/privacy
- **Google Play Billing** (in-app purchases and subscription payments): https://policies.google.com/privacy
- **RevenueCat** (Android purchase validation, access and purchase analytics): https://www.revenuecat.com/privacy/

## 4. Android Data Security

- Account-related data, cloud backups and supported V3 structured sync data are transmitted to Supabase over encrypted connections (HTTPS/TLS).
- Challenge/habit data is stored in your device's local app storage by default, protected by the OS app sandbox.
- The App excludes its databases, preferences and files from Android automatic cloud backup and device transfer. This does not prevent the separate data processing described above for account services, legacy cloud backup, supported V3 sync or third-party SDKs.
- Cloud backups are protected by row-level security: each user can only access their own backup.
- We do not sell your personal data to third parties.

## 5. Android Account and Data Deletion

On Android, you can request deletion through the App’s account deletion flow. In versions with the “Data controls” screen, go to Profile > Open data controls > Delete account and data, select “Delete account”, and follow the on-screen confirmation. Screen names may differ by version. If you cannot find the option or use the App, follow the instructions on the “UNCHAIN account and data deletion page” linked below.

The account deletion flow requests deletion of your Supabase account and associated remote data, and handles local data erasure. Remote deletion is complete only when the flow reports a confirmed result. A pending or failed result does not mean the remote data has been deleted. Erasing local data alone or uninstalling the App does not delete your remote account.

To request deletion of third-party purchase and access data, email stevenhuang42195@gmail.com. We may need enough information to confirm your identity and the relevant purchase access, such as your account email or an App user identifier if available. Do not send passwords, verification codes, keys or complete payment card details. Deleting an account in the App does not mean that all RevenueCat or store records have been automatically erased. Google handles Google Play transaction records, refunds and subscription management; account or data deletion does not automatically cancel a subscription.

This action **cannot be undone**. If you only want to sign out while keeping your data, use "Log Out" instead.

If you need to delete your data outside the App, follow the instructions on the [UNCHAIN Account and Data Deletion page](https://gist.github.com/goegibay/a952c6c60166772833c22b40314c95b5).

## 6. Children's Privacy

The App is not directed at children under 13, and we do not knowingly collect personal data from children. If you believe a child has provided personal data without parental consent, please contact us and we will remove it promptly.

## 7. Health & Safety Disclaimer

UNCHAIN is a general wellness tool for behavior tracking and self-reflection. It is **not a medical device** and does not diagnose, treat, cure, or prevent any medical condition. Content in the App is not a substitute for professional medical advice. Consult a qualified healthcare professional for medical advice, diagnosis, or treatment.

## 8. Changes to This Policy

We may update this Privacy Policy from time to time. Material changes will be communicated via an in-app notice or by updating the "Last updated" date above.

## 9. Contact Us

If you have any questions about this Privacy Policy or your data, please contact us at:

stevenhuang42195@gmail.com

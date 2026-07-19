---
title: UNCHAIN Privacy Policy / 隱私權政策
---

# UNCHAIN 隱私權政策

最後更新日期：2026-07-19

本隱私權政策說明 UNCHAIN（以下稱「本應用程式」）如何收集、使用、儲存與保護您的資料。使用本應用程式即表示您同意本政策的內容。

## 1. 我們收集的資料

| 資料類型 | 說明 | 儲存位置 |
| --- | --- | --- |
| 帳號資訊（電子郵件、密碼） | 用於建立帳號、登入與身分驗證 | Supabase（第三方雲端服務），密碼經加密雜湊處理，本應用程式不會明文儲存或讀取您的密碼 |
| 挑戰／習慣資料（名稱、分類、開始時間、重置紀錄、感想、觸發因素等） | 用於提供核心的習慣追蹤與統計功能 | **預設僅儲存於您的裝置本機**（Room 資料庫）。僅在您登入並使用「雲端備份」功能時，才會上傳（見下列「雲端備份資料」） |
| 雲端備份資料（選用；含挑戰／習慣資料、守護者進度、XP、護盾與反思日誌內容） | 用於跨裝置備份與還原您的進度 | Supabase（第三方雲端服務），僅在您**主動點選備份或登入帳號**時上傳；以資料列層級權限（RLS）保護，僅您本人可存取 |
| 使用分析事件（例如：完成 Onboarding、購買 Premium 等操作紀錄） | 用於了解功能使用情況、改善產品體驗 | Supabase（與您的帳號 ID 關聯） |
| 廣告與裝置資料（例如 IP 位址、廣告識別碼、同意狀態、App 互動與診斷資料） | 用於在取得適用的廣告同意後顯示與衡量 Google AdMob 橫幅廣告、分析及防詐；AdMob 可能由 IP 推估大概位置 | 由 Google User Messaging Platform（UMP）與 AdMob 收集與處理 |
| 購買紀錄（Premium 解鎖） | 用於驗證與啟用付費功能 | 由 Google Play 帳單服務處理 |

本應用程式不要求 Android 位置權限，也不會直接收集您的精確位置、聯絡人、相機／相簿內容或裝置上其他應用程式的資料。Google AdMob 仍可能處理 IP 位址並推估大概位置，如上所述。

## 2. 資料如何被使用

- **帳號資訊**：用於登入驗證、密碼重設、以及識別您的使用分析資料與帳號設定。
- **挑戰／習慣資料**：在本機處理，用於計算連續天數、產生統計圖表與重置歷史。**不登入即可使用核心功能**，此時資料不會離開您的裝置。
- **雲端備份資料（選用）**：若您登入帳號並使用「雲端備份／還原」，本應用程式會將您的挑戰資料與遊戲化進度（含反思日誌內容）上傳至 Supabase 供日後還原；首次登入時若雲端尚無備份，會自動上傳一次以保護您的進度。備份僅供您本人透過本應用程式存取，我們不會用於其他用途。
- **使用分析事件**：用於彙整匿名化的產品使用統計，協助我們了解哪些功能受歡迎、哪裡需要改善。
- **廣告與裝置資料**：本應用程式每次啟動會透過 Google UMP 更新您的同意狀態；只有 Google SDK 回報可請求廣告時才會初始化 AdMob 與載入橫幅廣告。AdMob 可能處理 IP 位址、廣告識別碼、App 互動與診斷資料，以投放／衡量廣告、分析及防詐。若所在地區要求，您可在設定頁重新開啟「廣告隱私選項」。您也可以在裝置系統設定中重設或限制廣告追蹤。
- **購買紀錄**：用於確認您已付費並為您解鎖 Premium 功能（移除廣告、解鎖小工具與專屬樣式）。

## 3. 第三方服務

本應用程式使用以下第三方服務，這些服務有各自的隱私權政策：

- **Supabase**（帳號驗證與雲端資料庫）：https://supabase.com/privacy
- **Google AdMob**（廣告服務）：https://policies.google.com/privacy
- **Google Play 帳單服務**（應用程式內購買）：https://policies.google.com/privacy

## 4. 資料安全

- 帳號相關資料與雲端備份透過加密連線（HTTPS/TLS）傳輸至 Supabase。
- 習慣／挑戰資料預設僅儲存在您的裝置本機儲存空間，並受作業系統的應用程式沙盒機制保護。
- 本應用程式已排除 Android 系統自動雲端備份與裝置轉移中的資料庫、偏好與檔案；資料只有在您登入後使用 UNCHAIN 雲端備份時才會上傳。
- 雲端備份以資料列層級安全性（Row Level Security）保護，每位使用者僅能存取自己的備份。
- 我們不會將您的個人資料出售給第三方。

## 5. 帳號與資料刪除

您可以隨時在本應用程式中刪除您的帳號：

**設定（我的） > 帳號 > 刪除帳號**

刪除帳號將會：

1. 永久刪除您在 Supabase 的帳號（包含登入資訊、使用分析紀錄與**雲端備份**）；
2. 清除您裝置本機儲存的所有挑戰、重置紀錄、守護者進度（XP、護盾、反思日誌）與個人化設定。

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

Last updated: 2026-07-19

This Privacy Policy explains how UNCHAIN ("the App") collects, uses, stores, and protects your data. By using the App, you agree to this policy.

## 1. Data We Collect

| Data type | Purpose | Where it's stored |
| --- | --- | --- |
| Account info (email, password) | Account creation, login, authentication | Supabase (third-party cloud service); passwords are hashed and never stored or read in plain text by the App |
| Challenge/habit data (name, category, start time, reset records, reflections, triggers) | Core habit-tracking and statistics features | **Stored on your device by default** (local Room database); only uploaded if you sign in and use Cloud Backup (see next row) |
| Cloud backup data (optional; includes challenge/habit data, guardian progress, XP, shields, and reflection journal content) | Backing up and restoring your progress across devices | Supabase (third-party cloud service); uploaded only when you **actively back up or sign in**; protected by row-level security so only you can access it |
| Analytics events (e.g. onboarding completed, Premium purchased) | Understand feature usage and improve the product | Supabase (linked to your account ID) |
| Advertising and device data (such as IP address, advertising ID, consent state, app interactions, and diagnostics) | Showing and measuring Google AdMob banner ads after applicable consent, analytics, and fraud prevention; AdMob may infer approximate location from IP | Collected and processed by Google User Messaging Platform (UMP) and AdMob |
| Purchase records (Premium unlock) | Validating and unlocking paid features | Processed by Google Play Billing |

The App does not request Android location permission or directly collect your precise location, contacts, camera/photo library content, or data from other apps on your device. Google AdMob may still process IP addresses and infer approximate location as described above.

## 2. How We Use Your Data

- **Account info**: login authentication, password resets, and linking analytics/settings to your account.
- **Challenge/habit data**: processed on-device to compute streaks, charts, and reset history. **Core features work without signing in**, in which case this data never leaves your device.
- **Cloud backup data (optional)**: if you sign in and use Cloud Backup/Restore, the App uploads your challenge data and gamification progress (including reflection journal content) to Supabase for later restore; on first sign-in, if no cloud backup exists yet, one is uploaded automatically to protect your progress. Backups are accessible only to you through the App and are not used for any other purpose.
- **Analytics events**: aggregated usage statistics to understand which features are popular and where improvements are needed.
- **Advertising and device data**: the App refreshes your consent status through Google UMP on every launch. AdMob is initialized and banner ads are requested only when Google's SDK reports that ads may be requested. AdMob may process IP addresses, advertising IDs, app interactions, and diagnostics for ad delivery/measurement, analytics, and fraud prevention. Where required, you can reopen “Ad privacy options” from Settings. You can also reset or limit ad tracking in system settings.
- **Purchase records**: confirming payment and unlocking Premium features (ad removal, home-screen widgets, exclusive app icon).

## 3. Third-Party Services

- **Supabase** (authentication & database): https://supabase.com/privacy
- **Google AdMob** (advertising): https://policies.google.com/privacy
- **Google Play Billing** (in-app purchases): https://policies.google.com/privacy

## 4. Data Security

- Account-related data and cloud backups are transmitted to Supabase over encrypted connections (HTTPS/TLS).
- Challenge/habit data is stored in your device's local app storage by default, protected by the OS app sandbox.
- The App excludes its databases, preferences, and files from Android automatic cloud backup and device transfer. Data is uploaded only through UNCHAIN Cloud Backup after you sign in.
- Cloud backups are protected by row-level security: each user can only access their own backup.
- We do not sell your personal data to third parties.

## 5. Account & Data Deletion

You can delete your account at any time from within the App:

**Settings (Profile) > Account > Delete Account**

Deleting your account will:

1. Permanently delete your Supabase account (login info, analytics records, and **cloud backups**);
2. Erase all locally stored challenges, reset history, guardian progress (XP, shields, reflection journal), and personal settings on your device.

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

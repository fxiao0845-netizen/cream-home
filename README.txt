奶油小窩 PWA 原型（第二版）

內容：
- index.html：互動考題 App
- manifest.webmanifest：可安裝到主畫面的設定
- sw.js：簡易離線快取

重要限制：
1. 這不是 APK，也不會自動建立 Android 系統鬧鐘。
2. 網頁/PWA 不能可靠地在被關閉或受系統省電限制時準時響鈴，也不能禁止關閉系統鬧鐘。
3. 安裝 PWA 通常需要把這些檔案放到支援 HTTPS 的網站。直接從 ZIP 或 file:// 開啟時，安裝與離線功能可能無法啟用。
4. 若要真正的背景鬧鐘，下一階段應建立原生 Android 專案，使用 Android AlarmManager / 通知與適當權限；不同 Android 版本有精確鬧鐘與電池限制。

快速預覽：
解壓縮後直接用瀏覽器開 index.html 即可試玩主要答題功能。


# AntiPlato: Installation & Setup Guide

Welcome to AntiPlato! Because this is a powerful, standalone screen-reading utility, Android's automated security will initially try to block it. This is standard for custom tools not downloaded from the Play Store. 

Here is how to get set up safely in about three minutes.

## Part 1: Installation 
1. Download the AntiPlato APK and tap the file to install it.
2. If you see a **"Blocked by Play Protect"** warning or simply "**App not installed**", close the installation screen.
3. Open your **Google Play Store** app.
4. Tap your profile picture in the top right corner and select **Play Protect**.
5. Tap the gear icon (top right) and turn off **Scan apps with Play Protect**.
6. Go back to your downloaded file and install the AntiPlato APK. 
7. **Important:** Once the installation finishes, return to the Play Store and turn Play Protect back **ON**. 
8. If a prompt appears asking to "Send unknown app to Google," click **Don't Send**.

## Part 2: Setup & Permissions
Open AntiPlato and tap **Global Settings** (the button at the bottom). 

To function as a game helper, AntiPlato needs three specific Android permissions. Here is exactly what they do and why we need them:

* **Notifications:** This simply keeps the app "alive" in the background so Android doesn't forcefully close it while you are playing your game.
* **Display Over Other Apps:** This allows AntiPlato to draw its floating menu and buttons on top of your game screen. *(Note: Android heavily restricts this setting. If it is greyed out, you may need to click "Allow restricted settings" or "Allow anyways" in your phone's app info menu).*
* **Accessibility:** This is the core engine. It allows AntiPlato to automatically execute the swiping motions on the grid for you.

## Part 3: Using AntiPlato
1. Once your settings are in place, AntiPlato will ask for **Screen Record** permission. This is strictly required to take a snapshot of the game grid so the app can read the letters (OCR). It does not record video or save anything to your phone.
2. Open your game. Tap the **Bound** button on the far right corner of the floating overlay.
3. Adjust the red box so it perfectly frames your game grid.
4. Tap the **OCR** button to scan the letters.
5. **The Training Phase:** During your first few games, the scan might result in a `?` instead of a letter. This is completely normal. The app's model learns from what you teach it. If it misidentifies a letter, tap **Edit** to correct the mistake. 
6. Once the grid letters are correct, hit **Auto Swipe** to let the app solve the board. 

Once it gathers enough data from your corrections, the OCR will work flawlessly!

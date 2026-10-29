# BarReady — Bar Exam Study Tracker

A responsive, personal study-tracking website for your Nepal Bar Exam preparation.

## Included features
- Countdown to the first exam day: **12 December 2026** (the exam dates are set in `app.js`).
- Pomodoro timer presets: 25 minutes, 50 minutes, and custom duration.
- Study stopwatch for open-ended sessions.
- Time is credited to the selected subject when you pause, reset, or finish a timer — you do not need to complete a Pomodoro.
- Daily totals automatically combine Pomodoro and stopwatch study time.
- Weekly and 7/14/30-day bar charts, daily averages, best study day, all-time total, and session history.
- Editable, addable, and removable subjects.
- Rotating motivational/legal quotes.
- Local browser storage and JSON export. No account or server is needed.

## Put it online with GitHub Pages
1. Download and unzip `barready-study-tracker.zip`.
2. Open your GitHub repository.
3. Upload **`index.html`**, **`style.css`**, and **`app.js`** into the repository's root (not inside an extra folder).
4. Commit the changes.
5. In the repository, open **Settings → Pages**. Choose deployment from the `main` branch and `/ (root)` if it is not already enabled.
6. Open the GitHub Pages URL when deployment finishes.

## Important notes
- Study records are saved in the browser's local storage on the device/browser where you use the site. They do not automatically sync between devices or different browsers.
- Export your data from the **Subjects** page occasionally as a backup.
- The countdown is configured for December 12, 2026. To change the date later, edit `EXAM_DATE` near the top of `app.js`.
- Motivational quotes are included as short attributions; one is marked “commonly attributed” where attribution is uncertain.

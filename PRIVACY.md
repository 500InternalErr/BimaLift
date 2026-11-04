# Privacy Policy — BimaLift

**Last updated:** 2026-11-04
**Developer:** Agus Wibawantara
**Contact:** me@guswei.my.id

BimaLift ("the app") is an offline workout tracker for personal use. This policy explains what data the app handles, where it is stored, and when data leaves your device.

## 1. Summary

- Your workout data is stored **on your device**, in the app's private database.
- The app has **no analytics, no advertising, and no crash reporting** from the developer, and no developer-run accounts. Sign-in happens only through Google or Huawei, and only when you choose a feature that needs it.
- Data leaves your device only in these cases, which you control: (a) you choose to back up to Google Drive, (b) you connect Huawei Health, which lets the app read your heart rate and calories through Huawei's services, and (c) the app loads exercise images and videos from third-party web servers.
- With Huawei Health connected, the app **reads** heart rate and calories burned. It **never writes** to Huawei Health. Heart rate and calorie readings are shown on screen during a workout and are **not saved** to the app's database or sent to the developer.

## 2. Data the app stores on your device

The app stores the following in its local database:

- Workout categories, exercises (including custom exercises you create), and workout templates (sets, reps, weight, notes).
- Your rotation order and progress.
- Completed workout sessions, including timings, sets, reps, and weights.

Images you add to a custom exercise (chosen from your gallery or taken with your camera) are copied into the app's private storage on your device.

This data is used only to show your workouts, history, and progress charts inside the app. It is not shared with the developer or any third party, except as described in Sections 3 and 4.

## 3. Optional Google Drive backup

You can back up and restore your data using your Google Drive account. This is entirely optional and happens only when you start it.

- **Sign-in:** Uses Google Sign-In. The app receives your Google account email address so it can show which account is connected.
- **Permission requested:** The `drive.file` scope. This lets the app access only files it creates itself. It cannot see or modify your other Drive files.
- **What is uploaded:** A JSON export of your workout database, saved in a folder named **"BimaLift Backups"** in your Drive.
- **Restore:** The app downloads a backup file you select and replaces the data on your device with its contents.
- **Who handles it:** Google processes these files under [Google's Privacy Policy](https://policies.google.com/privacy). The developer does not receive your backups.
- **Control:** You can delete backup files at any time from Google Drive. You can also revoke the app's access in your Google Account settings (Security → Third-party access).

## 4. Third-party content and services

**Huawei Health (optional).** If you connect Huawei Health, the app asks for two read-only permissions: **heart rate** and **calories burned**.

- The app reads the latest heart rate and today's calorie total from your Huawei Health data on this device, and shows them during an active workout.
- The app does not save these readings and does not send them to the developer.
- Huawei's Health Kit SDK communicates with Huawei's services as part of the connection. Huawei processes that data under its own privacy policy. The developer has no control over that processing.
- You can revoke access at any time in the Huawei Health app or in your Huawei ID settings. Without access, the watch readings simply do not appear.

**Exercise images and videos.** Some built-in exercises link to images and videos hosted on these servers:

- `pump-app.s3.eu-west-2.amazonaws.com` (Amazon Web Services)
- `raw.githubusercontent.com` (GitHub)

When these images are displayed, your device connects to those servers. As with any web request, those servers can see your IP address and the time of the request. The developer does not control these servers and does not receive this information.

Exercise video links open in your browser or video app. The app only opens `http` and `https` links.

**Fonts.** The app uses the Inter typeface through the Google Fonts service. On first use, it may download font files from Google. This is a standard request to Google's servers.

## 5. Permissions

| Permission | Why it is used |
|---|---|
| Camera | To take a photo for a custom exercise. |
| Photos / media (`READ_MEDIA_IMAGES`, or `READ_EXTERNAL_STORAGE` on Android 12 and older) | To pick an existing photo for a custom exercise. |
| Internet | Google Drive backup (optional), Huawei Health (optional), and loading exercise images and videos. |
| Huawei Health Kit: heart rate (read) | To show your current heart rate during a workout (optional). |
| Huawei Health Kit: calories burned (read) | To show calories burned during a workout (optional). |

The app asks for camera and photo access only when you use the feature that needs it. Huawei Health access is requested only when you connect the watch.

## 6. Data retention and deletion

- Your workout data stays on your device until you delete it in the app or uninstall the app. Uninstalling removes the local database and copied images.
- Backups stay in your Google Drive until you delete them there.
- The developer holds no copy of your data, so there is nothing to request from the developer. To remove data, use the in-app controls, uninstall the app, or delete the Drive backups.

## 7. Children

The app is not designed for children under 13 and does not knowingly collect data from them. Because the app stores data only on the device, no data is sent to the developer.

## 8. Health information

BimaLift is a workout log. It is not a medical device and does not provide medical advice. Workout data you enter is treated as personal information under this policy. Heart rate values read from Huawei Health are health information. They are displayed only during a session and are not stored by the app.

## 9. Changes to this policy

If this policy changes, the updated version will be published in this repository with a new "Last updated" date. Continued use of the app after a change means you accept the updated policy.

## 10. Contact

For questions about this policy, contact: **me@guswei.my.id**

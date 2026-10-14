# mounsokdara's F-Droid Repository

Personal F-Droid repository for **Video Player** and future apps.

## How to add this repository on your phone

1. Install the [F-Droid app](https://f-droid.org/).
2. Open this link on your Android phone:

**https://raw.githubusercontent.com/mounsokdara/fdroid/main/fdroid/repo**

3. Tap **Add to F-Droid** → **I have F-Droid** → **OK**.

After the first successful run of the workflow, the repository will contain the app and a fingerprint will be available.

## Apps included

| App | Description |
|-----|-------------|
| **Video Player** | Local-only Material 3 Android player using libmpv. Files stay on the device. |

## How updates work

- Every day the workflow checks for a new APK from [video-player](https://github.com/mounsokdara/video-player) releases.
- You can also trigger it manually: go to the **Actions** tab → **Generate F-Droid repo** → **Run workflow**.
- When a new APK is found, the F-Droid index is updated automatically.

## For the owner

Just keep publishing new releases (with an `.apk` file) in the video-player repository. The F-Droid repo will pick them up automatically.

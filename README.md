# Sarvatobhadra Vedic Transit Android APK

## GitHub upload structure

Upload the **contents of this folder** to the repository ROOT. Do not put this whole folder inside another folder.

Required paths at repository root:

- `build.gradle`
- `settings.gradle`
- `app/build.gradle`
- `app/src/main/AndroidManifest.xml`
- `app/src/main/java/.../MainActivity.java`
- `app/src/main/assets/index.html`
- `.github/workflows/android.yml`

**Important:** `app/build.gradle` must be directly inside `app/`, NOT inside `app/src/main/`.

## GitHub Actions

Open **Actions → Build Android APK** and run it. The run should show:

1. Verify project files
2. Verify Android tasks
3. Build debug APK
4. Upload APK

If the first two steps do not appear, the new workflow file has not been committed or the old workflow is being run.

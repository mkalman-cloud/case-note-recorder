
# Case‑Note Recorder (iPhone-friendly web app)

One‑file web app to record sessions and generate case notes in your preferred format.

## Quick Start (GitHub Pages)
1. Create a **new GitHub repo** (public or private with Pages enabled). Suggested name: `case-note-recorder`.
2. Upload the files from this folder: **index.html** and **.nojekyll** (and this README if you like).
3. Go to **Settings → Pages**:
   - **Source**: `Deploy from a branch`
   - **Branch**: choose the branch with your files (usually `main`) and set the folder to `/root`
   - Click **Save**. Wait for the green “Your site is live” message.
4. Open the Pages URL (like `https://<your-username>.github.io/case-note-recorder/`) in **Safari** on iPhone.
5. Tap **Share** → **Add to Home Screen**.

## Notes
- iOS prevents mic capture when the screen is locked or you leave Safari/PWA. Keep the screen awake while recording.
- Optional: in **Settings → Display & Brightness → Auto‑Lock**, pick **Never** during sessions (or use Guided Access).
- Voice commands use the browser’s speech recognition and may vary by iOS version.

## Customising
- The case‑note template is in `index.html` inside the `noteForm` submit handler.
- You can change labels/placeholders or add extra fields as needed.

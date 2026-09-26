# Black Flag Physique
A no-build, mobile-first bodybuilding coaching PWA inspired by the workflow of modern trainer platforms.

## Deploy on GitHub Pages
1. Create a new GitHub repository.
2. Upload every file in this folder to the repository root.
3. Open Settings → Pages.
4. Set Source to **Deploy from a branch**, branch **main**, folder **/(root)**.
5. Open the published URL on iPhone/Android and use **Add to Home Screen**.

## Included
- Coach dashboard and roster
- Client profiles/check-in status/habit adherence
- Program builder
- Client workout logging with volume calculation
- Bodyweight/waist/body-fat progress history
- Local device persistence
- JSON backup/export and import
- Installable/offline PWA shell

## Important architecture note
This is a static/local-first MVP. For real multi-user coaching, add a hosted database/auth layer (e.g. Supabase/Firebase), cloud media storage, secure messaging, and payment processing. Do not store sensitive medical information in this local demo.

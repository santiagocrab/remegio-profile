# James Remegio's Profile (Unit 8)

CC 207B Unit 8 exercise — James Remegio, BSIT 3-A.

Live site (GitHub Pages): https://santiagocrab.github.io/remegio-profile/

## Local run

```bash
cp cms.example.json cms.json   # then fill in your values
flutter pub get
flutter run --dart-define-from-file=cms.json
```

## Deploy

GitHub Actions builds and deploys on every push to `main`. Configure repository Variables (`CMS`, `CMS_URL`, `CMS_SPACE`) and Secrets (`OMDB_KEY`, `CMS_TOKEN`) first. Pages source must be **GitHub Actions**.

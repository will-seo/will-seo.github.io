# will-seo.github.io

The web page behind World Quizzer's daily-quiz share links (`https://will-seo.github.io/daily/?n=<quiz number>`).

- `.well-known/apple-app-site-association` tells iPhones that `/daily` links belong to the World Quizzer app
  (team K9P44ALFC9, bundle ID `com.williambarnespersonalteam.MapQuizTest`), so they open the app's daily quiz.
- `daily/index.html` is what anyone without the app sees: an App Store button on iPhone, and a note on Android
  that the app is iPhone-only.
- `.nojekyll` makes GitHub Pages serve the `.well-known` folder.

The privacy policy is a separate site: https://will-seo.github.io/world-quizzer-privacy/

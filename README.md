# will-seo.github.io

The web page behind World Quizzer's daily-quiz share links (`https://will-seo.github.io/daily/?n=<quiz number>`).

- `.well-known/apple-app-site-association` tells iPhones that `/daily` links belong to the World Quizzer app
  (team K9P44ALFC9, bundle ID `com.williambarnespersonalteam.MapQuizTest`), so they open the app's daily quiz.
- `daily/index.html` is what anyone without the app sees: both store buttons, on every device. Sending people
  straight to their own store is `/get`'s job only.
- `daily/share.png` is the picture shown when the link is shared (a copy of the Google Play feature graphic).
  `sitemap.xml` lists the page for search engines and is named in `robots.txt`.
- `get/share.jpg` is the picture shown when the `/get` link is shared (the share picture as a smaller JPEG).
- `.nojekyll` makes GitHub Pages serve the `.well-known` folder.

The privacy policy is a separate site: https://will-seo.github.io/world-quizzer-privacy/

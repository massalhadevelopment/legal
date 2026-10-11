# MASSALHA FZCO app legal pages

Privacy policies for the company's apps, served by GitHub Pages at **https://legal.massalhafzco.com**.
Plain HTML, no build step. Support email for every app: support@massalhafzco.com.
Terms of use: Apple's standard EULA (linked from each app).

## Add a page for a new app

1. Copy `looksmax/privacy/index.html` to `<app>/privacy/index.html` (lowercase app slug).
2. Rewrite every section to match what THAT app really does: which data it collects, where it's sent
   (OpenAI, Supabase, RevenueCat, Meta SDK, Mixpanel…), what's stored on the device vs. our servers,
   whether there's an account and how it's deleted, tracking (ATT) if the Meta SDK is used.
   It must agree with the App Privacy answers in App Store Connect. Keep the English and Arabic versions in sync.
3. Update "Last updated", add the app to the list in `index.html`.
4. Commit and push to `main`. The page is live at `https://legal.massalhafzco.com/<app>/privacy/` within a minute.
5. Put that URL in the app (paywall + settings) and in App Store Connect (Privacy Policy URL).

So3rati keeps its existing policy at https://privacy.massalhafzco.com (Carrd).

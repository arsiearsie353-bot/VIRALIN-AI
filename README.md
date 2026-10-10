# VIRALIN AI — Starter Project (Android)

Starter project for a full-featured AI creator app. It includes a Flutter mobile UI,
AI content-generation service interface, video-generation job interface, Firebase
configuration placeholders, and a minimal admin API outline.

## Included
- Dashboard with content tools
- Script / idea / title / description / hashtag generation UI
- Product ad copy workflow
- Prompt generation workflow
- Voice narration text workflow
- Video-generation job screen scaffold
- Project history scaffold
- Premium screen scaffold
- Admin/backend starter (Node.js + Express)
- Setup notes for Firebase and AI/video provider APIs

## Important
This is a development starter, not a ready-to-publish APK. It will run in demo mode
without secret API keys, and will return sample results. Real AI text, voice, and
video generation require provider accounts and server-side API keys. Never put API
keys in the Android app. Review privacy, child safety, payments, and Play Store
requirements before publishing.

## Run the Flutter app
1. Install Flutter SDK and Android Studio.
2. Create a Flutter project or use this folder as the project root:
   `flutter create .`
3. Replace/add the provided `lib/` files (keep generated platform folders).
4. Run `flutter pub get`
5. Run `flutter run`

## Run backend demo
1. Install Node.js 20+
2. `cd backend`
3. `npm install`
4. Copy `.env.example` to `.env` and fill provider settings if implementing real APIs.
5. `npm run dev`

## Production work still required
- Configure Firebase project, Authentication, Firestore and App Check.
- Implement real AI provider and video provider adapters in backend.
- Add provider-specific moderation, quotas, rate limiting and cost controls.
- Implement subscription billing with Google Play Billing.
- Add consent, privacy policy, account deletion, support contact and Play Console assets.
- Test on real Android devices and generate a signed release bundle.

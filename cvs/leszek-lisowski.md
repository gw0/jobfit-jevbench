# Leszek Lisowski
Warsaw, Poland (Remote) | leszek.lisowski@example.com | +48 601 223 445 | github.com/llisowski-dev

## Summary
Mobile engineer, 8 yrs, native + hybrid. Shipped apps 2M+ installs combined, fintech + logistics + one health-tech thing that got killed by legal (not my fault). Comfortable owning whole app lifecycle - architecture, CI, App Store/Play submissions, on-call. SwiftUI since it was buggy in 2019, still is honestly. Kotlin/Compose more recently. Can do Obj-C if forced, please don't force me.

## Skills
- **iOS:** Swift, SwiftUI, UIKit (legacy stuff mostly), Combine, async/await, Core Data, CryptoKit
- **Android:** Kotlin, Jetpack Compose, Coroutines/Flow, Room, WorkManager
- Architecture: MVVM, some MVI attempts (mixed results), modularization
- CI/CD: Fastlane, GitHub Actions, Bitrise (hate it, works though)
- Other: REST/GraphQL integration, gRPC (briefly), Firebase, unit+snapshot testing, Accessibility (VoiceOver/TalkBack)
- Tools - Xcode obviously, Android Studio, Instruments, Charles proxy for debugging api nonsense

## Experience

### Senior Mobile Engineer — Nordbrick Financial Systems (Warsaw, remote-first) — 2022–Present
fintech, payments app, ~400k MAU
- Rebuilt onboarding flow in SwiftUI, KYC step, dropped abandonment by 31% (measured over 2 quarters)
- introduced Kotlin Multiplatform for shared validation logic between iOS/Android — cut duplicate bug reports a LOT, team was skeptical at first
- On-call rotation lead, cut P1 incident response time roughly in half by writing actual runbooks (nobody had any before)
- mentored 2 junior engineers, one of them promoted since
- Led migration off deprecated push provider under deadline pressure (regulatory thing) — no downtime

### Mobile Engineer, iOS/Android — Vellamark Logistics GmbH (remote, Berlin HQ) — 2019–2022
driver-facing route optimization app, offline-first
- Built offline sync engine (Core Data + Room mirroring), handled flaky warehouse wifi environments
- SwiftUI adoption early - was one of first teams in company to go all-in, wrote internal migration guide
- Reduced crash rate from 4.1% to 0.6% over 6 months, mostly memory leaks in old UIKit screens
- worked closely with backend on gRPC migration for route data, latency down ~40%

### iOS Developer — Hearthglass Retail Technologies (Kraków) — 2017–2019
in-store POS + inventory scanning app
- Built barcode scanning module (AVFoundation), integrated with inventory backend
- maintained UIKit codebase, incremental Swift migration from Obj-C (painful, glad it's done)
- shipped v1 through v6, App Store, handled all submission/rejection cycles myself

## Education
**B.Sc. Computer Science** — Warsaw University of Technology (Politechnika Warszawska), 2013–2017

Some coursework in embedded systems too, not really relevant anymore but was fun at the time

# Product

<!-- impeccable:product-schema 1 -->

## Platform

android

## Stack

Single-file HTML/CSS/JS wrapped as an Android app with Capacitor 8, built in GitHub Actions (debug APK + release AAB). The same file is served as a PWA on GitHub Pages (rainboy07012.github.io/gudo). On-device detection with MediaPipe Tasks Vision (EfficientDet-Lite0).

## Users

Beginners who take travel and everyday photos (people in their 20s–30s) and want good photos of partners, friends and scenery without learning photography theory. They shoot one-handed, often outdoors, often in a hurry, often while the subject is waiting.

## Product Purpose

A camera that shows, live on the viewfinder, where to put the subject and how to hold the phone, then lets the user take the shot. Success: the user lines up a dot with a target, sees it turn green, and gets a better-composed photo than they would have without the app.

## Positioning

Covers more than people: horizon placement for scenery and vertical-line control (phone tilt) for buildings, alongside person and group placement. Android-first.

## Operating Context

Used in the field: bright sun, sunset, night streets, travel spots, cafes. Thumb reach on a tall phone matters. Detection and analysis run entirely on the device; photos never leave the phone unless the user shares them.

## Capabilities and Constraints

- Modes: 한 사람 (single person), 여럿 (group), 풍경 (landscape: horizon to a third line, level), 건축 (architecture: level + pitch, building centred).
- Guide flow: zoom suggestion → composition alignment (dot into circle, turns green) → exposure suggestion → shoot.
- Photo mode for trying the guide on an existing picture (drag to align).
- Uses camera and motion sensors; no account, no server.
- Monetization: free + PRO is planned (user asked for a recommendation; tier split is undecided). Billing is not implemented yet.
- Play Store requirements: target API 36; new personal developer accounts must run a 12-tester, 14-day closed test before production.

## Brand Commitments

- Name: 프레임핏 (FrameFit). App ID: io.github.rainboy07012.framefit.
- Korean UI, polite and short copy (존댓말).
- Must not look AI-generated or templated.

## Evidence on Hand

No users, reviews, ratings or press yet. Do not fabricate download counts, testimonials or ratings in any store listing or screen.

## Product Principles

1. The viewfinder is the product: chrome gets out of the way of the picture.
2. One instruction at a time, in plain Korean, that a beginner can act on without thinking.
3. Green means shoot: the success state is unmistakable at arm's length in sunlight.
4. Private by construction: everything stays on the phone.

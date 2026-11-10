# FormAI Live
### Computer Vision · AI-Assisted Exercise Analysis · Web Application

**An experimental web application that analyzes exercise videos using pose estimation.**

> **Portfolio showcase only.** The application's source repository is private. This public page contains no application source code, private configuration, access credentials, or user videos.

## Project overview

FormAI Live explores how computer vision can help people *review* their exercise movements. Users select an exercise, upload a video, and receive approximate joint measurements and observations generated from detected body landmarks.

The project is a **prototype**, not a medical device, injury-prevention system, or substitute for a qualified trainer. Its observations are exploratory and have not been clinically or professionally validated.

## The problem

Reviewing movement without direct coaching is difficult. FormAI investigates whether estimated landmarks and interpretable two-dimensional angles can provide an understandable starting point for self-observation.

## Core workflow

1. The user selects an exercise and reads recording guidance.
2. The user provides an exercise video through the browser.
3. The application samples video frames and estimates joint landmarks with MediaPipe Pose Landmarker.
4. It checks whether relevant landmarks are visible and estimates two-dimensional joint angles.
5. It presents approximate measurements and observations, with explicit limitations.

**Explored exercises:** squats, deadlifts, biceps curls and lunges.

## Technology

| Layer | Tools | Purpose |
|---|---|---|
| Frontend | HTML5, CSS3, JavaScript | Responsive user experience and video processing |
| Build tooling | Vite | Development workflow |
| Computer vision | MediaPipe Pose Landmarker | Landmark estimation from video frames |
| Authentication | Supabase Auth | Sign-up, sign-in and password recovery |
| Quality practices | GitHub, tests, CI workflow | Version tracking and automated checks |
| Deployment | Static web hosting | Browser-based access |

## Engineering workflow

```text
Video input → Frame sampling → Pose landmarks
            → Landmark visibility checks → 2D geometry
            → Exercise-specific exploratory observations
```

## What this demonstrates

- Integrating a pre-trained machine-learning model into a web workflow
- Transforming raw landmark coordinates into interpretable measurements
- Designing a responsive interface and clear user feedback
- Documenting assumptions, uncertainties and safety limitations
- Managing changes with Git and automated checks
- Building a user-facing prototype across multiple technical components

## Limitations and responsible use

- Results depend on camera position, lighting, occlusion, clothes and video quality.
- Two-dimensional angles do not reconstruct full three-dimensional biomechanics.
- A detected movement pattern does **not** prove an injury risk or a safe technique.
- The application does not diagnose conditions or replace professional assessment.
- Video processing is described in the source project's documentation as browser-side; third-party dependencies may still be downloaded.

## Interview talking points

**Challenge:** turn complex computer-vision outputs into clear, user-understandable observations while acknowledging uncertainty.

**Approach:** estimate landmarks, validate visibility, compute 2D joint angles and present exercise-specific observations.

**What I would improve:** evaluate the system against annotated reference videos, measure landmark/angle stability, strengthen accessibility testing and document false positives and false negatives.

## Source-code access

The primary repository is intentionally **private**. This showcase is public to communicate project purpose, approach and engineering decisions without distributing the repository or commit history.

For a technical interview, I can demonstrate the interface and discuss architecture, trade-offs, testing and limitations without granting source-repository access.

---

*Academic/portfolio prototype · No proprietary code included in this showcase.*
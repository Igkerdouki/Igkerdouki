<p align="center">
  <img src="./assets/hello.svg" width="100%" alt="Hello, I'm Ioanna. I build systems that notice what people miss.">
</p>

Hi, I'm **Ioanna Gkerdouki** — a Mathematics–Computer Science student at UC San Diego. I'm curious about almost everything, and I've learned I can walk into a field I know nothing about and build something real in it.

So far that has meant cameras that recognize a medical emergency, a model of where pesticides drift, pipelines that decode signals from the optic nerve, trading agents that keep a journal, and an open problem in number theory. Different fields, same method: find the question, then build the whole thing that answers it — the model, the architecture around it, and the interface that makes it trustworthy.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-5C6BC0?style=for-the-badge&logo=c&logoColor=white)
![Java](https://img.shields.io/badge/Java-E76F00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-D95319?style=for-the-badge)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## About me

- 🔭 **Product Owner & Software Developer Intern** at the San Diego Supercomputer Center, where I originated **Perceptra** — a platform that watches live video for falls, medical emergencies and other incidents — and built its detection models.
- 🧠 **Undergraduate Research Assistant** at UC San Diego's Integrated Electronics & Biointerfaces Laboratory, building ML pipelines in Python and MATLAB that decode neural signals.
- 🎓 B.S. Mathematics–Computer Science, UC San Diego — graduating December 2026.
- 🏆 Winner, IEEE Quarterly Projects (Spring 2026) with **WildSafe**.
- 🇬🇷 Greek (native) and English.

## What I can build

| If you need… | I build it with | Where I've done it |
|---|---|---|
| **Real-time computer vision** — from camera frame to alert | MediaPipe, YOLO, CLIP, pose estimation | Perceptra, [WildSafe](https://github.com/Igkerdouki/wildsafe-ml-service) |
| **A model that survives deployment** | FastAPI, Docker, ONNX Runtime | [wildsafe-ml-service](https://github.com/Igkerdouki/wildsafe-ml-service) |
| **Geospatial data platforms** | FastAPI, PostgreSQL/PostGIS, WebSockets, React, MapLibre GL | [GeoSync](https://github.com/Igkerdouki/geosync) |
| **Multi-agent systems** | FastAPI, SQLAlchemy, React, TypeScript, Interactive Brokers API | [Bloom](https://github.com/Igkerdouki/portfolio-tracker) |
| **Neural signal decoding** | Python, MATLAB, band-pass filtering, feature extraction, SVMs | Research at IEBL |
| **Developer tooling** | Python standard library, GitHub Actions | [SpecCheck](https://github.com/Igkerdouki/speccheck) |
| **Systems software, from scratch** | C, POSIX sockets, process control, memory management | [c-web-server](https://github.com/Igkerdouki/c-web-server), [c-shell](https://github.com/Igkerdouki/c-shell), [memory-allocator](https://github.com/Igkerdouki/memory-allocator) |
| **Edge hardware** | Raspberry Pi, H.264 over WebRTC, MQTT | WildSafe, [pi-camera](https://github.com/Igkerdouki/pi-camera) |

## Machine learning work

### Perceptra — cameras that recognize an emergency
Live video in, alert out: pose-based detection of falls, choking and unresponsiveness, built with MediaPipe, YOLO and FastAPI. I originated the product at the San Diego Supercomputer Center, designed the architecture from camera to alert, and wrote the detection pipeline. The code lives in SDSC's private repository; the front-end demo is [here](https://github.com/Igkerdouki/-percepta-demo).

### [WildSafe](https://github.com/Igkerdouki/wildsafe-ml-service) — the model said 98.5%. I proved it was 50%, then got it right.
A wildlife-collision prevention system: Raspberry Pi cameras stream to a hosted inference service running CLIP zero-shot classification and MediaPipe pose estimation. The most useful thing I did was catch a train/test leak in our own best number. 🏆 Winner, IEEE Quarterly Projects, Spring 2026 — [see it on Devpost](https://devpost.com/software/wildwatch-a-wildlife-detection-system-for-road-safety-3djoa9).

### [GeoSync](https://github.com/Igkerdouki/geosync) — where does pesticide drift go once it leaves the field?
A geospatial platform over California's Pesticide Use Reports that predicts off-farm drift with a Gaussian plume model, Pasquill–Gifford stability classes and live weather, then shows it as a live risk map.

### [Bloom](https://github.com/Igkerdouki/portfolio-tracker) — investing that teaches you as you go
Most investing tools assume you already know what you're doing. Bloom teaches you as you use it: ask "highlight the 3 best treasuries from this list" and the built-in assistant marks its picks and explains each one in plain language. Underneath are ML price prediction and a multi-agent system. It links to Interactive Brokers, Coinbase and Alpaca, or imports a CSV from any broker, with more platforms on the way. In progress.

<img src="./assets/bloom-bonds.png" width="100%" alt="Bloom's bond finder, with three Treasuries marked as the assistant's picks and the reasoning shown in a chat panel beside the list.">

### Neural signal decoding — what colour did the eye just see?
Research at UC San Diego's IEBL: Python and MATLAB pipelines that preprocess multi-channel electrophysiology, extract temporal and spectral features, and classify colour from optic nerve recordings. Lab work, so the code is not public.

## Tools and research

### [SpecCheck](https://github.com/Igkerdouki/speccheck) — did the AI actually build what the ticket asked for?
AI code reviewers read a diff and guess. SpecCheck runs each requirement against the live app, fast-forwards the clock when the ticket talks about time, and posts ✅ Met / ❌ Not met / ⚠️ Couldn't verify on the pull request with the full trace. No dependencies.

### [magic-square-congrua](https://github.com/Igkerdouki/magic-square-congrua) — is there a 3×3 magic square of squares?
Nobody knows; the problem has been open since 1984. Independent, computer-assisted research, with honest notes on what fails.

## Curious about

- Evaluation that tells the truth — the gap between a number that looks good and one that is real
- Vision systems that have to act, not just classify
- Decoding signals from the nervous system
- Open problems in number theory I can attack with a computer

## Say hello

[LinkedIn](https://www.linkedin.com/in/ioanna-gkerdouki-821b10153/) · [All my repositories](https://github.com/Igkerdouki?tab=repositories)

# Rafael Probst

I study Artificial Intelligence and Intelligent Data Systems at PUCPR, in Brazil.
I work on web products and multiplayer systems, and I build AI tools that run on consumer GPUs.

## Work

**Moureau Development**, full-stack developer (2026)\
TypeScript and Go on the studio's SaaS products and internal platform: subscription billing,
authentication and Google sign-in, file storage on Cloudflare R2 and KV, real-time notifications
over SSE, and a Go SDK for session validation. The studio's open source projects include
[Newstack](https://github.com/moureau-dev/newstack), a web framework, and
[Murow](https://github.com/moureau-dev/murow), a multiplayer game engine.

## Projects

**[Pop3D](https://pop3d.quest)**\
Free Windows app that turns 2D video into stereoscopic 3D in real time and plays it in a VR headset.
Depth comes from Video Depth Anything (via iw3) on PyTorch with CUDA Graphs, and the picture streams
to a Meta Quest over Wi-Fi. Available on the Meta Horizon Store, website in 10 languages.
The [Quest app](https://github.com/Sindelitcis/pop3d-quest) is open source (GPLv3): a fork of
Moonlight XR adapted to work as a remote monitor for the PC.

**[Moodcut](https://github.com/Sindelitcis/moodcut)**\
Turns long streams and podcasts into YouTube clips. Downloads with yt-dlp, transcribes with Whisper on CUDA,
uses an LLM in two passes to split topics and write titles, cuts with ffmpeg (NVENC, burned-in subtitles),
then makes the thumbnail and uploads through the YouTube API.

**[Radar VR](https://github.com/Sindelitcis/radar-vr)**\
Daily audio bulletin on what changed in the Steam VR games you follow: patches, sales, player counts.
It compares snapshots over time in SQLite, writes headlines with a local LLM and narrates them with Kokoro.
Built for the AI Factory program at PUCPR.

**[Moba-Newrow](https://github.com/Sindelitcis/Moba-Newrow)**\
3v3 MOBA prototype with a server-authoritative simulation at 20 Hz, built on Murow (ECS, netcode,
WebGPU rendering) and Newstack (SSR page and HUD). Game server on Bun, WebSocket to the browser.

**[KanjiMon](https://kanjimon.online)**\
Browser game for studying kanji, installable as a PWA.

Private projects: Persória, a faceless YouTube channel run by a pipeline (voice cloning with Chatterbox,
generated images, Whisper, Remotion), and Pólen, a VRChat world made in Unity with UdonSharp.

Earlier: a Telegram bot that monitored deliveries in SQL Server for WebHelp,
the [Impulso Digital website](https://impulsodigitalmarketing.com.br), and Discord bots.

## Tools

TypeScript, Go, Python, Bun, Node.js, PyTorch, CUDA, Whisper, ffmpeg, Cloudflare, AWS, MongoDB, Unity.

## Contact

rafaelprobst13@gmail.com · [LinkedIn](https://www.linkedin.com/in/rafael-probst-1705583b3/)

Open to freelance work. Goal: work with AI in Japan from 2029, studying for the JLPT N2.

---

**Em português:** estudo IA e Sistemas Inteligentes de Dados na PUCPR. Trabalho com produto web,
sistemas multiplayer e ferramentas de IA. Aberto a freelas. Contato: rafaelprobst13@gmail.com.

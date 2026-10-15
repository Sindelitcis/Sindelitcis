# Rafael Probst

<a href="https://www.linkedin.com/in/rafael-probst-1705583b3/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square" alt="LinkedIn"></a>
<a href="mailto:rafaelprobst13@gmail.com"><img src="https://img.shields.io/badge/rafaelprobst13@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://pop3d.quest"><img src="https://img.shields.io/badge/pop3d.quest-5B5BD6?style=flat-square" alt="pop3d.quest"></a>

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

<p>
  <a href="https://www.typescriptlang.org"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" title="TypeScript"></a>
  <a href="https://go.dev"><img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" title="Go"></a>
  <a href="https://www.python.org"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B" alt="Python" title="Python"></a>
  <a href="https://en.cppreference.com/w/c"><img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" title="C"></a>
  <a href="https://openjdk.org"><img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" title="Java"></a><br>
  <a href="https://nodejs.org"><img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" title="Node.js"></a>
  <a href="https://bun.sh"><img src="https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white" alt="Bun" title="Bun"></a>
  <a href="https://nullstack.app"><img src="https://tinyurl.com/nullstack-badge" alt="Nullstack" title="Nullstack"></a>
  <a href="https://www.cloudflare.com"><img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare" title="Cloudflare"></a>
  <a href="https://aws.amazon.com"><img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge" alt="AWS" title="AWS"></a>
  <a href="https://www.mongodb.com"><img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" title="MongoDB"></a>
  <a href="https://www.sqlite.org"><img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" title="SQLite"></a><br>
  <a href="https://pytorch.org"><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" title="PyTorch"></a>
  <a href="https://developer.nvidia.com/cuda-toolkit"><img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA" title="CUDA"></a>
  <a href="https://github.com/openai/whisper"><img src="https://img.shields.io/badge/Whisper-412991?style=for-the-badge" alt="Whisper" title="Whisper"></a>
  <a href="https://ffmpeg.org"><img src="https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white" alt="FFmpeg" title="FFmpeg"></a><br>
  <a href="https://unity.com"><img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" title="Unity"></a>
  <a href="https://www.w3.org/TR/webgpu/"><img src="https://img.shields.io/badge/WebGPU-005A9C?style=for-the-badge&logo=webgpu&logoColor=white" alt="WebGPU" title="WebGPU"></a>
  <a href="https://www.khronos.org/opengles/"><img src="https://img.shields.io/badge/OpenGL_ES-5586A4?style=for-the-badge&logo=opengl&logoColor=white" alt="OpenGL ES" title="OpenGL ES"></a>
  <a href="https://www.meta.com/quest/"><img src="https://img.shields.io/badge/Meta_Quest-0467DF?style=for-the-badge&logo=meta&logoColor=white" alt="Meta Quest" title="Meta Quest"></a>
</p>

## Contact

Open to freelance work. Goal: work with AI in Japan from 2029, studying for the JLPT N2.

🇧🇷 Pode me escrever em português também.

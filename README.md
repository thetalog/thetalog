<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00e5ff,50:7c3aed,100:ff2bd6&height=160&section=header&text=DEEPRAJ%20DAS&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=FULL-STACK%20ENGINEER%20//%20SYSTEMS%20//%20CLOUD&descAlignY=64&descSize=15" width="100%" alt="Deepraj Das" />

  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=2600&pause=800&color=00E5FF&center=true&vCenter=true&width=680&lines=Systems.+Interfaces.+Infrastructure.;Build+fast.+Ship+clean.+Scale+later." alt="typing status" />

  <br/>

  <a href="https://github.com/thetalog"><img src="https://img.shields.io/badge/github-030712?style=for-the-badge&logo=github&logoColor=00e5ff" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/deepraj-das/"><img src="https://img.shields.io/badge/linkedin-030712?style=for-the-badge&logo=linkedin&logoColor=00e5ff" alt="LinkedIn" /></a>
  <a href="https://thetalog.github.io"><img src="https://img.shields.io/badge/portfolio-030712?style=for-the-badge&logo=vercel&logoColor=ff2bd6" alt="Portfolio" /></a>
  <img src="https://img.shields.io/badge/open_to_work-030712?style=for-the-badge&logo=statuspage&logoColor=00e5ff" alt="Open to work" />
</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00e5ff,50:7c3aed,100:ff2bd6&height=3" width="100%" alt="" />

I ship **full-stack systems** // APIs, real-time apps, and cloud infra. Exploring DevOps, networking, and distributed design.

<div align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,nodejs,express,nuxt,vue,react,java,spring,python,mongodb,postgres,docker,aws,linux,git&perline=8" alt="tech stack" />
</div>

### [`PIXL`](https://github.com/thetalog/pixl) // production social platform

Instagram-class product I designed and shipped end to end.

**Repo:** [github.com/thetalog/pixl](https://github.com/thetalog/pixl)

Nuxt web client talking to a Node.js / Express API. Auth is OTP + JWT. Users can post, reel, story, like, save, comment, tag, follow, and discover. Realtime layer covers DMs, group chats, typing/read receipts, and live streams with live comments.

Infra: MongoDB + Prisma, media on **AWS S3**, push via **Firebase FCM**, Socket.IO for live events, API on **EC2**. Modular REST (auth, feed, media, messaging, live) with Joi validation and S3 uploads.

```text
Nuxt  ──HTTPS──►  Express / EC2  ──►  MongoDB + Prisma
                         │
                         ├── AWS S3 (media)
                         └── FCM + Socket.IO (realtime)

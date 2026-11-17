<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
    <img src="assets/header-light.svg" alt="Afonso Lima. Developer, Porto, Portugal" width="640">
  </picture>
</div>

<p align="center">
  I build :)<br>
  Informatics Engineering student at FEUP, currently all in on my <a href="https://github.com/Bebaz0/HomeLab">homelab</a>.
</p>

<br>

## HomeLab

The Linux box under my desk: 19 self-hosted services (passwords, shopping lists, fitness, location history, Spotify stats, retro games) behind a single Caddy reverse proxy, with local DNS at home and Tailscale everywhere else. No port forwarding: remote access is Tailscale only. The one public service is my personal site, [afonsolima.dev](https://afonsolima.dev): Cloudflare DNS points the domain at a Cloudflare Tunnel, which carries the traffic to an nginx container on the box. It also runs things I built myself: a PR reviewer that runs static analysis on my GitHub pull requests, and a Playwright bot that answers League invites in my friends' group chat.

<sub>Docker&ensp;·&ensp;Caddy&ensp;·&ensp;Tailscale&ensp;·&ensp;Cloudflare Tunnel&ensp;·&ensp;AdGuard Home&ensp;·&ensp;Komodo&ensp;·&ensp;Python&ensp;·&ensp;Playwright</sub>

**[View repository](https://github.com/Bebaz0/HomeLab)**

### homelab-status

Live status of my homelab, served from the edge. A push based collector feeds a Cloudflare Worker and D1, which powers this card and the homelab section of my site, without opening a single port at home.

<sub>Cloudflare Workers&ensp;·&ensp;D1&ensp;·&ensp;TypeScript&ensp;·&ensp;Python&ensp;·&ensp;Docker</sub>

**[View repository](https://github.com/Bebaz0/homelab-status)**

<a href="https://afonsolima.dev">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://status.afonsolima.dev/card.svg?theme=dark">
    <source media="(prefers-color-scheme: light)" srcset="https://status.afonsolima.dev/card.svg?theme=light">
    <img alt="Estado do homelab (arroz)" src="https://status.afonsolima.dev/card.svg?theme=dark" width="460">
  </picture>
</a>

<br>

## HabitWar

HabitWar turns habit building into a multiplayer competition: challenge your friends, keep your streaks alive and climb the leaderboard. Live on iOS and Android, with paying customers on both platforms.

<sub>React Native&ensp;·&ensp;Expo&ensp;·&ensp;TypeScript&ensp;·&ensp;Supabase&ensp;·&ensp;RevenueCat</sub>

**[habitwar.app](https://habitwar.app)**

<p>
  <a href="https://apps.apple.com/pt/app/habitwars/id6760320345">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/badge-appstore-dark.svg">
      <img src="assets/badge-appstore-light.svg" alt="Download on the App Store" height="44">
    </picture>
  </a>&ensp;<a href="https://play.google.com/store/apps/details?id=com.anonymous.habitwar">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/badge-googleplay-dark.svg">
      <img src="assets/badge-googleplay-light.svg" alt="Get it on Google Play" height="44">
    </picture>
  </a>
</p>

<br>

## Porto Box Cup

The official platform of the world's largest boxing tournament. Public event site, team dashboard for registrations and an admin dashboard that runs the entire event.

<table>
  <tr>
    <td align="center" width="140"><strong>348</strong><br><sub>REGISTERED TEAMS</sub></td>
    <td align="center" width="140"><strong>1,200+</strong><br><sub>TOTAL ATHLETES REGISTERED</sub></td>
    <td align="center" width="200"><strong>#1</strong><br><sub>LARGEST IN THE WORLD</sub></td>
  </tr>
</table>

<sub>React&ensp;·&ensp;Supabase&ensp;·&ensp;Framer Motion&ensp;·&ensp;i18next</sub>

**[portoboxcup.com](https://portoboxcup.com)**


<br>

## Minix Boxing

Two player boxing game for MINIX, written in C on top of our own keyboard, mouse, video, timer and RTC drivers. One player fights on the keyboard, hitting Q W E R prompts as they appear. The other fights on the mouse, clicking bubbles before they close. Perfect timing fills a combo bar, a miss costs you HP, and the timing windows shrink every round. Built by a team of four for Computer Laboratory at FEUP.

<sub>C&ensp;·&ensp;MINIX 3&ensp;·&ensp;Device drivers&ensp;·&ensp;VBE graphics</sub>

**[View repository](https://github.com/Bebaz0/minix-boxing)**

<br>

## TradeMyBooks

A book trading app built with a student team at FEUP (Software Engineering, LEIC). Developed end to end with scrum: product vision, user stories, sprints and CI/CD.

**[View repository](https://github.com/LEIC-ES-2025-26-2LEIC07/T4)**

<br>

## More projects

- **[Sensei Shelf](https://github.com/Bebaz0/sensei-shelf)** · A computer vision challenge made by Sensei that awarded my team 4th place in Junction X Lisbon 
- **[Scrim Image Editor](https://github.com/Bebaz0/Scrim-Image-Editor)** · Image editor written in C++
- **[Country Info](https://github.com/Bebaz0/country-info-with-themes)** · Country explorer in React with switchable themes
- **[Portfolio](https://afonsolima.dev)** · My personal website, self-hosted on my homelab behind a Cloudflare Tunnel
- **[Dean Rök](https://deanrok.com)** · Heavily animated website for the cinematic rock project Dean Rok, built with React, Tailwind CSS and Framer Motion

<br>

<div align="center">
  <sub>
    <a href="https://instagram.com/bebaz___">Instagram</a>
    &ensp;·&ensp;
    <a href="mailto:limaafonso57@gmail.com">limaafonso57@gmail.com</a>
  </sub>
</div>

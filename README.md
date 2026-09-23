<!--
  Hi, source-code inspector 👋

  Yes, there is HTML in this README.
  No, I don't regret it.
-->

<div align="center">

# Hi 👋, I'm Minh

### Software Engineer · Computer Science PhD Student · Systems Tinkerer

**Distributed systems · Storage · Security · Infrastructure · Local AI**

</div>

<img
align="right"
width="220"
hspace="0"
src="https://raw.githubusercontent.com/minh-tg/minh-tg/readme-assets/rainbow-cat-round.gif"
alt="Rainbow cat"
/>

I like building things, messing around with systems, and whatever rabbit hole I'm digging into at the moment. Currently, that's agent harnesses and security scanning.

My PhD work focuses mostly on **distributed storage and key management**, particularly how these systems behave under load and during failures.

Outside of that, I spend a lot of time with **NixOS, self-hosting, small local models, agent tooling, developer tools**, and side projects that tend to grow a bit out of the original scope.

A fairly common sequence of events:

> Find a tool → try it → hit one annoying limitation → try a few alternatives → build something instead.

<br clear="right" />

---

## 🔭 What I'm building

<table>
<tr>
<td width="50%" valign="top">

### 🔐 Distributed KMS

`distributed systems` `storage` `security` `performance`

A large part of my PhD work revolves around distributed KMS designs for storage systems, with a focus on **request handling, scaling, and failure behavior**.

<br>

</td>
<td width="50%" valign="top">

### 🛠️ Ground Control

`infrastructure` `control plane` `automation` `systems`

A control plane for **heterogeneous infrastructure**.

Machines, services, and environments are rarely as uniform as we'd like them to be. Ground Control is an attempt to manage that. It supports Proxmox and Xen Orchestra through a unified interface and is inherently designed in such a way, that other control planes can be easily integrated.

<br>

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🧠 Small-model coding agents

`local AI` `agents` `LLMs` `benchmarking`

I'm interested in how capable small local models can become when more of the work is handled by the surrounding **harness and tooling**.

I've been experimenting with tool policies, delegation, context management, and failure modes, with an emphasis on measuring what actually changes rather than just swapping models.

<br>

</td>
<td width="50%" valign="top">

### 🐧 Reproducible systems

`NixOS` `Linux` `containers` `homelab`

My NixOS config has gradually turned into a place for experimenting with more than just machine configuration.

It covers **reproducibility, Wayland, containers, self-hosting, multi-machine setups**, and various things I've decided would be nicer to manage declaratively.

<br>

</td>
</tr>
</table>

---

## 🌱 Open source

I usually contribute upstream when fixing something makes more sense than maintaining a workaround.

Some recent examples:

* **[TokenTracker](https://github.com/xiufengsun/TokenTracker)** - Linux/NixOS and WSL support, provider integrations, parser work, and token accounting fixes.
  [Antigravity process + port detection](https://github.com/xiufengsun/TokenTracker/pull/579) · [Command Code limits](https://github.com/xiufengsun/TokenTracker/pull/594) · [Antigravity token accounting](https://github.com/xiufengsun/TokenTracker/pull/599) · [DeepSeek Harness v3](https://github.com/xiufengsun/TokenTracker/pull/614)

* **[Serpantinum](https://github.com/ilyamiro/serpantinum)** - fixes around Wayland desktop behavior and display-manager integration.
  [SDDM compositor handling](https://github.com/ilyamiro/serpantinum/pull/282) · [autohide tray behavior](https://github.com/ilyamiro/serpantinum/pull/249)

* **Specht** - security tooling, vulnerability management, and fixes that occasionally require learning far more about a subsystem than expected.

---

## ⚙️ Toolbox

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/go/go-original.svg" height="32" alt="Go" title="Go" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" height="32" alt="Python" title="Python" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" height="32" alt="Linux" title="Linux" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nixos/nixos-original.svg" height="32" alt="NixOS" title="NixOS" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" height="32" alt="Docker" title="Docker" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" height="32" alt="PostgreSQL" title="PostgreSQL" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/kubernetes/kubernetes-original.svg" height="32" alt="Kubernetes" title="Kubernetes" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" height="32" alt="Git" title="Git" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" height="32" alt="C#" title="C#" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/dotnetcore/dotnetcore-original.svg" height="32" alt=".NET" title=".NET" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" height="32" alt="TypeScript" title="TypeScript" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" height="32" alt="JavaScript" title="JavaScript" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vuejs/vuejs-original.svg" height="32" alt="Vue.js" title="Vue.js" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" height="32" alt="React" title="React" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" height="32" alt="AWS" title="AWS" />
</div>

<p align="center">
  Most of my day-to-day coding is in <strong>Go</strong> and <strong>Python</strong>. The rest depends on whatever I'm working on.
</p>

Most of what I build falls somewhere around **backend services, research prototypes, developer tools, automation, benchmarks, dashboards**, and small tools that solve problems I keep running into.

<!-- TODO

---

## ✍️ Recently wrote

BLOG-POST-LIST:START
BLOG-POST-LIST:END

-->

---

## 📊 GitHub

<div align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://gitcard-studio.creativecode.com.co/api/stats?username=minh-tg&theme=dark&locale=en"
    />
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://gitcard-studio.creativecode.com.co/api/stats?username=minh-tg&theme=light&locale=en"
    />
    <img
      src="https://gitcard-studio.creativecode.com.co/api/stats?username=minh-tg&theme=light&locale=en"
      alt="Minh's GitHub statistics"
    />
  </picture>
</div>

<br>

<div align="center">
  <img
    src="https://streak-stats.demolab.com?user=minh-tg&theme=dracula&hide_border=true&border_radius=5&mode=weekly"
    height="165"
    alt="GitHub streak"
  />
</div>

<br>

<div align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/minh-tg/minh-tg/readme-assets/snake-dark.svg"
    />
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/minh-tg/minh-tg/readme-assets/snake.svg"
    />
    <img
      src="https://raw.githubusercontent.com/minh-tg/minh-tg/readme-assets/snake.svg"
      alt="GitHub contribution snake"
    />
  </picture>
</div>

---

<p align="center">
  <i>Usually building something, debugging something, or figuring out why it behaves differently than expected.</i>
</p>

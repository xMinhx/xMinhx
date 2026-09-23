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
  width="105"
  hspace="18"
  src="https://raw.githubusercontent.com/minh-tg/minh-tg/readme-assets/rainbow-cat-round.gif"
  alt="Rainbow cat"
/>

I like building things, taking systems apart to see what makes them tick, and benchmarking them until they do something weird.

My PhD work is mostly around **distributed storage and key management** — especially what happens when requests pile up, nodes disappear, or failover has to work for real instead of just looking nice in a diagram.

When I'm not doing that, I'm usually messing with **NixOS, self-hosting, small local models, agent tooling, developer tools**, or some infrastructure idea that was supposed to take 20 minutes.

The usual pattern goes something like this:

> Find a tool → try it → find one annoying thing → try four alternatives → “fine, I'll do it myself.”

<br clear="right" />

---

## 🔭 What I'm building

<table>
<tr>
<td width="50%" valign="top">

### 🔐 Distributed KMS

`distributed systems` `storage` `security` `performance`

My PhD work in code form: distributed KMS designs for storage systems, with a focus on the **request path, scaling, and failure**.

The interesting part usually starts when the happy path stops being happy.

<br>

</td>
<td width="50%" valign="top">

### 🛠️ Ground Control

`infrastructure` `control plane` `automation` `systems`

A control plane for **heterogeneous infrastructure**.

Real machines, services, and environments rarely look as uniform as architecture diagrams make them look. Ground Control is my attempt to embrace that instead of hiding it.

<br>

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🧠 Small-model coding agents

`local AI` `agents` `LLMs` `benchmarking`

How far can you push a small local model if the **harness does more of the work**?

I've been benchmarking tool policies, delegation, context, and failure modes instead of just swapping models and eyeballing the output.

<br>

</td>
<td width="50%" valign="top">

### 🐧 Reproducible systems

`NixOS` `Linux` `containers` `homelab`

My NixOS config stopped being just a config a while ago.

It's now where I experiment with **reproducibility, Wayland, containers, self-hosting, multi-machine setups**, and whatever else I've decided should probably be declarative.

<br>

</td>
</tr>
</table>

---

## 🌱 Open source

I tend to contribute upstream when a bug is easier to fix than work around.

Some recent examples:

- **[TokenTracker](https://github.com/xiufengsun/TokenTracker)** — Linux/NixOS and WSL support, provider integrations, parser work, and making token accounting less wrong.  
  [NixOS process + port detection](https://github.com/xiufengsun/TokenTracker/pull/579) · [Command Code limits](https://github.com/xiufengsun/TokenTracker/pull/594) · [Antigravity token accounting](https://github.com/xiufengsun/TokenTracker/pull/599) · [DeepSeek Harness v3](https://github.com/xiufengsun/TokenTracker/pull/614)

- **[Serpantinum](https://github.com/ilyamiro/serpantinum)** — fixes around Wayland desktop behavior and display-manager integration.  
  [SDDM compositor handling](https://github.com/ilyamiro/serpantinum/pull/282) · [autohide tray behavior](https://github.com/ilyamiro/serpantinum/pull/249)

- **Specht** — security tooling, vulnerability management, and the occasional fix that turns out to be considerably less small than expected.

A tiny bug turning into an afternoon spent understanding a completely different subsystem is, apparently, a recurring theme.

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
  Most of my actual coding happens in <strong>Go</strong> and <strong>Python</strong>. The rest tends to show up whenever the problem insists.
</p>

I usually end up building **backend services, research prototypes, developer tools, automation, benchmarks, dashboards**, and things I got tired of looking for.

<!--
Enable this once the personal website/blog has an RSS or Atom feed.

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
  <i>Building things, breaking things, and occasionally pretending that was the plan.</i>
</p>

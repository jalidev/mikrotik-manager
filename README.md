# HotSpot Manager — MikroTik Demo

A single-file hotspot management console in the style of a MikroTik operator panel: live user table with pause/resume, data counters, and a voucher card generator ready for print. No dependencies.

![Stack](https://img.shields.io/badge/stack-vanilla%20JS-c8f542) ![Deps](https://img.shields.io/badge/dependencies-0-c8f542)

## Features

- **User table** — profile, uptime, data used, status (active / paused / exhausted), with search
- **Pause / resume** per user
- **Voucher generator** — creates 6 printable card codes with profile and price in FCFA
- **Header stats** — active users, data today, cards sold, revenue today
- Router status bar modeled on a typical RB951 setup

## Run it

```bash
open index.html
```

Demo data only; not connected to a real router. A production version talks to the RouterOS API for live sessions, card printing and bandwidth policies.

---

*Demo project by [Jameel Ali](https://github.com/jalidev).*

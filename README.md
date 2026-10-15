<h1 align="center">Hi, I'm Daniel</h1>
<p align="center">
  Backend and systems developer
</p>

<p align="center">
  <a href="https://driver0.dev"><img src="https://img.shields.io/badge/driver0.dev-000000?style=flat&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://linkedin.com/in/drivera0"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

I mostly build backend software: databases, networked systems, and lately distributed systems in Go. I care about tools that fail loudly instead of being quietly wrong, and I like checking my work against real data before trusting it.

## What I'm building

**[Pulse](https://github.com/Drivera0/pulse)** · Go, TypeScript, WebRTC, TimescaleDB
Early warning for crowd crushes, using the phones already in the crowd. Instead of watching one phone at a time, it compares the timing of motion between neighbouring phones, which is how it tells a real push apart from dancing or a stadium wave. Built solo at StormHacks 2026. The Gemini API only writes the alert briefings; the Go server makes every detection decision. All numbers come from simulation, and the runs it missed are published next to the ones it caught.

**[whorl-touch](https://github.com/Drivera0/whorl-touch-public)** · KiCad, nRF52840, Python
A fingerprint-auth knob module for my NuPhy Air75 V3, with the full design history kept commit by commit. A Python preflight checks the board file before every fab order, after I learned the hard way that AI-written checkers can pass a broken design.

**[Places.ai](https://github.com/bcs-fotr/places-ai)** · React, TypeScript, Supabase
A trip planner built by a team of four in 24 hours at StormHacks 2025. I owned the frontend integration, including the drag-and-drop itinerary builder.

**[wedding-website-template](https://github.com/Drivera0/wedding-website-template)** · React, TypeScript, Tailwind, Supabase
A wedding site with personal invitations, RSVPs and an admin dashboard. Runs in demo mode with placeholder data.

## Other work I'd like to talk about

- **Networking:** five protocols built from the spec: an iterative DNS resolver in Java, a multithreaded POP3 server in C, a DICT client, a TCP sender with sliding-window flow control, and an IP router with longest-prefix match and NAT.
- **Backend:** a TypeScript/Express query engine and REST API, shipped by a team across four releases with code review and test suites.
- **Now learning:** distributed systems in Go and parallel computation in Erlang.

This code is private, but I'm happy to walk through any of it.

## Tools

<p>
  <img src="https://skillicons.dev/icons?i=go,py,ts,js,java,c,cpp,erlang&theme=dark" alt="Languages" />
  <br/>
  <img src="https://skillicons.dev/icons?i=nodejs,express,react,postgres,sqlite,supabase,githubactions,linux,git&theme=dark" alt="Tools" />
</p>

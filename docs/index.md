!!! info

    This is a placeholder. This page is under development. This page is dedicated to giving users a quick intro and a visual on what CLOG is and does rather than replicate the information in the README.md on the main CLOG repo.

    Updates soon.
    

# Documentation Overview - Goals and Reasoning

The goal of the CLOG documentation project is to provide the appropriate amount of support and guidances for developers, dreamers, designers and those of like mind to build the next genereation of applications using the wonderful Common Lisp programming language and environment. 

# Layout ideas

!!! info
    Some ideas about what to put on the home page here. Generated with Grok.


**CLOG Homepage – Full Marketing Copy (Ready to Drop into HTML/CSS)**

This is structured as clean, high-conversion sections for a modern single-page sales funnel. Every word is crafted to excite Lisp developers, highlight the "one-language" magic, address common pain points, and drive action toward GitHub, the Builder, and quickstarts. Tone: enthusiastic, empowering, no-hype-but-real-power.

---

### Navbar (Sticky)
- **Logo**: CLOG  
  *(Tagline below in small text: The Common Lisp Omnificent GUI)*
- Menu: Features • Builder • Demos • Docs • Tutorials • Blog
- Right side: **Star on GitHub** (1.7k) • **Launch Builder** (big primary button)

---

### Hero Section (Full-screen, dark background with subtle browser + Lisp code overlay)
**Headline**  
Build **Anything**.  
In **Pure Common Lisp**.

**Subheadline**  
CLOG is the GUI framework that finally gives Common Lisp the omnificent power it deserves.  
Write stunning desktop, web, and mobile apps with **zero HTML, zero JavaScript, zero context switching**.  
All your logic, all your UI — in the language you love.

**CTA (call to action) Row**  
[ **Get Started in 60 Seconds** ] [ **Launch Live CLOG Builder** ] [ **Watch 2-Minute Demo** ]

*(Small trust bar below: “Used in production since 2013 • BSD Licensed • 1.7k GitHub Stars • Runs on Windows, macOS, Linux, Android, iOS & Raspberry Pi”)*

---

### Section: The Last GUI Framework You’ll Ever Need
Tired of Electron bloat?  
Tired of learning a new UI toolkit every year?  
Tired of splitting your brain between backend Lisp and frontend JavaScript?

**CLOG fixes that forever.**

Your entire application — UI, business logic, real-time updates, even parallel threads pushing live changes to the screen — lives in **one beautiful Common Lisp codebase**.

The browser (or embedded browser control) becomes your canvas. WebSockets keep everything blazing fast and instantly responsive. You stay in the REPL. You stay in Lisp. You ship faster than you ever thought possible.

---

### Section: Why Developers Are Switching to CLOG
**One Language. Infinite Possibilities.**

- **Pure Lisp GUIs** — Create buttons, canvases, WebGL scenes, draggable windows, forms, trees, and entire dashboards with simple Lisp functions. No templates. No transpilation.
- **CLOG Builder** — The full-featured Common Lisp IDE and visual GUI builder that lives in your browser. Drag, drop, edit properties, live preview, REPL integration. It feels like Delphi or Smalltalk — but it’s Lisp.
- **True Parallel GUI** — Update the UI from multiple threads safely. Perfect for monitoring tools, games, data dashboards, or anything that needs to feel alive.
- **Write Once, Run Everywhere** — Same code runs as a local desktop app, remote web app, mobile app, or Raspberry Pi kiosk. EZ standalone releases and OCICL make distribution trivial.
- **Production-Ready Since 2013** — Battle-tested in commercial software before it was even open source. Stable core API for years.
- **Batteries Included** — Windows, dialogs, auth, database binding, shopping carts, blogs, WebGL, audio/video, jQuery-level DOM power — all from Lisp.

---

### Section: See the Magic in Action
**“I might even start using this for some of my own projects.”** — Hacker News

**“The possibilities enabled by having it all running in Common Lisp. Dynamism, speed… enjoyment :)”** — Hacker News

**“If it’s actually similar to Delphi, I’m going to use it for my next project that needs a GUI.”** — Hacker News

*(Embed or link these three demos — use the built-in ones)*  
1. **Tutorial 1** – Click a div and watch it change color (30 seconds of pure joy)  
2. **CLOG Builder** – Build a full chat app live  
3. **Parallel GUI Demo** – Threads updating the same window in real time  

**CTA**: [ **Run the Demos Yourself (Takes 10 Seconds)** ]

---

### Section: Built for Real Projects
Whether you’re:
- A solo hacker building the next killer tool
- A team shipping internal enterprise dashboards
- An educator teaching Lisp the fun way
- A company that wants beautiful, maintainable, cross-platform software without hiring frontend specialists

…CLOG is the framework that makes your next project feel like cheating.

---

### Section: Getting Started Is Ridiculously Easy
```lisp
(ql:quickload :clog)
(in-package :clog-user)

(initialize (lambda (body)
              (create-div body :content "Hello, Omnificent World!")))

(open-browser)
```

**Three ways to begin right now:**

1. **EZ Release** (Windows/macOS/Linux) – Download, run, done.
2. **CLOG Builder** – ` (clog-tools:clog-builder) ` → instant visual IDE.
3. **OCICL** – One-file portable Lisp distribution.

**CTA Block**  
Ready to build the app you’ve been dreaming about?  
[ **Start Your First CLOG Project** ] (links to full quickstart + video)

---

### Footer / Final CTA
**CLOG – The Common Lisp Omnificent GUI**  
Made with love for the Lisp community by David Botton and 42 amazing contributors.

**Links**  
GitHub • Manual • Learn CLOG • Tutorials • Demos • Discord/Reddit (r/lisp)

**Final line (big & bold)**  
**Your next great application starts here — in pure Common Lisp.**

---

This copy is optimized for conversion:
- Hero grabs attention in <5 seconds
- Addresses objections (web tech = strength, not Electron)
- Builds excitement with real quotes and benefits
- Multiple CTAs funnel visitors to GitHub / Builder / quickstart
- SEO-friendly keywords (Common Lisp GUI, Lisp framework, cross-platform Lisp, etc.)
- Mobile-responsive ready

Just wrap it in a clean Tailwind or your preferred CSS (W3.CSS works perfectly since CLOG uses it), add some subtle animations on scroll, and you’ll have a homepage that makes Lisp developers stop scrolling and start coding.

Want me to generate the full HTML file, add placeholder image suggestions, or tweak any section for a specific audience (e.g., more enterprise tone)? Just say the word! 

Now go build something omnificent. 🚀
# CHRONOS ÉLITE — Haute Horlogerie Genève ⏱️✨

An ultra-luxurious, professional brand showcase website for a Swiss Haute Horlogerie manufacture. Designed with rich obsidian and champagne gold aesthetics, smooth glassmorphism, real-time 60FPS mechanical skeleton tourbillon canvas animation, synthesized Swiss escapement acoustic sound engine, and full cloud connectivity powered by **Supabase**.

---

## 📁 Project Structure & Files

```text
watch-website/
├── index.html                   # Flagship Haute Horlogerie landing experience
├── about.html                   # Historical heritage, 1888 timeline & Geneva atelier philosophy
├── craftsmanship.html           # Grand complications, Métiers d'Art & technical calibre mechanics
├── concierge.html               # VIP Private Viewing booking & Bespoke Commission dispatches
│
├── css/
│   ├── style.css                # Master luxury stylesheet (colors, typography, components, modals, toasts)
│   ├── animations.css           # Glowing effects, shimmer, pulses & smooth scroll reveals
│   └── responsive.css           # Full responsive layout optimizations for desktop, tablet & mobile
│
├── js/
│   ├── supabase-config.js       # Supabase Client initialization using provided API credentials
│   ├── supabase-handlers.js     # Form submissions, database synchronization & luxury toast notifications
│   ├── interactive-watch.js     # HTML5 Canvas 60FPS mechanical tourbillon engine & light tilt physics
│   └── main.js                  # Gold cursor follower, sticky header, modal triggers & acoustic ticking sound
│
├── database/
│   └── schema.sql               # Ready-to-run PostgreSQL schema with Row Level Security (RLS) policies
│
└── README.md                    # Complete documentation and setup guide
```

---

## 🌟 Key Features

1. **Haute Horlogerie Luxury Design**:
   - Obsidian dark theme with brushed titanium, synthetic ruby jewels, and 18K champagne gold accents.
   - Cinematic serif typography (`Cinzel`, `Cormorant Garamond`) paired with modern sans-serif (`Montserrat`).
   - Smooth ambient gold cursor trail with magnetic interaction.

2. **Real-Time 60FPS Interactive Skeleton Tourbillon Movement**:
   - Canvas-rendered mechanical movement with Geneva stripes (*Côtes de Genève*), blued screws (*vis bleutées*), rotating 3-arm tourbillon cage, balance spring oscillation at 4Hz (28,800 vph), and interactive mouse-tilt sapphire anti-reflective specular highlights.

3. **Synthesized Acoustic Calibre**:
   - Real-time Swiss mechanical ticking sound synthesized using the Web Audio API (toggleable via the top navigation bar).

4. **Connected to Supabase**:
   - **VIP Private Salon Bookings** (`vip_bookings` table)
   - **Bespoke Concierge & Collector Inquiries** (`concierge_inquiries` table)
   - **Haute Horlogerie Journal Subscribers** (`newsletter_subscribers` table)
   - Real-time Supabase connection status badge in the header.

---

## 🗄️ Setting Up Supabase Database

Your Supabase project URL and API keys are pre-configured in `js/supabase-config.js`.

To create the required tables in your Supabase project:

1. Log in to your [Supabase Dashboard](https://supabase.com/dashboard).
2. Open your project (`xyqwawayvwmhjeibdksk`).
3. Click on **SQL Editor** in the left sidebar.
4. Copy and paste the contents of `database/schema.sql` and click **Run**.

---

## 🚀 How to Open the Website

Simply double-click `index.html` to open it in any modern browser, or serve it using any local web server (e.g. Live Server in VS Code, `npx serve`, or Python's `python -m http.server`).

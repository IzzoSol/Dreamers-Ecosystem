# Dreamers Climb

A dreamlike arcade-climbing game and a companion wellness dashboard.

## 🎮 Dreamers Climb

A vertical climbing / building / combat arcade game. Climb the dream-tower, place ladders, fight bosses, and compete.

| Build | File | Status |
|-------|------|--------|
| **v25 — Dream-Arcade Edition** | [`dreamers-climb-v25.html`](dreamers-climb-v25.html) | ⭐ **Current.** Revamped menu (animated starfield + parallax skyline), fixed sprite loading (relative paths), smooth UI. Base for the full gameplay revamp. |
| v24.0 | [`dreamers-climb-v24.0.html`](dreamers-climb-v24.0.html) | Archived. Building-upgrade beta. |
| v22 | [`dreamers-climb-v22.html`](dreamers-climb-v22.html) | Archived. |
| v15 | [`dreamers-climb-v15.html`](dreamers-climb-v15.html) | Archived. |

> **Run it:** open `dreamers-climb-v25.html` in a browser. Sprites load from `sprites/` (relative), so it works locally and from a clone of this repo. Older archived builds use legacy absolute paths and are kept for history only.

### Controls (default "Classic" scheme)
- **← →** move · **↑** climb / jump · **↓** down
- **Z** attack · **X** special · **Space** charged attack
- Switch schemes (WASD / Arrow-pad) in Settings.

## 🌙 Dreamer Dashboard

Wellness + creativity dashboard: recipes, workouts, practices, journaling, Day Builder, calendar.

- [`dreamer-dashboard-v6.39.html`](dreamer-dashboard-v6.39.html)

## 📁 Layout

```
dreamers-climb-v25.html      # current game build
dreamers-climb-v24.0.html    # archived builds
dreamers-climb-v22.html
dreamers-climb-v15.html
dreamer-dashboard-v6.39.html # wellness dashboard
sprites/                     # game art (loaded by v25 via relative paths)
docs/                        # design + build plans
```

## 🗺️ Roadmap

The v25 revamp is staged so each phase ships a working game:

- [x] **Phase 1** — relative sprite paths (fixes missing menu/loading art), Dream-Arcade menu redesign
- [ ] **Phase 2** — smooth platformer climbing (momentum, coyote-time, smooth camera)
- [ ] **Phase 3** — combat + VS mode (full moveset, knockback/hitstun, CPU AI, health bars)
- [ ] **Phase 4** — graphics polish (parallax, lighting, particles) + building variety

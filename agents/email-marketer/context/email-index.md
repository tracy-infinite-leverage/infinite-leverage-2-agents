# Email Sequence Index

## Sequence metadata

- **Campaign name:** New Lead Welcome
- **Applies to sources:** all (newsletter, contact)
- **Total stages:** 1 (expand as sequence grows)
- **Last updated:** 2026-05-10

---

## Stages

### Stage 0 — Welcome + Latest Post
- **Delay from signup:** immediately (`next_send_at = now()`)
- **Subject:** Welcome — glad you're here
- **Body (HTML):**

```html
<p>Hi {{name}},</p>

<p>Welcome — glad you're here.</p>

<p>I'm Tracy. I help founders build AI-powered businesses using Claude, GitHub, Vercel, and Supabase — the Infinite Leverage stack.</p>

<p>I just published something I think is worth your time:</p>

<p><strong><a href="https://infinite-leverage-2-hello-tracy.vercel.app">The Infinite Leverage Agenda</a></strong></p>

<p>Five tracks. Everything you need to run a modern AI business — mindset, infrastructure, building, team, and continuity.</p>

<p>More soon.</p>

<p>— Tracy</p>
```

- **Next stage delay:** none (single-stage sequence — set `status = 'completed'` after send)

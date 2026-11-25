# Team log

Newest at the bottom. 2-4 lines per session: date, area, what changed, what's next.

- 2026-11-25 · all · Working base created: 3D rooms, avatars + wardrobe, build mode, AI/keyword rooms, house types + onboarding, invites with housemate/guest codes, live presence, chat + nudges, points + streak + records, Connect Four, Tic-Tac-Toe, Draw & Guess, gallery, calendar, wish list, weather, movies, travel, link boards, notes, portals. Demo mode + Supabase backend. Next: each owner starts their kickoff prompt.
- 2026-11-25 · core · Moved to forks + safety nets: Claude Code scope guard hook (.claude/), PR checks (build + scope + smoke test), npm run smoke/scope/check, role titles and new kickoff prompts for all 5 roles, TEAM_START.md. Next: Game Director turns on Pages + ruleset, everyone forks and starts.
- 2026-11-25 · world · Day 1 (issue #2): avatars no longer walk through furniture (new src/world/walkGrid.js: blocked cells from build.footprint, rugs stay walkable, tap-to-walk finds a path around things, WASD slides along furniture, spawn never inside furniture). Camera: ⟳ rotate button (+ Q/E on desktop) turns the view 90°, the two near walls hide automatically, WASD follows the camera, the whole room fits any screen (phone portrait too), zoomed in the camera follows you. Pinch no longer counts as a tap. Name tags and speech bubbles sit closer to the head.
  Next: Day 2: smoother walk animation, face the tapped item, sit on sofas/chairs, emoji reactions.

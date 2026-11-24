# BE journey · Holo tube showcase (Zone 04)

Preview page for the holo tube showcase: the holo tube stand (4 tubes for now; set COUNT = 5 in index.html to add Long service awards) (left) and the 4K landscape LED/LCD (3840 × 2160, red outline = exact screen size).

- Start: the official Bapco logo reveal (`intro_reveal.mp4` = brand asset Bapco_LogoReveal_Dark_Short_16x9_UHD, native 3840 × 2160, audio removed) plays on the LED, then the logo glides to its idle position (`logo_stacked_reveal.png`, colors matched to the reveal) and the idle screen builds in. Press R to replay the intro.
- Attract loop: after 60 s with no touch or key press, the LED shows the logo reveal: the logo forms, holds while two slow light sweeps pass across it, eases out, and forms again (about 13 s per cycle). Picking a tube goes straight to that topic; any other touch returns to the idle screen. Press A to start it by hand. Change `IDLE_SEC` in index.html to adjust the time.
- Click a holo tube (or press 1–4) → its topic plays on the LED. Press 0 or "Idle screen" for the attract screen.
- Holo tube loops: `holo1.mp4` … `holo4.mp4` (seamless loops cut from the Magnific 3D animations, 1080×1920; medal = one-direction half turn, 4.4 s). They replace the placeholders automatically. Prompts: HOLO_TUBE_VISUAL_PROMPTS.md.
- Text: BE content sheet Rev 3 (Zone 4). Long service awards (5th tube) is hidden until the client finalizes 4 or 5.
- Photos: Bapco archive scans from the client WeTransfer (h1–h5), plus original Islander / Good Idea booklet covers (h*-doc).

GitHub Pages: upload all files to the repo root → Settings → Pages → Deploy from branch `main` / root.

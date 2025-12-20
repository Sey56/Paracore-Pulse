# 🎤 Day 02 — Paracore UI and CoreScript (≈ 5 minutes)

**Quick overview:** A short walkthrough of Paracore's interface, CoreScript basics, and creating your first script. Ideal for a ~5 minute voiceover. ✅

---

## Scene 1 — Reminder (0:00–0:30) 🔔
> **Narration:** “Before we start, make sure you’ve downloaded the latest Paracore build. It’s evolving quickly, so grab the newest version before following along.”

**Cue:** Short, friendly tone; invite listeners to prepare their workspace.

---

## Scene 2 — UI Tour (0:30–1:30) 🧭
> **Narration:** “Let’s look at the Paracore interface.”

**Visual guide (top-to-bottom, left-to-right):**
- **TopBar:** menu, app title, theme toggle, Revit connection, automation modes, help, and sign‑in options.
- **Sidebar (left):** load or unload *source folders* — these contain your scripts.
- **Gallery (center):** script cards, with search and the **New Script** button.
- **ScriptInspector (right):** tabs for **Parameters**, **Console**, **Table**, and **Metadata**.
- **FloatingCodeViewer:** read-only view of script code; click **Edit in VSCode** to open the full workspace.

**Delivery tip:** Pause briefly after introducing each area so the viewer can visually follow along.

---

## Scene 3 — CoreScript & Globals (1:30–2:30) ⚙️
> **Narration:** “CoreScript is just plain C# running inside Paracore. You’re not learning a new language — it’s the same C# you already know, with full IntelliSense.”

**Key points:**
- Familiar Revit objects are available: `Doc`, `UIDoc`, `UIApp`.
- `Transact` is a simple wrapper for Revit transactions.
- Helpful globals: `Print` and `Println` (console output), `Show` (renders tables in the Table tab).

**Sound/Style:** Confident and reassuring — emphasize that this is familiar territory for C# devs.

---

## Scene 4 — Creating a Script (2:30–4:00) ✍️
> **Narration:** “To create a script, first load a source folder from the Sidebar. Then in the Gallery, click **New Script**. Select it, and in the Inspector you’ll see the FloatingCodeViewer.”

**Steps (quick demo):**
1. Click **Edit in VSCode** — Paracore generates a temporary workspace with full IntelliSense.
2. With autosave on, edits in VSCode update the FloatingCodeViewer instantly.
3. Save and run: e.g., write a simple wall creation script (a few lines of C#), save, return to Paracore, and run it — the wall appears in Revit.

**Delivery tip:** Use an excited tone on the “run” moment — it's the payoff the viewer wants to see.

---

## Scene 5 — Wrap Up (4:00–5:00) 🏁
> **Narration:** “Today we explored the Paracore UI, explained CoreScript and its globals, and created our first script. It’s just C#, made easy.”

**Closing notes:**
- Tease Day 3: parameters (sliders, dropdowns, multi-selects) transforming scripts into interactive tools.
- End with a friendly sign-off: *See you in Day 3.*

---

## Notes for the narrator 💡
- Keep the overall pace conversational and slightly upbeat.
- Use short pauses between scenes to let on-screen highlights register.
- Emphasize practical wins (IntelliSense, autosave, instant run) — these are viewer takeaways.

---

*Edited for clarity, structure, and delivery. Remove duplicates and keep this file as the canonical Day 2 narration.*
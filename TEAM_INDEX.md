# Sky Aces Studio — Team Index
**Maintained by:** Jarvis
**Last updated:** 2026-04-19 (studio resumed after 9-day pause — see `Team Inbox/tasks/ACTIVATION_Studio_Resume_2026-04-19.md`)

---

## Team Members

| Name | Role | Status |
|------|------|--------|
| Nico Corleone | Senior Game Developer | Active |
| Sal Corrano | Senior 2D Game Artist / Pixel Art Specialist | Active |
| Marco Ferrante | Art Director | Active |
| Caruso | Sound Designer / Audio Producer | Active |
| Luca Corleone Ferretti | WW1 Historical Advisor | Active |
| Dante Marzano | Senior Game Designer | Active |
| Fixer (Enzo Conti) | Level / Campaign Designer | Active |
| Benny Falcone | 2D Game Animator | Active |
| Vito | Game Writer / Narrative Copywriter | Active |
| Enzo Caruso | Database Specialist | Active |
| Sunny | Senior Researcher | Active |
| Tom | HR Manager | Active |

---

## Activation Dispatches (2026-04-19)

| Agent | Ping file | Top priority |
|---|---|---|
| Nico | `PING_NICO_Resume_2026-04-19.md` | Wire Belgium parallax (re-escalated) |
| Sal | `PING_SAL_Resume_2026-04-19.md` | Belgium Mid A/B/C rework + Flanders poppy |
| Caruso | `PING_CARUSO_Resume_2026-04-19.md` | Ship MG `.wav` candidates — wave stalled on him |
| Dante | `PING_DANTE_Resume_2026-04-19.md` | Belgium UX + perf review (doc only) |
| Luca + Vito | `PING_LUCA_VITO_Resume_2026-04-19.md` | Belgium faction intros |
| Marco / Benny / Fixer / Enzo(DB) | `PING_SUPPORT_Roles_Resume_2026-04-19.md` | Oversight, VFX, configs, Firebase |

---

## Current Assignments (2026-04-10)

### Nico — Senior Game Developer
**Active tasks:**
- Wire Belgium mid/fore parallax layers into game (`TASK_NICO_Wire_Belgium_Assets.md`)
- SFX in-game trigger review with Caruso (`TASK_NICO_SFX_Review.md`)
- Various open code blockers (`FIX_Nico_*.md` files — review and triage)

**Recently completed:**
- Audio system wiring (14 SFX assets)
- Campaign map implementation (faction toggle, 5-state nodes)
- Burst button restart fix, engine pitch inversion fix
- Faction/plane mismatch fix on campaign start
- Node position recalibration for new parchment map

---

### Sal — Senior 2D Game Artist
**Active tasks:**
- Campaign map background (`CampaignMapBG.png`) — IN PROGRESS (refs delivered, Luca + Marco cleared, awaiting delivery)
- Node sprites 5 states (`assets/ui/map_nodes/`) — IN PROGRESS
- Belgium parallax layers — DELIVERED (mid/fore, sky, far variants all in place)

**Blockers cleared:**
- Luca historical review: PASSED with corrections (fake place names replaced)
- Marco style review: PASSED with corrections (no gradients, palette adjustment)

---

### Marco — Art Director
**Active tasks:**
- Style oversight on Sal's campaign map output (review when delivered)

**Recently completed:**
- Map reference style review (`REVIEW_Marco_MapStyle_v1.md`)

---

### Caruso — Sound Designer / Audio Producer
**Active tasks:**
- SFX quality review with Nico (`TASK_CARUSO_SFX_Review.md`)
- Reaper processing pass on all 14 SFX assets (`TASK_CARUSO_SFX_Processing.md`)
- Steady engine loop improvement (`TASK_CARUSO_SteadyEngine_2026-04-10.md`)
- Machine gun SFX pack (`TASK_CARUSO_MachineGun_SFX_Pack_2026-04-10.md`)

---

### Luca — WW1 Historical Advisor
**Active tasks:**
- Ongoing historical advisory for all campaign content

**Recently completed:**
- Map reference historical review (`REVIEW_Luca_MapHistorical_v1.md`) — cleared with corrections

---

### Dante — Senior Game Designer
**Active tasks:**
- Settings UX sign-off (`TASK_DANTE_VITO_Settings_UX_2026-04-10.md`)
- Design review of remaining 9 campaign configs

---

### Fixer (Enzo Conti) — Level / Campaign Designer
**Active tasks:**
- 9 remaining campaign configs (Marne through Hundred Days)
- Audio pacing co-lead (`TASK_FIXER_AudioPacing_CoLead_2026-04-09.md`)
- Machine gun campaign fit review (`TASK_FIXER_MachineGun_CampaignFit_2026-04-10.md`)

---

### Benny — 2D Game Animator
**Active tasks:**
- Belgium vertical slice VFX: flak burst, smoke trail, fire states, muzzle flash, death explosion
- All animations pending Marco sign-off before delivery to Nico

---

### Vito — Game Writer / Narrative Copywriter
**Active tasks:**
- Settings UX copy (`TASK_DANTE_VITO_Settings_UX_2026-04-10.md`)
- Mission briefings, pilot bios, aircraft descriptions — pending Luca research briefs per campaign

---

### Enzo (Database) — Database Specialist
**Active tasks:**
- Firebase/Firestore leaderboard implementation (`FIX_Nico_Firebase.md` — coordinate with Nico)
- Note: `DB_Design_Enzo.md` was written against Supabase — needs update to Firebase

---

### Sunny — Senior Researcher
**Available for:** Research briefs for new roles, WW1 topic research on request

---

### Tom — HR Manager
**Available for:** New hire proposals on request from Jarvis

---

## Open Blockers

| Blocker | Owner | Priority |
|---------|-------|----------|
| `sfx_ui_aircraft_unlock` — no good ElevenLabs result yet | Caruso | Low |
| DR.1 ace sprite alpha fixes (7 files) — were these done yesterday? | Marco / Sal | Confirm |
| Node map positions may need visual fine-tuning after recalibration | Nico | Medium |
| `CampaignMapBG.png` — pending Sal delivery | Sal | High |
| 9 remaining campaign data configs | Fixer | High |
| Armistice completion screen | Dante / Sal | Medium |
| German campaign content (Luftstreitkräfte perspective) | Luca / Fixer | Medium |

---

## Git Remote
`origin` → `https://github.com/L4stJedi/WONML.git` ✓ (corrected 2026-04-10)

Latest commit: `8526f1c` — faction/plane fix + node recalibration

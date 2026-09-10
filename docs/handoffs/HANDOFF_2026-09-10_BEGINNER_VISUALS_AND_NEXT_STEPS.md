# IsoTraining Handoff — 2026-09-10

## Purpose of this handoff

This document is intended to let a new ChatGPT conversation resume the IsoTraining project without relying on prior chat context. It captures what has been researched, what is locked, where the files are, what image assets exist, what has and has not been committed to GitHub, and the recommended next steps.

Repository: https://github.com/epaulson2/IsoTraining

---

## 1. Project goal

Build a practical, evidence-informed training manual and eventually a polished PDF/product around **Extreme Isometric / Iso-Extreme style training**, taking Jay Schroeder / EVO material as the historical core while clearly separating:

1. **Schroeder / EVO Original** — directly described in Schroeder/EVO material or documented by trainees who received EVO instruction.
2. **Schroeder-Derived** — close coaching interpretations and regressions that preserve the original concept.
3. **Evidence-Based Extensions** — modern applications built from isometric research, long-muscle-length principles, biomechanics, and practical tool use.

The project intentionally includes both:

- **Integrated bodyweight positions** for whole-body stabilization, coordination, and force distribution.
- **Targeted strap-assisted positions** for precise joint-angle control and concentrated force production.

The user has an adjustable **non-elastic strap with handles**, and the system is designed to leverage it where useful without replacing the awkward / integrated bodyweight holds.

---

## 2. Core training philosophy already locked

### Extreme Iso is not passive holding
The defining principle is active intent in a demanding position. In many classic Schroeder positions, the trainee is trying to pull deeper or create force while the visible body position changes little or not at all.

### Duration and intensity are separate variables
The system deliberately separates:

- **Position / Extreme-Iso work** — longer, submaximal-to-hard holds emphasizing geometry, active intent, positional control, and accumulated time.
- **High-intent targeted isometrics** — shorter, higher-force efforts, usually strap- or support-assisted, at selected joint angles.

A 3–5 minute position hold is therefore not treated as a maximal-effort isometric, and a high-intent isometric is not expected to last minutes.

### Progression hierarchy

Technique → active intent → bout duration → accumulated time → effort → leverage/load → Extreme Slow → force absorption → rebound/reactive work

### Advancement is competency-based
Do not advance merely because a calendar week has elapsed. Progress only when the current prescription is performed cleanly in repeated sessions with correct geometry, force direction, controlled exit, and no sharp pain, pinching, numbness, or tingling.

---

## 3. Locked exercise-library architecture

The project uses **13 movement / position families**, not a flat list of unrelated exercises.

1. Split stance / lunge
2. Squat / knee-dominant
3. Hip hinge / hamstring
4. Horizontal push / chest
5. Vertical push / triceps
6. Vertical pull / scapular-lat
7. Horizontal pull / row
8. Elbow flexion / biceps
9. Calf / ankle plantar flexion
10. Adductor / lateral stance
11. Hip-flexor / long split
12. Shoulder rotation / stabilization
13. Anterior chain / quadriceps

Canonical library file:

- `docs/02-exercises/EXERCISE_MASTER_LIST.md`

Whole-library audit:

- `docs/01-research/WHOLE_LIBRARY_TECHNICAL_AUDIT_2026-09-10.md`

Project index:

- `docs/PROJECT_INDEX.md`

---

## 4. Tier system after comprehensive audit

### Tier A — Programming Core
Routine beginner/intermediate programming should primarily use these.

1. Integrated Extreme Lunge — EVO Original
2. Iso-Extreme Wall Squat — EVO Original
3. Standing Glute-Ham / Standing Hamstring Iso — EVO Original
4. Extreme Push-Up — EVO Original
5. Scapular Pull-Up / Active Hang Extreme Iso — EVO Original
6. Preacher Curl Extreme Iso — EVO Original
7. Strap Extreme Chest Press — Evidence-Based Extension
8. Body-Supported Row Iso — Evidence-Based Extension
9. Straight-Knee Calf Iso — Evidence-Based Extension
10. Bent-Knee Calf Iso — Evidence-Based Extension
11. Supported Lateral-Lunge / Cossack Iso — Evidence-Based Extension
12. Strap Overhead Triceps Iso — Evidence-Based Extension
13. Strap External-Rotation Iso — Evidence-Based Extension
14. Supported Sissy-Squat Iso — Schroeder-derived / later associated use

### Tier B — Secondary / Developmental
Used after competency in the Tier A pattern or when a specific need justifies them.

Includes single-leg squat, standing push-off, assisted hang, strap row, strap curl, Copenhagen, hip-flexor variants, standing straight-leg raise, strap knee-extension, dip, strap lat pull, overhead shoulder stability.

### Tier C — Optional / Accessory
Redundant or specialized variants retained for completeness but not routine program content.

Includes strap split-stance, strap knee-dominant, strap hinge, strap hamstring curl, strap overhead press, long-arm strap row, strap calf, strap adduction, rear-leg active split as a cue/variation, and strap internal rotation.

---

## 5. Important biomechanical correction from audit

The historical **Standing Straight-Leg Raise** should **not** be described as a long-length quadriceps exercise. Hip flexion plus knee extension does not place rectus femoris at a globally long length. It is better treated as an **anterior-chain / hip-flexor–quadriceps control position**.

The **Supported Sissy-Squat** is the primary long-length quadriceps anchor in the final library.

---

## 6. Learn Mode system

Every exercise should have two representations:

### Learn Mode
Detailed teaching sequence used before the athlete is expected to perform the exercise fluently.

The master teaching order is:

Geometry → pressure distribution → working depth → primary action → opposing/stabilizing action → combined force vectors → Extreme-Iso intent → short competency hold → controlled exit

Every Learn Mode should include:

- visual checkpoint — does the body look right?
- tension checkpoint — is the intended musculature carrying the work?
- intent checkpoint — is the athlete producing the correct internal action?
- common setup errors
- regression hierarchy
- competency hold
- exit practice

Template:

- `docs/03-position-learning/POSITION_LEARNING_TEMPLATE.md`

### Workout Mode
After competence, reduce the instruction to:

- exercise name
- prescribed duration / intensity
- no more than ~3 critical cues
- optional regression / variation note

---

## 7. Exercise-family files already built

All 13 family files exist under:

- `docs/02-exercises/families/`

Key files:

- `01_SPLIT_STANCE_LUNGE_FAMILY.md`
- `02_SQUAT_KNEE_DOMINANT_FAMILY.md`
- `03_HIP_HINGE_HAMSTRING_FAMILY.md`
- `04_HORIZONTAL_PUSH_CHEST_FAMILY.md`
- `05_VERTICAL_PUSH_TRICEPS_FAMILY.md`
- `06_VERTICAL_PULL_SCAPULAR_LAT_FAMILY.md`
- `07_HORIZONTAL_PULL_ROW_FAMILY.md`
- `08_ELBOW_FLEXION_BICEPS_FAMILY.md`
- `09_CALF_ANKLE_FAMILY.md`
- `10_ADDUCTOR_LATERAL_STANCE_FAMILY.md`
- `11_HIP_FLEXOR_LONG_SPLIT_FAMILY.md`
- `12_SHOULDER_ROTATION_STABILIZATION_FAMILY.md`
- `13_QUADRICEPS_LONG_LENGTH_FAMILY.md` (conceptually renamed to Anterior Chain / Quadriceps after audit)

The first three families also received a dedicated deeper validation pass:

- `docs/01-research/FIRST_THREE_FAMILIES_DEEP_VALIDATION_2026-09-10.md`

Important findings from that pass:

### Extreme Lunge
Strong historical support for:

- long split stance
- front shin roughly vertical
- front thigh around parallel in the deeper version
- front hamstring drag-back intent
- active rear-leg contribution
- “scissor” relationship between the legs
- tall / controlled torso
- full front-foot pressure

### Extreme Push-Up
Strong historical support for:

- deep position
- forearms near vertical
- rigid trunk
- active shoulders
- actively pulling deeper rather than passively hovering

### Scapular Active Hang
Confirmed as a core EVO position, but exact scapular geometry in surviving source material is less precise. The current file intentionally avoids overclaiming exact depression/retraction rules.

---

## 8. Programming architecture already locked

Canonical programming principles:

- `docs/04-programming/PROGRAMMING_PRINCIPLES.md`

Program-level architecture:

- `docs/04-programming/PROGRAM_LEVEL_ARCHITECTURE.md`

### Effort scale

- 3–4/10: learning / rehearsal
- 5–6/10: foundational position work
- 7–8/10: hard training with technical reserve
- 9/10: advanced high-intent work
- 10/10: true maximal effort, rarely needed and not used by beginners

### Hold framework

#### Learn Mode
- 6–15 sec
- 3–5/10 effort

#### Beginner position work
- 10–30 sec per bout
- usually 2–4 bouts
- about 30–90 sec accumulated per exercise

#### Intermediate position work
- 20–45 sec per bout
- usually 2–4 bouts
- about 60–150 sec accumulated per exercise

#### Advanced position work
- 30–60+ sec per bout where appropriate
- selected Schroeder-style positions may eventually reach 2–5 min accumulated

#### High-intent targeted work
- 5–10 sec per effort
- usually 3–5 efforts

### Weekly frequency

- Beginner: 3 sessions/week
- Intermediate: 3–4 sessions/week
- Advanced: typically 4 sessions/week

### Default block rhythm

For programs longer than 4 weeks:

- Weeks 1–3 build
- Week 4 consolidate
- Weeks 5–7 build
- Week 8 consolidate/reassess

Consolidation reduces accumulated time by roughly 30–40% and high-intent set count by about one third while preserving technique and frequency.

---

## 9. Beginner program is complete

File:

- `docs/04-programming/beginner/BEGINNER_8_WEEK_PROGRAM.md`

Structure:

- 8 weeks
- 3 nonconsecutive full-body sessions per week
- Weeks 1–2: Learn Mode / position acquisition
- Week 3: first build
- Week 4: consolidation
- Weeks 5–7: build accumulated time + introduce limited targeted strap work
- Week 8: consolidation and readiness reassessment rather than max testing

Repeated beginner anchors:

- Extreme Lunge
- Wall Squat
- Standing Hamstring
- Extreme Push-Up
- Body-Supported Row
- Scapular Active Hang

Supporting exposures:

- Straight-Knee Calf
- Bent-Knee Calf
- Lateral Lunge / Cossack
- Strap Chest Press
- Strap External Rotation
- Preacher Curl
- Strap Overhead Triceps
- Supported Sissy-Squat

Beginner graduation target:

- reproducible Tier A setups
- 20–30 sec clean integrated holds
- roughly 60–90 sec quality accumulated time on main positions
- short strap efforts around 7/10 without posture changes
- correct force direction and no passive joint loading
- normal recovery across 3 weekly sessions

---

## 10. Beginner visual package completed

A complete **24-image beginner visual set** has been generated.

### 14 canonical exercise plates

1. Extreme Lunge
2. Wall Squat
3. Standing Hamstring
4. Extreme Push-Up
5. Body-Supported Row
6. Scapular Active Hang
7. Straight-Knee Calf Iso
8. Bent-Knee Calf Iso
9. Lateral Lunge / Cossack
10. Strap Chest Press
11. Strap External Rotation
12. Preacher Curl
13. Strap Overhead Triceps
14. Supported Sissy-Squat

These use a consistent visual language:

- white background
- dark/navy typography
- athletic male model
- red/orange force arrows
- labeled positional checkpoints
- bottom section with Workout Cues and Common Errors

### 6 Learn Mode visuals

1. Extreme Lunge — Learn Mode
2. Wall Squat — Learn Mode
3. Standing Hamstring — Learn Mode
4. Extreme Push-Up — Learn Mode
5. Scapular Active Hang — Learn Mode
6. Strap Chest Press — Learn Mode

These include step-by-step learn sequences and setup errors.

### 3 Session maps

- Beginner Program — Session A
- Beginner Program — Session B
- Beginner Program — Session C

### 1 diagram/force legend

- How to Read the Diagrams

Explains:

- primary force / main intent arrow
- opposing force / scissor action arrows
- position checkpoint marker
- workout-cue section
- common-error section

---

## 11. Beginner visual asset manifest in GitHub

Committed file:

- `assets/beginner/README.md`

Direct URL:

https://github.com/epaulson2/IsoTraining/blob/main/assets/beginner/README.md

Canonical intended repo structure:

```text
assets/
  beginner/
    exercise-plates/
      01_extreme_lunge.webp
      02_wall_squat.webp
      03_standing_hamstring.webp
      04_extreme_push_up.webp
      05_body_supported_row.webp
      06_scapular_active_hang.webp
      07_straight_knee_calf.webp
      08_bent_knee_calf.webp
      09_lateral_lunge_cossack.webp
      10_strap_chest_press.webp
      11_strap_external_rotation.webp
      12_preacher_curl.webp
      13_strap_overhead_triceps.webp
      14_supported_sissy_squat.webp
    learn-mode/
      LM01_extreme_lunge.webp
      LM02_wall_squat.webp
      LM03_standing_hamstring.webp
      LM04_extreme_push_up.webp
      LM05_scapular_active_hang.webp
      LM06_strap_chest_press.webp
    session-maps/
      session_A.webp
      session_B.webp
      session_C.webp
    guides/
      how_to_read_diagrams.webp
```

### Important limitation

The GitHub connector available in this conversation did **not** expose a safe direct binary-file upload action for the generated image files. The image binaries were therefore **not individually committed to the repo** during this conversation.

Instead, all 24 visuals were organized and packaged locally in a GitHub-ready ZIP:

- `IsoTraining_Beginner_Visual_Pack.zip`

The ZIP was generated in the working environment at:

- `/mnt/data/IsoTraining_Beginner_Visual_Pack.zip`

In the originating conversation, it was downloadable with:

- `sandbox:/mnt/data/IsoTraining_Beginner_Visual_Pack.zip`

A new conversation may not automatically retain that local file unless the user re-uploads it or the environment still exposes the prior attachment. If the ZIP is available, extract its contents directly into `assets/beginner/` and commit them without renaming, because the folder and filenames already match the GitHub manifest.

If the ZIP is unavailable in the new conversation, the visual filenames and required content are documented here and in `assets/beginner/README.md`, so the assets can be regenerated or re-uploaded without ambiguity.

### Asset policy

- Individual plates are canonical.
- Collage/contact-sheet images generated during experimentation are **not canonical source assets**.
- Optimized repository copies are intended to use WebP.
- Source PNGs are preferred as master-quality assets for future PDF assembly.

---

## 12. Visual QA notes / caution for next conversation

The generated visuals are strong overall, but before final PDF publication they should receive a **visual QA pass against the written exercise specs**. AI-generated instructional anatomy/position images can occasionally contain subtle setup inconsistencies or label/arrow inaccuracies even when they look polished.

Recommended QA for each plate:

1. Compare body geometry against the corresponding family markdown file.
2. Verify all force arrows match the intended internal action.
3. Verify the image does not accidentally show a passive position where active tension is intended.
4. Check that the written cue wording matches the locked terminology in Workout Mode.
5. Correct any misleading anchor/strap routing before publication.
6. Preserve the provenance label accurately (EVO Original / derived / extension).

Do not assume visual polish alone means the exercise mechanics are perfect.

---

## 13. What is complete vs incomplete

### Complete enough to lock

- project architecture
- provenance framework
- 13 exercise families
- Learn Mode architecture
- exercise-library technical audit
- Tier A/B/C hierarchy
- programming principles
- beginner/intermediate/advanced level architecture
- full 8-week beginner program
- 14 beginner exercise plates
- 6 Learn Mode visuals
- 3 beginner session maps
- 1 force-arrow legend
- GitHub asset manifest

### Not yet complete

- actual binary image files committed to GitHub
- intermediate week-by-week program
- advanced week-by-week / method progression
- final visual QA pass
- final manual chapter prose / intro material
- final PDF layout and assembly
- references/bibliography formatted for publication
- potential legal/disclaimer page

---

## 14. Recommended next steps — exact order

### NEXT STEP 1 — Preserve the image binaries in GitHub

If the ZIP is accessible:

1. Extract `IsoTraining_Beginner_Visual_Pack.zip`.
2. Copy its folders into `assets/beginner/`.
3. Commit the binary assets to the repo using the exact names from the manifest.
4. Verify that every path in `assets/beginner/README.md` resolves.

If binary upload remains unavailable through the current connector, the user may need to upload the ZIP to GitHub manually or use a local git clone / browser workflow. Do not falsely claim the images are committed until they are actually present in the repository.

### NEXT STEP 2 — Run visual QA

Create a checklist or markdown audit for all 24 images. Compare each against:

- the family technical spec
- Workout Mode cues
- Learn Mode logic
- force direction
- strap routing

Correct only the images that genuinely need changes.

### NEXT STEP 3 — Build the intermediate program

Use:

- `PROGRAMMING_PRINCIPLES.md`
- `PROGRAM_LEVEL_ARCHITECTURE.md`
- beginner graduation criteria
- Tier A core + selected Tier B

Target intermediate design:

- 3–4 sessions/week
- 5–7 exercises/session
- integrated + targeted balance
- 20–45 sec position holds
- 60–150 sec accumulated time
- 5–10 sec targeted high-intent efforts
- later intermediate introduction of **Extreme Slow** only when competency gates are met

### NEXT STEP 4 — Build advanced progression

Advanced progression should add methods before simply adding more exercises:

1. longer accumulated Extreme-Iso work
2. increased leverage / loading
3. Extreme Slow
4. controlled force absorption
5. rebound / reactive pairing
6. task/sport-specific expression

Do not introduce reactive work merely by calendar week.

### NEXT STEP 5 — Assemble the beginner manual / PDF

Only after visual QA and the program are stable, assemble the beginner manual with:

1. title / intro
2. what Extreme Isometrics are
3. Schroeder/EVO historical context
4. modern evidence and what is / is not established
5. how to read the diagrams
6. Learn Mode explanation
7. exercise tutorials
8. beginner program structure
9. week-by-week plan
10. session maps
11. progress / readiness criteria
12. safety / stop criteria
13. references

The PDF should clearly distinguish historical Schroeder/EVO material from project-developed extensions.

---

## 15. Suggested instruction to give the next ChatGPT conversation

Copy/paste this:

> Continue the IsoTraining project from the handoff at `docs/handoffs/HANDOFF_2026-09-10_BEGINNER_VISUALS_AND_NEXT_STEPS.md` in `epaulson2/IsoTraining`. Read that handoff, the project index, programming principles, program-level architecture, exercise master list, and beginner program before making changes. Preserve the existing provenance rules and integrated-vs-targeted philosophy. First verify whether the 24 beginner visual binaries are actually present in `assets/beginner/`; if not, help me get them committed. Then run a visual QA pass against the exercise specs before moving on to the intermediate program.

---

## 16. Key URLs

Repository:

https://github.com/epaulson2/IsoTraining

Project index:

https://github.com/epaulson2/IsoTraining/blob/main/docs/PROJECT_INDEX.md

Exercise master list:

https://github.com/epaulson2/IsoTraining/blob/main/docs/02-exercises/EXERCISE_MASTER_LIST.md

Programming principles:

https://github.com/epaulson2/IsoTraining/blob/main/docs/04-programming/PROGRAMMING_PRINCIPLES.md

Program-level architecture:

https://github.com/epaulson2/IsoTraining/blob/main/docs/04-programming/PROGRAM_LEVEL_ARCHITECTURE.md

Beginner 8-week program:

https://github.com/epaulson2/IsoTraining/blob/main/docs/04-programming/beginner/BEGINNER_8_WEEK_PROGRAM.md

Beginner visual manifest:

https://github.com/epaulson2/IsoTraining/blob/main/assets/beginner/README.md

Whole-library audit:

https://github.com/epaulson2/IsoTraining/blob/main/docs/01-research/WHOLE_LIBRARY_TECHNICAL_AUDIT_2026-09-10.md

First-three deep validation:

https://github.com/epaulson2/IsoTraining/blob/main/docs/01-research/FIRST_THREE_FAMILIES_DEEP_VALIDATION_2026-09-10.md

---

## 17. Final state at handoff

The project is in a strong state for continuation.

The **exercise library and beginner programming are structurally complete**, the **programming framework is locked**, and the **beginner visual package is complete as a generated asset set**. The most important operational task is to ensure the actual image binaries are committed to GitHub and QA-checked before the PDF is assembled.

After that, the next major content milestone is the **intermediate program**, followed by the advanced progression and final manual/PDF assembly.

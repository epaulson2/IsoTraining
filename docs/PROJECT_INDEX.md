# IsoTraining Project Index

## Current phase

**Phase 2 complete — Programming Architecture locked.**

Phase 1 established and audited the exercise library. Phase 2 now defines the programming rules that all beginner, intermediate and advanced plans must follow.

## Architecture and templates

- [Exercise Library Architecture](00-project/EXERCISE_LIBRARY_ARCHITECTURE.md)
- [Exercise Specification Template](02-exercises/EXERCISE_SPEC_TEMPLATE.md)
- [Position Learning Template](03-position-learning/POSITION_LEARNING_TEMPLATE.md)
- [Exercise Master List](02-exercises/EXERCISE_MASTER_LIST.md) — canonical post-audit tiered inventory

## Programming source of truth

- [Programming Principles](04-programming/PROGRAMMING_PRINCIPLES.md) — intensity, duration, accumulated time, rest, frequency, progression, stop criteria, pairing logic and deload rules
- [Program-Level Architecture](04-programming/PROGRAM_LEVEL_ARCHITECTURE.md) — beginner, intermediate and advanced structure

## Completed movement families

1. [Split Stance / Lunge Family](02-exercises/families/01_SPLIT_STANCE_LUNGE_FAMILY.md)
2. [Squat / Knee-Dominant Family](02-exercises/families/02_SQUAT_KNEE_DOMINANT_FAMILY.md)
3. [Hip Hinge / Hamstring Family](02-exercises/families/03_HIP_HINGE_HAMSTRING_FAMILY.md)
4. [Horizontal Push / Chest Family](02-exercises/families/04_HORIZONTAL_PUSH_CHEST_FAMILY.md)
5. [Vertical Push / Triceps Family](02-exercises/families/05_VERTICAL_PUSH_TRICEPS_FAMILY.md)
6. [Vertical Pull / Scapular-Lat Family](02-exercises/families/06_VERTICAL_PULL_SCAPULAR_LAT_FAMILY.md)
7. [Horizontal Pull / Row Family](02-exercises/families/07_HORIZONTAL_PULL_ROW_FAMILY.md)
8. [Elbow Flexion / Biceps Family](02-exercises/families/08_ELBOW_FLEXION_BICEPS_FAMILY.md)
9. [Calf / Ankle Family](02-exercises/families/09_CALF_ANKLE_FAMILY.md)
10. [Adductor / Lateral-Stance Family](02-exercises/families/10_ADDUCTOR_LATERAL_STANCE_FAMILY.md)
11. [Hip Flexor / Long-Split Family](02-exercises/families/11_HIP_FLEXOR_LONG_SPLIT_FAMILY.md)
12. [Shoulder Rotation / Stabilization Family](02-exercises/families/12_SHOULDER_ROTATION_STABILIZATION_FAMILY.md)
13. [Anterior Chain / Quadriceps Family](02-exercises/families/13_QUADRICEPS_LONG_LENGTH_FAMILY.md)

## Research notes

- [First Three Families — Deep Validation](01-research/FIRST_THREE_FAMILIES_DEEP_VALIDATION_2026-09-10.md)
- [Whole-Library Technical Audit](01-research/WHOLE_LIBRARY_TECHNICAL_AUDIT_2026-09-10.md)

## Locked design decisions

- Organize the system by 13 movement / position families rather than a flat exercise list.
- Preserve both **integrated bodyweight Extreme Isos** and **targeted strap-assisted Extreme Isos**.
- Every exercise receives detailed **Learn Mode** and compact **Workout Mode** treatment.
- Learn Mode separates **geometry → pressure → working depth → tension → intent → competency hold → exit**.
- Provenance remains explicit:
  - Schroeder / EVO Original
  - Schroeder-Derived
  - Evidence-Based Extension
- Programming uses three exercise tiers:
  - **Tier A — Programming Core**
  - **Tier B — Secondary / Developmental**
  - **Tier C — Optional / Accessory**
- Historical cues are preserved without automatically accepting speculative physiological explanations.
- “Extreme” means the deepest/longest actively controllable position, not forced passive range.
- Duration and contraction intensity are separate programming variables.

## Locked programming model

### Two distinct training modes

1. **Position / Extreme-Iso work** — longer, submaximal-to-hard holds emphasizing position, active intent, stabilization and accumulated time.
2. **High-intent targeted isometrics** — short, high-force efforts at controlled joint angles, usually with straps/supports.

These are not interchangeable and should not automatically use the same duration or effort prescription.

### Default level structure

- **Beginner:** 3 full-body sessions/week; 4–6 exercises/session; integrated-dominant; holds mostly 10–30 sec; 30–90 sec accumulated per exercise.
- **Intermediate:** 3–4 sessions/week; 5–7 exercises/session; balanced integrated + targeted work; holds mostly 20–45 sec; 60–150 sec accumulated.
- **Advanced:** typically 4 sessions/week; block-specific method emphasis; selected holds 30–60+ sec and 2–5 min accumulated where appropriate; short high-intent efforts remain separate.

### Effort conventions

- Learn Mode: 3–5/10
- Foundation position work: 5–6/10
- Hard training work: 7–8/10
- Advanced high-intent work: ~9/10
- 10/10 maximal efforts are rarely needed and are not used by beginners

### Progression hierarchy

**Technique → active intent → bout duration → accumulated time → effort → leverage/load → Extreme Slow → force absorption → rebound/reactive work**

### Progression gate

A trainee progresses only when the current prescription is completed cleanly in at least two sessions with stable geometry, correct force direction, controlled exit and no sharp pain/pinching/numbness/tingling.

### Deload / consolidation convention

Default for plans longer than four weeks: **3 build weeks + 1 consolidation week**. Consolidation reduces accumulated time by roughly 30–40% and high-intent sets by about one third while preserving technique and frequency.

## Major audit changes already incorporated

- Retained all 13 families for educational completeness.
- Reduced routine programming to a smaller Tier A core.
- Demoted redundant strap variations rather than allowing targeted work to crowd out integrated positions.
- Kept the Extreme Push-Up + Strap Chest Press pairing because they provide meaningfully different integrated vs targeted benefits.
- Kept straight-knee + bent-knee calf work as distinct variants.
- Kept lateral-lunge/Cossack + Copenhagen as complementary integrated/targeted adductor choices; strap adduction is optional.
- Kept external-rotation shoulder work as the primary targeted shoulder-rotation accessory; internal rotation is optional.
- Demoted the strap overhead press because it adds little unique value relative to push-up/dip/triceps/shoulder-stability work.
- Reclassified the historical Standing Straight-Leg Raise as an **anterior-chain position**, not a long-length quadriceps exercise.
- Supported Sissy-Squat is now the primary long-length quadriceps exercise in that family.

## Next phase

**Phase 3 — Actual Programs**

Recommended order:

1. Build the beginner program week by week.
2. Validate exercise order, session length and weekly balance against the locked rules.
3. Build the intermediate program.
4. Build the advanced progression, introducing Extreme Slow and later force-absorption / rebound work only after competency gates.
5. Develop illustration / force-map requirements from the final Learn Mode specs.
6. Begin manual / PDF assembly only after the programs are stable.

## Publication principle

The final PDF/manual must clearly distinguish historical Schroeder/EVO instruction from modern evidence-based extensions and must never use speculative physiological explanations as established fact.

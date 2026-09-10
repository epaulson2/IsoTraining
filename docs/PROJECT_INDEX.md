# IsoTraining Project Index

## Current phase

**Phase 1 — Exercise Library + Position Learning System**

Goal: validate movement families and build complete technical specifications before writing final beginner / intermediate / advanced programming.

## Architecture and templates

- [Exercise Library Architecture](00-project/EXERCISE_LIBRARY_ARCHITECTURE.md)
- [Exercise Specification Template](02-exercises/EXERCISE_SPEC_TEMPLATE.md)
- [Position Learning Template](03-position-learning/POSITION_LEARNING_TEMPLATE.md) — refined to separate geometry, pressure, tension, intent, regression hierarchy and exit practice.

## Validated / active family drafts

1. [Split Stance / Lunge Family](02-exercises/families/01_SPLIT_STANCE_LUNGE_FAMILY.md)
2. [Squat / Knee-Dominant Family](02-exercises/families/02_SQUAT_KNEE_DOMINANT_FAMILY.md)
3. [Hip Hinge / Hamstring Family](02-exercises/families/03_HIP_HINGE_HAMSTRING_FAMILY.md)
4. [Horizontal Push / Chest Family](02-exercises/families/04_HORIZONTAL_PUSH_CHEST_FAMILY.md)
5. [Vertical Pull / Scapular-Lat Family](02-exercises/families/06_VERTICAL_PULL_SCAPULAR_LAT_FAMILY.md)

## Research notes

- [First Three Families — Deep Validation](01-research/FIRST_THREE_FAMILIES_DEEP_VALIDATION_2026-09-10.md)

## Core design decisions

- Organize the system by movement / position families rather than a flat exercise list.
- Preserve both **integrated bodyweight Extreme Isos** and **targeted strap-assisted Extreme Isos**.
- Every exercise receives a detailed **Learn Mode** and a compact **Workout Mode**.
- Learn Mode explicitly separates **geometry → pressure → tension → intent** before a competency hold.
- Every movement / cue is labeled by provenance:
  - Schroeder / EVO Original
  - Schroeder-Derived
  - Evidence-Based Extension
- Extensions must be technically validated before entering the final library.
- Programming is downstream of exercise validation, not the other way around.
- Historical cues are preserved without automatically accepting speculative physiological explanations attached to them.

## Current validation notes

- **Lunge:** strong historical support for long split stance, front-shin control, front-hamstring drag-back intent and active rear-leg contribution.
- **Wall Squat:** strong direct Schroeder description — upright torso, lower legs perpendicular, feet flat, continually pull deeper.
- **Single-Leg Squat:** strong historical evidence for specific box / bench geometry, but surviving sources contain more than one implementation; variants remain explicitly separated.
- **Standing Glute-Ham / Standing Hamstring:** strong historical support as a core EVO position; current draft emphasizes hip hinge, soft knees, active downward pull, and maintained posterior-chain tension. Toe-elevated / heel-biased versions remain labeled as later coaching variants rather than canonical rules.
- **Push-Up:** strong historical support for deep position, vertical forearms and active pulling into the bottom position rather than passive hovering.
- **Scapular Pull-Up:** confirmed as a core EVO position, but exact scapular geometry remains less certain and is therefore intentionally conservative in the draft.

## Next recommended work

1. Build and validate the **vertical push / triceps family**.
2. Then build:
   - horizontal pull / row;
   - elbow flexion / biceps;
   - calf / ankle;
   - adductor / lateral stance;
   - hip-flexor / long split;
   - shoulder rotation / stabilization;
   - quadriceps long-length / straight-leg raise / sissy-squat decision.
3. Revisit the Exercise Specification Template after 1–2 more families to ensure it captures every recurring technical field.
4. Only after the final exercise library is validated, create beginner, intermediate and advanced programming.

## Publication principle

Draft technical material should remain clearly labeled as provisional until source review and biomechanical validation are complete. The final PDF/manual should never blur historical Schroeder instruction with modern extensions developed in this project.

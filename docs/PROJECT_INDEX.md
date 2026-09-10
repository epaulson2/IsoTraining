# IsoTraining Project Index

## Current phase

**Phase 1 — Exercise Library + Position Learning System**

Goal: validate movement families and build complete technical specifications before writing final beginner / intermediate / advanced programming.

## Architecture and templates

- [Exercise Library Architecture](00-project/EXERCISE_LIBRARY_ARCHITECTURE.md)
- [Exercise Specification Template](02-exercises/EXERCISE_SPEC_TEMPLATE.md)
- [Position Learning Template](03-position-learning/POSITION_LEARNING_TEMPLATE.md)

## Completed initial family drafts

1. [Split Stance / Lunge Family](02-exercises/families/01_SPLIT_STANCE_LUNGE_FAMILY.md)
2. [Horizontal Push / Chest Family](02-exercises/families/04_HORIZONTAL_PUSH_CHEST_FAMILY.md)
3. [Vertical Pull / Scapular-Lat Family](02-exercises/families/06_VERTICAL_PULL_SCAPULAR_LAT_FAMILY.md)

## Core design decisions

- Organize the system by movement / position families rather than a flat exercise list.
- Preserve both **integrated bodyweight Extreme Isos** and **targeted strap-assisted Extreme Isos**.
- Every exercise receives a detailed **Learn Mode** and a compact **Workout Mode**.
- Every movement / cue is labeled by provenance:
  - Schroeder / EVO Original
  - Schroeder-Derived
  - Evidence-Based Extension
- Extensions must be technically validated before entering the final library.
- Programming is downstream of exercise validation, not the other way around.

## Next recommended work

1. Deep-source validation of the three initial family drafts, especially subtle Schroeder / EVO body-position and internal-force cues.
2. Refine the templates based on what the first three families reveal.
3. Build the next families:
   - squat / knee-dominant;
   - hip hinge / hamstring;
   - vertical push / triceps;
   - horizontal pull / row;
   - elbow flexion / biceps;
   - calf / ankle;
   - adductor / lateral stance;
   - hip-flexor / long split;
   - shoulder rotation / stabilization;
   - quadriceps long-length.
4. Only after the final exercise library is validated, create beginner, intermediate and advanced programming.

## Publication principle

Draft technical material should remain clearly labeled as provisional until source review and biomechanical validation are complete. The final PDF/manual should never blur historical Schroeder instruction with modern extensions developed in this project.

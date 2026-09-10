# IsoTraining Project Index

## Current phase

**Phase 1 — Exercise Library + Position Learning System**

Goal: validate movement families and build complete technical specifications before writing final beginner / intermediate / advanced programming.

## Architecture and templates

- [Exercise Library Architecture](00-project/EXERCISE_LIBRARY_ARCHITECTURE.md)
- [Exercise Specification Template](02-exercises/EXERCISE_SPEC_TEMPLATE.md)
- [Position Learning Template](03-position-learning/POSITION_LEARNING_TEMPLATE.md) — refined to separate geometry, pressure, tension, intent, regression hierarchy and exit practice.
- [Exercise Master List](02-exercises/EXERCISE_MASTER_LIST.md) — canonical inventory for all families and variants.

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
13. [Quadriceps Long-Length Family](02-exercises/families/13_QUADRICEPS_LONG_LENGTH_FAMILY.md)

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
- **Push-Up:** strong historical support for deep position, vertical forearms and active pulling into the bottom position rather than passive hovering.
- **Scapular Pull-Up:** confirmed as a core EVO position, but exact scapular geometry remains less certain and is therefore intentionally conservative in the draft.
- **Wall Squat:** strong direct Schroeder description — upright torso, lower legs perpendicular, feet flat, continually pull deeper.
- **Single-Leg Squat:** strong historical evidence for specific box / bench geometry, but surviving sources contain more than one implementation; variants remain explicitly separated.
- **Standing Glute-Ham / Hamstring:** historical support for active downward pull plus glute / hamstring contribution rather than passive stretching.
- **Preacher Curl and Straight-Leg Raise:** retained as historically associated core positions.
- **Modern strap, row, calf, adductor and shoulder-rotation exercises:** clearly labeled as extensions rather than attributed to Schroeder.

## Phase 1 completion status

**All 13 planned movement families now have initial technical specifications and Learn Mode logic.**

This does not mean every individual exercise is permanently locked. Some variants are marked provisional where:
- surviving historical documentation is incomplete;
- a modern extension may prove redundant;
- exact joint-angle guidance should be refined during programming and illustration review.

## Next recommended work

1. Run a **whole-library technical audit** for redundancy, gaps, provenance consistency and safety / setup clarity.
2. Lock the final exercise list for programming.
3. Define programming variables: duration, intensity, accumulated time, frequency, progression criteria and deload / fatigue rules.
4. Build beginner programming first, then intermediate and advanced.
5. Develop illustration / force-map requirements from the final Learn Mode specs.

## Publication principle

Draft technical material should remain clearly labeled as provisional until source review and biomechanical validation are complete. The final PDF/manual should never blur historical Schroeder instruction with modern extensions developed in this project.

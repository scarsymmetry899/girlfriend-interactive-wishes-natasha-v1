# 🌌 Natasha’s Interactive Birthday Experience
## “Inside Her Universe” — Production Build Prompt

---

## PROJECT OVERVIEW

A **single-file, self-contained HTML app** — an interactive surreal birthday experience for **Natasha**.

This is not a traditional birthday card. It is a **cinematic, symbolic journey** where the user explores a world that behaves like Natasha — unpredictable, emotional, chaotic, and beautiful.

**Format:**
- 10 interactive scenes
- Each scene represents a metaphor
- Final emotional reveal

**Tech Stack:**
- Vanilla HTML + CSS + JavaScript
- Web Audio API (no external files)
- All assets inline
- Single `index.html`

---

## EXPERIENCE PHILOSOPHY

> This is not a story about Natasha.
> This is a world that feels like her.

Design principles:
- Emotion through interaction
- Minimal text, maximum feeling
- Abstract storytelling
- Calm ending after chaos

---

## DESIGN SYSTEM

### Fonts
- Headings: Playfair Display
- Body: Inter

### Color Palette
```
:root {
  --void: #0B0C10;
  --glow: #66FCF1;
  --dream: #C5C6C7;
  --pulse: #FF4D6D;
  --mystic: #9D4EDD;
  --light: #F8F9FA;
}
```

### Visual Style
- Soft gradients and glow effects
- Depth using blur and parallax
- Minimal UI elements
- Smooth cinematic transitions

---

## APP STRUCTURE

```
#splash
#experience
  ├── #scene-container
  │     └── .scene
  ├── #progress-indicator
#audio-toggle
#transition-layer
#final-overlay
```

---

## NAVIGATION

- Tap or swipe to progress
- No visible "Next" button initially
- Interaction unlocks next scene
- Idle hint after 4 seconds
- Smooth transitions between scenes

---

## AUDIO SYSTEM

- Ambient evolving tones per scene
- Subtle interaction feedback
- Final scene uses warm minimal tones

---

## SCENE FLOW

---

### SCENE 1 — THE VOID 🌑
Tap to create ripple of light

---

### SCENE 2 — GRAVITY SHIFT 🌌
Drag to change gravity

---

### SCENE 3 — COLOR AWAKENING 🎨
Tap to restore color

---

### SCENE 4 — IMPERFECT PUZZLE 🧩
Drag to connect imperfectly

---

### SCENE 5 — TIME LOOP ⏳
Long press to break loop

---

### SCENE 6 — MULTIPLE FACES 🎭
Tap to switch moods

---

### SCENE 7 — LIGHT REVEAL 🕯️
Drag to reveal light trails

---

### SCENE 8 — CHAOS SYSTEM 🌀
Attempt to organize chaos

---

### SCENE 9 — RIPPLE WORLD 🌊
Tap to create ripple effects

---

### SCENE 10 — REALITY BREAK 🎁
Tap to shatter screen

---

## FINAL SCENE 💖

Text:

“After everything…”
“It’s still just you”
“Happy Birthday, Natasha ❤️”

Optional:
“I’m glad I get to exist in your world”

---

## TRANSITIONS

- Fade + zoom
- Particle dissolve
- Glitch effects
- Glass break animation

---

## STATE MANAGEMENT

```
const state = {
  currentScene: 0,
  completed: [],
  audioOn: true
};
```

---

## CORE FUNCTIONS

```
initExperience()
renderScene(index)
handleInteraction(type)
completeScene(index)
transitionToNext()
playAudio(scene)
```

---

## FINAL EXPERIENCE GOAL

User journey:
- Curiosity
- Confusion
- Engagement
- Realization
- Emotional pause

---

## DEPLOYMENT

- Single index.html
- Netlify / GitHub Pages
- No dependencies

---

## CREATOR NOTE

- Avoid clichés
- Keep it minimal
- Let interaction drive meaning
- Focus on feeling over explanation

---

**End of Prompt**

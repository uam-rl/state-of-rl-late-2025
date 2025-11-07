# State of Reinforcement Learning - Late 2025 Overview

Presentation slides for the UAM RL Team's overview of the state of reinforcement learning in late 2025.

## Links

- **Slides (PDF)**: [https://uam-rl.github.io/state-of-rl-late-2025/slides.pdf](https://uam-rl.github.io/state-of-rl-late-2025/slides.pdf)
- **Slides 4:3 (PDF)**: [https://uam-rl.github.io/state-of-rl-late-2025/slides-4-3.pdf](https://uam-rl.github.io/state-of-rl-late-2025/slides-4-3.pdf)
- **Handout (PDF)**: [https://uam-rl.github.io/state-of-rl-late-2025/handout.pdf](https://uam-rl.github.io/state-of-rl-late-2025/handout.pdf)
- **Handout 4:3 (PDF)**: [https://uam-rl.github.io/state-of-rl-late-2025/handout-4-3.pdf](https://uam-rl.github.io/state-of-rl-late-2025/handout-4-3.pdf)
- **Repository**: [https://github.com/uam-rl/state-of-rl-late-2025](https://github.com/uam-rl/state-of-rl-late-2025)

## Building Locally

To compile the slides locally, you need [Typst](https://github.com/typst/typst) installed.

```bash
# Standard 16:9 slides
typst compile src/main.typ build/slides.pdf

# 4:3 aspect ratio
typst compile src/main.typ build/slides-4-3.pdf --input aspect-ratio="4-3"

# Handout version
typst compile src/main.typ build/handout.pdf --input handout="true"

# Handout 4:3
typst compile src/main.typ build/handout-4-3.pdf --input handout="true" --input aspect-ratio="4-3"
```

## Deployment

The slides are automatically deployed to GitHub Pages via GitHub Actions on every push to the `master` branch.

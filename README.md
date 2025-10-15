# CycleGAN vs. Stable Diffusion — A Short Comparative Study

Graduate-level course project comparing two popular generative methods:

- **CycleGAN** (`cycle-gan-high-epoch.ipynb`): unpaired image-to-image translation with cycle-consistency.
- **Stable Diffusion** (`stable_diffusion.ipynb`): latent diffusion for text/image-conditioned synthesis and stylization.

---

## What we asked
**When should you use CycleGAN vs. Stable Diffusion?**  
We compare sample quality, faithfulness to conditioning, style control, and data/compute requirements.

## Key takeaways (summary)
- **CycleGAN** shines for **domain translation** (A↔B) when no paired data exists (e.g., horses→zebras), preserving scene layout and structure.
- **Stable Diffusion** excels at **open-ended generation** and **prompt-controlled edits** with strong diversity; minimal training needed (often none), but careful prompt engineering and safety filtering matter.
- Typical trade-off: **CycleGAN = task-specific training, strong structure preservation**; **SD = broad capability, strong priors, less control over exact geometry without extra guidance/LoRA/ControlNet**.

---

## Repository structure

# Sonic Stage

## Auto-Generating Interactive Spatial Soundscapes from Dialogue Videos for Blind Viewers

**Authors:**
[Shuchang Xu](https://shuchangxu.github.io/)<sup>a</sup>,
[Xiaofu Jin](https://xiaofu-jin.github.io/)<sup>a</sup>,
[Gaurav Jain](https://gaurav1302.github.io/)<sup>b</sup>,
[Wenshuo Zhang](https://zhang373.github.io/)<sup>a</sup>,
[Huamin Qu](https://facultyprofiles.hkust.edu.hk/profiles.php?profile=huamin-qu-huamin)<sup>a</sup>,
[Brian A. Smith](https://www.engineering.columbia.edu/faculty-staff/directory/brian-smith)<sup>b</sup>,
[Yukang Yan](https://rochester-bear-lab.github.io/yukang)<sup>c</sup>

**Affiliations:** <sup>a</sup> HKUST <sup>b</sup> Columbia University <sup>c</sup> University of Rochester

**Venue:** UIST 2026

![Sonic Stage Teaser](static/images/1_Teaser.png)

[Read the paper](https://doi.org/10.1145/3772363.3798425)

## Video Presentation

[Watch the video presentation on YouTube](https://www.youtube.com/watch?v=uS_oWUInBkI)

## Abstract

We present Sonic Stage, a system that transforms dialogue videos into interactive spatial soundscapes, enabling BLV audiences to intuitively understand characters' actions and movements through immersive auditory cues. Sonic Stage conveys essential visual information during dialogue through three auditory techniques:

1. **Spatialized dialogue** to represent spatial layout.
2. **Diegetic sound** to convey character actions.
3. **Interactive descriptions** to provide context-specific visual details.

## The Accessibility Challenges in Dialogue Videos

![Figure 2](static/images/2_Problem.png)

In scenes with lots of dialogue, there is little opportunity to insert audio descriptions (AD). Consequently, blind and low-vision (BLV) viewers often miss crucial visual information, such as characters’ actions, movements, and facial expressions.

## Our Solution: Sonic Stage

![Figure 3](static/images/3_Walkthrough.png)

Sonic Stage conveys essential visual information during dialogue using three auditory techniques: spatialized dialogue, diegetic sound, and interactive descriptions. These techniques enable BLV viewers to perceive on-screen actions within an immersive auditory experience.

## Sonic Stage's Audio Spatialization Pipeline

![Figure 4](static/images/4_Pipeline.png)

To create a coherent auditory experience across camera changes, Sonic Stage reconstructs a 3D scene representation from dialogue videos and renders all auditory cues within a shared spatial soundscape. Its pipeline consists of three stages:

1. **Frame sampling**
2. **Scene reconstruction**
3. **Soundscape optimization**

## Technical Evaluation with Diverse Video Types

![Figure 5](static/images/5_Video_Gallery.png)

Sonic Stage’s pipeline achieved **91.9% overall accuracy** in character trajectory reconstruction across a diverse video set. It performed well in scenes with distinct backgrounds, even under fast motion and sparse views.

The remaining errors mainly arise from two issues:

1. Too few full or medium shots for robust spatial reconstruction.
2. Insufficient feature points for multi-view alignment.

## User Evaluation with BLV Viewers

![Figure 6](static/images/6_Evaluation.png)

In a user study with 12 BLV viewers, Sonic Stage significantly improved video comprehension, spatial presence, and narrative engagement compared to a baseline modeled after SPICA, the state-of-the-art method for accessible video exploration.

## Opportunities Across Diverse Video Genres

![Figure 7](static/images/7_Extension.png)

Sonic Stage’s techniques could be extended to diverse video genres, including sketch comedy, opera, dance, and documentary. We hope this work inspires future research on immersive, interactive audio representations that improve video accessibility for blind audiences.

## More Video Examples from Sonic Stage

### Friends

[![Friends video thumbnail](https://img.youtube.com/vi/xOd_z5jei9g/maxresdefault.jpg)](https://www.youtube.com/watch?v=xOd_z5jei9g)

[Watch “Friends” on YouTube](https://www.youtube.com/watch?v=xOd_z5jei9g)

### Diana: The Musical

[![Diana: The Musical video thumbnail](https://img.youtube.com/vi/UbV0Azireik/maxresdefault.jpg)](https://www.youtube.com/watch?v=UbV0Azireik)

[Watch “Diana: The Musical” on YouTube](https://www.youtube.com/watch?v=UbV0Azireik)

### Forrest

[![Forrest video thumbnail](https://img.youtube.com/vi/PIRWkgYPf38/maxresdefault.jpg)](https://www.youtube.com/watch?v=PIRWkgYPf38)

[Watch “Forrest” on YouTube](https://www.youtube.com/watch?v=PIRWkgYPf38)

### The Bilibili Interview

[![The Bilibili Interview video thumbnail](https://img.youtube.com/vi/L2WzK5hvjIY/maxresdefault.jpg)](https://www.youtube.com/watch?v=L2WzK5hvjIY)

[Watch “The Bilibili Interview” on YouTube](https://www.youtube.com/watch?v=L2WzK5hvjIY)

## More Works from Our Research Team

### [DanmuA11y](https://dl.acm.org/doi/full/10.1145/3706598.3713496)

Making real-time video comments accessible to blind viewers.

**Venue:** CHI 2025 Honorable Mention 🏅

### [Branch Explorer](https://dl.acm.org/doi/full/10.1145/3746059.3747791)

Supporting interactive 360 video viewing for blind users.

**Venue:** UIST 2025

### [Front Row](https://dl.acm.org/doi/abs/10.1145/3586183.3606830)

Generating immersive audio representations of tennis broadcasts for blind viewers.

**Venue:** UIST 2023

## BibTeX

```bibtex
@article{SonicStage2026,
  title={Sonic Stage: Automatically Generating Interactive Spatial Soundscapes to Facilitate Dialogue Video Comprehension for Blind Viewers},
  author={Xu, Shuchang and Jin, Xiaofu and Jain, Gaurav and Zhang, Wenshuo and Qu, Huamin and Smith, Brian A. and Yan, Yukang},
  booktitle={Proceedings of the 39th Annual ACM Symposium on User Interface Software and Technology (UIST '26)},
  year={2026},
  url={https://doi.org/10.1145/3830398.3830486}
}
```

---

This page was built using the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), which was adapted from the [Nerfies](https://nerfies.github.io) project page.

The website is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

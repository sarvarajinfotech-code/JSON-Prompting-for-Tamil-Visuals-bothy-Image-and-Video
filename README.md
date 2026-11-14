# Week 2 – Day 2: Use JSON Prompting for Tamil Visuals

## Project Overview

This project demonstrates how structured JSON prompting can be used to generate culturally authentic Tamil visuals using AI image-generation tools.

The selected scene is a traditional flower market near **Meenakshi Amman Temple, East Masi Street, Madurai, Tamil Nadu, India**, during the Chithirai festival.

The project uses a reusable JSON prompt template to maintain consistency across multiple image generations while changing selected visual parameters.

## Project Objectives

- Understand structured JSON prompting for AI image generation.
- Create a reusable JSON prompt template.
- Generate three visual variations from the same Tamil cultural scene.
- Experiment with lighting and camera composition.
- Create a video-generation prompt using the same scene and visual context.
- Document the prompts and generated outputs for reuse.

## Selected Tamil Scene

**Location:** East Masi Street, near Meenakshi Amman Temple, Madurai  
**Time period:** Contemporary Madurai, 2020s  
**Occasion:** Chithirai Festival  
**Subject:** A Tamil woman flower seller arranging jasmine and marigold garlands.

The visual composition includes:
- A traditional Tamil flower seller wearing a cotton sari.
- Fresh jasmine, marigold and rose garlands.
- Woven baskets filled with flowers.
- Meenakshi Amman Temple's Dravidian-style gopuram.
- Everyday street-market activity.
- Authentic South Indian cultural details.

## Image Generation Experiments

Three images were generated using the same core scene with controlled prompt variations.

### Image 1 – Base Template

**Objective:** Establish the original visual composition.

- Wide establishing shot.
- 35mm camera perspective.
- Eye-level documentary photography.
- Soft, warm early-morning natural lighting.
- Flower seller, flower baskets, street activity and temple gopuram visible.

![Image 1 – Base Template](images/image_1_base.png)

### Image 2 – Golden Hour

**Objective:** Experiment with lighting while retaining the original scene.

Changes:
- Time of day: Golden hour.
- Lighting: Warm golden sunlight with gentle shadows.

The subject and overall market composition remain consistent.

![Image 2 – Golden Hour](images/image_2_golden_hour.png)

### Image 3 – Close-Up

**Objective:** Experiment with camera composition and subject focus.

Changes:
- Camera shot: Close-up.
- Focus: Flower seller's hands arranging jasmine garlands.
- Background: Temple and market activity softly blurred.

![Image 3 – Close-Up](images/image_3_closeup.png)

## JSON Prompt Structure

The reusable prompt template is stored in `tamil_prompt.json`.

It contains the following fields:

| Field | Purpose |
|---|---|
| `subject` | Defines the main character and activity |
| `setting` | Defines location, era and time |
| `lighting` | Controls natural and artificial lighting |
| `camera` | Defines shot, lens and angle |
| `palette` | Specifies the visual colour palette |
| `style` | Defines the photographic style |
| `aspect_ratio` | Sets the image dimensions ratio |
| `avoid` | Lists unwanted visual elements |

## Video Generation Prompt

The project also includes a video-generation prompt stored in `tamil_video_prompt.json`.

The video prompt extends the original JSON template with a `motion` field.

It defines:

- Subject movement: The flower seller arranging jasmine garlands.
- Camera movement: Slow dolly-in.
- Duration: 10 seconds.
- Background movement: Natural street-market activity.
- Audio direction: Ambient market sounds and distant temple bells.

The prompt is designed to maintain visual continuity with the three image variations.

*Note: The JSON file is a video-generation prompt; an actual video output should be added separately once generated.*

## Project Structure

```text
Week-2-Day-2-Tamil-JSON-Prompting/
│
├── tamil_prompt.json
├── tamil_video_prompt.json
├── README.md
│
├── images/
│   ├── image_1_base.png
│   ├── image_2_golden_hour.png
│   └── image_3_closeup.png
│
└── video/
    └── madurai_chithirai_10sec.mp4
```

## Key Learnings

1. JSON prompting helps organize image-generation instructions into reusable components.
2. Structured prompts make it easier to control subjects, locations, lighting and camera composition.
3. Changing specific prompt parameters can produce different visual results while retaining the same core scene.
4. Camera framing and lighting have a significant impact on the final image.
5. A reusable JSON structure can also be extended for AI video-generation workflows.

## Tools Used

- ChatGPT – Prompt development and AI image generation.
- JSON – Structured prompt definition.
- Visual experimentation – Lighting and camera composition variations.
- GitHub – Project documentation and version control.

## Conclusion

This exercise demonstrates how structured JSON prompts can help generate consistent, culturally grounded Tamil visuals.

By keeping the core scene consistent and experimenting with selected parameters, it becomes easier to understand, reproduce and refine AI-generated visual outputs.

---

**Assignment:** Social Eagle – Gen AI Architect  
**Week:** 2  
**Day:** 2  
**Topic:** Use JSON Prompting for Tamil Visuals


---
name: create-handdrawn-insurance-posters
description: Create a coordinated series of Chinese hand-drawn insurance social posters from one or more visual references and multiple copy lines. Use when Codex needs to turn insurance, student protection, family protection, accident, medical, critical-illness, or claims scenarios into separate 1:1 or portrait raster posters with oversized handwritten Chinese headlines, marker circles/underlines, simple narrative illustrations, accurate copy, and consistent art direction.
---

# Create Hand-Drawn Insurance Posters

Turn supplied reference images and insurance copy into a coherent poster series. Use the image-generation skill and built-in image tool for every raster output.

## Workflow

1. Inspect every reference image before generating. Label each as a style reference unless the user explicitly requests an edit or preservation of a subject.
2. Extract only transferable visual traits: typography scale, paper texture, color accents, annotation marks, illustration density, composition, and emotional tone. Do not copy the reference subject matter, branding, or slogans.
3. Preserve each user-provided copy line verbatim. Treat one numbered copy item as one independent poster unless the user requests a collage.
4. Resolve only blocking omissions. Otherwise default to:
   - square 1:1 social-media poster;
   - warm white or off-white paper background;
   - oversized black handwritten Chinese headline;
   - rough red and yellow marker circles or underlines;
   - simple friendly hand-drawn narrative scene;
   - black, red, yellow, and a small amount of blue;
   - spacious hierarchy with no logo or watermark.
5. Plan a distinct visual metaphor for each poster while locking the shared system. Prefer one clear scene over many decorative elements.
6. Generate each distinct poster with a separate image-generation call. Pass the same style references to every call and explicitly identify them as style references.
7. Quote the exact Chinese copy in every prompt. Specify line breaks and which phrase receives a circle or underline.
8. Inspect each output for:
   - exact Chinese characters and punctuation;
   - correct insurance meaning;
   - no invented benefit, price, claim promise, logo, or disclaimer;
   - non-graphic, age-appropriate scenes;
   - consistent typography, palette, texture, and illustration style;
   - clearly different scene content for each copy item.
9. If text or meaning is wrong, regenerate only the affected poster with a single targeted correction. Do not redo correct posters.
10. Deliver all final images together and state the count and format. Avoid claiming text accuracy without visual inspection.

## Copy and Compliance Guardrails

- Keep benefit statements exactly as supplied. Do not broaden coverage or imply guaranteed reimbursement.
- Do not invent prices. If the copy says “每天几毛钱,” retain that phrase without adding a specific amount.
- Show injuries mildly and non-graphically. Use bandages, supportive gestures, or a relieved expression.
- Depict students in an age-appropriate way. Avoid fear-heavy imagery.
- Use readable Chinese as the priority; decorative annotations must not cross or obscure key characters.
- Keep supporting text minimal. Prefer no extra copy beyond labels that are essential to the illustration.

## Prompt Construction

Read [references/prompt-pattern.md](references/prompt-pattern.md) before generating. Fill one prompt per poster and keep series-level constants identical.

## Series QA

Compare the final set as a group:

- Headline block occupies a similar proportion on every poster.
- Marker colors and stroke treatment remain consistent.
- Illustration detail and character rendering remain consistent.
- No poster looks like a different campaign.
- Each poster is understandable at thumbnail size.

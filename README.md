# Create Promo Video Skill

This is a **Gemini** skill that helps you automatically generate promotional TikTok-style short videos for your software projects using [Remotion](https://www.remotion.dev/).

## What it does

This skill acts as an expert videographer and motion designer. It:
1.  **Analyzes your project** to understand its core functionality and selling points.
2.  **Extracts branding** (colors, fonts, logos) from your existing codebase.
3.  **Generates a Remotion video project** in a `video/` subfolder.
4.  **Creates a professional composition** with a hook, product showcase, and call to action.
5.  **Renders the final video** in your preferred format:
    *   **Portrait (9x16)** for TikTok, Shorts, Reels.
    *   **Landscape (16x9)** for YouTube, Twitter/X, LinkedIn.

## Installation

You can install this skill directly using the `findskill` CLI:

```bash
npx findskill install create-promo-video
```

Or if you have `findskill` installed globally:

```bash
findskill install create-promo-video
```

## Usage

Once installed, you can activate the skill in your Gemini session to start generating videos for your current project.

```text
@create-promo-video create a promo video for this project
```

## Requirements

*   Node.js 18+
*   npm
*   ffmpeg

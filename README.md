# Create Promo Video Skill

This is a **Claude** skill that helps you automatically generate promotional short videos for your software projects using [Remotion](https://www.remotion.dev/).

## What it does

Here's a quick example of what this skill enable. I asked it to generate the video for the actual skill.

![Promo Video Demo](promo.gif)


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

Or just download this repo and add it to your favourite `.agent-cli/skills` folder (e.g. `.codex/skills/` `.gemini/skills`)


## Usage

Once installed, you can activate the skill in your Claude Code session to start generating videos for your current project.

```text
hei claude let's make  a promo video for this project
```

## Interactive Editing
    
You get full control over the output. The skill sets up a local Remotion Studio where you can:
    
-   **Preview changes live** in the browser.
-   **Tweak props** (text, colors) using visual controls.
-   **Modify the code** directly if you need custom animations or layouts.


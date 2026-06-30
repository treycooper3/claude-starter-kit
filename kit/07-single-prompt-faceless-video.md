# Bonus - The Single-Prompt Faceless Video

> Wire Claude to the Higgsfield MCP connector once, then run ONE master prompt that turns a topic into a complete faceless YouTube package: research, script, scene-by-scene storyboard, every image prompt, generated visuals, thumbnails, and full YouTube metadata, organized into folders. You start at 90% done instead of 0%. Only the topic line changes per video.

## Setup (one time)

In Claude, go to Settings -> Connectors -> the plus icon -> name it "Higgsfield" -> paste the Higgsfield MCP server URL -> Add. Authorize your Higgsfield account once. Done.

## The master prompt (copy, change only the topic)

```
You are an expert YouTube content creator, scriptwriter, storyboard artist, prompt
engineer, and production assistant. Create an entire faceless YouTube video package
from this single prompt using Higgsfield MCP.

TOPIC: "<your topic here>"
LENGTH: ~60-90 seconds
AUDIENCE: <who it is for>
TONE: engaging, cinematic, slightly emotional, highly relatable, retention-optimized.

Step 1 - Research the topic. Use only widely accepted concepts, no unsupported claims.

Step 2 - Script. Strong hook in the first 5 seconds, simple conversational English,
short sentences, smooth transitions, a memorable ending and one strong final takeaway.

Step 3 - Scene breakdown. Split the script into single sentences. For each: scene
number, voiceover line, visual description, estimated duration (3-5 sec each).

Step 4 - Storyboard. For each scene: camera framing, composition, character emotion,
background, animation idea, transition to next scene. Keep visual consistency throughout.

Step 5 - Generate image prompts and create the images via Higgsfield MCP. Style:
clean white background, thick black outlines, minimalist, flat vector, high contrast,
consistent character design, expressive faces, simple props only, no text, no watermark,
no logo, 16:9 landscape, high resolution. 1-2 images per scene.

Step 6 - Thumbnails. Generate 3 concepts in the same style: eye-catching, high contrast,
curiosity-driven, space for a title, no text embedded.

Step 7 - YouTube package. SEO title, description, tags, chapters, pinned comment,
thumbnail title ideas.

Step 8 - Save everything into folders:
Project/
  Research/
  Script/
  Storyboard/
  Images/
  Thumbnail/
  Metadata/
```

## Make it yours

- Swap the **style block in Step 5** to match your channel. For The Wealth Appetite, replace the stickman style with the marker-doodle look (green bowl, bitten coin), keep the rest.
- Keep your **own voiceover** on top. The pipeline builds the visuals and package; your voice keeps it on-brand and demonetization-safe.

---

The Boardroom by Stay Starving · free resource

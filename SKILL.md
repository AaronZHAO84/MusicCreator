---
name: musiccreator
description: Use when creating, revising, arranging, packaging, or releasing a Chinese song and the work needs a consistent theme, lyric, Suno Style, vocal direction, version record, artifact tracking, or release preview workflow.
---

# musicCreator

Use this skill as the default workflow for the user's Chinese songwriting and Suno projects. The goal is not to write a full project report; it is to keep the song's theme, lyrics, music, performance, files, and release presentation aligned.

## Fixed sequence

Follow this order unless the user explicitly skips a gate:

> Theme confirmation → Overall view → Title direction → Lyric writing → Lyric preview/revision → Lyric confirmation → Suno Style and performance direction → Audio generation → Listening/selection → Cover → Release artifact → Archive/retrospective

### 1. Theme confirmation

Confirm why the song is being written, the person/event/relationship, the setting, the intended resonance, and what must be avoided. For character work, confirm the character interpretation before writing lyrics. Do not invent source facts when the source cannot be read.

### 2. Overall view (required before title or lyrics)

After the theme is confirmed, make a whole-song view even if the title, lyrics, Style, and vocal direction are not decided yet. State the intended or unwanted direction for:

- title atmosphere and degree of indirectness;
- lyric perspective, narrative spine, imagery, density, and ending;
- genre, mood, instrumentation, tempo/meter, and vocal behavior;
- performance register, emotional arc, and whether one or two connected-enjambment moments fit;
- explicit exclusions and likely risks.

The overall view is the alignment anchor. Do not let title, lyrics, Style, and cover independently drift away from it.

Every song is held to a high creative target: treat the confirmed title, lyrics, Style, and overall performance as candidates for a lasting classic and a widely loved hit. This is a quality target, not a promise of popularity. Judge choices by memorability, emotional truth, singability, distinctiveness, replay value, and whether the complete song feels intentional rather than merely polished.

### 3. Parallel choices

When there are multiple genuinely parallel options, offer choices instead of silently selecting one. Recommend Style and performance directions from the current theme plus prior preferences, then let the user choose.

Use **murpick** when the user must compare or check multiple options such as titles, lyric routes, Styles, vocal/performance routes, cover directions, release styles, or Skill modules. Treat checked and unchecked choices as decisions. Do not invoke murpick for a single clear path or routine local lyric edit. If adapting murpick to a pure choice menu, state which default research/menu stages were omitted and why.

### 4. Pre-preview creative inspection

Before showing a lyric preview, independently inspect the complete lyric together with the overall view and intended performance. Check for inappropriate or out-of-place wording, unnatural diction or singing, missing logic, broken emotional transitions, over-explanation, forced literary language, excessive colloquial phrasing, repetition, and words/lines/sections that need polishing for performance. Fix every clear issue before presenting the preview; do not provide an obviously general or rough draft merely to wait for the user to ask for corrections. The standard is natural, unforced, neither affected nor casual for its own sake.

### 5. Title and lyric gates

Present title candidates with their mood, imagery, and risks; by default draw on classical Chinese language and imagery from the *Book of Songs*, classical poetry, ci poetry, and other古文 when appropriate. Borrow the atmosphere and semantic resonance, not unexamined quotations or archaic ornament. Wait for title direction confirmation before saving song files. Draft lyrics only after the overall view and title direction are stable. Preview lyrics before writing files, but run the full pre-preview inspection first and complete obvious optimizations before showing the user. For a near-final draft, make contextual, local “surgical” edits; preserve accepted structure, imagery, and meaning. Check the whole lyric after every revision for natural Chinese, breath-friendly phrasing, singability, repetition, and a coherent emotional spine.

Default lyric aesthetics:

- favor natural, image-led, literary Chinese with clear singable lines and deliberate space;
- use light, weather, streets, rivers, seasons, objects, sound, time, and spatial change to carry emotion;
- avoid slogan-like conclusions, direct moralizing, piled-up explanation, and mechanical repetition;
- preserve ancient imagery and action pictures in ancient-style work; do not flatten them into daily speech to solve one pronunciation issue;
- when suitable, use comedy to express tragedy, and indirect/winding expression rather than explaining the pain;
- let light, shadow, time rotation, weather, and observed action reveal the inner life;
- use connected enjambment sparingly—normally one or two connected moments only when meaning naturally continues across lines.

### 6. Style and performance

Only after lyrics are confirmed, write the final Suno Style. Keep Style focused on musical controls, not a duplicate story summary. Recommended order:

> genre/mood → vocal register/timbre → melodic behavior → verse/chorus contrast → instrumentation → tempo/meter → prohibitions → ending behavior

Default user preference:

- lyric sensibility associated with 唐恬: natural, detailed, emotionally restrained, image-led;
- mature male vocal traits associated with 陈楚生、杨宗纬、郑中基、王杰: clear diction, lived-in expression, useful low/mid register, controlled tension;
- do not imitate a named singer; translate the reference into vocal, register, phrasing, diction, and emotional traits;
- do not make the volume excessively loud. A chorus does not have to contain the song title;
- when both male and female voices are used, the secondary voice must not be only harmony: create audible contrast through tail-word handoffs, full-line alternation, call-and-response, or section changes. For long lines, use rhythmic accents, pauses, and dynamic variation so a low register still has force and layers;
- require a clear melodic line and emotional progression. Let power come from rhythm, breath, accents, harmony, timbre, and arrangement changes;
- prohibit high-note sprints, sustained high register, shouting, sharp head voice, forced upward transposition, and explosive endings;
- a rap section may be fast and dense, but stays in a lower register with clear diction;
- after rapid rap, a Spoken section may suddenly strip back to slow, low, close, unpitched reading;
- give the chorus strength without raising the register: use low/mid melody, wide harmony, and drum-group motion to create tension;
- allow a local lift, then return to a relaxed low/mid register.

For Suno v4.5-all, count the exact final Style characters. Treat `<=1000` as a hard delivery gate. A concise Style is a starting heuristic, not proof of musical success; actual generations and listening are required.

### 7. Audio, cover, and release gates

Distinguish prepared inputs, generated audio, listened candidates, and selected audio. Never claim audio generation or listening from the existence of lyric/Style files.

Create a cover only after lyrics and Style are confirmed. Base the prompt on both, not on the title alone. Check composition, text absence/accuracy, and fit with the song's atmosphere.

Release artifacts must define the text range before layout. Required credit:

> Aaron，Z作品

Keep title hierarchy, typography, colors, spacing, punctuation, lyric formatting, credit placement, and cover/player treatment consistent. HTML release previews must accommodate phone, tablet, and desktop widths; test long titles, long lyrics, image scaling, audio containers, wrapping, and footer visibility.

### 8. HTML deliverables and web-sourced materials

When making an HTML preview, usage guide, release page, or other visual artifact, obtain visual/content materials from the relevant website or other user-provided web source when such a source exists. Inspect the source directly, use only materials that are relevant and permitted, preserve source attribution where needed, and do not invent product facts, logos, screenshots, or statistics. If the website cannot be read, say so and use clearly labeled placeholders or ask for supplied materials.

Keep the HTML focused on the user's content and visual system. Do not paste a full Suno Style into an HTML page. Instead, show a few concise Style core phrases or keywords, such as `cinematic Chinese folk-pop`, `restrained low-mid vocal`, `subtle strings`, or `no belting`; choose only the phrases relevant to the current song. Do not use repetitive fixed prose such as “成熟男声，低中音区为主，吐字清楚……” as a generic description. Translate the confirmed direction into short, natural display copy.

For HTML output, keep text scope, typography, colors, spacing, and credit consistent; test narrow and wide layouts, long Chinese text, image scaling, audio containers, wrapping, and footer visibility. Required public credit remains `Aaron，Z作品`.

### 9. Versioning and default project path

Once the title is confirmed, use the default root:

```text
D:\MyPlaces\GPT Projects\自己\音乐创作\
```

Create or use:

```text
D:\MyPlaces\GPT Projects\自己\音乐创作\《歌名》\
```

If the root or user-specified alternative path does not exist, notify the user and stop file creation. Ask them to create it or specify another valid path. Do not silently create a replacement path. Preview and discussion may continue while saving is paused.

Suggested per-song layout:

```text
《歌名》/
├─ 《歌名》创作记录_v1.0.md
├─ 《歌名》歌词_v1.0.txt
├─ 《歌名》Style_v1.0.txt
├─ 《歌名》Suno生成说明_v1.0.md
├─ 《歌名》封面_v1.0.png
├─ audio/
├─ preview/
└─ archive/
```

Never overwrite an accepted version. Use v1.0 for the first confirmed version, v1.1/v1.2 for local revisions, and v2.0 for a material change in theme, structure, or direction. Before saving a revision, reread the actual file; after saving, read back path, name, size, and relevant content.

### 10. Artifact-based progress with manual override

Default progress mode is artifact-based. Inspect the confirmed song folder and infer only what the artifacts prove:

| Evidence | Stage it can support |
|---|---|
| confirmed title folder / creative record | title and project initialization |
| lyric file | lyric draft or confirmed lyric, depending on record |
| Style file | Style prepared |
| generation note | generation instructions prepared |
| audio files | audio generated |
| listening/selection record | audio listened and selected |
| cover file | cover prepared |
| HTML/WeChat release file | release artifact prepared |
| archive/version log | archive/retrospective recorded |

Do not infer listening, selection, visual QA, publication, or generated audio from a file's mere existence. If a browser UI cannot read the local folder directly, ask the user to select the song folder or provide its path; report the limitation honestly.

The user may manually set any stage to `completed`, `current`, or `not completed`. Manual changes override automatic inference until the user requests a rescan or returns to automatic mode. Show both the status and its source (`artifact` or `manual`) when possible.

### 11. Lightweight creative record

Every song's version record includes this optional, concise section. It is a creative trace, not a comprehensive project report; fields may be left blank.

```text
【创作背景与共鸣】
写作缘起：
想抓住的特点：
想突出的人物性格或情绪：
想表达的事情：
实际看到的场景或细节：
场景背后的共鸣：
采用的艺术表达方式：
刻意避免的直白表达：
总体歌词、音乐与演绎方向：
```

## Minimal intake template

Ask only for missing variables that materially affect the direction:

```text
歌曲主题：
人物/事件：
核心关系：
创作缘起：
想表达的内容：
参考材料：
希望保留的意象：
不希望出现的内容：
是否采用喜剧表达悲剧：
是否采用不说破、少讲道理的表达：
演唱偏好：
是否需要音频、封面、发布物：
```

## Common mistakes

- Writing lyrics before the overall view: pause and align title, lyric, Style, and performance first.
- Saving before preview confirmation: keep preview and file writing separate.
- Rewriting an almost accepted lyric wholesale: make contextual local alternatives.
- Treating a prepared Style as generated music: label artifacts precisely.
- Guessing a missing source or character fact: state the gap and request readable source text.
- Overwriting a prior version: create the next version and preserve the archive.
- Scanning a non-existent directory: notify and wait for directory creation or a new path.
- Calling murpick for ceremony: use it only for real parallel choices.
- Making intensity equal loudness or high notes: build force through rhythm, breath, accents, harmony, timbre, and arrangement.
- Treating a female/male part as decorative harmony: use handoffs, alternation, call-and-response, or section contrast when dual vocals are intended.
- Showing a preview without whole-song inspection: run the pre-preview creative inspection first.
- Offering a rough lyric and waiting for the user to request obvious fixes: complete the inspection and clear optimizations before preview.
- Choosing a generic modern title when classical resonance fits: consult the *Book of Songs*, classical poetry, ci poetry, and other古文 before naming.


# The Bespoke Site Kit

*Your own website, in a style that is yours. A questionnaire and a prompt to build a one-page personal site with Claude. Free to use.*

By Milena Boc · milena-boc.github.io

---

## How it works

1. **Choose your style** from the six in Part 1.
2. **Answer the questions** in Part 2. Allow about twenty minutes. Specific answers make a specific site.
3. **Gather your assets**: two or three photos of you (natural light, no stock images), your logo or wordmark if you have one, and your brand colours and fonts if you have them.
4. **Paste the prompt** from Part 3 into Claude, with your answers filled in, and attach your photos.
5. **Review the draft** and ask for changes in plain words: "warmer", "less text here", "make this section shorter".
6. **Publish it free** on GitHub Pages using Part 4.

---

## Part 1: Choose your style

Pick one. Each style changes the layout, the type and the details, not just the colours.

| Style | How it feels | Signature details |
| :-- | :-- | :-- |
| **Magazine** | Editorial, considered, unhurried | A large masthead, an opening spread, numbered sections, fine rules, pull quotes |
| **Newspaper** | Sharp, informed, front-page energy | A broadsheet nameplate, a dateline, columns, headlines and bylines, a "latest" sidebar |
| **Futuristic** | Precise, experimental, a little cinematic | A dark or high-contrast canvas, a monospaced detail font, a grid, subtle motion |
| **Typewriter** | Personal, handwritten-feeling, honest | Monospaced type, paper texture, a letter-style introduction, notes in the margins |
| **Art Deco** | Glamorous, geometric, celebratory | Symmetry, gold or metallic accents, stepped frames, tall display type |
| **Minimal** | Calm, spacious, confident | Lots of white space, one typeface family, a single accent colour, almost no ornament |

My style: **[CHOOSE ONE]**

---

## Part 2: The questions

### You
1. Your name, as you want it set at the top of the page:
2. One line on what you do, in plain words:
3. Where you are based, and where your work has taken you:
4. The one idea or question you want to be known for:
5. Three words people use to describe you:

### Your reader
6. Who should land on this page? (recruiters, collaborators, clients, peers, students)
7. What should they do next? (connect on LinkedIn, follow on Instagram, read your writing, say hello)

### Your proof
8. Your roles, newest first. For each: years, title, organisation, and **one highlight**:
9. Your education and certificates:
10. Two or three numbers you can stand behind, with their source and month:
11. Two or three short quotes from people you have worked with, with their names and permission:

### Your perspective
12. Two or three questions you keep turning over in your field, with a few sentences on each:

### Beyond work
13. What you love outside work (movement, culture, food, travel, music):
14. Three books and three podcasts you would recommend right now:

### Your look
15. Your colours, with their HEX values. If you have none, describe the feeling (for example warmer, quieter, earthier, brighter, neon):
16. Your fonts (one for headings, one for body text). If you have none, write "suggest a pairing for my style":
17. Brands, places or Pinterest boards whose look you admire:
18. Anything you never want to see (for example italics, gradients, emojis, stock photos):

### Your links
19. LinkedIn, Instagram, GitHub, YouTube, newsletter or other links, in order of importance:

---

## Part 3: The prompt

Copy everything below, fill in the brackets with your answers, and paste it into Claude with your photos attached.

```
Build me a one-page personal website in the [STYLE] style. It should feel bespoke to me, not like a template.

ABOUT ME
- Name for the top of the page: [1]
- What I do: [2]
- Where I am based and where my work has taken me: [3]
- The idea I want to be known for: [4]
- How people describe me: [5]

READER AND GOAL
- The page is for: [6]
- After reading, they should: [7]

SECTIONS (adapt their names and layout to the [STYLE] style)
1. An opening: my name, a short headline, two sentences about me, my main photo, two buttons, and a row of links so the page also works as my link hub.
2. Experience: a compact list, one highlight per role. [8] Learning: [9]
3. Reach: my numbers, each with its source and month. Never combine numbers from different platforms or periods. [10]
4. Perspective: my open questions, two or three of them. [12]
5. Beyond work: a second photo, my interests, and my books and podcasts. [13] [14]
6. Testimonials, quoted exactly as written. [11]
7. Connect: a warm, personal invitation and my links. [19]

STYLE
- Style: [STYLE]. Use its signature details: [paste the "Signature details" from the table for your style].
- Colours: [15]. Use them as named design tokens. Decide which colour is the background, which is the text, and keep the strongest colour for accents and buttons.
- Fonts: [16], from Google Fonts, with fallbacks.
- References: [17]
- Never: [18]
- One considered load animation that respects reduced-motion settings.
- Fully responsive down to phone width, with no sideways scrolling.

OUTPUT
- One self-contained index.html file plus an images folder, ready for GitHub Pages.
- British English, no placeholder text, and no facts about me that I have not given you.
```

---

## Part 4: Publish it free on GitHub Pages

1. Create a free account at github.com.
2. Create a new public repository named `yourusername.github.io` (with your own username).
3. Upload `index.html` and your `images` folder with **Add file → Upload files**, then **Commit changes**.
4. Open **Settings → Pages**. Under **Branch**, choose `main` and save.
5. After a minute or two, your site is live at `https://yourusername.github.io`.
6. Optional: connect your own domain under **Settings → Pages → Custom domain**.

---

## What makes it feel bespoke

- **Your real colour values**, not "beige" or "navy". Paste the HEX codes from your brand kit.
- **Your own photos**, in the same light and mood. Two strong photos are better than six average ones.
- **Specific highlights**, one line per role. Leave the full detail to LinkedIn.
- **Numbers with sources and dates.** They earn trust; rounded boasts lose it.
- **A personal section.** It is often the part people remember.

*Learn. Connect. Experiment. Inspire.*

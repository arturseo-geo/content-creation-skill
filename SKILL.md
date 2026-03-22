---
name: content-creation
description: Create high-quality, on-brand content for blogs, landing pages, email sequences, social media, video scripts, newsletters, case studies, whitepapers, and more. Use this skill whenever the user wants to write, rewrite, repurpose, or improve any piece of content — including blog posts, articles, LinkedIn posts, Twitter/X threads, Instagram captions, YouTube scripts, email campaigns, lead magnets, product descriptions, or brand copy. Trigger when the user mentions content calendars, editorial briefs, content strategy, tone of voice, brand voice, or asks to create content for a specific platform or audience. Also trigger for repurposing content (e.g., "turn this blog post into a LinkedIn thread").
---

# Content Creation Skill

## Workflow

### Step 1: Capture the Brief
Before writing, confirm (or infer from context):
- **Content type**: blog post / social post / email / video script / etc.
- **Platform**: Website / LinkedIn / X / Instagram / YouTube / Email / etc.
- **Audience**: Who is this for? Pain points, vocabulary, sophistication level
- **Goal**: Educate / Entertain / Convert / Build authority / Drive traffic
- **Tone**: Professional / Conversational / Bold / Empathetic / Witty
- **Length**: Approximate word/character count or format constraints
- **SEO target**: Primary keyword (if applicable)
- **CTA**: What should the reader do next?

If the user hasn't provided these, make reasonable assumptions and state them at the top of the output so they can correct.

---

## Content Types & Formats

### Blog Post / Article
Structure:
1. **Headline**: Benefit-driven or curiosity-driven. Use numbers when possible.
2. **Hook** (first 2–3 sentences): Empathize with pain or make a bold claim
3. **Intro** (100–200 words): Set up the problem, preview the solution
4. **Body** (H2/H3 sections): Each section = one idea, with examples
5. **CTA / Conclusion**: Summarize key takeaway + one clear next step

Long-form (1500–3000 words) for SEO. Short-form (600–900 words) for quick reads.

### Email (Single or Sequence)
- **Subject line**: 40–50 chars, curiosity/benefit/urgency. Provide 3 variants.
- **Preview text**: Complements subject, 80–100 chars
- **Body**: Short paragraphs (2–3 sentences), one idea per paragraph
- **CTA**: Single, prominent, action-verb driven ("Download the guide", not "Click here")

Sequences — label each email:
- Email 1: Welcome / Promise
- Email 2: Problem agitation
- Email 3: Solution introduction
- Email 4: Social proof
- Email 5: Objection handling
- Email 6: Offer / CTA

### LinkedIn Post
- Hook (first line must stop the scroll — bold claim, contrarian take, or question)
- 3–5 short paragraphs or bullet points
- No links in body (add in first comment)
- End with a question or soft CTA
- Target: 150–300 words for feed posts; 1200–1500 for long-form articles

### X / Twitter Thread
- Tweet 1: The hook — bold, standalone, makes people want more
- Tweets 2–8: One point per tweet, numbered (2/8, 3/8...)
- Tweet 9: Summary / key takeaway
- Tweet 10: CTA (follow, RT, reply, link)
- Each tweet: max 280 chars; use line breaks for readability

### YouTube Script
Structure:
- **Hook** (0–30s): Pattern interrupt + promise
- **Intro** (30–60s): Who this is for, what they'll learn
- **Body** (chapters with timestamps suggested)
- **Outro**: Recap + subscribe CTA + next video suggestion
- Write in spoken language; flag pauses, B-roll cues `[B-ROLL: ...]`, and emphasis `**bold**`

### Instagram / Social Captions
- Lead with the most important thing (truncated after 2 lines)
- Tell a story or share a tip
- Hashtags: 5–15 relevant ones at the end (or first comment)
- Emojis: use sparingly for visual break, not decoration
- CTA: "Save this", "Tag someone who needs this", "Link in bio"

### Case Study
1. Client background (1 paragraph)
2. The challenge / problem
3. The solution / approach
4. Results (with specific numbers)
5. Key quote from client
6. Takeaways / what made it work

### Landing Page Copy
Sections:
1. Hero: Headline + subheadline + primary CTA
2. Pain: Agitate the problem
3. Solution: Introduce the product/service
4. Features → Benefits (always translate features into outcomes)
5. Social proof: testimonials, logos, stats
6. FAQ: Address top 3–5 objections
7. Final CTA with urgency element

---

## Content Repurposing

### Repurposing Matrix
When the user wants to repurpose content:

| Source → | Blog Post | LinkedIn | X Thread | Email | YouTube Script |
|---|---|---|---|---|---|
| Blog Post | — | Extract 3 insights | 10-tweet breakdown | Key takeaway email | Script the main points |
| Podcast ep. | Transcribe + expand | 5 quotes + lesson | Thread of tips | Episode summary | Repurpose audio to video |
| YouTube | Blog from transcript | 3 lessons | Best moments thread | Summary + link | — |
| Case study | Full blog post | Result story | Before/after thread | Client win email | Testimonial video script |

### Repurposing Workflow (Blog → Multi-Platform)
1. **Blog post** → published on website (SEO anchor)
2. **LinkedIn post** → extract the single boldest insight + personal angle
3. **X/Twitter thread** → break key points into numbered tweets
4. **Email** → send to list with a unique angle or exclusive detail
5. **Instagram carousel** → visualize 5–7 key points as slides
6. **YouTube short / Reel** → 60-second spoken version of the hook + main takeaway
7. **Newsletter** → curate with 2–3 other pieces for weekly digest

Rule: each platform version must feel native, not copy-pasted. Adjust tone, length, and CTA per platform.

See `references/repurposing.md` for detailed workflows.

---

## Brand Voice & Tone Consistency
When generating content for a brand:
- **Define voice attributes**: Pick 3–5 adjectives (e.g., bold, empathetic, precise)
- **Create a "We say / We don't say" list**: e.g., "We say 'people' not 'users'"
- **Maintain consistency across platforms**: Same voice, different tone per context (LinkedIn = professional-warm, X = punchy-bold, email = personal-direct)
- **Tone spectrum**: Map content types on a scale from formal → casual. Whitepapers sit formal; social sits casual. The voice stays the same.
- If a brand voice file exists (`.agents/product-marketing-context.md` or similar), apply it automatically to every piece.

---

## Content Calendar & Editorial Planning
When helping with content strategy:
- **Weekly cadence**: Recommend 2–3 blog posts, 5 social posts, 1 email, 1 long-form per week (adjust to capacity)
- **Theme weeks**: Group content around a single topic for compounding SEO and audience clarity
- **Content pillars**: Identify 3–5 recurring themes that map to business goals (e.g., product education, industry trends, customer stories)
- **Seasonal hooks**: Flag relevant dates, industry events, or trending moments to build content around
- **Pipeline stages**: Idea → Brief → Outline → Draft → Edit → Approve → Publish → Distribute → Measure
- **Batch creation**: Write multiple pieces in one sitting, schedule across the week — reduces context-switching

---

## SEO-Optimized Content Creation
For any content targeting search:
- **Primary keyword**: Place in title, H1, first 100 words, meta description, URL slug
- **Secondary keywords**: Weave 2–4 related terms naturally through H2s and body
- **Meta description**: 150–160 chars, include keyword + benefit + CTA
- **Internal linking**: Link to 2–5 related pages. Use descriptive anchor text, not "click here"
- **External linking**: 1–3 authoritative sources per post to build trust signals
- **Content depth**: Aim to be the most comprehensive answer — cover subtopics competitors miss
- **Featured snippet targeting**: Use a direct answer (40–60 words) right after the question heading
- **Image alt text**: Describe the image + include keyword where natural
- **URL structure**: Short, keyword-rich, no dates (evergreen by default)

See `references/seo-content.md` for detailed SEO writing guidelines.

---

## AI-Assisted Content Workflow
Recommended process for using Claude to create content:
1. **Outline**: Generate a structured outline with H2/H3 sections and key points per section
2. **Draft**: Expand the outline into a full draft — section by section for long-form
3. **Edit pass 1 — Accuracy**: Verify claims, check stats, add sources
4. **Edit pass 2 — Voice**: Apply brand tone, remove AI-isms, add personality
5. **Edit pass 3 — SEO**: Check keyword placement, meta description, internal links
6. **Human review**: Final read by a human — add personal stories, adjust nuance
7. **Publish + distribute**: Post and trigger repurposing workflow

Tips:
- Always provide context (audience, goal, tone) before asking for a draft
- Generate multiple headline options and A/B test
- Use Claude for first drafts, not final drafts — human polish is the differentiator

---

## Platform-Specific Formatting Quick Reference

| Platform | Max Length | Format Notes |
|---|---|---|
| LinkedIn feed post | 3,000 chars | Hook in first line; no links in body; use line breaks |
| LinkedIn article | 125,000 chars | Long-form; supports images, headers |
| X / Twitter | 280 chars/tweet | Threads: number tweets; standalone hook in tweet 1 |
| Instagram caption | 2,200 chars | First 2 lines visible; hashtags at end or first comment |
| YouTube description | 5,000 chars | First 200 chars matter most; timestamps; links |
| Email subject | 40–50 chars | Preview text: 80–100 chars |
| Blog post (SEO) | 1,500–3,000 words | H2 every 200–300 words; images every 500 words |
| TikTok caption | 2,200 chars | First line is the hook; 3–5 hashtags |

See `references/platforms.md` for full platform guidelines.

---

## Writing Principles
- **Show, don't tell**: Replace "we're experts" with a specific example
- **Active voice**: "We increased revenue" not "Revenue was increased"
- **Short sentences**: Aim for avg 15–20 words. Mix short and long.
- **Specificity wins**: "47% increase in 90 days" beats "significant growth"
- **One idea per paragraph** for digital content
- **Read aloud test**: If it sounds weird spoken, rewrite it
- **No throat-clearing**: Don't open with "In today's post, we will..."
- **Front-load value**: Put the most important information first — readers skim
- **Pattern interrupts**: Break visual monotony with bold text, short paragraphs, questions
- **Sensory language**: Use concrete, visual words over abstract concepts

---

## Output Format
Always deliver:
1. The content piece itself (ready to copy-paste)
2. Any variants requested (e.g., 3 subject line options)
3. A one-line note on any assumption made about tone/audience
4. Optional: suggested posting time or distribution tip

---

## Reference Files
This skill includes detailed reference guides in the `references/` directory:
- `references/platforms.md` — Platform-specific content rules, character limits, formatting, posting times
- `references/templates.md` — Ready-to-use content templates for common formats
- `references/repurposing.md` — Content repurposing workflows and strategies
- `references/seo-content.md` — SEO writing best practices for content creators

---

## Project Context File
If a `.agents/product-marketing-context.md` or `.claude/product-marketing-context.md` exists in the project, read it before generating any content. It contains brand voice, target audience, product description, and tone guidelines. Always apply this context automatically — never ask the user to re-explain what their product does if this file is present.

---

## Competitor Alternatives / Comparison Content
High-converting SEO content type:
- **"[Your Product] vs [Competitor]"** pages — target users actively comparing
- **"Best [Competitor] Alternatives"** pages — target users looking to switch
- Structure: feature table → prose comparison → who each is best for → CTA
- Tone: fair and factual (not attack ads) — credibility wins conversions

---

## Newsletter / Digest Format
- Subject line: same rules as email (curiosity, benefit, specificity)
- Opening: 1 hook sentence — why this issue matters
- Sections: 3–5 items max (link + 2–3 sentence summary)
- One "big idea" section: your original take on a trend
- CTA: reply, share, or upgrade prompt
- Length: 400–800 words for weekly newsletters

---

## Content Humanization
When AI-generated content needs to sound more natural:
- Replace: "In conclusion" / "It's worth noting" / "Dive into" / "Leverage" / "Delve"
- Add: contractions, sentence fragments for emphasis, rhetorical questions, personal asides
- Vary sentence length aggressively — mix 4-word punches with longer flowing sentences
- Add a specific personal or brand story to anchor abstract advice
- Use "you" liberally — speak directly to one reader, not an audience

---

## Product Update / Changelog Content
For announcing new features:
1. **What changed** (1 sentence)
2. **Why it matters** (the problem it solves)
3. **How to use it** (one-two steps)
4. **Screenshot or demo link**
5. **What's next** (builds anticipation)

Keep short — under 150 words for in-app, 300 words for email.

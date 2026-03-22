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

## Repurposing Matrix
When the user wants to repurpose content:

| Source → | Blog Post | LinkedIn | X Thread | Email | YouTube Script |
|---|---|---|---|---|---|
| Blog Post | — | Extract 3 insights | 10-tweet breakdown | Key takeaway email | Script the main points |
| Podcast ep. | Transcribe + expand | 5 quotes + lesson | Thread of tips | Episode summary | Repurpose audio to video |
| YouTube | Blog from transcript | 3 lessons | Best moments thread | Summary + link | — |
| Case study | Full blog post | Result story | Before/after thread | Client win email | Testimonial video script |

---

## Writing Principles
- **Show, don't tell**: Replace "we're experts" with a specific example
- **Active voice**: "We increased revenue" not "Revenue was increased"
- **Short sentences**: Aim for avg 15–20 words. Mix short and long.
- **Specificity wins**: "47% increase in 90 days" beats "significant growth"
- **One idea per paragraph** for digital content
- **Read aloud test**: If it sounds weird spoken, rewrite it
- **No throat-clearing**: Don't open with "In today's post, we will..."

---

## Output Format
Always deliver:
1. The content piece itself (ready to copy-paste)
2. Any variants requested (e.g., 3 subject line options)
3. A one-line note on any assumption made about tone/audience
4. Optional: suggested posting time or distribution tip

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

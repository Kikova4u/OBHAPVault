# TEMP4 — How-To Step-by-Step Guide with Affiliate Products

**HomeAppliancePicks.com** **Last Updated:** March 2026 **Author:** Mamoune Essaghir **Rank Math Target:** 90+/100 **Use When:** Keyword is "how to [task]", "[N] steps to [task]", "how to use [product]" **Voice:** We / Our team (or "you" when addressing the reader directly in steps) **Word Count:** 2,000–2,500 words

---

## WHEN TO USE TEMP4

- "How to clean a coffee maker filter"
- "How to season a cast iron skillet"
- "5 steps to deep clean your vacuum"
- "How to install a smart thermostat"
- "How to set up a Zigbee smart plug"
- "How to plant a container vegetable garden"
- Any article where the primary value is teaching the reader HOW to do something, with products recommended at each relevant step

---

## KEY DIFFERENCES FROM TEMP1/TEMP2

|Feature|TEMP1/TEMP2|TEMP4|
|---|---|---|
|Structure|Product-led|Step-led|
|Voice|"We tested X products"|"Here is how to do X"|
|Affiliate placement|After each product review|At each relevant step|
|Word count|2,500–2,700|2,000–2,500|
|Quick Picks table|Yes|No — replaced by "What You Need" list|
|Keyword type|"best X for Y"|"how to X" / "N steps to Y"|
|Internal links|Product listicles|Product listicles AND category hubs|
|Featured snippet|Quick Picks table|Numbered steps (H2s)|

---

## IMAGE STYLE — ST-10 MAGAZINE SPREAD

**All TEMP4 articles use ST-10 — Magazine Spread.** How-to articles = editorial authority = magazine layout.

**Accent color by topic:**

|Topic|ACCENT_COLOR|Tool|
|---|---|---|
|Kitchen / Food|Coral `#FF6B6B`|ChatGPT DALL-E 3|
|Cleaning / Appliance|Cobalt `#1F4CAD`|ChatGPT DALL-E 3|
|Smart Home / Tech|Teal `#00A693`|ChatGPT DALL-E 3|
|Garden / Outdoor|Forest Green `#1B4332`|ChatGPT DALL-E 3|
|Health / Personal Care|Coral `#FF6B6B`|ChatGPT DALL-E 3|

**Image prompt template (fill in [VARIABLES] before generating):**

```
Editorial magazine spread hero, 16:9 ratio, 1792x1024px.
Background: clean off-white #F8F6F2 — paper-like texture, very subtle,
not a flat color fill.

Left 40% of image: typographic zone — large editorial headline text in
black Playfair Display Bold (serif):
  LINE 1: "HOW TO" very large 72px
  LINE 2: "[PRODUCT TYPE / TASK IN 2-3 WORDS]" medium 40px
Lines are left-aligned, stacked, with generous leading.
Below the headline: thin [ACCENT_COLOR] horizontal line (3px, width of 
text block).
Below the line: subtitle in Montserrat Regular 14px: "Step-by-Step · 2026"

Right 55% of image: hero product photograph — [MAIN PRODUCT NAME] — 
sharp, transparent background, positioned on the off-white surface,
with a subtle soft drop shadow beneath it.
Product occupies 80% of the right panel height, slightly angled 5 degrees.

A thin vertical HAP Navy #0A173C line (4px) separates the text and 
product zones at the 42% horizontal mark.

Bottom strip: full width, [ACCENT_COLOR] at 8% height, containing white
Montserrat text: "HomeAppliancePicks.com — [FOCUS KEYWORD]"
Professional, authoritative, journalistic feel.
No watermarks, no brand logos on background, no people, photorealistic 
render, professional e-commerce quality.
```

**Pinterest Pin variant (1000×1500px — 2:3) — append to prompt:**

```
Also generate a vertical 1000×1500px Pinterest pin version — extend the
off-white background vertically, reposition the product to center-upper
third at the same 5-degree angle, keep the typographic headline on the 
left. Add a second text block at the bottom third: "[ARTICLE TITLE IN 
ALL CAPS MAX 6 WORDS]" in bold white Montserrat on a semi-transparent
[ACCENT_COLOR] overlay strip. Keep the HAP Navy vertical rule and bottom
strip branding.
```

---

## RANK MATH FIELDS

|Field|Rule|Example|
|---|---|---|
|**Focus Keyword**|"how to [task]" or "[N] steps to [task]"|`how to clean a coffee maker filter`|
|**SEO Title**|Under 60 chars, keyword at start, year|`How to Clean a Coffee Maker Filter (2026)`|
|**Meta Description**|150–160 chars, keyword + specific result + →|`Learn how to clean a coffee maker filter in 5 simple steps. We tested 3 methods and found the one that actually removes buildup fast in 2026 →`|
|**URL Slug**|Under 60 chars, focus keyword, no year|`/kitchen/how-to-clean-coffee-maker-filter/`|
|**Additional Keywords**|4 secondary keywords|`clean coffee maker vinegar`, `descale coffee maker`, `coffee maker maintenance 2026`, `how to descale coffee maker`|
|**Schema Type**|HowTo (set in Rank Math Advanced)|—|
|**Author**|Mamoune Essaghir|—|

---

## HTML TEMPLATE

```html
<!-- ============================================================
     HOMEAPPLIANCEPICKS.COM — TEMP4 HOW-TO STEP-BY-STEP GUIDE
     ARTICLE: [Full Title]
     PRIMARY KEYWORD: [exact focus keyword — "how to X"]
     SECONDARY KEYWORDS: [kw2], [kw3], [kw4], [kw5]
     URL SLUG: /[category]/[how-to-slug]/ (under 60 chars, no year)
     META TITLE: [under 60 chars — keyword at start + year]
     META DESCRIPTION: [150–160 chars — keyword + result + →]
     AUTHOR: Mamoune Essaghir
     LAST UPDATED: [Month Year]
     IMAGE STYLE: ST-10 Magazine Spread — [ACCENT_COLOR]
     ============================================================ -->


<!-- ===== H1 TITLE ===== -->

<h1>[How to / N Steps to] [Task] ([Year])</h1>


<!-- ===== HERO IMAGE ===== -->
<!-- Generate using ST-10 Magazine Spread prompt above -->
<!-- Tool: ChatGPT DALL-E 3 | Size: 1792x1024px -->

<div style="text-align:center; margin:28px auto 8px auto; max-width:780px;">
  <img src="[HERO IMAGE URL — upload to WordPress first]"
       alt="[How to Task] — [focus keyword] step by step guide 2026"
       width="780"
       style="width:100%; max-width:780px; height:auto; display:block; margin:0 auto; border-radius:10px; box-shadow:0 3px 12px rgba(10,23,60,0.12);" />
  <p style="font-size:13px; color:#888; margin-top:8px; text-align:center; font-style:italic;">[Brief caption — what this guide covers + year]</p>
</div>


<!-- ===== DISCLOSURE — TOP ===== -->

<p style="background:#f4f6fb; border-left:4px solid #0A173C; padding:12px 16px; font-size:13px; color:#555; margin:24px 0 28px 0;">
  <strong>Disclosure:</strong> HomeAppliancePicks.com is a participant in the Amazon Services LLC Associates Program. As an Amazon Associate, I earn from qualifying purchases. We independently research, test, and recommend products; we may receive commissions on purchases made through our links.
</p>


<!-- ===== INTRO ===== -->

<p>[Hook sentence — state the problem the reader has. Primary keyword in first 100 words. Include one dofollow Wikipedia link naturally on a relevant technical term. Example: "Knowing how to [task] correctly can save you [time/money/effort] — most people skip the one step that makes all the difference."]</p>

<p>[Second paragraph: brief overview of what the reader will learn. "In this guide, we walk through [N] clear steps to [task], with the exact products we recommend at each stage. Whether you are a beginner or just want a faster method, this is the only guide you need."]</p>


<!-- ===== WHAT YOU NEED ===== -->

<h2>What You Need Before You Start</h2>

<p>Before starting, gather these items. We have linked each one to our top pick on Amazon — these are the exact products we use in this guide.</p>

<div style="background:#f9fafc; border:1px solid #dde3f0; border-radius:8px; padding:20px 24px; margin:20px 0;">
  <ul style="padding-left:20px; margin:0; line-height:2.2;">
    <li><strong><a href="[amzn.to link]" rel="nofollow sponsored" target="_blank">[Product 1 Name]</a></strong> — [one line: why you need it for this task]</li>
    <li><strong><a href="[amzn.to link]" rel="nofollow sponsored" target="_blank">[Product 2 Name]</a></strong> — [one line: why you need it]</li>
    <li><strong><a href="[amzn.to link]" rel="nofollow sponsored" target="_blank">[Product 3 Name]</a></strong> — [one line: why you need it]</li>
    <li><strong><a href="[amzn.to link]" rel="nofollow sponsored" target="_blank">[Product 4 Name]</a></strong> — [one line: why you need it]</li>
    <!-- Add more as needed — aim for 4–6 items -->
  </ul>
</div>

<p style="font-size:13px; color:#666; margin-top:0;">⏱ <strong>Time required:</strong> [X–Y minutes] &nbsp;|&nbsp; 🎯 <strong>Difficulty:</strong> [Easy / Moderate / Advanced] &nbsp;|&nbsp; 🔁 <strong>How often:</strong> [Weekly / Monthly / Every 6 months]</p>


<!-- ===== TABLE OF CONTENTS ===== -->

<nav style="background:#f4f6fb; border:1px solid #dde3f0; border-radius:8px; padding:20px 24px; margin:28px 0;">
  <p style="margin:0 0 10px 0; font-weight:bold; font-size:15px; color:#0A173C;">Table of Contents</p>
  <ol style="margin:0; padding-left:20px; line-height:2;">
    <li><a href="#what-you-need" style="color:#0A173C; text-decoration:none; font-size:15px;">What You Need</a></li>
    <li><a href="#step-1" style="color:#0A173C; text-decoration:none; font-size:15px;">Step 1 — [Step Name]</a></li>
    <li><a href="#step-2" style="color:#0A173C; text-decoration:none; font-size:15px;">Step 2 — [Step Name]</a></li>
    <li><a href="#step-3" style="color:#0A173C; text-decoration:none; font-size:15px;">Step 3 — [Step Name]</a></li>
    <li><a href="#step-4" style="color:#0A173C; text-decoration:none; font-size:15px;">Step 4 — [Step Name]</a></li>
    <li><a href="#step-5" style="color:#0A173C; text-decoration:none; font-size:15px;">Step 5 — [Step Name]</a></li>
    <li><a href="#pro-tips" style="color:#0A173C; text-decoration:none; font-size:15px;">Pro Tips</a></li>
    <li><a href="#mistakes" style="color:#0A173C; text-decoration:none; font-size:15px;">Common Mistakes to Avoid</a></li>
    <li><a href="#faq" style="color:#0A173C; text-decoration:none; font-size:15px;">FAQ</a></li>
    <li><a href="#final-verdict" style="color:#0A173C; text-decoration:none; font-size:15px;">Final Tips</a></li>
  </ol>
</nav>


<!-- ===== STEP BLOCK — REPEAT FOR EACH STEP ===== -->
<!-- Copy this entire block for each step. Change id, number, content, product. -->

<h2 style="margin-top:48px;" id="step-1">Step 1 — [Step Name: Short Action Verb + Object]</h2>

<!-- Step Product Image — ONLY include if a specific product is recommended in this step -->
<div style="text-align:center; margin:20px auto; max-width:560px;">
  <a href="[amzn.to link]" rel="nofollow sponsored" target="_blank">
    <img src="[product image URL]"
         alt="[Product Name] — [focus keyword] [step context]"
         width="480"
         style="width:100%; max-width:480px; height:auto; display:block; margin:0 auto; border-radius:8px; box-shadow:0 2px 8px rgba(10,23,60,0.10); mix-blend-mode:multiply;" />
  </a>
  <p style="font-size:13px; color:#666; margin-top:8px; text-align:center;">[Product Name] — [one line caption relevant to this step]</p>
</div>

<p>[Step instruction paragraph — clear, actionable, 2–3 sentences. Tell the reader exactly what to do, why, and how to know they have done it correctly. Use specific numbers, temperatures, times, or measurements where possible.]</p>

<p>[Optional second paragraph: what to watch out for, common variation, or extra detail that makes the step easier.]</p>

<!-- Product recommendation for this step (only if a product is used in this step) -->
<div style="background:#f0f4ff; border-left:4px solid #0A173C; border-radius:0 8px 8px 0; padding:14px 18px; margin:16px 0 24px 0;">
  <p style="margin:0; font-size:14px;"><strong>Recommended for this step:</strong> <a href="[amzn.to link]" rel="nofollow sponsored" target="_blank"><strong>[Product Name]</strong></a> — [one sentence: why this product is best for this specific step]. <a href="[amzn.to link]" rel="nofollow sponsored" target="_blank" style="color:#0A173C; font-weight:bold;">Check price on Amazon →</a></p>
</div>

<!-- ===== END STEP BLOCK ===== -->


<!-- ===== PRO TIPS ===== -->

<h2 id="pro-tips" style="margin-top:48px;">Pro Tips for Better Results</h2>

<p>[Intro sentence: "These tips come from hands-on testing and real buyer feedback — they are the details most guides skip."]</p>

<h3>[Pro Tip 1 Title]</h3>
<p>[2–3 sentences. Specific, actionable detail that most beginner guides miss. Can include a secondary product recommendation if relevant.]</p>

<h3>[Pro Tip 2 Title]</h3>
<p>[2–3 sentences.]</p>

<h3>[Pro Tip 3 Title]</h3>
<p>[2–3 sentences. Include second dofollow Wikipedia link if natural.]</p>


<!-- ===== COMMON MISTAKES ===== -->

<h2 id="mistakes">Common Mistakes to Avoid</h2>

<p>[Intro: "Most problems come from one of these three mistakes. Avoid them and the process works every time."]</p>

<h3>❌ [Mistake 1 Title]</h3>
<p>[2–3 sentences. What the mistake is, why people make it, and the correct approach.]</p>

<h3>❌ [Mistake 2 Title]</h3>
<p>[2–3 sentences.]</p>

<h3>❌ [Mistake 3 Title]</h3>
<p>[2–3 sentences.]</p>


<!-- ===== FAQ ===== -->

<h2 id="faq">Frequently Asked Questions About [Topic]</h2>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "[Question 1 — from People Also Ask]?",
      "acceptedAnswer": { "@type": "Answer", "text": "[Answer 1 — 2-3 sentences, include focus keyword naturally.]" }
    },
    {
      "@type": "Question",
      "name": "[Question 2]?",
      "acceptedAnswer": { "@type": "Answer", "text": "[Answer 2.]" }
    },
    {
      "@type": "Question",
      "name": "[Question 3]?",
      "acceptedAnswer": { "@type": "Answer", "text": "[Answer 3.]" }
    },
    {
      "@type": "Question",
      "name": "[Question 4]?",
      "acceptedAnswer": { "@type": "Answer", "text": "[Answer 4.]" }
    },
    {
      "@type": "Question",
      "name": "[Question 5]?",
      "acceptedAnswer": { "@type": "Answer", "text": "[Answer 5.]" }
    },
    {
      "@type": "Question",
      "name": "[Question 6]?",
      "acceptedAnswer": { "@type": "Answer", "text": "[Answer 6.]" }
    },
    {
      "@type": "Question",
      "name": "[Question 7]?",
      "acceptedAnswer": { "@type": "Answer", "text": "[Answer 7.]" }
    },
    {
      "@type": "Question",
      "name": "[Question 8]?",
      "acceptedAnswer": { "@type": "Answer", "text": "[Answer 8.]" }
    }
  ]
}
</script>

<h3>[Question 1]?</h3>
<p>[Answer 1 — 2–3 sentences. Focus keyword included naturally.]</p>

<h3>[Question 2]?</h3>
<p>[Answer 2 — 2–3 sentences.]</p>

<h3>[Question 3]?</h3>
<p>[Answer 3 — 2–3 sentences. Secondary keyword included.]</p>

<h3>[Question 4]?</h3>
<p>[Answer 4 — 2–3 sentences.]</p>

<h3>[Question 5]?</h3>
<p>[Answer 5 — 2–3 sentences.]</p>

<h3>[Question 6]?</h3>
<p>[Answer 6 — 2–3 sentences.]</p>

<h3>[Question 7]?</h3>
<p>[Answer 7 — 2–3 sentences. Focus keyword included.]</p>

<h3>[Question 8]?</h3>
<p>[Answer 8 — 2–3 sentences.]</p>


<!-- ===== FINAL TIPS + INTERNAL LINKS ===== -->

<h2 id="final-verdict">Final Tips — [How to Task] Done Right</h2>

<p>[1–2 sentences summarizing the most important thing to remember. Restate focus keyword naturally. Example: "Knowing how to [task] correctly comes down to one thing: [key insight]. Follow the steps in this guide and you will get [specific result] every time."]</p>

<p>[Product roundup sentence: "For the products we used in this guide, the <strong><a href="[amzn.to top product]" rel="nofollow sponsored" target="_blank">[Top Product Name]</a></strong> is our top recommendation — [one reason why]."]</p>

<p>Looking for more guides? Browse our full <a href="/[category-hub]/">[Category] hub</a> for more step-by-step guides and product picks. You may also find our guide to the <a href="/[category]/[related-article]/">[Related Article Title]</a> useful, and our <a href="/[category]/[related-article-2]/">[Related Article 2]</a> covers everything you need for the next step.</p>

<!-- Final CTA -->
<div style="text-align:center; margin:24px 0 40px 0;">
  <a href="[amzn.to top product link]" rel="nofollow sponsored" target="_blank"
     style="background:#0A173C; color:#fff; padding:14px 36px; text-decoration:none; border-radius:5px; display:inline-block; font-size:16px; font-weight:bold; margin-bottom:10px;">
    Get the Recommended Product on Amazon →
  </a>
</div>


<!-- ===== DISCLOSURE — BOTTOM ===== -->

<h2>Affiliate Disclosure</h2>
<h3>How We Make Money on HomeAppliancePicks.com</h3>
<p>HomeAppliancePicks.com is a participant in the Amazon Services LLC Associates Program, an affiliate advertising program designed to provide a means for sites to earn advertising fees by advertising and linking to Amazon.com. As an Amazon Associate, I earn from qualifying purchases. All product prices are accurate at the time of publication. We independently research, test, and recommend products; we may receive commissions on purchases made through our links.</p>
```

---

## ARTICLE STRUCTURE — QUICK REFERENCE

```
H1 Title
Hero Image (ST-10 Magazine Spread — centered, max-width 780px)
Disclosure — Top
Intro (2 paragraphs)
What You Need (product list with affiliate links)
Time / Difficulty / Frequency badge
Table of Contents
Step 1 (H2) → instruction + product recommendation box
Step 2 (H2) → instruction + product recommendation box
Step 3 (H2) → instruction + product recommendation box
Step 4 (H2) → instruction + product recommendation box
Step 5 (H2) → instruction + product recommendation box
Pro Tips (H2 → H3s)
Common Mistakes (H2 → H3s)
FAQ (H2 + 8 Q&As + JSON-LD schema)
Final Tips + Internal Links (H2)
Affiliate Disclosure — Bottom
```

---

## IMAGE RULES FOR TEMP4

- **Hero image:** `max-width:780px; width:100%; height:auto` — centered, full-width responsive, NO mix-blend-mode (editorial image, not product)
- **Step product images:** `max-width:480px; width:100%; height:auto; mix-blend-mode:multiply` — centered, medium size
- **Never use fixed pixel widths** — always use `max-width` + `width:100%` so images scale correctly on mobile
- **Always include `height:auto`** — prevents image distortion on resize
- **Hero image does NOT use mix-blend-mode** — it is a generated editorial image, not a product photo
- **Step product images DO use mix-blend-mode:multiply** — removes white backgrounds from Amazon product photos

---

## HOWTO SCHEMA — ADD TO RANK MATH

In addition to FAQ schema, TEMP4 articles should have HowTo schema. Set in: **Rank Math → Advanced → Schema → HowTo**

Fill in:

- Name: article title
- Description: meta description
- Total Time: [e.g. PT15M for 15 minutes]
- Steps: one entry per H2 step with name and description

---

## PRE-PUBLISH CHECKLIST — TEMP4

- [ ] Word count 2,000–2,500
- [ ] Focus keyword ("how to X") in H1 at the start
- [ ] Focus keyword in first 100 words
- [ ] Focus keyword in at least 3 H2 step headings or section headings
- [ ] Focus keyword in hero image alt text
- [ ] Keyword density 1–1.5%
- [ ] URL slug under 60 characters, contains focus keyword, no year
- [ ] Meta title under 60 characters
- [ ] Meta description 150–160 characters with → at end
- [ ] Hero image: max-width 780px, centered, height:auto, no mix-blend-mode
- [ ] Step product images: max-width 480px, mix-blend-mode:multiply
- [ ] At least 4 affiliate product links (one per step minimum)
- [ ] "What You Need" list with affiliate links at top
- [ ] Time / Difficulty / Frequency badge present
- [ ] Product recommendation box (blue highlight) in each relevant step
- [ ] Pro Tips section present (3+ tips)
- [ ] Common Mistakes section present (3 mistakes)
- [ ] 8 FAQ questions with JSON-LD schema block
- [ ] HowTo schema set in Rank Math Advanced
- [ ] 1–2 dofollow Wikipedia links in intro or pro tips
- [ ] 3+ internal links: at least 1 category hub + 2 article links
- [ ] Disclosure at TOP (below hero image) and BOTTOM
- [ ] Rank Math score 90+ before publishing
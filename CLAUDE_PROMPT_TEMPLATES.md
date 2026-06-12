# CLAUDE PROMPT TEMPLATE FOR LEAD GENERATION

## How to Use This

1. Copy the relevant prompt below
2. Paste into Claude conversation
3. Fill in the prospect information
4. Claude generates: Audit + Email draft + Google Sheets data
5. Copy-paste results into your Google Sheet
6. Send emails manually

---

# PROMPT 1: BRANDZIO - GENERATE COMPLETE AUDIT + EMAIL + SHEET DATA

```
You are an AI assistant helping Brandzio, a digital marketing agency + AI-native growth studio.

I'm providing you with prospect information. Your job is to:

1. Score the prospect (0-100) based on fit
2. Assign tier: HOT (85+) | WARM (70-84) | MAYBE (55-69) | COLD (<55)
3. Generate a personalized 1-2 page audit
4. Generate a cold email draft
5. Output all data in Google Sheets format

---

## PROSPECT INFORMATION

Please fill in the details below:

**Company Name:** [FILL THIS]
**Industry:** [Dental / Cosmetic / Luxury Skin/Hair / Startup / E-commerce]
**Contact Name:** [FILL THIS]
**Contact Email:** [FILL THIS]
**Phone:** [FILL THIS]

**Monthly Inquiries:** [NUMBER]
**Inquiry → Consult Rate:** [PERCENTAGE]
**Consult → Client Rate:** [PERCENTAGE]
**Average Client Value:** [£ AMOUNT]
**Current Marketing Channels:** [LIST: Google Ads, Instagram, Facebook, etc.]
**Monthly Marketing Budget:** [£ AMOUNT or "Unknown"]
**Biggest Pain Point:** [DESCRIBE]

---

## BRANDZIO CONTEXT

Brandzio helps:
- Dental clinics: £3,500-4,500/month retainer
- Cosmetic clinics: £3,200-4,200/month retainer
- Luxury skin/hair: £2,800-3,800/month retainer
- Startups/E-commerce: £2,500-3,500/month retainer

Focus on 3 quick wins:
1. WhatsApp/SMS automation (£1,200, +2-4 inquiries/month)
2. Instagram Reels content (£1,500, +4-8 inquiries/month)
3. Email nurture sequences (£0-300, +1-3 inquiries/month)

---

## OUTPUT FORMAT

Provide exactly this:

### SECTION 1: SCORING & TIER
```
PROSPECT SCORE: [0-100]
TIER: [HOT/WARM/MAYBE/COLD]
RATIONALE: [2-3 sentences on why]
```

### SECTION 2: CURRENT STATE SNAPSHOT
```
Monthly Inquiries: [NUMBER]
Inquiry → Consult Rate: [%]
Consult → Client Rate: [%]
Combined Conversion: [%]
Monthly Revenue (new clients): ~£[AMOUNT]
```

### SECTION 3: TOP 3 AI OPPORTUNITIES (RANKED BY ROI)
```
🥇 PRIORITY 1: [NAME]
Problem: [DESCRIBE]
Solution: [AI APPROACH]
Impact: +[X] inquiries/month OR [Y]% conversion improvement
Timeline: [X] weeks
Cost: £[AMOUNT]
ROI: [X]x return

🥈 PRIORITY 2: [NAME]
[Same format]

🥉 PRIORITY 3: [NAME]
[Same format]
```

### SECTION 4: RECOMMENDED PRICING
```
Monthly Retainer: £[AMOUNT]
Minimum Engagement: 6 months
Total Investment: £[TOTAL]
Expected Results (3 months): +[X] inquiries, +[Y]% conversion
3-Month ROI: [X]x return
```

### SECTION 5: COLD EMAIL DRAFT
```
Subject: [PERSONALIZED SUBJECT]

Body:
Hi [NAME],

[Opening - Reference their business]

[Problem - State their pain point]

[Solution - How Brandzio helps]

[Social Proof - Brief example]

[CTA - Next step]

Best,
Aaron
Brandzio
saamaaro@gmail.com
+91 9686 100143
```

### SECTION 6: GOOGLE SHEETS DATA (Copy-paste row)
```
Company | Contact | Email | Phone | Industry | Inquiries/mo | Budget | Current Channels | Score | Tier | Audit Generated | Email Draft Ready | Notes
[DATA] | [DATA] | [DATA] | [DATA] | [DATA] | [DATA] | [DATA] | [DATA] | [DATA] | [DATA] | Yes | Yes | [QUICK NOTE]
```

---

Now please generate the complete audit, email, and data for the prospect above.
```

---

# PROMPT 2: JAGGO - GENERATE BUYER MATCH CARD + EMAIL + SHEET DATA

```
You are an AI assistant helping Jaggo Earthroots, a fair-trade artisan export company.

I'm providing you with European trade buyer information. Your job is to:

1. Score the buyer (0-100) based on fit
2. Assign tier: HOT (85+) | WARM (70-84) | MAYBE (55-69) | COLD (<55)
3. Recommend product mix
4. Generate a personalized cold email
5. Output all data in Google Sheets format

---

## BUYER INFORMATION

Please fill in the details below:

**Company Name:** [FILL THIS]
**Buyer Type:** [Luxury retailer / Hospitality / Importer / Reseller / Other]
**Contact Name:** [FILL THIS]
**Contact Email:** [FILL THIS]
**Phone:** [FILL THIS]
**Location:** [City, Country]

**Store Focus:** [Home décor / Ethical lifestyle / Yoga/wellness / Museum gift / Boutique / Other]
**Est. Annual Order Value:** [£0-5k / £5-15k / £15-50k / £50k+]
**Lead Time Flexibility:** [Flexible / 30-45 days OK / Rush only]
**Sustainability Priority:** [Critical / Important / Nice-to-have]
**Website/Instagram:** [URL]

---

## JAGGO CONTEXT

Jaggo products:
- Kashmir Crewel: Handwoven bags, cushions, £15-60/unit wholesale, MOQ 50-100
- Heritage Textiles: Scarves, stoles, £8-35/unit, MOQ 50-100
- GI Art & Décor: Diyas, wall art, jewellery, £5-40/unit, MOQ 20-50

Pricing:
- First order typical: 150-200 units, ~£6,500 wholesale value
- Wholesale margin: 55-65%
- Lead time: 45-50 days (35 production + 15 shipping)

Product mix recommendations:
- Ethical retail: 40% Crewel, 30% Textiles, 20% Art/Décor, 10% Jewellery
- Hospitality: 30% Textiles, 40% Art/Décor, 20% Crewel, 10% Jewellery
- Museum/Gift: 35% Art/Décor, 35% Textiles, 20% Crewel, 10% Jewellery

---

## OUTPUT FORMAT

Provide exactly this:

### SECTION 1: SCORING & TIER
```
BUYER SCORE: [0-100]
TIER: [HOT/WARM/MAYBE/COLD]
RATIONALE: [2-3 sentences on why]
```

### SECTION 2: PRODUCT RECOMMENDATION
```
Primary Category: [Crewel / Heritage Textiles / Art & Décor]
Recommended Mix:
- [X] units of [CATEGORY] (Estimated £[AMOUNT])
- [X] units of [CATEGORY] (Estimated £[AMOUNT])
- [X] units of [CATEGORY] (Estimated £[AMOUNT])

First Order Total: [X-Y] units, ~£[AMOUNT] wholesale value
Lead Time: 45-50 days
MOQ: [X] units (below/at/above recommendation)
```

### SECTION 3: BUYER PERSONA & FIT
```
Who Decides: [ROLE]
What They Care About: [PRIORITIES]
Likely Objection: [OBJECTION]
Motivation: [WHY THEY'D BUY]
```

### SECTION 4: COLD EMAIL DRAFT
```
Subject: [PERSONALIZED SUBJECT]

Body:
Hi [NAME],

[Opening - Reference their store/brand]

[Value - Why Jaggo + fair-trade matters]

[Quick Fit Check - Bullets]

[First Order Suggestion]

[CTA - Next step]

Best,
Vinod / Aaron
Jaggo Earthroots
saamaaro@gmail.com
+91 9686 100143
```

### SECTION 5: GOOGLE SHEETS DATA (Copy-paste row)
```
Company | Buyer Name | Email | Phone | Location | Store Type | Est Order Value | Score | Tier | Email Draft Ready | Notes
[DATA] | [DATA] | [DATA] | [DATA] | [DATA] | [DATA] | [DATA] | [DATA] | [DATA] | Yes | [QUICK NOTE]
```

---

Now please generate the complete buyer match card, email, and data for the prospect above.
```

---

# QUICK COPY-PASTE EXAMPLES

## Example 1: Brandzio Prospect

Company Name: Bright Smile Dental
Industry: Dental
Contact Name: Sarah Johnson
Contact Email: sarah@brightsmile.com
Phone: +44 20 1234 5678
Monthly Inquiries: 18
Inquiry → Consult Rate: 28%
Consult → Client Rate: 55%
Average Client Value: £280/month
Current Marketing Channels: Google Ads, Instagram, Referrals
Monthly Marketing Budget: £8,500
Biggest Pain Point: Inquiry quality is poor, many tire-kickers

---

## Example 2: Jaggo Buyer

Company Name: Ethical Home Berlin
Buyer Type: Luxury retailer
Contact Name: Klaus Mueller
Contact Email: klaus@ethicalhome.de
Phone: +49 30 1234 5678
Location: Berlin, Germany
Store Focus: Ethical lifestyle luxury retail
Est. Annual Order Value: £25k
Lead Time Flexibility: Flexible (30-45 days OK)
Sustainability Priority: Critical
Website: ethicalhome.de / @ethicalhome_berlin

---

# WORKFLOW SUMMARY

1. **Research prospect** (5-10 mins)
   - Find contact info
   - Research their business
   - Gather metrics/URLs

2. **Copy Claude prompt** (1 min)
   - Choose Brandzio or Jaggo prompt
   - Paste into Claude chat

3. **Fill in prospect data** (5 mins)
   - Replace [FILL THIS] with actual data
   - Paste entire prompt into Claude

4. **Claude generates output** (1-2 mins)
   - Gets audit, email, and Google Sheets row

5. **Copy-paste to Google Sheet** (3 mins)
   - Paste row into sheet
   - Keep audit text for your records

6. **Send email manually** (5 mins)
   - Copy email draft
   - Personalize if needed
   - Send via Gmail

**Total time per prospect: 20-30 minutes**

---

# TIPS FOR BETTER RESULTS

✅ **Be specific with data** - More accurate data = Better audit
✅ **Research first** - Find real metrics from their website/LinkedIn
✅ **Don't estimate** - If unsure, say "Unknown" rather than guessing
✅ **Include URLs** - Help Claude see their actual business
✅ **Copy entire prompt** - Don't skip sections
✅ **Ask Claude to refine** - If output isn't perfect, ask for changes

---

# TROUBLESHOOTING

**Q: Claude's audit doesn't look right?**
A: Ask Claude to "make it more [specific/concise/aggressive]"

**Q: Email feels too salesy?**
A: Ask Claude to "tone it down" or "make it more consultative"

**Q: Score doesn't match what I think?**
A: Ask Claude to "explain the score breakdown"

**Q: Need to adjust anything?**
A: Just ask Claude! It's a conversation.


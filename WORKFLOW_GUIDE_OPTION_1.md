# COMPLETE WORKFLOW GUIDE: Option 1 (Manual Claude)

## Overview

You have a **20-30 minute workflow** per prospect:

1. **Research prospect** (5-10 mins) → Find contact info, metrics, pain points
2. **Prepare data** (2 mins) → Organize what you found
3. **Use Claude prompt** (1-2 mins) → Copy-paste template, fill data
4. **Claude generates** (1-2 mins) → Audit + email + Google Sheets row
5. **Copy to Google Sheet** (3 mins) → Paste data into sheet
6. **Send email** (5 mins) → Copy email, send via Gmail, update sheet

---

## STEP-BY-STEP WORKFLOW

### STEP 1: RESEARCH THE PROSPECT (5-10 minutes)

#### For Brandzio Prospects (Dental, Cosmetic, Skincare, Startups)

**Find this information:**
- Company website → Current services, pricing
- LinkedIn → Company size, decision maker, industry
- Google Maps → Business listing, reviews (shows volume)
- Instagram → Content quality, engagement, audience size
- Their ads → Are they running Google/Facebook ads? What messaging?

**Gather these metrics:**
- How many reviews/followers = proxy for inquiry volume
- Website traffic rank (optional, use Similarweb)
- Social media posting frequency = marketing sophistication
- Current marketing channels (evident from website footer, ads)

**Find contact info:**
- Company website → "Contact" or "Book Consultation"
- LinkedIn → Search decision maker (Owner, Marketing Manager, Practice Manager)
- Hunter.io or Clearbit → Email format
- Directly call and ask

**Example research output:**
```
Company: Bright Smile Dental
URL: brightsmile.com
Decision Maker: Sarah Johnson (Practice Manager)
Email: sarah@brightsmile.com
Phone: +44 20 1234 5678

Metrics (estimated from research):
- Website gets ~200 visits/month (backlinks suggest local search)
- Instagram: 1.2k followers, posting 3x/week
- Currently running Google Ads (see ads at bottom of website)
- Services: General + Cosmetic dentistry
- Price range: £150-400/month retainers based on typical procedures

Pain point: Website is dated, social media is inconsistent = likely struggling with inquiry quality
```

#### For Jaggo Buyers (European Retailers, Hospitality, Importers)

**Find this information:**
- Company website → Product range, price point, brand positioning
- Instagram/Instagram Shop → What's selling, engagement, aesthetic
- LinkedIn → Company size, buyer role, headquarters
- Glassdoor/Facebook → Company reviews (shows ethics focus)
- Google Maps → Physical location, reviews (shows foot traffic)

**Gather these metrics:**
- Product price range = luxury indicator
- Social media followers = buyer sophistication
- Posting frequency & aesthetic = brand consciousness
- Reviews mention = "ethical", "fair-trade", "artisan" = sustainability focus

**Find contact info:**
- Website → "Wholesale" or "Contact Us" page
- LinkedIn → Search "Buyer", "Merchandiser", "Owner"
- Email format from domain
- Call and ask for buyer

**Example research output:**
```
Company: Ethical Home Berlin
URL: ethicalhome.de
Decision Maker: Klaus Mueller (Buyer)
Email: klaus@ethicalhome.de
Phone: +49 30 1234 5678

Metrics (from research):
- Website: Luxury home décor, €100-500 price range
- Instagram: 8.5k followers, daily posts, high engagement
- Product aesthetic: Contemporary + ethical = perfect for Jaggo
- Ethical positioning: 5★ reviews mention "fair-trade" and "sustainable"
- Store location: Mitte district Berlin = high foot traffic

Pain point: High-end retailer looking for exclusive, ethical suppliers
```

---

### STEP 2: PREPARE YOUR DATA (2 minutes)

**Create a simple text note with all the info:**

```
=== BRANDZIO PROSPECT ===

Company Name: Bright Smile Dental
Industry: Dental
Contact Name: Sarah Johnson
Contact Email: sarah@brightsmile.com
Phone: +44 20 1234 5678

Monthly Inquiries: 18 (estimated from Google reviews + website traffic)
Inquiry → Consult Rate: 28% (typical for dental clinics with poor follow-up)
Consult → Client Rate: 55% (typical for cosmetic-focused clinic)
Average Client Value: £280/month (recurring patients)
Current Marketing Channels: Google Ads, Instagram, Referrals
Monthly Marketing Budget: £8,500 (appears from ad frequency + website quality)
Biggest Pain Point: Inquiry quality is poor — they're getting leads but many tire-kickers
```

---

### STEP 3: USE CLAUDE PROMPT (1-2 minutes)

**In Claude conversation:**

1. Go to https://claude.ai → Start new conversation
2. Copy the relevant prompt from CLAUDE_PROMPT_TEMPLATES.md
   - For Brandzio → Copy "PROMPT 1: BRANDZIO - GENERATE COMPLETE AUDIT..."
   - For Jaggo → Copy "PROMPT 2: JAGGO - GENERATE BUYER MATCH CARD..."
3. Replace [FILL THIS] with your research data
4. Paste entire thing into Claude
5. Press Enter

**Example (Brandzio):**

```
[Copy full prompt from CLAUDE_PROMPT_TEMPLATES.md]

[Replace fields:]
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

[Paste entire prompt into Claude]
```

---

### STEP 4: CLAUDE GENERATES (1-2 minutes)

Claude will output:

✅ **SECTION 1: SCORING & TIER**
```
PROSPECT SCORE: 87
TIER: HOT
RATIONALE: High budget (£8,500/month), clear pain point (inquiry quality), already investing in marketing. Easy to help.
```

✅ **SECTION 2: CURRENT STATE SNAPSHOT**
```
Monthly Inquiries: 18
Inquiry → Consult Rate: 28% (industry avg: 30-35%)
Consult → Client Rate: 55% (industry avg: 45-55%)
Combined Conversion: 15% (industry avg: 14-19%)
Monthly Revenue (new clients): ~£2,352 (18 inquiries × 28% × 55% × £280/client)
```

✅ **SECTION 3: TOP 3 AI OPPORTUNITIES**
```
🥇 PRIORITY 1: WhatsApp Pre-Qualification Bot
Problem: 72% of inquiries are tire-kickers (not serious about treatment)
Solution: WhatsApp bot that pre-qualifies based on treatment interest, budget, timeline
Impact: +25% qualified inquiry rate = more consultations from same traffic
Timeline: 2 weeks
Cost: £1,200 (setup) + £200/month
ROI: 3.5x (saves sales time, increases conversions)
...
```

✅ **SECTION 4: RECOMMENDED PRICING**
```
Monthly Retainer: £3,500 (Dental clinic bracket)
Minimum Engagement: 6 months
Total Investment: £21,000
Expected Results (3 months): +8 inquiries/month (18→26), +10% conversion (15%→25%)
3-Month ROI: 2.1x return
```

✅ **SECTION 5: COLD EMAIL DRAFT**
```
Subject: Your Bright Smile clinic is leaving £2,800 on the table each month

Body:
Hi Sarah,

I work with boutique dental clinics helping them scale inquiries and convert faster.

I noticed Bright Smile is getting around 18 inquiries per month, but only 28% are booking consultations...
[Full email]
```

✅ **SECTION 6: GOOGLE SHEETS DATA**
```
Bright Smile Dental | Sarah Johnson | sarah@brightsmile.com | +44 20 1234 5678 | Dental | 18 | £8,500 | Google Ads, Instagram, Referrals | 87 | HOT | Yes | Yes | Good budget, clear pain point
```

---

### STEP 5: COPY TO GOOGLE SHEET (3 minutes)

1. **Open your Google Sheet:** https://sheets.google.com/YOUR_SHEET
2. **Go to relevant tab:**
   - Brandzio tab for dental/cosmetic/startups
   - Jaggo tab for European buyers
3. **Find the next empty row** (or scroll to bottom)
4. **Copy-paste the data row from Claude** into your sheet
5. **Fill in the date** in Column A (today's date)
6. **Leave Email Sent, Response, Call Booked blank** for now

**Example in Sheet:**

```
Date | Company | Contact | Email | Phone | Industry | Inquiries | Budget | Channels | Score | Tier | Notes
11/06/2026 | Bright Smile Dental | Sarah Johnson | sarah@brightsmile.com | +44 20 1234 5678 | Dental | 18 | £8,500 | Google Ads, Instagram, Referrals | 87 | HOT | Good budget, clear pain point
```

---

### STEP 6: SEND EMAIL (5 minutes)

1. **Open Gmail:** gmail.com
2. **Click Compose**
3. **To:** sarah@brightsmile.com (from Claude data)
4. **Subject:** Copy from Claude email draft
5. **Body:** Copy from Claude email draft
6. **Personalize (optional):**
   - Change generic phrases to specific references
   - Add calendar link if available
7. **Send**
8. **Update Google Sheet:**
   - Column N (Email Sent): "Yes"
   - Column N (Email Sent Date): Today's date

---

## FULL WORKFLOW TIMELINE (Per Prospect)

```
0:00 - Start research
0:10 - Finish research, prepare data
0:12 - Open Claude, copy prompt
0:13 - Fill in prospect data in prompt
0:14 - Paste into Claude, send
0:16 - Claude generates output (wait)
0:17 - Claude finishes, read output
0:22 - Copy data to Google Sheet
0:25 - Open Gmail, compose email
0:28 - Personalize and send email
0:30 - Update Sheet with email sent status

TOTAL: 30 minutes per prospect
```

---

## WEEKLY WORKFLOW

### MONDAY-TUESDAY: BRANDZIO OUTREACH (2-3 hours)

```
Target: 5-7 new prospects

0:00 - Open research tab (Google Docs with prospects to research)
0:10 - Research prospect 1, prepare data
0:25 - Use Claude prompt, generate audit
0:30 - Copy to Google Sheet
0:35 - Send email
0:40 - Repeat for prospects 2-7
2:00 - Done with 5 prospects
```

### WEDNESDAY-THURSDAY: JAGGO OUTREACH (2-3 hours)

```
Target: 10-15 new European buyers

0:00 - Open buyer research list (LinkedIn, design websites)
0:10 - Research buyer 1, prepare data
0:25 - Use Claude prompt, generate match card
0:30 - Copy to Google Sheet
0:35 - Send email
0:40 - Repeat for buyers 2-15
2:30 - Done with 10-15 buyers
```

### FRIDAY: ADMIN + FOLLOW-UPS (1-2 hours)

```
0:00 - Check Gmail for replies
0:15 - Update Google Sheet with responses
0:30 - Send follow-up emails to WARM tier (no response)
0:45 - Review metrics in Summary tab
1:00 - Prepare next week's prospect list
1:30 - Done
```

---

## MONTHLY CHECKLIST

### Week 1
- [ ] Research and add 5-7 Brandzio prospects
- [ ] Research and add 10-15 Jaggo buyers
- [ ] Send all HOT tier emails
- [ ] Update Google Sheet

### Week 2
- [ ] Follow up on HOT tier (if no response)
- [ ] Send WARM tier emails
- [ ] Add new prospects as you find them
- [ ] Review replies, update status

### Week 3
- [ ] Book calls with interested prospects
- [ ] Update "Call Booked" column
- [ ] Follow up pending responses
- [ ] Add new prospects

### Week 4
- [ ] Review monthly metrics (Summary tab)
- [ ] Check conversion rates (emails sent → calls booked)
- [ ] Identify best-performing industries/geographies
- [ ] Plan next month's targets
- [ ] Archive lost prospects

---

## SUCCESS METRICS

### Brandzio Targets
- Month 1: 12-15 prospects researched, 5-6 emails sent, 2-3 calls booked, 0-1 clients
- Month 2: Repeat + 1-2 new clients signed
- Month 3: 2-3 clients total

### Jaggo Targets
- Month 1: 40-50 buyers identified, 15-20 emails sent, 0-1 calls booked
- Month 2: 2-4 calls booked with Vinod
- Month 3: 1-2 orders placed

---

## COMMON ISSUES & FIXES

### Issue: "Claude's audit doesn't match my expectations"

**Fix:**
```
Ask Claude:
"Can you make the audit more focused on [specific opportunity]?"
or
"The score seems high. Can you lower it to 75 based on [reason]?"
or
"Can you make the email less salesy and more consultative?"

Claude will adjust!
```

### Issue: "I can't find contact information"

**Fix:**
```
1. Use Hunter.io (free tier) → enter domain, get emails
2. Use RocketReach → search by company
3. Call the company directly → ask for buyer/practice manager
4. LinkedIn → search by title + company
```

### Issue: "Research is taking too long"

**Fix:**
```
1. Limit research to 5-7 minutes max
2. Use templates → know what data you need before starting
3. Focus on key metrics only → ignore nice-to-haves
4. Make estimates → it's OK to estimate monthly inquiries
```

### Issue: "Google Sheet is getting messy"

**Fix:**
```
1. Freeze header row (View → Freeze → 1 row)
2. Add filters (Data → Create a filter)
3. Color code by tier (HOT = red, WARM = yellow)
4. Archive old rows into "Archive" tab
```

---

## TIPS FOR SPEED

✅ **Create templates in Google Docs** → Copy prospect structure so you fill it in seconds
✅ **Use Claude bookmarks** → Save the prompt in your browser
✅ **Set up Gmail filters** → Automatically sort Brandzio vs Jaggo replies
✅ **Use keyboard shortcuts** → Ctrl+C/Ctrl+V to copy-paste faster
✅ **Batch similar tasks** → Do all research first, then all Claude prompts, then all emails
✅ **Set timers** → Keep yourself on pace (5 mins research, 2 mins prep, etc)

---

## YOU'RE READY TO GO!

Next steps:

1. ✅ Set up Google Sheet (columns from GOOGLE_SHEETS_TEMPLATE.md)
2. ✅ Copy Claude Prompt (from CLAUDE_PROMPT_TEMPLATES.md)
3. ✅ Find 1 prospect to test
4. ✅ Research them (5-10 mins)
5. ✅ Use Claude prompt (get audit in 2 mins)
6. ✅ Copy to Google Sheet (3 mins)
7. ✅ Send email (5 mins)
8. ✅ Track response

**Total for first prospect: 30 minutes**

If it works → Scale to 5-7/week

Let me know if you get stuck! 🚀

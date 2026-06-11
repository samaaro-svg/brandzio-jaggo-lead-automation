# Brandzio + Jaggo Earthroots: Complete Lead Automation Framework

## 📁 What's in This Repository

This repository contains **complete automation templates** for generating and capturing leads for both Brandzio (digital marketing agency) and Jaggo Earthroots (artisanal exports).

### Files Included

1. **BRANDZIO_PROSPECT_TEMPLATE.txt**
   - 8-question intake form for collecting prospect information
   - Scoring guidelines (HOT/WARM/MAYBE/COLD)
   - Instructions for deploying via email, Typeform, Airtable, or Zapier

2. **AUDIT_OUTPUT_TEMPLATE.md**
   - Complete 1-2 page audit PDF template
   - Sections: Current state, AI opportunities, benchmarks, quick wins, pricing recommendation
   - Ready to customize for each prospect

3. **PRICING_QUICK_REFERENCE.txt**
   - Monthly retainer pricing by industry & tier
   - Negotiation scripts & objection handling
   - Upsell & expansion opportunities

4. **IMPLEMENTATION_PLAYBOOK.md** (Referenced)
   - Weekly cadence & operational guidelines
   - Google Sheet structure
   - Meeting scripts
   - Success metrics

---

## 🚀 How to Use This Framework

### STEP 1: Collect Prospect Data
1. Use **BRANDZIO_PROSPECT_TEMPLATE.txt**
2. Send the 8-question form via:
   - Email
   - Google Forms / Typeform
   - Airtable
   - LinkedIn / WhatsApp (direct messaging)

### STEP 2: Score the Prospect
1. Review their answers against scoring criteria
2. Assign tier: HOT (85+) | WARM (70-84) | MAYBE (55-69) | COLD (<55)

### STEP 3: Generate Audit
1. Use **AUDIT_OUTPUT_TEMPLATE.md**
2. Plug in prospect data
3. Fill in personalized sections (opportunities, benchmarks, quick wins)
4. Export as PDF

### STEP 4: Assign Pricing
1. Use **PRICING_QUICK_REFERENCE.txt**
2. Look up prospect tier & industry
3. Recommend retainer price in audit
4. Prepare negotiation script if needed

### STEP 5: Send + Follow-up
1. Email audit to prospect
2. Schedule 30-min discovery call
3. Log in Google Sheet (shared CRM)
4. Follow up based on tier:
   - HOT: This week
   - WARM: 2-week email sequence
   - MAYBE: Monthly nurture
   - COLD: Archive

---

## 📊 Integration with Automation Tools

### Option A: Manual Workflow
1. Prospect fills form (email/Typeform)
2. You review answers
3. You fill in audit template
4. You send PDF + schedule call
5. Log in Google Sheet

**Time per prospect:** ~35-40 minutes

### Option B: Semi-Automated (Zapier/Make.com)
1. Prospect fills Typeform
2. Zapier captures response → sends to Claude API
3. Claude auto-generates audit text
4. Zapier sends audit PDF + calendar invite to prospect
5. Zapier logs response to Google Sheet

**Time per prospect:** ~5 minutes (review only)

### Option C: Fully Automated (Zapier + Claude + Email)
1. Prospect fills Typeform
2. Zapier → Claude API → generates audit
3. Zapier → Google Docs → converts to PDF
4. Zapier → Gmail → sends audit + calendar link automatically
5. Zapier → Google Sheets → logs lead

**Time per prospect:** ~1 minute (you just wait for replies)

---

## 🔧 Setup Instructions

### For Manual Workflow
1. Copy **BRANDZIO_PROSPECT_TEMPLATE.txt** → Create Google Form or send as email
2. Copy **AUDIT_OUTPUT_TEMPLATE.md** → Save as Google Doc template
3. Copy **PRICING_QUICK_REFERENCE.txt** → Keep on desk as reference
4. Create Google Sheet with columns: Company | Contact | Email | Score | Tier | Audit Sent | Call Booked | Status
5. Start reaching out to prospects

### For Semi-Automated Workflow (Zapier)
**Prerequisites:** Typeform account, Zapier account, Claude API key

**Workflow:**
```
Typeform Submission
↓
Zapier (Capture)
↓
Claude API (Generate audit text)
↓
Zapier (Send email with audit)
↓
Google Sheets (Log lead)
```

**Zapier Actions:**
1. Trigger: Typeform response submitted
2. Action 1: Format response into Claude prompt
3. Action 2: Call Claude API (custom action) with prompt
4. Action 3: Send email with Claude output
5. Action 4: Append to Google Sheet

### For Fully Automated Workflow (Advanced)
**Prerequisites:** All of above + Google Docs API + Gmail API

**Workflow:**
```
Typeform Submission
↓
Zapier (Capture)
↓
Claude API (Generate audit)
↓
Google Docs (Create doc from template)
↓
Google Drive (Convert to PDF)
↓
Gmail (Send PDF)
↓
Google Calendar (Send meeting invite)
↓
Google Sheets (Log everything)
```

---

## 📈 Success Metrics

### Month 1 Targets
- **Brandzio:** 12-15 prospects researched, 5-6 audits sent, 2-3 calls booked
- **Jaggo:** 40-50 buyers identified, 15-20 matcher cards generated

### Month 3 Targets
- **Brandzio:** 1-2 clients signed at £3,000-4,500/month = £6,000-9,000 MRR
- **Jaggo:** 2-3 orders placed at £5,000-8,000 each = £10,000-24,000 revenue

---

## 🎯 Key Customization Points

Before deploying, customize these files with:

1. **Your contact info** (email: samaaro@gmail.com, phone: [YOUR_PHONE])
2. **Your benchmarks** (industry averages specific to your clients)
3. **Your pricing** (update retainer ranges if different)
4. **Your quick wins** (tailor AI opportunities to your services)
5. **Your calendar link** (Calendly or Google Calendar)
6. **Your team names** (if working with partners)

---

## 📞 Questions?

**Email:** samaaro@gmail.com  
**Phone:** [YOUR_PHONE]

For technical questions about automation setup, check Zapier docs or contact support.

---

## 📝 Version History

**v1.0** (June 11, 2026)
- Initial release
- 3 core templates: Prospect intake, Audit output, Pricing reference
- Manual + semi-automated workflows documented

---

**Last Updated:** June 11, 2026

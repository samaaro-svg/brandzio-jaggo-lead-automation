# GOOGLE SHEETS TEMPLATE FOR LEAD TRACKING

## How to Use This

1. **Create new Google Sheet** → Open https://sheets.google.com
2. **Copy the columns below** → Create headers in your sheet
3. **Share with team** → Get link for Vinod or team members
4. **Fill in data** → As Claude generates leads
5. **Track progress** → Use tabs and formulas to monitor pipeline

---

## BRANDZIO LEADS - Tab 1

### Column Headers (Copy these into Row 1)

```
A: Date Added
B: Company Name
C: Contact Name
D: Email
E: Phone
F: Industry
G: Monthly Inquiries
H: Current Budget (£)
I: Main Channels
J: Pain Point
K: Score (0-100)
L: Tier (HOT/WARM/MAYBE/COLD)
M: Audit Generated
N: Email Sent
O: Response
P: Call Booked
Q: Status
R: Notes
```

### Sample Row (To show format)

```
11/06/2026 | Bright Smile Dental | Sarah Johnson | sarah@brightsmile.com | +44 20 1234 5678 | Dental | 18 | £8,500 | Google Ads, Instagram, Referrals | Poor inquiry quality | 87 | HOT | Yes | 11/06/2026 | 12/06/2026 - Replied positive | Pending | In discussion | Good budget, clear pain point
```

### Formatting Tips

**Column A (Date Added):** Set format to Date
**Column K (Score):** Format as Number, 0-100
**Column L (Tier):** Use Data Validation → HOT, WARM, MAYBE, COLD
**Column M-O:** Use Data Validation → Yes, No, Pending
**Column Q (Status):** Use Data Validation → Prospect, Qualified, In Discussion, Proposal Sent, Client, Lost

---

## JAGGO BUYERS - Tab 2

### Column Headers (Copy these into Row 1)

```
A: Date Added
B: Company Name
C: Buyer Name
D: Email
E: Phone
F: Location
G: Store Type
H: Annual Order Potential (£)
I: Sustainability Priority
J: Lead Time Flexibility
K: Score (0-100)
L: Tier (HOT/WARM/MAYBE/COLD)
M: Product Mix Recommended
N: Email Sent
O: Response
P: Call Booked (Vinod)
Q: Order Placed
R: Order Value (£)
S: Status
T: Notes
```

### Sample Row (To show format)

```
11/06/2026 | Ethical Home Berlin | Klaus Mueller | klaus@ethicalhome.de | +49 30 1234 5678 | Berlin, Germany | Luxury Retailer | £25,000 | Critical | Flexible | 88 | HOT | 40% Crewel, 30% Textiles, 20% Art, 10% Jewellery | 11/06/2026 | 12/06/2026 - Interested | 13/06/2026 | Pending | TBD | In discussion | Strong fit, high order potential
```

### Formatting Tips

**Column A (Date Added):** Set format to Date
**Column K (Score):** Format as Number, 0-100
**Column L (Tier):** Use Data Validation → HOT, WARM, MAYBE, COLD
**Column I (Sustainability):** Use Data Validation → Critical, Important, Nice-to-have
**Column J (Lead Time):** Use Data Validation → Flexible, 30-45 days OK, Rush only
**Column S (Status):** Use Data Validation → Research, Outreach Sent, In Discussion, Call Booked, Order Placed, Lost

---

## SUMMARY TAB - Tab 3

### Tracking Metrics

Create a summary tab to track KPIs:

```
=== BRANDZIO PIPELINE ===

Total Prospects: =COUNTA(Brandzio!B2:B100)
HOT Tier: =COUNTIF(Brandzio!L2:L100,"HOT")
WARM Tier: =COUNTIF(Brandzio!L2:L100,"WARM")
MAYBE Tier: =COUNTIF(Brandzio!L2:L100,"MAYBE")
COLD Tier: =COUNTIF(Brandzio!L2:L100,"COLD")

Emails Sent: =COUNTIF(Brandzio!N2:N100,"Yes")
Responses: =COUNTIF(Brandzio!O2:O100,"Yes")
Response Rate: =(Responses / Emails Sent) * 100%

Calls Booked: =COUNTIF(Brandzio!P2:P100,"Yes")
Clients Signed: =COUNTIF(Brandzio!Q2:Q100,"Client")

---

=== JAGGO PIPELINE ===

Total Buyers: =COUNTA(Jaggo!B2:B100)
HOT Tier: =COUNTIF(Jaggo!L2:L100,"HOT")
WARM Tier: =COUNTIF(Jaggo!L2:L100,"WARM")
MAYBE Tier: =COUNTIF(Jaggo!L2:L100,"MAYBE")
COLD Tier: =COUNTIF(Jaggo!L2:L100,"COLD")

Emails Sent: =COUNTIF(Jaggo!N2:N100,"Yes")
Responses: =COUNTIF(Jaggo!O2:O100,"Yes")
Response Rate: =(Responses / Emails Sent) * 100%

Calls Booked: =COUNTIF(Jaggo!P2:P100,"Yes")
Orders Placed: =COUNTIF(Jaggo!Q2:Q100,"Yes")
Total Order Value: =SUMIF(Jaggo!Q2:Q100,"Yes",Jaggo!R2:R100)
Average Order Value: =AVERAGEIF(Jaggo!Q2:Q100,"Yes",Jaggo!R2:R100)
```

### Monthly Targets Tracker

```
=== MONTH [MM/YYYY] TARGETS ===

BRANDZIO:
 Prospects Researched: [Target] / [Actual]
 Audits Sent: [Target] / [Actual]
 Calls Booked: [Target] / [Actual]
 Clients Signed: [Target] / [Actual]
 MRR Generated: £[Target] / £[Actual]

JAGGO:
 Buyers Identified: [Target] / [Actual]
 Emails Sent: [Target] / [Actual]
 Calls Booked: [Target] / [Actual]
 Orders Placed: [Target] / [Actual]
 Total Revenue: £[Target] / £[Actual]
```

---

## HOW TO FILL IN FROM CLAUDE

When Claude generates a prospect:

**Claude gives you this:**
```
Company | Contact | Email | Phone | Industry | Inquiries/mo | Budget | Current Channels | Score | Tier | Audit Generated | Email Draft Ready | Notes
Bright Smile Dental | Sarah Johnson | sarah@brightsmile.com | +44 20 1234 5678 | Dental | 18 | £8,500 | Google Ads, Instagram, Referrals | 87 | HOT | Yes | Yes | Poor inquiry quality
```

**You copy-paste into Row 2 of your Google Sheet:**
- Column A: Today's date (11/06/2026)
- Column B: Bright Smile Dental
- Column C: Sarah Johnson
- Column D: sarah@brightsmile.com
- Column E: +44 20 1234 5678
- Column F: Dental
- Column G: 18
- Column H: £8,500
- Column I: Google Ads, Instagram, Referrals
- Column J: Poor inquiry quality
- Column K: 87
- Column L: HOT
- Column M: Yes (Audit Generated)
- Column N: Leave blank until you send
- Column O: Leave blank until they respond
- Column P: Leave blank
- Column Q: Prospect (or your status)
- Column R: Any extra notes

**Then later update:**
- Column N: "Yes" when you send email
- Column O: "Yes" if they reply
- Column P: "Yes" when call booked
- Column Q: Update to "In Discussion" / "Proposal Sent" / etc

---

## SHARING WITH TEAM

### For Vinod (Jaggo)
1. Create sheet
2. Click "Share" → Add vinod@email.com
3. Set permission to "Editor"
4. He can see Jaggo buyers tab
5. He updates when calls book and orders come in

### For Yourself
- Keep all tabs visible
- Update daily with new prospects
- Check summary tab weekly

---

## MONTHLY WORKFLOW

**Week 1:** 
- Add all new prospects from Claude
- Research and verify data

**Week 2:**
- Send emails for HOT tier
- Follow up previous week's WARM tier

**Week 3:**
- Book calls with interested prospects
- Update "Response" and "Call Booked" columns

**Week 4:**
- Update status based on calls
- Review summary metrics
- Plan next month's targets

---

## FORMULAS YOU CAN USE

### Get HOT tier only (for bulk email)
```
=FILTER(Brandzio!A2:R100, Brandzio!L2:L100="HOT")
```

### Average score by industry
```
=AVERAGEIF(Brandzio!F2:F100,"Dental",Brandzio!K2:K100)
```

### Count by status
```
=COUNTIF(Brandzio!Q2:Q100,"Client")
```

### Sum order values
```
=SUMIF(Jaggo!Q2:Q100,"Yes",Jaggo!R2:R100)
```

---

## TIPS

✅ **Update daily** - Keep data fresh
✅ **Color code tiers** - HOT (red), WARM (yellow), MAYBE (blue), COLD (gray)
✅ **Protect headers** - Freeze first row so you can scroll
✅ **Use comments** - Add notes for follow-ups
✅ **Archive old rows** - Keep sheet clean, use archive tab for closed leads
✅ **Download monthly** - Backup as CSV


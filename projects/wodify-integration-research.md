# Wodify Integration Research

**Date:** 2026-01-31
**API Key:** `pcb9oc8elqlj3xjkz6rr8kzd9` (saved to `/Users/daneel/clawd/config/wodify-credentials.json`)
**Status:** Initial testing — awaiting Promote tier upgrade

---

## 🔑 API Access Confirmed

**Base URL:** `https://api.wodify.com/v1/`
**Authentication:** Header `x-api-key: {apiKey}`

---

## ✅ Connection Status

- TLS handshake: ✅ Successful
- Authentication: ✅ Working (server accepts header format)
- Endpoint Access: ❌ Forbidden (likely requires Promote tier)

---

## 🧪 Tests Performed

| Test | Endpoint | Method | Result |
|------|----------|--------|--------|
| Root API | `/` | GET | Forbidden |
| Workouts | `/workouts/formattedworkout` | GET | Forbidden |
| Workouts with params | `/workouts/formattedworkout?date=2026-01-31&location=CrossFit+Blaze&program=CrossFit` | GET | Forbidden |

---

## 📋 Next Steps (Once Promote Tier is Active)

### Phase 1: Test Available Endpoints
1. **Test workouts endpoint** — Fetch daily WODs for Blaze
2. **Test schedule endpoint** — Retrieve class schedule
3. **Explore leads endpoint** — If available, test lead creation/retrieval

### Phase 2: Build Integration Scripts
1. **WOD Fetcher Script**
   - Fetch daily workout programmatically
   - Format for display (website, Telegram, etc.)
   - Automate daily updates

2. **Lead Management Script**
   - Monitor for new leads
   - Trigger welcome email (use Template 1)
   - Track trial completions

3. **Member Data Script**
   - Export inactive members (if API allows)
   - Automate re-engagement campaigns
   - Track member engagement metrics

### Phase 3: Automations
1. **Daily Briefing Enhancement**
   - Include today's WOD
   - Show class attendance metrics
   - Flag new leads/at-risk members

2. **Telegram Bot Integration**
   - Command to fetch today's WOD
   - Command to check class schedule
   - Quick member lookup

---

## ⚠️ Current Limitations

**Promote Tier Requirement:**
- Most endpoints return "Forbidden"
- Jason has contacted support; expects update Monday
- Likely requires Promote tier subscription for full API access

---

## 💡 What We Can Do Now (Without Promote Tier)

### Manual Exports
1. **Inactive Member Export**
   - Export from Wodify (Clients > Export Client Data)
   - Filter for 3+ months inactive
   - Use re-engagement templates (already created)

2. **Lead Management**
   - Monitor new leads manually in Wodify
   - Use welcome templates when new trials book
   - Track conversions manually

### Prepare for Promote Tier
1. **API Script Skeleton**
   - Create base API client with authentication
   - Set up error handling and retry logic
   - Prepare data structures for leads, members, workouts

2. **Automation Blueprint**
   - Document desired workflows
   - Map Wodify data to Daneel templates
   - Prepare testing checklist

---

## 📊 Expected Impact (Once Promote Tier is Active)

- **Time Saved:** 5-10 hours/week (automated lead follow-up, member management)
- **Lead Response Time:** From hours/days to minutes (automated triggers)
- **Member Retention:** Proactive outreach to at-risk members
- **Daily Briefing:** richer context (WODs, attendance, metrics)

---

## 🎯 Action Items for Jason

1. **Monday Follow-up**
   - Contact Wodify support about Promote tier upgrade
   - Confirm timeline for access
   - Note any pricing changes

2. **Share Wodify Details (if needed)**
   - Location name in Wodify
   - Program names (CrossFit, etc.)
   - Any special API configurations

---

*Last updated: 2026-01-31*

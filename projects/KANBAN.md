# CrossFit Blaze - Kanban Board

*Active projects, backlog, and ideas tracked by Daneel*

**Last Updated:** 2026-02-03 (5:30 PM)

---

## 🟢 IN PROGRESS (Active Work)

### Specialist Agents Framework
- **Status:** Active (Launched 2026-02-02)
- **Priority:** High
- **Description:** Focused AI specialists with cron-based heartbeats
- **Active Specialists:**
  - ✅ Night Owl (Overnight: 11 PM - 5 AM, every 30 min)
  - ✅ Closer (Lead Manager: 9 AM & 5 PM daily)
  - ✅ Spark (Content: 10 AM & 6 PM daily)
  - ✅ Ops (Operations: 8 AM & 7 PM daily)
- **Features:**
  - Isolated execution (no coordination overhead)
  - Cost-efficient model selection
  - Clear roles and responsibilities
  - Easy to add more specialists
- **Next Steps:**
  - Monitor overnight productivity
  - Track lead conversion improvements
  - Add more specialists as needed

### Multi-Model Efficiency Implementation
- **Status:** In Progress (Started 2026-02-03)
- **Priority:** High
- **Description:** Implement Alex Finn-style multi-model workflow efficiency
- **Changes:**
  - [ ] Autonomous decision matrix (stop asking, start doing)
  - [ ] Batch processing windows (4x daily)
  - [ ] New specialist agents (Scout, Skeptic, Analyst, Builder)
  - [ ] Cost optimization dashboard
  - [ ] Unified output format for all agents
- **Next Steps:** 
  - Define High/Medium/Low confidence criteria
  - Set up auto-execute rules
  - Create specialist sub-agents

### Gmail Mass Cleanup
- **Status:** In Progress (Started 2026-02-03)
- **Priority:** Medium
- **Description:** Bulk delete spam and organize 35,000+ emails
- **Progress:** ~2,951 emails deleted so far
- **Targets Identified:** beehiiv (410), Yelp (185), GORUCK (173), TheGrint (140), etc.
- **Next Steps:** Continue batch deletions during API quota windows

### Dashboard Redesign
- **Status:** In Progress
- **Priority:** Medium
- **Description:** Redesign local dashboard at http://100.104.101.21:8080/index.html
- **Changes Made:**
  - ✅ Updated styling (modern CSS, responsive grid)
  - ✅ Changed Wodify link to app.wodify.com
  - ✅ Removed Crabwalk Home reference
- **Issue:** Changes not showing on refresh (caching?)
- **Next Step:** Troubleshoot caching issue

### Email Automation System
- **Status:** In Progress (Active)
- **Priority:** High
- **Description:** Automated email replies for leads, drop-ins, free trials
- **Templates Created:** ✅ Drop-in, Free Trial Welcome, No-Signup Follow-up, New Lead
- **Cron Job:** ✅ Running every 5 minutes (streamlined 2026-02-03)
- **Features:**
  - ✅ PDF waiver extraction
  - ✅ Auto-drafting replies
  - ✅ Lead logging to CSV/JSON
  - ✅ Automatic follow-up reminders
- **Next Step:** Test with real leads, refine based on responses
- **Notes:** Permission granted for up to 10% discounts

### Gmail Integration (Daneel's Email)
- **Status:** ✅ Completed 2026-02-03
- **Priority:** High
- **Description:** cosdaneelolivaw@gmail.com fully connected via Google Workspace MCP
- **Features Working:**
  - ✅ Read/send emails
  - ✅ Search and organize
  - ✅ PDF extraction (waiver info)
  - ✅ 5-minute inbox monitoring
  - ✅ Auto-processing for drop-ins/trials/leads
- **Result:** Fully operational for email automation

### Wodify API/Integration
- **Status:** In Progress
- **Priority:** High
- **Description:** API access for automation and data integration
- **Status:** Email sent to Wodify support (2026-02-01)
- **Follow-up:** Scheduled for Wednesday, Feb 4
- **Notes:** Exploring Workflows vs API access

### Lead Tracking System
- **Status:** In Progress
- **Priority:** Medium
- **Description:** Organized tracking for leads and free trials
- **Files Created:**
  - ✅ `/memory/leads-follow-up.md`
  - ✅ `/memory/free-trials-follow-up.md`
- **Calendar Reminders:** ✅ Set for follow-ups
- **Next Step:** Populate with real data as leads come in

### Voice/Phone Setup
- **Status:** In Progress (Mentioned)
- **Priority:** Medium
- **Description:** Setting up voice capabilities and phone integration
- **Notes:** Mentioned as future goal, no immediate action

---

## 🟡 WAITING (Blocked/On Hold)

### Blaze Gmail Integration (jason@crossfitblaze.com)
- **Status:** Waiting
- **Priority:** High
- **Description:** Full access to send emails from business address
- **Blocker:** OAuth authentication needs to be completed on Mac mini via Screen Sharing
- **Impact:** Until resolved, all client emails must be drafted → sent by Jason
- **Next Step:** Jason to complete OAuth when ready

### Notion Integration
- **Status:** Waiting
- **Priority:** Medium
- **Description:** Full Notion workspace integration for project tracking
- **Blocker:** Need Notion API token/integration setup
- **Workaround:** Using Google Sheets/local files for now
- **Next Step:** Set up Notion integration when ready

### Moltbook (AI Social Network)
- **Status:** Waiting
- **Priority:** Low
- **Description:** AI social network registration
- **Blocker:** API connectivity issues
- **Notes:** Not blocking for daily operations

### Instagram API Automation (Option 2)
- **Status:** Waiting (Added 2026-02-02)
- **Priority:** Medium
- **Requires:** Both Jason & Daneel
- **Description:** Full Instagram posting automation via Meta Business API
- **Current:** Spark drafts content, Jason posts manually (working fine)
- **Blocker:** Requires setup time from Jason:
  1. Create/verify Facebook Page (if needed)
  2. Connect Instagram Business Account
  3. Get Instagram Graph API credentials from Meta
  4. Configure posting automation
- **Advantage:** Fully automated posting, scheduling, analytics
- **Notes:** Manual workflow (Option 1) working now, upgrade when ready
- **Impact:** Saves Jason time posting daily, consistent schedule
- **Next Step:** Add to Jason's schedule when he has 30-60 min for setup

---

## 🔵 BACKLOG (Future Ideas)

### Polymarket Sentiment Analysis
- **Priority:** Low
- **Description:** Business expansion research via prediction markets
- **Notes:** Part of "Overnight Business Brief" support lane

### Tailscale SSH Setup
- **Priority:** Low
- **Description:** Remote access to work computer
- **Notes:** Do AFTER Gmail + Notion setup

### Old Member Re-Engagement Campaign
- **Status:** In Progress (Overnight Task)
- **Priority:** Medium
- **Description:** Email campaign for inactive members (3+ months)
- **Templates:** ✅ Already created at `/templates/old-member-reengagement-templates.md`
- **Work Being Done Overnight:**
  - [ ] Create campaign workflow and SOP
  - [ ] Set up tracking system for responses
  - [ ] Create follow-up sequences (3-touch system)
  - [ ] Document export process from Wodify
- **Next Step:** Export inactive member list from Wodify when ready

---

## ✅ COMPLETED (Recently Finished)

### X/Twitter Integration
- **Completed:** 2026-02-03
- **Priority:** High
- **Description:** Full X/Twitter access via bird CLI for social monitoring and engagement
- **Features Working:**
  - ✅ Search tweets and trends
  - ✅ Read user timelines
  - ✅ Post tweets and replies
  - ✅ Check mentions
- **Use Cases:** OpenClaw news monitoring, community engagement
- **Auth:** AUTH_TOKEN and CT0 in ~/.zshrc, authenticated as @Blazedbarbell

### Progress.txt Tracking
- **Completed:** 2026-02-03
- **Priority:** Medium
- **Description:** Lightweight session-to-session state tracking
- **Location:** `/projects/progress.txt`
- **Purpose:** Quick state carryover between sessions (complements KANBAN)

### Gmail Integration (Daneel's Email)
- **Completed:** 2026-02-03
- **Priority:** High
- **Description:** cosdaneelolivaw@gmail.com fully connected via Google Workspace MCP
- **Features Working:**
  - ✅ Read/send emails
  - ✅ Search and organize
  - ✅ PDF extraction (waiver info)
  - ✅ 5-minute inbox monitoring
  - ✅ Auto-processing for drop-ins/trials/leads

### Email Automation Health Check
- **Completed:** 2026-02-03
- **Schedule:** Daily at 9:00 AM EST
- **Purpose:** Verify email system is working (sends test email, checks delivery)
- **Alert:** Notifies if email automation is broken

### AI News Digest (Enhanced)
- **Completed:** 2026-02-03
- **Schedule:** Daily at 6:15 AM EST
- **Enhancement:** Added 🦞 OpenClaw Updates section
- **Sources:** Web search + X/Twitter (@openclaw, community posts)
- **Content:** Actionable AI news, new tools, models, OpenClaw features

### X/Twitter Integration
- **Completed:** 2026-02-03
- **Tool:** bird CLI by @steipete
- **Auth:** Cookie-based (AUTH_TOKEN/CT0)
- **Capabilities:** Search, read, post, monitor mentions
- **Use Case:** OpenClaw news monitoring, community engagement

### Email Templates Library
- **Completed:** 2026-02-01
- **Location:** `/templates/crossfitblaze-email-templates.md`
- **Includes:**
  - Drop-in visitor template (with maps & Instagram)
  - Free trial welcome template
  - Free trial no-signup follow-up
  - New lead template
  - Revolt Fitness customer service response

### Inbox Organization System
- **Completed:** 2026-02-01
- **System:** Labels + tracking files + calendar reminders
- **Rules:**
  - Leads → IMPORTANT + track
  - Free trials → STARRED + track
  - Drop-ins → Trash after reply
  - API keys/credentials → Archive

### API Credit Setup
- **Completed:** 2026-02-01
- **Status:** Grok and Kimi credits added
- **Research:** Token pricing completed, GLM-4.7 confirmed cheapest
- **Code Safety Rules:** Documented in AGENTS.md and MEMORY.md

### PDF Extraction Tools
- **Completed:** 2026-02-01
- **Installed:** pdfplumber via Python venv
- **Use Case:** Extracting waiver data (email, city, state) for personalization

### Workflow Orchestration Framework
- **Completed:** 2026-02-01
- **Files Created:**
  - `/tasks/todo.md` - Active task plans with checkboxes
  - `/tasks/lessons.md` - Lessons learned from corrections (16 lessons documented)
- **Updated:** AGENTS.md with full workflow principles
- **Includes:**
  - Plan Mode for complex tasks
  - Subagent strategy
  - Self-improvement loop
  - Verification checklist
  - Demand elegance principle
  - Autonomous problem solving
  - Task management system
  - Core principles (Simplicity, No Laziness, Minimal Impact)
- **Model Upgrades:** Grok 3 → Grok 4

---

## 💡 IDEAS (Brainstorming)

### Automation Ideas
- [ ] Auto-forward Wodify notifications to Daneel for processing
- [ ] Automated birthday emails for members
- [ ] Class attendance alerts for coaches
- [ ] Monthly member progress reports

### Business Expansion Ideas
- [ ] Corporate wellness partnerships
- [ ] Nutrition coaching add-on
- [ ] Youth/teen programs
- [ ] Beach workouts seasonally

### Content Ideas (Instagram)
- [ ] Member transformation stories
- [ ] Coach spotlights
- [ ] Workout of the Day highlights
- [ ] Behind-the-scenes gym life

---

## 📊 SYSTEMS STATUS

| System | Status | Notes |
|--------|--------|-------|
| Gmail (Daneel) | ✅ Active | Full access |
| Gmail (Blaze) | ⏳ Pending | OAuth needed |
| Google Workspace MCP | ✅ Active | All tools working |
| X/Twitter | ✅ Active | bird CLI, @Blazedbarbell |
| Wodify | 🔧 In Progress | API discussions |
| Notion | ⏳ Pending | Setup needed |
| Cron (5-min inbox) | ✅ Active | Running every 5 mins |
| AI News Digest | ✅ Active | 6:15 AM daily + OpenClaw section |
| Email Health Check | ✅ Active | 9:00 AM daily test |

---

## 🎯 THIS WEEK'S PRIORITIES (Feb 1-7)

### Completed ✓
1. ~~**X/Twitter integration**~~ - For OpenClaw news and community monitoring
2. ~~**Streamline Gmail cron**~~ - Reduce error noise, improve efficiency

### Active
3. **Get Blaze Gmail OAuth working** - Top priority for professional client communication
4. **Test email templates with real leads** - Refine based on responses
5. **Wodify follow-up** - Wednesday, get clarity on Workflows vs API
6. **Populate lead tracker** - Start tracking real leads
7. **Set up Notion Kanban** - Better project visibility

---

*This Kanban is maintained by Daneel. For updates, questions, or to add items, just ask!* 🤖

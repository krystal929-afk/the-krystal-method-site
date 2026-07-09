# The Krystal Method — Master Manual

## The No-App System: Running Your Business from Google Calendar

This manual outlines the complete system for managing clients, projects, and content using only Google Calendar and Make.com automation. No apps. No complexity. Just clarity.

---

## Part 1: The Foundation

### Why Google Calendar?

Google Calendar is the single source of truth for your business. Every client, every project, every post, every deadline lives here. It's:
- **Always with you** (on your phone)
- **Searchable** (find anything in seconds)
- **Shareable** (send links to clients)
- **Automatable** (Make.com watches it)
- **Free** (no subscription)

### Setup

1. Open Google Calendar on your phone and desktop
2. Create three calendars:
   - **Clients** (for CRM workflow)
   - **Content** (for social posts)
   - **Operations** (for internal tasks)
3. Color-code them for quick visual scanning

---

## Part 2: The CRM Workflow

### How to Log a Lead

**Step 1: Create an All-Day Event**
- Open Google Calendar
- Click the date when you want to follow up with this lead
- Select "All-day event"

**Step 2: Title Format**
```
[STATUS] Client Name
```

**Status codes:**
- `[AUDIT]` — Initial discovery/audit phase
- `[DISCOVERY]` — In the discovery form stage
- `[PROPOSAL]` — Waiting on proposal response
- `[KICKOFF]` — Ready to start intensive
- `[ACTIVE]` — Currently working together
- `[FOLLOW-UP]` — Need to check in

**Examples:**
- `[AUDIT] Sarah Chen`
- `[DISCOVERY] Marcus Thompson`
- `[PROPOSAL] The Inner Hour Publishing`

**Step 3: Add Details in the Description**
Paste the following template and fill it in:

```
Name: 
Instagram: 
Email: 
Website: 

Project Overview:
[Describe what they're building]

Key Notes:
[Any important context]

Next Action:
[What do we do next?]
```

**Step 4: Color-Code by Temperature**
- **Red** = Hot lead (follow up ASAP)
- **Yellow** = Warm lead (follow up this week)
- **Green** = Cold lead (follow up next month)
- **Blue** = Active client

### Daily CRM Ritual

**Every morning:**
1. Open Google Calendar on your phone
2. Look at today's date
3. Do the red items first
4. Update the status of each event as you work through it

### Example CRM Week

```
Monday, July 15
- [AUDIT] Sarah Chen (Red) — Send discovery form
- [FOLLOW-UP] Marcus Thompson (Yellow) — Check if he filled out form

Tuesday, July 16
- [DISCOVERY] The Inner Hour (Red) — Review submission, schedule call

Wednesday, July 17
- [KICKOFF] Sarah Chen (Blue) — 72-hour intensive begins

Thursday, July 18
- [PROPOSAL] Marcus Thompson (Yellow) — Send proposal

Friday, July 19
- [ACTIVE] Sarah Chen (Blue) — Deliver brand guide
- [FOLLOW-UP] The Inner Hour (Green) — Check in next week
```

---

## Part 3: The Social Workflow

### How to Create Content Events

**Step 1: Create a 15-Minute Event**
- Open Google Calendar
- Click the time you want to post
- Make it 15 minutes long

**Step 2: Title Format**
```
[POST] Caption or Content Idea
```

**Examples:**
- `[POST] Behind-the-scenes studio setup`
- `[POST] New brand identity reveal`
- `[POST] Client testimonial video`

**Step 3: Add Details in the Description**
```
Platform: Instagram / Facebook / Both
Caption: [Full caption text]
Image/Video: [Link to asset or description]
Hashtags: [List of hashtags]
```

**Step 4: Schedule Posts**
- Create events for the times you want to post
- Make.com will automatically post when the event time arrives

### Weekly Content Planning

**Every Sunday evening:**
1. Open Google Calendar
2. Create 5-7 `[POST]` events for the week
3. Spread them out across the week
4. Add captions and asset links
5. Make.com handles the rest

### Example Content Week

```
Monday, July 15 at 10 AM
[POST] Monday motivation: "The strongest brands aren't invented. They're revealed."

Wednesday, July 17 at 2 PM
[POST] Case study: Mr. Satan brand ecosystem

Friday, July 19 at 6 PM
[POST] Behind-the-scenes: The Krystal Method process

Sunday, July 21 at 9 AM
[POST] Week ahead: What's coming in August
```

---

## Part 4: Make.com Automation

### Setting Up Make.com

**Step 1: Create a Make.com Account**
1. Go to https://www.make.com
2. Sign up with your email
3. Create a new scenario

**Step 2: Create the Automation**

**Trigger: Google Calendar**
- Watch for new events
- Filter for events with `[POST]` in the title
- Set to trigger 5 minutes before event time

**Action 1: Get Event Details**
- Extract the caption from the event description
- Extract the image/video link
- Extract hashtags

**Action 2: Post to Instagram**
- Use the Instagram connector
- Post the image/caption/hashtags
- Schedule for the exact event time

**Action 3: Post to Facebook**
- Use the Facebook connector
- Post the same content
- Schedule for the exact event time

### Make.com Template (Simplified)

```
Trigger: Google Calendar → New Event
  - Filter: Title contains "[POST]"
  - Time: 5 minutes before event

Action 1: Parse Description
  - Extract caption
  - Extract image URL
  - Extract hashtags

Action 2: Instagram
  - Post image
  - Add caption + hashtags
  - Time: Event time

Action 3: Facebook
  - Post image
  - Add caption + hashtags
  - Time: Event time
```

### Troubleshooting Make.com

**Posts not going out?**
- Check that the event title has `[POST]` in it
- Verify the image URL is working
- Check Make.com scenario is turned ON

**Posts going out at wrong time?**
- Verify your timezone in Google Calendar
- Verify your timezone in Make.com
- Check the event time is set correctly

---

## Part 5: The Operating System

### The Four Rules

**Rule 1:** If it's in the calendar, it's real. If it's not in the calendar, it doesn't exist.
- Don't keep tasks in your head
- Don't use email as a to-do list
- Don't use Slack as a project manager
- Everything goes in the calendar

**Rule 2:** Check your phone every morning. Do the red items first.
- Red = Hot leads or urgent tasks
- Yellow = This week
- Green = This month
- Blue = Active ongoing work

**Rule 3:** Every client, every project, every post lives as a calendar event. One source of truth.
- No spreadsheets
- No separate CRM
- No project management tool
- Just the calendar

**Rule 4:** The calendar is your business. Treat it like it.
- Keep it clean
- Keep it updated
- Keep it honest
- Check it every day

---

## Part 6: Monthly Ritual

### End of Month Review

**Last Friday of each month:**

1. **Review Completed Work**
   - Look at all events marked as complete
   - Note patterns (what worked, what didn't)

2. **Review Pipeline**
   - Count hot leads (red)
   - Count warm leads (yellow)
   - Count cold leads (green)

3. **Review Content Performance**
   - Which posts got the most engagement?
   - Which times work best?
   - Adjust next month's schedule accordingly

4. **Clean Up**
   - Archive completed events
   - Delete cancelled events
   - Update client statuses

5. **Plan Next Month**
   - Create all client follow-up events for next month
   - Plan content calendar for next month
   - Set any important deadlines

---

## Part 7: Common Questions

### Q: What if a client needs to reschedule?
**A:** Just drag the event to the new date. The calendar updates automatically. If it's a `[POST]` event, Make.com will post at the new time.

### Q: Can I share the calendar with clients?
**A:** Yes. Create a separate "Client Schedule" calendar and share the link. They can see kickoff dates, delivery dates, etc. Keep your internal CRM calendar private.

### Q: What if I need to add more details?
**A:** Use the event description field. You can paste long notes, links, assets, anything. Google Calendar supports rich text.

### Q: Can this scale to a team?
**A:** Yes. Create shared calendars for different team members. Everyone sees the same events. Make.com can be set up to post from different accounts.

### Q: What if I want to use a different social platform?
**A:** Make.com supports most platforms. You can add actions for TikTok, LinkedIn, Twitter, YouTube, etc. Just add more "Action" steps to the scenario.

---

## Part 8: The Philosophy

This system works because it's built on **clarity before complexity**.

You don't need:
- 10 different apps
- Complicated workflows
- Expensive software
- Confusing integrations

You need:
- One source of truth (the calendar)
- Clear naming conventions (status codes)
- Simple automation (Make.com)
- Daily discipline (check every morning)

**The calendar is your business.** Everything else is just tools.

---

## Quick Reference

### CRM Status Codes
- `[AUDIT]` — Initial discovery
- `[DISCOVERY]` — Form submitted
- `[PROPOSAL]` — Waiting on response
- `[KICKOFF]` — Starting intensive
- `[ACTIVE]` — Currently working
- `[FOLLOW-UP]` — Need to check in

### Color Codes
- 🔴 Red = Hot (follow up ASAP)
- 🟡 Yellow = Warm (this week)
- 🟢 Green = Cold (this month)
- 🔵 Blue = Active client

### Daily Ritual
1. Open calendar on phone
2. Look at today's date
3. Do the red items first
4. Update statuses as you work

### Weekly Ritual
1. Sunday evening: Plan content for the week
2. Create 5-7 `[POST]` events
3. Add captions and asset links
4. Make.com posts automatically

### Monthly Ritual
1. Review completed work
2. Review pipeline (hot/warm/cold)
3. Review content performance
4. Clean up and plan next month

---

**The Krystal Method is the practice of uncovering the common thread that gives a brand its authentic identity—and building every decision from that foundation.**

This calendar system is how you **live** that practice every single day.

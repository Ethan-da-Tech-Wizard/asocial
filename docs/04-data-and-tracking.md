# 04 Data And Tracking

Last updated: September 14, 2026

The project needs a simple database, but it can start as a spreadsheet or Notion/Airtable table. The goal is to track ideas, posts, sources, performance, and lessons. The database should help answer one question every week:

> What should I make more of, less of, or differently?

## Core Tables

### 1. Ideas

Purpose: Capture topics before they disappear.

Fields:

- Idea ID.
- Date captured.
- Topic.
- Content pillar.
- Format.
- Primary viewer payoff: seen, warned, informed, mistake avoided, next step.
- Hook draft.
- Why it matters.
- Target audience.
- Source level: Level 1, Level 2, or Level 3.
- Claim risk: Low, Medium, or High.
- Source link.
- Urgency level.
- Confidence score.
- Status: backlog, scripting, recorded, posted, archived.

### 2. Sources

Purpose: Keep factual content credible.

Fields:

- Source ID.
- Title.
- URL.
- Publisher.
- Date published.
- Date accessed.
- Main claim.
- Notes.
- Reliability rating.
- Related idea ID.

### 3. Scripts

Purpose: Store reusable content drafts.

Fields:

- Script ID.
- Related idea ID.
- Platform target.
- Hook.
- Script body.
- Call to action.
- Estimated length.
- Status.
- Revision notes.

### 4. Posts

Purpose: Track what was actually published.

Fields:

- Post ID.
- Date posted.
- Platform.
- URL.
- Content pillar.
- Format.
- Primary viewer payoff.
- Topic.
- Hook used.
- Length.
- Caption.
- Hashtags.
- Source links.
- Repurposed from.

### 5. Metrics

Purpose: Compare performance honestly.

Fields:

- Post ID.
- Platform.
- Views.
- Qualified views, if available.
- Watch time.
- Average view duration.
- Completion rate.
- Likes.
- Comments.
- Shares.
- Saves.
- New followers.
- Profile visits.
- Revenue, if any.
- Likes per 1,000 views.
- Comments per 1,000 views.
- Shares per 1,000 views.
- Saves per 1,000 views.
- Follows per 1,000 views.
- Review label: keep, revise, or kill.
- Notes.

### 6. Lessons

Purpose: Turn activity into learning.

Fields:

- Lesson ID.
- Date.
- Related post ID.
- What worked.
- What failed.
- Hypothesis.
- Next test.

## Minimum Weekly Review

Once per week, review:

- Top 5 posts by views.
- Top 5 posts by shares.
- Top 5 posts by saves.
- Posts with best follower conversion.
- Posts with weak retention.
- Hooks that worked.
- Topics that caused comments.
- Topics that are worth turning into long-form YouTube.

## Key Metrics By Stage

### Stage 1: Starting From Zero

Most important:

- Posts published.
- Views.
- Average watch time.
- Comments.
- Shares.
- Saves.
- Follows per post.

Do not obsess over revenue yet.

### Stage 2: Finding Repeatable Formats

Most important:

- Completion rate.
- Shares per 1,000 views.
- Saves per 1,000 views.
- Comments per 1,000 views.
- Follows per 1,000 views.
- Topic clusters that repeat well.

### Stage 3: Monetization Eligibility

Most important:

- Platform-specific eligibility progress.
- Qualified views.
- Watch hours.
- Followers/subscribers.
- Revenue per 1,000 qualified views where available.
- Sponsor inquiries.
- Email or community signups.

## Naming System

Use simple IDs:

- IDEA-0001
- SRC-0001
- SCR-0001
- POST-0001
- LESSON-0001

## Starting Tools

Free options:

- Google Sheets.
- Notion free plan.
- Airtable free plan.
- Obsidian plus a spreadsheet.
- Plain markdown files.

Recommended starting choice:

Use Google Sheets or Notion first. Do not overbuild the database before there is content to track.

## Working CSV Templates

Spreadsheet-ready templates now live in `trackers/`:

- `ideas.csv`
- `sources.csv`
- `scripts.csv`
- `posts.csv`
- `metrics.csv`
- `lessons.csv`
- `weekly-review.csv`

Open or import these files into the tool you prefer. The CSVs are the current working version of the tracker.

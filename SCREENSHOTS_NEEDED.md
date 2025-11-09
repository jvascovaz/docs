# Screenshot Guide for Friction Documentation

This document lists all screenshots referenced in the Mintlify documentation and where to capture them from the application.

## General Screenshot Guidelines

**Resolution**: 1920x1080 or higher (retina displays preferred)
**Format**: PNG with transparency where applicable
**Location**: Save all screenshots to `/images/` directory
**Naming**: Use kebab-case matching the filenames below
**Quality**: Ensure UI is fully loaded, no skeleton states or loading spinners
**Data**: Use realistic sample data (not "Test Brand" or lorem ipsum)
**Privacy**: Blur any sensitive information (emails, API keys)

---

## Homepage & Overview

### `friction-dashboard-hero.png`
**Location**: Dashboard root (`/`)
**Content**: Full dashboard view showing:
- Brand selector with logo
- Quick metrics cards
- Performance trends chart
- Competitive gaps table
- Navigation sidebar (expanded)

**Notes**: Show a healthy brand with good metrics (70-85 scores)

---

## Onboarding Flow

### `onboarding-flow.png`
**Location**: Create a diagram or flowchart showing the 6 phases
**Content**: Visual representation of:
1. Brand Discovery
2. Industry Detection
3. Subcategory Selection
4. Competitor Collection
5. Brand Prompts (Optional)
6. Commerce Prompts (Optional)

**Notes**: Can use Figma, Miro, or screenshot annotated user flow

### `onboarding-phase1.png`
**Location**: `/onboarding` (Phase 1)
**Content**: Brand discovery form showing:
- Brand name input field
- Website URL input field
- "Discovering your brand..." loading state OR
- Confirmation screen with detected logo, domain, description

### `onboarding-phase2.png`
**Location**: `/onboarding` (Phase 2)
**Content**: Industry detection showing:
- AI-suggested industry with confidence score
- Industry dropdown selector
- Selected industry highlighted

### `onboarding-phase3.png`
**Location**: `/onboarding` (Phase 3)
**Content**: Subcategory selection showing:
- AI-suggested subcategories (4-5 cards)
- Selected subcategories (2-3 highlighted)
- "Show all categories" option
- Counter showing "3/5 selected"

### `onboarding-phase4.png`
**Location**: `/onboarding` (Phase 4)
**Content**: Competitor collection showing:
- 2-3 competitors added with logos and URLs
- "Add competitor" input field
- Competitor cards with remove buttons

### `onboarding-phase5.png`
**Location**: `/onboarding` (Phase 5)
**Content**: Brand prompts creation showing:
- Intro screen explaining brand visibility prompts OR
- AddPromptsContent interface with 3-5 sample prompts
- "Get Friction Suggestions" button
- Tag selection options

### `onboarding-phase6.png`
**Location**: `/onboarding` (Phase 6)
**Content**: Commerce prompts creation showing:
- Intro screen explaining commerce tracking OR
- CommerceAddPromptsContent interface
- "Get Commerce Suggestions" button
- Product URL input fields

### `onboarding-complete.png`
**Location**: `/onboarding/complete`
**Content**: Completion screen showing:
- Success animation or checkmark
- "Welcome to friction!" message
- Tutorial or dashboard preview

---

## Define (Brand Visibility) Page

### `define-page-overview.png`
**Location**: `/define`
**Content**: Full page view showing:
- Prompts header with search and filters
- Prompts table with 8-10 sample prompts
- Sources panel on right
- Insights panel on right

### `define-page-sections.png`
**Location**: `/define`
**Content**: Annotated screenshot highlighting the 4 main sections:
1. Prompts Header (top)
2. Prompts Table (main area)
3. Sources Panel (right sidebar)
4. Insights Panel (right sidebar)

**Notes**: Use arrows or boxes to label each section

### `define-add-prompts.png`
**Location**: `/define/add` or modal
**Content**: Add prompts interface showing:
- Text input area with 3-5 sample prompts
- "Get Friction Suggestions" button
- Tag input chips
- "Add Prompts" and "Cancel" buttons

### `define-prompts-table.png`
**Location**: `/define`
**Content**: Close-up of prompts table showing columns:
- Prompt text (with checkboxes)
- Brand Mentioned (checkmarks)
- Sentiment (badges: Positive/Neutral/Negative)
- Avg Position numbers
- Last Executed dates
- Tags chips
- Actions dropdown

**Notes**: Show 6-8 rows with varied data

### `define-search.png`
**Location**: `/define`
**Content**: Search bar in use showing:
- Search term entered (e.g., "compare")
- Filtered results in table below
- "2 of 15 prompts" or similar count

### `define-tag-filters.png`
**Location**: `/define`
**Content**: Tag filter interface showing:
- Multiple tag chips (product, comparison, brand-awareness, etc.)
- 2-3 tags selected (highlighted)
- Filtered results based on tags

### `define-execute.png`
**Location**: `/define`
**Content**: Execute action showing:
- Selected prompts (checkboxes checked)
- "Execute Selected" button highlighted
- Or single prompt with play icon highlighted

### `define-edit-prompt.png`
**Location**: `/define` (edit dialog open)
**Content**: Edit prompt dialog showing:
- Prompt text in editable field
- Tags selection
- Save and Cancel buttons

### `define-sources-panel.png`
**Location**: `/define` (right sidebar)
**Content**: Sources panel showing:
- Top 5-7 domains cited by AI models
- Your domain highlighted if present
- Competitor domains
- Citation count or percentage

### `define-insights-panel.png`
**Location**: `/define` (right sidebar)
**Content**: Insights panel showing:
- 3-4 insight cards
- Different insight types (low visibility, sentiment warnings, etc.)
- Actionable recommendations

---

## Analyze (Competitive Analysis) Page

### `analyze-page-overview.png`
**Location**: `/analyze`
**Content**: Full page view showing:
- Brand Health Summary Card at top
- Metric tabs (Purchase Intent, Authority, Sentiment, Visibility)
- Trend chart
- Score breakdown
- Insights panel

### `analyze-page-components.png`
**Location**: `/analyze`
**Content**: Annotated screenshot labeling:
1. Brand Health Summary
2. Metric Tabs
3. Trend Charts
4. Score Breakdown
5. Insights Panel

**Notes**: Use arrows or numbered labels

### `analyze-visibility-metric.png`
**Location**: `/analyze` (Visibility tab selected)
**Content**: Visibility metric deep dive showing:
- Visibility score (e.g., 78/100)
- Trend chart over 30 days
- Sub-metric breakdown
- AI model comparison

### `analyze-sentiment-metric.png`
**Location**: `/analyze` (Sentiment tab selected)
**Content**: Sentiment metric showing:
- Sentiment score
- Positive/Neutral/Negative distribution
- Trend over time
- Sentiment examples

### `analyze-authority-metric.png`
**Location**: `/analyze` (Authority tab selected)
**Content**: Authority metric showing:
- Authority score
- Source quality breakdown
- Citation context
- Category leadership indicators

### `analyze-purchase-intent-metric.png`
**Location**: `/analyze` (Purchase Intent tab selected)
**Content**: Purchase Intent metric showing:
- Purchase Intent score
- Recommendation strength
- Use case matching
- Comparison positioning

### `analyze-trend-charts.png`
**Location**: `/analyze`
**Content**: Trend chart showing:
- 7 days, 30 days, 90 days period selector
- Line chart with metric over time
- Trend indicators (up/down arrows)
- Data points clearly visible

### `analyze-score-breakdown.png`
**Location**: `/analyze`
**Content**: Expandable score breakdown showing:
- Overall score at top
- Sub-metrics listed with scores
- Weighted contribution indicators
- Expand/collapse state

### `analyze-engine-comparison.png`
**Location**: `/analyze`
**Content**: AI engine comparison showing:
- GPT-4, Claude, Gemini, Perplexity tabs or chart
- Per-model scores
- Comparison bars or charts
- Model-specific insights

### `analyze-insights-panel.png`
**Location**: `/analyze` (insights section)
**Content**: Insights showing:
- Quick wins
- Strategic priorities
- Competitive alerts
- Maintenance reminders

---

## Commerce Tracking Page

### `commerce-page-overview.png`
**Location**: `/commerce`
**Content**: Full page view showing:
- Commerce prompts header
- Commerce prompts table
- Top e-commerce websites panel
- Commerce insights panel

### `commerce-page-sections.png`
**Location**: `/commerce`
**Content**: Annotated screenshot showing:
1. Commerce Prompts Header
2. Commerce Prompts Table
3. E-Commerce Websites Panel
4. Commerce Insights Panel

### `commerce-add-prompts.png`
**Location**: `/commerce/add` or modal
**Content**: Add commerce prompts showing:
- Prompt input area
- "Get Commerce Suggestions" button
- Product URL fields
- Tags for commerce prompts

### `commerce-prompts-table.png`
**Location**: `/commerce`
**Content**: Commerce prompts table showing:
- Prompt text
- Recommended (yes/no)
- Purchase Intent strength
- E-Commerce Platforms count
- Avg Position
- Sentiment
- Last Executed

### `commerce-websites-panel.png`
**Location**: `/commerce` (right sidebar)
**Content**: Top e-commerce websites showing:
- Amazon, Walmart, Your Site, etc.
- Recommendation frequency percentages
- Platform logos
- Highlight your own site

### `commerce-insights-panel.png`
**Location**: `/commerce` (insights section)
**Content**: Commerce insights showing:
- Low purchase intent alerts
- Missing platform opportunities
- Competitor e-commerce advantages
- Pricing/review gaps

---

## Experiments Page

### `experiments-page-overview.png`
**Location**: `/experiments`
**Content**: Experiments list page showing:
- "Create Experiment" button
- Status filter buttons
- Experiments table with 5-6 experiments
- Pagination controls

### `experiments-status-flow.png`
**Location**: Create a diagram
**Content**: Flow diagram showing:
Draft → Scheduled → Running → Completed/Failed → Archived

**Notes**: Visual flowchart with status badges and arrows

### `experiments-create-form.png`
**Location**: `/experiments/new`
**Content**: Create experiment form showing:
- Experiment name field
- Hypothesis field
- Target metrics selector (chips)
- LLM models selector
- AI platforms selector
- Date range inputs

### `experiments-add-prompts.png`
**Location**: `/experiments/new` (prompts step)
**Content**: Add prompts to buckets showing:
- Control bucket with 5-7 prompts
- Variant bucket with 5-7 prompts
- "Add Prompt" buttons for each bucket
- Prompt count indicators

### `experiments-list.png`
**Location**: `/experiments`
**Content**: Experiments list showing:
- Status filter tabs (All, Draft, Scheduled, Running, Completed, etc.)
- Table with columns: Name, Status, Target Metrics, Created, Last Executed
- Mix of statuses with color-coded badges
- Pagination: "Page 1 of 3, Show: 25 per page"

### `experiments-detail-page.png`
**Location**: `/experiments/[id]`
**Content**: Experiment detail showing:
- Experiment name and status badge
- Hypothesis
- Target metrics
- Timeline
- Results (if completed)
- Prompt lists

### `experiments-results-comparison.png`
**Location**: `/experiments/[id]` (completed experiment)
**Content**: Results comparison showing:
- Control bucket scores
- Variant bucket scores
- Side-by-side metric comparison
- Lift percentages
- Winner badge or indicator

### `experiments-winner-badge.png`
**Location**: `/experiments/[id]`
**Content**: Close-up of winner indicator showing:
- "Winner: Variant" badge
- Or "Control wins" badge
- Confidence level displayed

---

## Dashboard Overview Page

### `dashboard-overview-sections.png`
**Location**: `/` (dashboard)
**Content**: Dashboard showing key sections:
- Quick Metrics Cards (4 metrics)
- Performance Trends Chart
- Competitive Gaps Table
- Top Sources panel
- Quick actions buttons

---

## Additional Diagrams

### `competitive-analysis-workflow.png`
**Purpose**: Explain competitive analysis workflow
**Content**: Flowchart showing:
1. Add competitors
2. Create prompts
3. Run analysis
4. Compare results
5. Optimize

### `prompt-execution-flow.png`
**Purpose**: Explain how prompt execution works
**Content**: Diagram showing:
1. User creates/selects prompts
2. Prompts sent to AI models (GPT-4, Claude, Gemini, etc.)
3. Responses analyzed
4. Metrics calculated
5. Results displayed

---

## Screenshot Capture Checklist

Before taking screenshots:

- [ ] Use production or staging environment with realistic data
- [ ] Ensure all images/logos load properly
- [ ] No loading spinners or skeleton screens
- [ ] Use a consistent browser (Chrome recommended)
- [ ] Clear browser width: 1920px or wider
- [ ] Hide browser chrome if possible (use screenshot tools)
- [ ] Consistent zoom level (100%)
- [ ] Light mode (unless documenting dark mode)
- [ ] Clean up notifications, errors, or temporary UI states

---

## Recommended Tools

**macOS**:
- CleanShot X (paid, best quality)
- Shift + Command + 4 (native screenshot)
- Snagit (paid)

**Windows**:
- Snipping Tool
- Snagit (paid)
- ShareX (free)

**Browser Extensions**:
- Awesome Screenshot
- Full Page Screen Capture
- GoFullPage

**Editing**:
- Figma (for annotations and diagrams)
- Photoshop
- Preview (macOS)
- GIMP (free)

---

## Priority Order

**High Priority** (needed for launch):
1. Overview pages (dashboard, define, analyze, commerce, experiments)
2. Onboarding flow (all 6 phases)
3. Main feature pages

**Medium Priority**:
4. Detailed component screenshots (tables, panels, dialogs)
5. Workflow diagrams

**Low Priority**:
6. Additional variations
7. Edge cases
8. Dark mode variants

---

## Notes

- Some screenshots can be combined (e.g., `analyze-page-overview.png` could show all tabs in one scrolling capture)
- Diagrams can be created in Figma, Miro, or similar tools instead of screenshots
- Annotated screenshots with arrows/labels help clarify complex interfaces
- Consider creating GIFs or short video clips for interactive features (optional enhancement)

---

**Total Screenshots Needed**: ~50-60 images
**Estimated Time**: 3-4 hours with proper setup
**Recommended**: Dedicate focused time block, don't rush individual screenshots

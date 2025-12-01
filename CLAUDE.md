# CLAUDE.md - AI Assistant Guide for mcadetxx Profile Repository

**Last Updated**: 2025-12-01
**Repository Type**: GitHub Profile README
**Primary Maintainer**: Marckenrold Cadet (@mcadetxx)

---

## 📋 Table of Contents

1. [Repository Overview](#repository-overview)
2. [Repository Structure](#repository-structure)
3. [Development Workflows](#development-workflows)
4. [Content Guidelines](#content-guidelines)
5. [Technical Conventions](#technical-conventions)
6. [Git Workflow](#git-workflow)
7. [AI Assistant Best Practices](#ai-assistant-best-practices)
8. [Common Tasks & Examples](#common-tasks--examples)
9. [Resources & References](#resources--references)

---

## 🎯 Repository Overview

### What This Repository Is

This is a **special GitHub profile repository** (username/username pattern). The `README.md` file in this repository is automatically displayed on the GitHub profile page at `https://github.com/mcadetxx`.

**Purpose**: Professional portfolio and personal branding for Marckenrold Cadet, showcasing:
- Professional experience and achievements
- Technical skills and expertise
- Featured projects and case studies
- Education and certifications
- Contact information and networking opportunities

**Audience**:
- Recruiters and hiring managers
- Potential collaborators and clients
- Professional network and peers
- Open source community

### Key Characteristics

- **Single-File Focus**: Primary content is in `README.md`
- **Markdown-Based**: Uses GitHub-Flavored Markdown (GFM)
- **Visually Rich**: Incorporates badges, images, animations, and dynamic content
- **Professional Tone**: Balance between technical expertise and approachability
- **Data-Driven**: Emphasizes measurable impact and quantified achievements

---

## 📁 Repository Structure

```
mcadetxx/
├── .git/                  # Git version control directory
├── README.md              # GitHub profile page content (main file)
└── CLAUDE.md             # This file - AI assistant documentation
```

### File Descriptions

#### README.md
- **Purpose**: GitHub profile page content
- **Size**: ~21KB (545 lines)
- **Format**: GitHub-Flavored Markdown
- **Special Features**:
  - Animated headers and typing effects
  - Dynamic badges and metrics
  - Mermaid diagrams (timeline)
  - External API integrations (GitHub stats, shields.io)
  - Responsive tables and layouts

#### CLAUDE.md (This File)
- **Purpose**: Documentation for AI assistants
- **Audience**: Claude, GPT, and other AI coding assistants
- **Maintenance**: Update when conventions or structure changes

---

## 🔄 Development Workflows

### Standard Update Workflow

1. **Identify Change Request**
   - User requests specific update to profile
   - Review current content in README.md
   - Understand context and surrounding sections

2. **Make Changes**
   - Use `Edit` tool for targeted modifications
   - Preserve existing formatting and style
   - Maintain consistency with surrounding content
   - Test markdown rendering mentally (or suggest preview)

3. **Commit Changes**
   - Write clear, descriptive commit message
   - Follow format: `<action> <target> in README.md`
   - Examples:
     - `Update education status in README.md`
     - `Add new project section to README.md`
     - `Fix LinkedIn URL in README.md`

4. **Push to Branch**
   - Always push to designated `claude/*` branch
   - Use: `git push -u origin <branch-name>`
   - Branch naming: `claude/claude-md-<session-id>`

### Common Change Types

| Change Type | Workflow | Example |
|-------------|----------|---------|
| **URL Fix** | Edit specific line → Commit → Push | Fix broken LinkedIn link |
| **Content Update** | Edit section → Verify formatting → Commit → Push | Update job title or dates |
| **New Section** | Add content → Integrate styling → Commit → Push | Add new project showcase |
| **Metrics Update** | Edit numbers → Update related text → Commit → Push | Update cost savings from $2.3M to $2.5M |
| **Restructure** | Plan changes → Edit multiple sections → Commit → Push | Reorganize skills section |

---

## 📝 Content Guidelines

### Writing Style

**Voice & Tone**:
- **Professional yet personable**: Not overly formal
- **Achievement-focused**: Lead with measurable impact
- **Active voice**: "Built ETL pipeline" vs "ETL pipeline was built"
- **Confident without arrogance**: Let results speak
- **Technical but accessible**: Avoid unnecessary jargon

**Quantification Standards**:
- Always include dollar amounts with `$` and magnitude markers (`M`, `K`)
- Use percentages for improvements (e.g., "35% efficiency gain")
- Include scale metrics (e.g., "500K+ transactions monthly")
- Provide concrete timeframes (e.g., "Q1 2026", "2023-2024")

**Example Patterns**:
```markdown
✅ Good: "Delivered $2.3M+ in cost savings through data-driven optimization"
❌ Bad: "Saved money by optimizing processes"

✅ Good: "Built ETL pipeline processing 500K+ monthly transactions"
❌ Bad: "Created a data pipeline for the company"

✅ Good: "Reduced operational inefficiencies by 35%"
❌ Bad: "Made things more efficient"
```

### Content Structure Principles

1. **Hero Section** (Lines 1-43)
   - Animated banner
   - Name and typing animation
   - Key metrics badges
   - Social links
   - **Never remove**: Core branding elements

2. **Introduction** (Lines 45-99)
   - "Who I Am" overview
   - Mission statement
   - "What Sets Me Apart" table
   - **Update frequency**: High (job changes, achievements)

3. **Education** (Lines 102-114)
   - Table format with emoji icons
   - Degrees and certifications
   - **Update frequency**: Low (add new certs)

4. **Projects** (Lines 117-239)
   - Featured work in table layout
   - Impact metrics and tech stack
   - Links to repos/demos
   - **Update frequency**: Medium (new projects quarterly)

5. **Experience Timeline** (Lines 242-259)
   - Mermaid diagram
   - Career milestones
   - **Update frequency**: Low (major career changes)

6. **Technical Skills** (Lines 262-314)
   - Categorized by type
   - Shield.io badges
   - **Update frequency**: Medium (new tech adoption)

7. **GitHub Stats** (Lines 317-348)
   - Dynamic API-generated graphics
   - **Update frequency**: Never (auto-updates)

8. **Current Focus** (Lines 350-421)
   - Active projects
   - Collaboration opportunities
   - **Update frequency**: High (monthly reviews)

9. **Life Beyond Code** (Lines 424-469)
   - Personal interests and hobbies
   - **Update frequency**: Low (major life changes)

10. **Contact & Footer** (Lines 472-546)
    - Contact methods
    - Call-to-action
    - **Update frequency**: Low (contact info changes)

### Content Restrictions

**DO NOT**:
- Remove or modify animated elements without explicit request
- Change shield.io badge URLs unless fixing broken links
- Alter table structures without preserving alignment
- Add emoji without matching existing style patterns
- Modify mermaid diagram syntax carelessly
- Change GitHub username or core identity elements
- Add fictional achievements or exaggerated metrics
- Include unverified external links

**DO**:
- Maintain visual consistency across sections
- Preserve existing formatting patterns
- Keep tables aligned and properly structured
- Use existing emoji patterns for new content
- Verify all URLs before adding them
- Fact-check numerical claims with user
- Match existing badge styles when adding new ones

---

## 🔧 Technical Conventions

### Markdown Standards

**GitHub-Flavored Markdown (GFM)**:
- Use GFM features: tables, task lists, emoji shortcodes
- Support for HTML when needed (alignment, styling)
- Mermaid diagrams for visualizations

**Image Handling**:
```markdown
# External API Images (auto-updating)
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mcadetxx&...)

# Static Images with Alt Text
<img src="URL" alt="Description" width="380" />

# Aligned Images
<img align="right" alt="Description" width="380" src="URL" />
```

**Badge Formatting**:
```markdown
# Standard shields.io badge
![Label](https://img.shields.io/badge/Label-Text-Color?style=for-the-badge&logo=icon&logoColor=white)

# Custom metrics badge
<img src="https://img.shields.io/badge/💰_Impact-$2.3M+_Saved-00DC82?style=for-the-badge" />
```

**Table Structure**:
```markdown
# Two-column layout pattern
<table>
<tr>
<td width="50%">

Content for left column

</td>
<td width="50%">

Content for right column

</td>
</tr>
</table>
```

### URL Conventions

**External Services Used**:
- `capsule-render.vercel.app` - Animated headers
- `readme-typing-svg.demolab.com` - Typing animations
- `shields.io` / `img.shields.io` - Badges and metrics
- `github-readme-stats.vercel.app` - GitHub statistics
- `github-readme-streak-stats.herokuapp.com` - Contribution streaks
- `github-readme-activity-graph.vercel.app` - Activity graphs
- `github-profile-trophy.vercel.app` - Achievement trophies
- `quotes-github-readme.vercel.app` - Quote generation
- `icons8.com` - Icon images
- `komarev.com/ghpvc` - Profile view counter

**Link Patterns**:
```markdown
# Social links
LinkedIn: https://www.linkedin.com/in/marckenrold/
Email: mcadet.analytics@gmail.com
Website: https://duetoanalytics.com
GitHub: https://github.com/mcadetxx

# Project links (placeholder pattern)
[View Case Study](https://github.com/mcadetxx/project-name)
[Live Demo](https://app.powerbi.com/...)  # Often placeholder
```

### Color Scheme

**Brand Colors** (maintained throughout):
- Primary Blue: `#3B82F6`
- Purple: `#9333EA`
- Green (success): `#00DC82`
- Orange (accent): `#F59E0B`
- Dark background: `#0d1117` (GitHub dark theme)
- Text: `#c9d1d9` (light gray)

**Badge Color Codes**:
- Impact/Money: `00DC82` (green)
- Scale: `3B82F6` (blue)
- Data: `9333EA` (purple)
- Leadership: `F59E0B` (orange)

---

## 🌿 Git Workflow

### Branch Strategy

**Working Branches**:
- Pattern: `claude/claude-md-<random-string>-<session-id>`
- Example: `claude/claude-md-mimsoc0k5ippnrgb-01X2AAq2JS691G9cjwsPiMNW`
- **Rule**: Always work on designated claude branch
- **Never**: Push directly to main without authorization

### Commit Message Conventions

**Format**: `<action> <target> [context]`

**Action Verbs**:
- `Update` - Modify existing content
- `Add` - Introduce new content
- `Fix` - Correct errors or broken elements
- `Revise` - Substantial rewrite
- `Refactor` - Restructure without content change
- `Remove` - Delete content
- `Enhance` - Improve existing feature

**Examples** (from git history):
```bash
Update degree timeline in README.md
Revise education status in README
Fix LinkedIn URL in README.md
Update README.md  # Acceptable but less specific
```

**Best Practices**:
```bash
# Good - Specific and clear
git commit -m "Update RNDC cost savings from $2.3M to $2.5M in README.md"
git commit -m "Add new AI Investment project section to README.md"
git commit -m "Fix broken DueTo Analytics website link"

# Avoid - Too vague
git commit -m "Update README"
git commit -m "Changes"
git commit -m "Fix stuff"
```

### Push Guidelines

**Standard Push**:
```bash
git push -u origin claude/claude-md-<session-id>
```

**Retry Logic** (on failure):
- Retry up to 4 times with exponential backoff
- Delays: 2s, 4s, 8s, 16s
- Only retry on network errors (not auth failures)

**Branch Validation**:
- ✅ Branch MUST start with `claude/`
- ✅ Branch MUST end with matching session ID
- ❌ Pushing to wrong branch → 403 error

---

## 🤖 AI Assistant Best Practices

### Before Making Changes

**ALWAYS**:
1. **Read README.md first** - Never propose changes to unseen content
2. **Understand context** - Review surrounding sections
3. **Verify current state** - Check if information is already present/accurate
4. **Ask clarifying questions** - When user request is ambiguous
5. **Preserve formatting** - Match existing style patterns

**NEVER**:
1. Guess or assume content without reading the file
2. Remove sections without explicit permission
3. Change URLs without verifying they're broken
4. Add fictional achievements or metrics
5. Alter visual elements (badges, animations) unnecessarily

### Making Edits

**Use Edit Tool Properly**:
```python
# ✅ Good - Specific, includes context
Edit(
    file_path="/home/user/mcadetxx/README.md",
    old_string="**MS in Data Science** | Florida Polytechnic University | 2023-2024",
    new_string="**MS in Data Science** | Florida Polytechnic University | 2023-2025"
)

# ❌ Bad - Too much context (not unique)
Edit(
    file_path="/home/user/mcadetxx/README.md",
    old_string="## 🎓 Education & Certifications\n\n<div align=\"center\">\n\n| 🎯 Degree/Cert | 🏫 Institution |",
    new_string="..."  # Entire section replacement
)
```

**When to Use Write vs Edit**:
- **Edit**: Modifying existing content (99% of cases)
- **Write**: Never use for README.md unless complete rewrite requested
- **Read**: Always use before any Edit operation

### Commit Strategy

**Single Logical Changes**:
```bash
# ✅ Good - One logical change per commit
1. Update job title → Commit "Update job title in README.md"
2. Update project metrics → Commit "Update RNDC dashboard metrics in README.md"

# ❌ Bad - Multiple unrelated changes
1. Update job title + Add new project + Fix typo → Single commit
```

**Commit Frequency**:
- Small targeted updates: 1 commit
- Multiple section updates: Multiple commits (one per section)
- Large restructure: Single commit with detailed message

### Common Pitfalls

| Pitfall | Why It's Wrong | Solution |
|---------|----------------|----------|
| Not reading file first | Propose changes to unseen content | Always use Read tool first |
| Breaking table alignment | Markdown tables are sensitive | Preserve exact spacing and pipes |
| Changing badge URLs | Breaks visual consistency | Only change if verifying broken |
| Removing line numbers from old_string | Edit tool needs exact match | Copy content after line number prefix |
| Assuming placeholder links are broken | Many links are intentional placeholders | Ask user before "fixing" |
| Adding emoji inconsistently | Breaks visual pattern | Match existing emoji usage style |

---

## 📚 Common Tasks & Examples

### Task 1: Update Employment Status

**Scenario**: User got promoted or changed jobs

**Workflow**:
```markdown
1. Read README.md (check current job info)
2. Identify all occurrences:
   - Line 7: Professional subtitle
   - Line 52: "Who I Am" section
   - Line 253: Experience timeline
3. Edit each occurrence with proper context
4. Commit: "Update employment status to [New Role] in README.md"
5. Push to claude branch
```

**Example Edit**:
```python
Edit(
    file_path="/home/user/mcadetxx/README.md",
    old_string="**Senior Operations Analyst** at **Republic National Distributing Company (RNDC)**",
    new_string="**Lead Data Scientist** at **Republic National Distributing Company (RNDC)**"
)
```

### Task 2: Add New Project

**Scenario**: User completed new project to showcase

**Workflow**:
```markdown
1. Read README.md (review existing project format)
2. Identify insertion point (lines 164-239, project table)
3. Gather project details:
   - Title and impact metrics
   - Description and features
   - Tech stack
   - Links (repo, demo, docs)
4. Create table cell following existing pattern
5. Edit to insert new project
6. Commit: "Add [Project Name] to featured projects in README.md"
7. Push to claude branch
```

**Template Pattern**:
```markdown
<td width="50%" valign="top">

#### 🎯 **Project Title**
**Impact:** [Metric] | **Status:** [Status]

[Brief description of project and its purpose]

**Key Features:**
- Feature 1 with metric
- Feature 2 with metric
- Feature 3 with metric

**Tech:** Tool1 • Tool2 • Tool3 • Tool4

🔗 [GitHub Repo](https://github.com/mcadetxx/project) • 🌐 [Live Demo](https://...)

</td>
```

### Task 3: Update Metrics/Achievements

**Scenario**: User achieved new milestone or updated numbers

**Workflow**:
```markdown
1. Read README.md (find all instances of old metric)
2. Use Grep if needed: grep "2.3M" README.md
3. Identify all occurrences:
   - Line 12: Key metrics bar
   - Line 66: "What Sets Me Apart" section
   - Line 131: RNDC Operations Dashboard
4. Update consistently across all sections
5. Commit: "Update cost savings metric from $2.3M to $2.5M in README.md"
6. Push to claude branch
```

### Task 4: Fix Broken Link

**Scenario**: URL returns 404 or needs updating

**Workflow**:
```markdown
1. Read README.md
2. Locate broken link
3. Verify with user what correct URL should be
4. Edit link preserving markdown format
5. Commit: "Fix [Link Type] URL in README.md"
6. Push to claude branch
```

**Example**:
```python
Edit(
    file_path="/home/user/mcadetxx/README.md",
    old_string='<a href="https://linkedin.com/in/marckenrold">',
    new_string='<a href="https://www.linkedin.com/in/marckenrold/">'
)
```

### Task 5: Add New Certification

**Scenario**: User earned new certification

**Workflow**:
```markdown
1. Read README.md (review education section, lines 102-114)
2. Note table format and existing entries
3. Create new row following pattern
4. Insert in appropriate order (by date or importance)
5. Commit: "Add [Certification Name] to education section in README.md"
6. Push to claude branch
```

**Table Row Pattern**:
```markdown
| **Certification Name** | Issuing Organization | Year | Highlights/Topics |
```

---

## 🔍 Resources & References

### Markdown & GitHub

- **GitHub-Flavored Markdown**: https://github.github.com/gfm/
- **GitHub Profile READMEs**: https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme
- **Mermaid Diagrams**: https://mermaid.js.org/
- **Markdown Tables**: https://www.markdownguide.org/extended-syntax/#tables

### External Services

- **Shields.io Badges**: https://shields.io/
- **GitHub Readme Stats**: https://github.com/anuraghazra/github-readme-stats
- **Capsule Render**: https://github.com/kyechan99/capsule-render
- **Typing SVG**: https://github.com/DenverCoder1/readme-typing-svg
- **Icons8**: https://icons8.com/

### Portfolio Best Practices

- **GitHub Profile Guide**: https://github.com/abhisheknaiidu/awesome-github-profile-readme
- **Markdown Badges**: https://github.com/Ileriayo/markdown-badges
- **Profile Examples**: https://github.com/codestackr/codestackr

### User's Professional Links

- **LinkedIn**: https://www.linkedin.com/in/marckenrold/
- **Email**: mcadet.analytics@gmail.com
- **Website**: https://duetoanalytics.com
- **GitHub**: https://github.com/mcadetxx

---

## 📝 Maintenance Notes

### When to Update This File

- Repository structure changes (new files added)
- New conventions adopted (style guide updates)
- Workflow changes (new git procedures)
- Common patterns emerge (add to examples)
- External services change (API updates)

### Version History

| Date | Change | Reason |
|------|--------|--------|
| 2025-12-01 | Initial creation | Provide AI assistant guidance |

---

## 🎯 Quick Reference Checklist

**Before Every Change**:
- [ ] Read README.md first
- [ ] Understand user request completely
- [ ] Check git status and current branch
- [ ] Verify you're on correct `claude/*` branch

**Making Changes**:
- [ ] Use Edit tool (not Write) for modifications
- [ ] Preserve exact formatting and structure
- [ ] Match existing style patterns
- [ ] Keep tables aligned
- [ ] Maintain visual consistency

**After Changes**:
- [ ] Write clear commit message
- [ ] Use format: `<action> <target> in README.md`
- [ ] Push to designated claude branch
- [ ] Verify push succeeded

**Quality Checks**:
- [ ] URLs are valid (or acknowledged placeholders)
- [ ] Metrics are accurate (verified with user)
- [ ] Formatting matches existing patterns
- [ ] Tables are properly aligned
- [ ] No broken markdown syntax

---

## 💡 Tips for Success

1. **Read First, Edit Later**: Always understand current state before proposing changes
2. **Be Specific in Commits**: Future you (and users) will thank you
3. **Preserve Visual Consistency**: This profile is carefully designed
4. **Ask Questions**: Better to clarify than assume
5. **Test Mentally**: Visualize how markdown will render
6. **Keep It Professional**: This represents someone's career
7. **Verify Metrics**: Don't guess numbers - ask the user
8. **Respect Placeholders**: Some "broken" links are intentional

---

**Remember**: This README is Marckenrold's professional brand. Every change should enhance, not detract from, that professional image. When in doubt, ask the user for clarification.

**Happy Editing! 🚀**

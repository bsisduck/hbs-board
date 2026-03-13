# HBS Board

Get MBA-level strategic advice from 12 world-class business school professors — without the $200K tuition. Ask any business question and the right advisor activates automatically with structured, actionable frameworks.

## Advisors

| Advisor | School | What You Get |
|---|---|---|
| Case Study Analyzer | Harvard Business School | Real company case studies with Socratic questioning |
| Michael Porter | Harvard Business School | Five Forces, competitive positioning, strategic action plan |
| Clayton Christensen | Harvard Business School | Disruption analysis, jobs-to-be-done framework |
| Wharton Accounting Professor | Wharton | Financial statement analysis, 10 key ratios, red flags |
| Stanford GSB Leadership Coach | Stanford GSB | Leadership style assessment, 90-day development plan |
| Kellogg Marketing Professor | Kellogg | STP analysis, positioning statement, 90-day marketing plan |
| Harvard Negotiation Master | Harvard Law School | BATNA analysis, word-for-word scripts, concession strategy |
| Chicago Booth Finance Professor | Chicago Booth | DCF valuation, WACC, NPV/IRR, capital structure |
| MIT Sloan Operations Professor | MIT Sloan | Process mapping, bottleneck analysis, lean waste elimination |
| INSEAD Growth Advisor | INSEAD | Ansoff Matrix, 3-year expansion roadmap, partnership strategy |
| Columbia Startup Finance Advisor | Columbia | Funding stage assessment, pitch deck structure, cap table |
| Harvard Kennedy Decision Strategist | Harvard Kennedy School | Decision matrix, pre-mortem analysis, bias audit |

## How It Works

This is a [Claude Skill](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/skills) — a set of instructions that teach Claude specialized workflows. When you ask a business question, the skill automatically routes to the right advisor and delivers a complete, structured analysis using that school's signature frameworks.

You can also request a **"board meeting"** to run multiple advisors sequentially for a comprehensive business review.

## Installation

### Claude.ai

1. Download or clone this repo
2. Zip the `hbs-board` folder
3. Go to Claude.ai → Settings → Capabilities → Skills
4. Upload the zip file and enable the skill

### Claude Code

```bash
git clone https://github.com/bsisduck/hbs-board.git
cp -r hbs-board/hbs-board ~/.claude/skills/hbs-board
```

## Usage

Ask any business question:

- **"Help me analyze my competitive position in SaaS"** → Porter delivers Five Forces + positioning map
- **"Prepare me for a salary negotiation"** → Harvard Negotiation builds BATNA + scripts
- **"Teach me about pricing strategy with a real example"** → HBS walks through a case study
- **"Full board meeting review of my startup"** → All advisors run sequentially
- **"Should I raise VC or bootstrap?"** → Columbia + Chicago Booth analyze together

## License

MIT

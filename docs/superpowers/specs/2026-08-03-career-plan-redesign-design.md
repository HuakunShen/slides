# Career Plan Slidev Redesign

## Goal

Rewrite `slides/career-plan/` as a short, dark, conversational presentation that explains the user's career situation to his parents. The deck should help non-technical family members understand the available paths, the real constraints, the two software products, and why finishing a public MVP before making a final career choice is a reasonable next step.

## Audience and tone

- The audience is the user's parents, not investors, recruiters, or potential customers.
- The tone is a straightforward family conversation: calm, specific, and natural.
- Avoid slogans, inspirational quotes, pitch language, corporate report language, and dramatic closing statements.
- Avoid unnecessary technical terms. Define `MVP` once as “可以公开发布、让别人实际使用的第一版”.
- Do not include the user's name, date, location line, UTC offset, or phrases such as “给家人的一份说明”.
- The cover contains only the title `职业规划`.

## Visual direction

- Force Slidev dark mode and use a near-black background throughout.
- Use off-white primary text, muted gray secondary text, thin borders, and restrained blue/green/orange accents.
- Prefer simple tables, two-column comparisons, progress bars, and a small decision flow.
- Avoid decorative blobs, oversized quotation marks, bright cards, gradients used as decoration, and dense dashboards.
- Keep each slide readable at a glance. Body copy should generally stay at or above 22 px on a 1280 px canvas.
- Use no external image assets. The products are explained through plain language and simple interface-like graphics.

## Slide structure

### 1. 职业规划

- Title only.
- No subtitle, author, date, slogan, or footer.

### 2. 我希望最后得到什么

Explain the user's actual preferences without framing them as a manifesto:

- The ideal outcome is a product that can earn recurring revenue instead of relying entirely on selling working hours.
- The work should leave some control over time and place, ideally allowing life in Hong Kong or Shenzhen and staying closer to family.
- The path should build something that remains valuable even as AI automates more routine programming work.
- A suitable job is still a valid choice; it is not presented as failure.

### 3. 现在可以走的几条路

Use the approved five-row comparison table without replacing it with marketing copy:

| 路线 | 收入上限 | 短期确定性 | 地点自由 | 对长期创业的帮助 | 我的判断 |
|---|---:|---:|---:|---:|---|
| CrossCopy startup | 极高 | 低 | 极高 | 极高 | 主攻方向 |
| 海外 Remote，住香港/深圳 | 高 | 中低 | 极高 | 中高 | 最理想的就业备选 |
| 美国线下或 Hybrid | 很高 | 中 | 低 | 中 | 高价值期权 |
| 香港本地工作 | 中高 | 中高 | 高 | 中 | 最现实的过渡方案 |
| 深圳/大陆工作 | 中 | 中高 | 高 | 中低 | 现金流保底 |

Add one short note explaining that the table compares different kinds of trade-offs and is not a promise that the first row will succeed.

### 4. 现在找工作的难点

Explain four concrete difficulties:

- The user does not yet have large-company work experience, which makes high-paying roles harder to enter.
- Large-company interviews still emphasize algorithm questions and writing code without AI assistance.
- The user has spent more than a year using AI heavily to ship products faster, so traditional handwritten coding speed now requires dedicated practice to recover.
- Time spent preparing for conventional interviews is time not spent finishing the products; leaving both products unfinished would waste their value as either potential businesses or strong portfolio evidence.

Include the AI pressure in measured language. Attribute the `90%` / approaching `99%` statement to Elon Musk as his opinion, not an objective benchmark. The conclusion is that routine code production is losing value, while product judgment, technical understanding, direction-setting, and responsibility remain important.

### 5. CrossCopy

Describe CrossCopy as a practical utility for moving files and clipboard content and coordinating actions across phones and computers, including devices on different networks. Do not explain protocols or architecture.

Show two independent progress bars:

- `达到可以发布的 MVP：约 40%`
- `达到比较成熟的产品：约 20%`
- Estimated remaining time to the MVP: `约 1–2 个月`

Clarify that progress is estimated by readiness for ordinary users, not by code volume. The current foundation is substantial, but the application workflow, permissions, onboarding, release packaging, and polish still need work.

Use LocalSend as market evidence:

- Approximately `8.6 万` GitHub Stars.
- Roughly one of the top `200` public repositories on GitHub at the current count.
- More than `500 万` downloads reported by its official site.
- Stars and downloads do not equal active users, but they demonstrate that cross-device file transfer is not a niche need.

Explain the business fit in plain language: CrossCopy can sell useful advanced features to individuals first, and may later support teams or companies. This is why it is the current primary project.

### 6. Kunkun

Describe Kunkun as a desktop toolbox: users install small plugins for search, file and system tools, and AI-assisted tasks. Its potential audience is broad, but turning that broad utility into something people will pay for is difficult.

Show two independent progress bars:

- `达到可以发布的 MVP：约 70%`
- `达到比较成熟的产品：约 45%`
- Estimated remaining time to the MVP: `约 2 个月`

Explain that the product shape and plugin system already exist. The release difficulty comes from polishing many details, stabilizing plugin compatibility, security boundaries, packaging, and supporting plugins. This makes Kunkun valuable but less suitable than CrossCopy as the immediate monetization focus.

### 7. 不同工作地点的实际区别

Use four compact comparisons:

- Shenzhen / mainland: familiar life, convenient, lower costs, and close to family; weaker work culture, more overtime, and a lower ceiling for many roles.
- Hong Kong: close to Shenzhen, existing work authorization, and easier access to international companies; fewer technology roles and higher living costs.
- Overseas remote while living in Hong Kong or Shenzhen: maximum location freedom and continued product work; global competition and employer-location restrictions make it difficult.
- United States / Canada: higher salary and career ceiling and generally better work culture at established companies; relocation, competition, and interview preparation create a higher entry cost.

Do not include visa-document checklists or detailed immigration procedures.

### 8. 为什么先把 MVP 做出来

Define the MVP as the first release that is stable enough for other people to use, even if it has fewer features.

Explain the two benefits of reaching this point:

- If users use it and some are willing to pay, CrossCopy can continue toward a business.
- If the commercial signal is weak, the released product, demo, users, and engineering work become much stronger evidence for job applications than another unfinished private project.

State that fewer polished features are preferable to many unfinished ones. Do not mention Product Hunt rankings, Hacker News votes, fundraising, or marketing tactics.

### 9. 接下来怎么走

Show a simple flow rather than a motivational conclusion:

1. Focus on finishing and publicly releasing the CrossCopy MVP.
2. Once it can be demonstrated, begin job applications while continuing to collect product feedback.
3. If usage and payment signals are promising, invest more in the product.
4. If they are weak, use the finished project to pursue suitable work in Hong Kong, remote teams, or North America.

End on this practical flow. Do not add a separate closing slide or family-message slide.

## Content exclusions

- No author name, date, `UTC+8`, or identity/visa checklist.
- No slogans such as “保留选择权”, “不孤注一掷”, “看信号不看情绪”, or “不是兴趣项目，是资产”.
- No slide titled “我希望家人理解的三件事”.
- No six-month checkpoint timeline, salary scorecard, or dramatic final quote.
- No Product Hunt, Hacker News, fundraising, VC, or launch-ranking strategy.
- No detailed technical architecture, protocol names, repository statistics, code volume, or commit counts.
- No unsupported mapping from GitHub Stars to active users.

## Sources and factual wording

- Current product progress is a rough planning estimate based on repository state and the user's own remaining-time estimate; the deck must label it as approximate.
- LocalSend figures are time-sensitive and should be rounded in the visible slide copy.
- The Elon Musk statement must be presented as his claim or opinion, not as established measurement.
- Source links may appear as unobtrusive footnotes on the relevant slides and in speaker notes.

## Verification

- Run the local Slidev build and confirm there are no Markdown, Vue, CSS, or asset errors.
- Export or render the deck and inspect all nine slides at presentation size.
- Confirm that no text overflows, no table row is clipped, and both progress-bar pairs are immediately understandable.
- Confirm the deck stays dark in both the browser presentation and exported output.
- Scan the final source for every excluded phrase and metadata field.

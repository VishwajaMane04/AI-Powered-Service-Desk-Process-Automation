# Options Appraisal

Before defining requirements, four realistic options were evaluated against the findings from the data analysis. The goal was to justify the recommended solution on evidence, not assumption.

## The options
- Retain current process  keep logging every issue to the service desk (the baseline).
- Improve the knowledge base  write more and better self-help articles.
- Self-service portal, a searchable menu/FAQ where staff find fixes themselves.
- AI chatbot — a natural-language assistant that interprets the issue and guides the fix.

| Criterion | Retain current process | Improve knowledge base | Self-service portal | AI chatbot |
|---|---|---|---|---|
| Implementation cost | None | Low | Medium | Medium–High |
| Time to deliver | None | Low | Medium | High |
| Expected deflection | 0% | Low | Medium | High (~45%) |
| Fit with the evidence | Poor | Poor — KB already exists | Partial — vague queries | Strong |
| Ongoing effort | None | Medium | Medium | Low |
| Risk of not solving it | High | High | Medium | Low |

# Recommendation

## The AI chatbot.

It carries the highest build cost, but it is the only option that addresses all three findings from the analysis:
A knowledge base already existed for 86% of calls and stores called anyway, so improving it does not fix the underlying access gap.
A self-service portal improves access but relies on staff typing a sensible search term, and 41% of call descriptions are three words or fewer ("HHt not woking", "Scanner till 3"), which a menu or search box handles poorly.
Only an AI assistant that understands natural, imprecise language brings the existing fix to staff at the point of need.
The lower-cost options fail on fit, not on price. The chatbot is therefore recommended, and its requirements are defined in the next section.

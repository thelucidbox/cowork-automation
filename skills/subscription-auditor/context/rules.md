# Subscription Auditor — Rules & Guidelines

## Output Format

### subscriptions.md
```markdown
# Subscription Inventory

## Active Subscriptions

| Service | Cost | Frequency | Category | Last Used |
|---------|------|-----------|----------|-----------|
| Netflix | $15.99 | Monthly | Streaming | This week |
| Spotify | $10.99 | Monthly | Music | Daily |
| Adobe CC | $54.99 | Monthly | Software | Monthly |

## Summary
- Total monthly: $XXX
- Total annual: $XXX
- Subscription count: XX

## By Category
| Category | Monthly | Annual |
|----------|---------|--------|
| Streaming | $XX | $XXX |
| Software | $XX | $XXX |
```

### recommendations.md
```markdown
# Optimization Recommendations

## Immediate Savings
| Action | Service | Savings |
|--------|---------|---------|
| Cancel | [unused service] | $X/mo |
| Downgrade | [overtiered service] | $X/mo |

## Consider
- [Service A] overlaps with [Service B]
- Annual plan saves $X on [Service]

## Keep
- [Essential services with justification]
```

---

## Detection Patterns

### Common Subscription Names
- Streaming: Netflix, Hulu, Disney+, HBO
- Music: Spotify, Apple Music, YouTube Music
- Software: Adobe, Microsoft, Notion
- Storage: Dropbox, iCloud, Google One

### Billing Patterns
- Monthly: Same date each month
- Annual: Same date each year
- Quarterly: Every 3 months

---

*Part of Art of Fact Cowork Skill Library*

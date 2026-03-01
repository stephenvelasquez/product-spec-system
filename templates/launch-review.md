# Launch Review: [Feature Name]

**Date:** ___ | **Feature flag:** ___ | **Spec:** [Link]

## Go / No-go

| Area | Owner | Status | Notes |
|------|-------|--------|-------|
| QA | | Ready / Blocked | |
| Analytics | | Ready / Blocked | |
| Performance | | Ready / Blocked | |
| Security | | Ready / Blocked | |
| Support readiness | | Ready / Blocked | |
| Rollback plan | | Ready / Blocked | |

**Decision:** Go / No-go
**Decided by:** ___

## Rollout plan

| Phase | % of users | Duration | Promotion criteria |
|-------|-----------|----------|-------------------|
| Canary | 1% | 24 hours | No errors, latency normal |
| Beta | 10% | 3 days | Metrics neutral or positive |
| GA | 100% | - | All criteria met |

## Monitoring

| Metric | Alert threshold | Dashboard link |
|--------|----------------|---------------|
| Error rate | > 1% | |
| P99 latency | > 500ms | |
| Primary metric | < baseline | |

## Rollback

- **Trigger:** ___
- **Method:** Feature flag kill switch
- **Estimated recovery time:** < 5 minutes
- **Owner:** ___

## Communication plan

| Audience | Channel | When | Owner |
|----------|---------|------|-------|
| Internal | Slack #launches | At launch | |
| Support | Zendesk article | Before launch | |
| External | Changelog / blog | After GA | |

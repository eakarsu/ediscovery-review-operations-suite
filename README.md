# eDiscovery Review Operations Suite

Wave:
- Portfolio next-20 completion batch

Source candidates represented:
- `AIeDiscoveryReviewOperationsAssistant`
- `AIeDiscoveryReviewOperationsOperations`
- `AIeDiscoveryReviewOperationsAnalytics`
- `AIeDiscoveryReviewOperationsWorkflow`

This suite is a runnable merged app with one login, one dashboard, one feature-first sidebar, PostgreSQL-backed records/documents/notifications/audit, role behavior, and smoke coverage.

## Local Run

```bash
cd /Users/erolakarsu/projects/merged/ediscovery-review-operations-suite
./start.sh
```

Local URL:
- `http://127.0.0.1:5610`

Seeded users:
- `admin@ediscovery-review-operations.local / admin123`
- `manager@ediscovery-review-operations.local / manager123`
- `analyst@ediscovery-review-operations.local / analyst123`

## Validation

```bash
cd /Users/erolakarsu/projects/merged/ediscovery-review-operations-suite/frontend
npm run typecheck
SMOKE_BASE_URL=http://127.0.0.1:5610 npm run smoke
```

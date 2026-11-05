# Final pool

Implemented tasks collected from the developer branches of BenchTasksCollv3,
cross-checked against the Task Tracker in Notion.

Each task directory was copied unchanged from the developer branch that owns it,
and is exposed here at `tasks/finalpool/<task-name>/`.

Layout follows `tasks/examples/example-task`: `docs/task.md` and
`docs/agent_system_prompt.md` are required (non-empty, English only);
`docs/user_system_prompt.md`, `preprocess/main.py`, `evaluation/main.py`,
`initial_workspace/` and `groundtruth_workspace/` are optional.

## Pooled tasks (79)

| Task | Source branch |
| --- | --- |
| activity-logger | `lueyang-dev` |
| alert-system | `yuzhen-dev` |
| analytics-dashboard | `lv` |
| asset-optimizer | `yuxuan-dev` |
| backup-utility | `xiaochen_dev` |
| blog-engine | `gyy` |
| booking-system | `junteng_dev` |
| cache-optimizer | `wenshuo-dev` |
| calendar-sync | `junteng_dev` |
| canvas-automation | `ruige` |
| canvas-grade-automation | `jl_dev` |
| certificate-manager | `zhaochen` |
| chat-bot | `lv` |
| client-portal | `lueyang-dev` |
| cms-builder | `gyy` |
| contact-manager | `junteng_dev` |
| content-manager | `yuxuan-dev` |
| content-scheduler | `gyy` |
| coupon-manager | `fan-dev` |
| crm-system | `lueyang-dev` |
| customer-feedback-processor | `jl_dev` |
| customer-portal | `junteng_dev` |
| data-analytics | `ruige` |
| data-validator | `yuzhen-dev` |
| deal-manager | `lueyang-dev` |
| deployment-tool | `xiaochen_dev` |
| discount-calculator | `fan-dev` |
| email-campaign | `lueyang-dev` |
| email-classification-system | `jl_dev` |
| error-tracker | `xiaochen_dev` |
| expense-tracker | `ruige` |
| feedback-collector | `lv` |
| file-manager | `ruige` |
| follow-up-reminder | `lueyang-dev` |
| form-builder | `yuzhen-dev` |
| health-monitor | `xiaochen_dev` |
| help-desk | `junteng_dev` |
| image-processor | `wenshuo-dev` |
| inventory-management | `jl_dev` |
| invoice-generator | `yuzhen-dev` |
| load-balancer | `zhaochen` |
| log-analyzer | `ruige` |
| loyalty-program | `fan-dev` |
| media-organizer | `haoze` |
| monitoring-agent | `xiaochen_dev` |
| network-analyzer | `yuxuan-dev` |
| order-processor | `junteng_dev` |
| payment-processor | `yuzhen-dev` |
| pdf-report-generator | `jl_dev` |
| permission-manager | `yuzhen-dev` |
| personalization-service | `lv` |
| price-tracker | `fan-dev` |
| product-catalog | `junteng_dev` |
| qr-generator | `junxian_dev` |
| reminder-service | `junteng_dev` |
| robots-handler | `gyy` |
| sales-pipeline | `lueyang-dev` |
| scheduler | `wenshuo-dev` |
| search-engine | `wenshuo-dev` |
| security-scanner | `xiaochen_dev` |
| sentiment-analyzer | `lv` |
| shipment-tracker | `junteng_dev` |
| sitemap-generator | `gyy` |
| social-connector | `junxian_dev` |
| social-publisher | `gyy` |
| status-checker | `xiaochen_dev` |
| storage-manager | `zhaochen` |
| streaming-service | `haoze` |
| subtitle-generator | `haoze` |
| survey-builder | `lv` |
| sync-service | `yuxuan-dev` |
| tag-manager | `gyy` |
| task-scheduler | `yuxuan-dev` |
| template-engine | `zhaochen` |
| territory-manager | `lueyang-dev` |
| translation-api | `junxian_dev` |
| video-trimmer | `haoze` |
| voice-processor | `lv` |
| web-crawler | `ruige` |

## Reviewed but still implementing (not pooled)

These newest tasks failed the English-only documentation requirement, so they
are tracked as `implementing` in Notion and intentionally excluded from this pool.

| Task | Source branch | Reason |
| --- | --- | --- |
| currency-converter | `junxian_dev` | task.md CHINESE |
| insights-engine | `lv` | agent_system_prompt.md CHINESE |
| audit-logger | `yuzhen-dev` | agent_system_prompt.md CHINESE |
| resource-monitor | `yuzhen-dev` | agent_system_prompt.md CHINESE |

## Review scope

The latest `Work on ... tasks` commit of every developer branch was reviewed.
29 new tasks were added to the Notion Task Status Table: 25 implemented and
4 implementing. Together with the 54 tasks already marked implemented in the
tracker, this pool contains 79 tasks.
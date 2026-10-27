# Final Pool — Implemented Tasks

Aggregated from the Notion Task Tracker (`Task Status = implemented`).
Each implemented task under `tasks/finalpool/<task-name>/` mirrors the completed skeleton:
- `docs/agent_system_prompt.md` (non-empty, English)
- `docs/task.md` (non-empty, English)
- `docs/user_system_prompt.md` (optional; present where the source task has it)
- `evaluation/main.py` (present where the source task has it)
- `preprocess/main.py` (present where the source task has it)

## Implemented tasks (54)

### fan-dev
- coupon-manager
- price-tracker

### gyy
- blog-engine
- cms-builder
- content-scheduler
- social-publisher

### haoze
- subtitle-generator
- video-trimmer

### jl_dev
- canvas-grade-automation
- email-classification-system
- pdf-report-generator

### junteng_dev
- booking-system
- calendar-sync
- contact-manager
- order-processor
- product-catalog
- reminder-service
- shipment-tracker

### junxian_dev
- qr-generator
- translation-api

### lueyang-dev
- activity-logger
- crm-system
- deal-manager
- email-campaign
- follow-up-reminder
- sales-pipeline

### lv
- chat-bot
- feedback-collector
- personalization-service
- sentiment-analyzer
- voice-processor

### ruige
- canvas-automation
- data-analytics
- expense-tracker
- file-manager

### wenshuo-dev
- image-processor
- search-engine

### xiaochen_dev
- backup-utility
- deployment-tool
- error-tracker
- monitoring-agent
- security-scanner

### yuxuan-dev
- asset-optimizer
- content-manager
- network-analyzer
- task-scheduler

### yuzhen-dev
- alert-system
- data-validator
- form-builder
- invoice-generator
- payment-processor
- permission-manager

### zhaochen
- load-balancer
- template-engine

## Excluded — latest-commit tasks still `implementing`

Excluded from the final pool because completion artifacts are not finalized
(missing required `task_config.json` with `needed_mcp_servers` / `needed_local_tools`
including `claim_done`; several also have non-English content in required docs or
lack `evaluation/main.py`).

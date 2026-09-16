├── workflows/
│   ├── ci.yml          # Continuous integration
│   ├── cd.yml          # Continuous deployment
│   └── security-scan.yml
src/
├── workflows/
│   ├── lead-capture.json  # n8n workflow export
│   └── escalation.json
├── scripts/
│   ├── deploy.sh
│   └── rollback.sh
└── tests/
    ├── unit/
    └── integration/
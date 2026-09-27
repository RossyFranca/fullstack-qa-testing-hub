# fullstack-qa-testing-hub
Complete QA Automation Framework built with Playwright (UI &amp; REST API testing), k6 (Performance/Load testing), and Stryker Mutator (Mutation testing) using TypeScript &amp; Node.js.


---
fullstack-qa-testing-hub/
├── .github/
│   └── workflows/
│       ├── ui-api-tests.yml
│       ├── performance-tests.yml
│       └── mutation-tests.yml
├── config/
│   ├── playwright.config.ts
│   ├── stryker.config.json
│   └── k6.config.js
├── src/
│   ├── api/                  # Módulos de API (Playwright RequestContext)
│   │   ├── clients/
│   │   └── specs/
│   ├── ui/                   # Módulos de UI (Page Object Model - POM)
│   │   ├── pages/
│   │   ├── components/
│   │   └── specs/
│   ├── performance/          # Scripts do k6
│   │   ├── scenarios/
│   │   └── payload/
│   ├── utils/                # Fixtures, geradores de massa de dados (Faker.js)
│   └── types/                # Definições de tipos TypeScript
├── package.json
└── README.md

---

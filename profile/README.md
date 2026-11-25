# TeamControlium

Test automation tooling. Current development: **Controlium** — Node.js/TypeScript test framework for browser, API, native and integrated applications.

## Current — Controlium (Node.js / TypeScript)

Complete *ground-up* rewrite in Node.js/TypeScript, modelled on test frameworks delivered for recent clients — themselves derived from TeamControlium .NET/Java frameworks and delivering high-test-count reliable/robust API-Based and Browser-based AUT Test Suites.

| Repo | Purpose |
|---|---|
| [Framework.nodejs](https://github.com/TeamControlium/Framework.nodejs) | Tooling-agnostic general framework providing general functionality for building of Test Suites validating local/remote API-Based, Browser-based and standalone applications and/or systems. |
| [Cucumber.nodejs](https://github.com/TeamControlium/Cucumber.nodejs) | Cucumber-JS driver, for use with `@controlium/framework`, providing step-definitions and hooks needed to access functionality provided by Framework|
| [Utilities.nodejs](https://github.com/TeamControlium/Utilities.nodejs) | Low-level test automation oriented utilities, used extensively by TeamControlium Node.js Framework and tooling drivers |

### Status: active development (```Initial development phase```).
Current focus: vertical-slice development of core Cucumber-based framework, targeting API-based test suites.

#### Roadmap

1. **API testing**\
Cucumber-js test suites providing full validation of single or grouped API-based applications under framework control, with fully test-controlled mocking/controlled-passthrough.
3. **Browser UI testing**\
browser automation support for test suites validating browser-based applications.  Includes fully test-controlled mocking/controlled-passthrough for standalone function regression testing if needed
5. **AI-assisted automation**\
provider-agnostic agentic AI integration enabling test generation, test maintenance and AUT defect tracing.  This will allow organisations/teams to utilise AI to assist in automation generation/maintenance (*assist* testers, not *replace* testers!), test-failure investigation and results analysis for reporting.
7. **Broader tooling support**\
additional test-tool and test-runner drivers, extending framework coverage across toolsets and integrations.

(Timescales depend very much on contracts (need to earn to pay for food and a roof :joy:).  Between contracts — full steam ahead. On contract — evenings and weekends, coffee/family permitting.)

## Legacy — .NET (C#)

Not maintained. Retained for reference and existing NuGet consumers. Original framework that started the TeamControlium journey, still used by some Test Suites but no longer actively maintained.  Yet.

| Repo | Purpose |
|---|---|
| [Controlium.net](https://github.com/TeamControlium/Controlium.net) | UI tool support code (Selenium etc.), via NuGet |
| [Utilities.net](https://github.com/TeamControlium/Utilities.net) | General test utilities |
| [NonGUI.net](https://github.com/TeamControlium/NonGUI.net) | Non-UI HTTP/S interface helpers; error-state reporting, detailed logging |
| [NonGUI.Net.Examples](https://github.com/TeamControlium/NonGUI.Net.Examples) | NonGUI.net usage examples |
| [Database.net](https://github.com/TeamControlium/Database.net) | Database utilities |

### Status: Not Maintained (```No active development```).

## Legacy — Java

Not maintained. Retained for reference and existing Maven consumers.  Translated from the Legacy .NET framework.  Used by some legacy Test Suites but no longer actively maintained.

| Repo | Purpose |
|---|---|
| [Controlium.java](https://github.com/TeamControlium/Controlium.java) | UI tool support code (Selenium etc.)|
| [Utilities.java](https://github.com/TeamControlium/Utilities.java) | Test automation utilities |
| [HTTPNonUI.java](https://github.com/TeamControlium/HTTPNonUI.java) | Non-UI HTTP endpoint testing utilities |

### Status: Not Maintained (```No active development```).

---

Lead: [Mat Walker](https://www.linkedin.com/in/mathieuwalker)

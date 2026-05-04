# Neil Marshall
### Senior SDET · AI Test Automation Architect · Healthcare & Fintech

> *Building AI-powered test frameworks that scale quality beyond what human hands can write alone.*

---

## 👋 About Me

I'm a Senior SDET and Test Automation Architect with **44 years of engineering experience** across Salesforce, Microsoft, Indeed, Finix, and Ooyala/Dalet — now specializing in **AI-augmented test automation** and **FHIR healthcare API testing**.

My focus is the intersection of two things most engineers know separately but rarely combine:
- **Deep SDET fundamentals** — test architecture, CI/CD ownership, API validation, contract testing
- **Modern AI tooling** — LLM-powered test generation, self-healing detection, AI failure triage

I build frameworks that let small teams maintain enterprise-grade coverage at scale.

📍 San Francisco Bay Area &nbsp;|&nbsp; 🎯 Open to Senior SDET · AI Test Automation Engineer roles

---

## 🚀 Featured Projects

---

### 🤖 [`ai-test-automation-python`](https://github.com/njmarshall/ai-test-automation-python) &nbsp; ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white) ![CI](https://github.com/njmarshall/ai-test-automation-python/actions/workflows/ci.yml/badge.svg)

**AI-powered healthcare FHIR R4 test framework — Python/pytest**

A production-grade Python framework targeting **FHIR R4 healthcare APIs** with two layers of validation — HTTP contract testing *and* FHIR data model conformance.

| Capability | Implementation |
|-----------|---------------|
| 🏥 FHIR R4 API Testing | Patient, Observation, Encounter — full CRUD + search |
| 🤖 AI Test Generation | Anthropic SDK generates pytest tests from resource definitions |
| 🔧 Self-Healing Detection | AST parsing detects test drift before CI failures |
| 📊 Allure Reporting | Published to GitHub Pages on every push |
| ⚙️ CI/CD | GitHub Actions + pytest-xdist parallel execution |
| 🎨 Design Patterns | CRTP, Factory, Singleton, Facade, Fluent Interface, Template Method |

> *Validates not just HTTP status codes, but clinical code systems (LOINC, SNOMED), resource references, and OperationOutcome structure — the layer most API test suites skip entirely.*

---

### ☕ [`ai-test-automation`](https://github.com/njmarshall/ai-test-automation) &nbsp; ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white) ![TestNG](https://img.shields.io/badge/TestNG-FF6C37?style=flat) ![CI](https://github.com/njmarshall/ai-test-automation/actions/workflows/ci.yml/badge.svg)

**AI-powered enterprise test framework — Java/TestNG**

The Java counterpart — an enterprise-grade RestAssured + TestNG framework with LLM integration, OpenAPI-driven test generation, and full CI/CD pipeline.

| Capability | Implementation |
|-----------|---------------|
| 🔥 RestAssured API Testing | Insurance Quote and Healthcare FHIR capstone projects |
| 🤖 LLM Test Generation | OpenAPI spec → TestNG test cases automatically |
| 📊 Allure + GitHub Pages | Live test report published on every build |
| 🏗️ Enterprise Architecture | CRTP, Fluent Interface, Singleton, Factory patterns |
| 🔁 Dual Language Parity | Mirrors the Python framework — same patterns, different stack |

---

### 🐍 [`python-testrail`](https://github.com/njmarshall/python-testrail) &nbsp; ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![CI](https://github.com/njmarshall/python-testrail/actions/workflows/ci.yml/badge.svg)

**TestRail integration for pytest — battle-tested at Finix**

A pytest plugin that automatically pushes test results to TestRail on every run — zero per-test boilerplate. Built from production experience at Finix (fintech payments infrastructure).

- `pytest_runtest_makereport` hook — automatic result capture
- Bulk upload with retry + backoff — no dropped results on flaky networks
- Dynamic test run creation — no hardcoded run IDs
- 16-test mock suite — fully CI-runnable without a live TestRail instance

---

### ☕ [`java-testrail`](https://github.com/njmarshall/java-testrail) &nbsp; ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)

**TestRail integration for TestNG — Java counterpart**

Parallel Java implementation of the TestRail integration — `@TestRailCase` annotation, `ITestListener` bulk upload, and `HttpClient`-based REST wrapper. Completes the polyglot TestRail story alongside `python-testrail`.

---

### 🔄 [`upgrade`](https://github.com/njmarshall/upgrade) &nbsp; ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)

**Modernized Java project — legacy to production-ready**

A 2020 take-home project fully modernized to 2024 standards — demonstrating refactoring discipline, CI/CD setup from scratch, and honest engineering judgment about third-party test targets.

- `ConfigManager` singleton — externalized config, zero hardcoded credentials
- GitHub Actions CI — Lombok, clean compile pipeline
- README documents why live WAF-protected targets have a shelf life

---

## 🛠️ Tech Stack

**Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**Test Frameworks**
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![TestNG](https://img.shields.io/badge/TestNG-FF6C37?style=flat)
![RestAssured](https://img.shields.io/badge/RestAssured-009639?style=flat)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white)

**AI & Automation**
![Anthropic](https://img.shields.io/badge/Anthropic_SDK-191919?style=flat)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)

**CI/CD & Reporting**
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Allure](https://img.shields.io/badge/Allure-FF6C37?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

**Healthcare & APIs**
![FHIR](https://img.shields.io/badge/FHIR_R4-E8143C?style=flat)
![REST](https://img.shields.io/badge/REST_API-009688?style=flat)
![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat&logo=openapiinitiative&logoColor=white)

**Data Engineering**
![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)

---

## 🏆 Career Highlights

- 🏥 **FHIR R4 Test Framework** — End-to-end healthcare API validation with AI-powered test generation targeting the regulatory-mandated standard for US health systems
- 🤖 **Dual-language AI framework** — Same architecture in Python and Java — signals polyglot depth, not just language familiarity
- 🔥 **Spark Summit 2014** — Co-presented *"Testing Spark: Best Practices"* — 1,000-node elastic cluster testing at Ooyala
- 💳 **TestRail at Finix** — Battle-tested payment infrastructure test reporting at a Series C fintech
- 📈 **44 years** across Salesforce · Microsoft · Indeed · Finix · Ooyala/Dalet

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/njmarshall)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/njmarshall)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=njmarshall&show_icons=true&theme=dark&hide_border=true&count_private=true" height="150"/>
  &nbsp;&nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=njmarshall&layout=compact&theme=dark&hide_border=true" height="150"/>
</p>

---

*Open to Senior SDET · AI Test Automation Engineer · Staff QA Engineer opportunities in the Bay Area and remote.*

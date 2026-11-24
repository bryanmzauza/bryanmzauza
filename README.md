<div align="center">

# Bryan Munaretto Zauza

**Chemical Engineer (UFRGS) · Software developer · Porto Alegre, Brazil**

I model chemical processes, work with plant data and build the software around them:
reactor simulations, control-system simulators, industrial data pipelines, business systems and AI tools.

[![GitHub](https://img.shields.io/badge/GitHub-bryanmzauza-181717?logo=github)](https://github.com/bryanmzauza)
![Location](https://img.shields.io/badge/Porto%20Alegre-Brazil-009C3B)

</div>

## Featured

| Project | What it is | Stack |
| --- | --- | --- |
| **[hefa-process-simulation](https://github.com/bryanmzauza/hefa-process-simulation)** | Sustainable Aviation Fuel from macaúba oil by the HEFA route. Two adiabatic PFRs in series (hydrodeoxygenation, then hydrocracking with isomerization), with intermediate separation and recycle. Optimization raises SAF yield from 47% to 66%. Undergraduate thesis | Python · SciPy |
| **[Six-tank control bench](https://github.com/bryanmzauza/ufrgs-lab-controle)** | Multivariable six-tank plant with four level loops. A Modelica model compiled by OpenModelica runs in the browser. Linearized at the operating point, with RGA analysis and SIMC tuning of the PID controllers | Modelica · Python |
| **[Six-tank plant HMI](https://github.com/bryanmzauza/simulador-planta-seis-tanques)** | Supervisory screen built on a live P&ID. Faceplates have AUTO/MAN mode, setpoints and tuning, plus trend charts and test logging. Runs either the simulated plant or the physical one through an Arduino | JavaScript · WebSocket |
| **Industrial ERP** *(private)* | Five integrated apps for a manufacturer: public site, ERP, shop-floor MES, sales rep portal and e-commerce, all served by one central API | NestJS · Next.js · PostgreSQL |
| **[RespondoIA](https://github.com/bryanmzauza/RespondoIA)** | Windows tray app that reads the open WhatsApp chat on screen, masks it, and suggests replies in your own style. You send each message yourself. History is stored encrypted on your computer | Python · LLM |
| **[Tenax Protocol](https://github.com/Tenax-Protocol/Tenax-Protocol)** | On-chain forecasting network on Base. Forecasters are scored by Brier score, liquidity is protocol-owned on Uniswap v4, and the contracts are immutable | Solidity · Foundry |

## Projects

Entries marked *private* are closed-source or client work, listed for reference.

### ⚗️ Chemical engineering & process modeling

- **[hefa-process-simulation](https://github.com/bryanmzauza/hefa-process-simulation)**: HEFA route to SAF (see Featured). Reactor kinetics, sensitivity analysis on temperature, pressure, H₂/oil ratio and LHSV, and multi-objective optimization.
- **HDO reactor conceptual design** *(private)*: trickle-bed hydrodeoxygenation reactor for 100 t/h of macaúba oil (modeled as triolein) to green diesel. Compares the HDO, DCO and DCO₂ routes and includes the kinetics, hydrodynamics, two feed/effluent heat exchangers and a three-phase high-pressure flash separator.
- **[ufrgs-lab-controle](https://github.com/bryanmzauza/ufrgs-lab-controle)**: six-tank bench simulator for the Control Laboratory course (see Featured).
- **[Six-tank plant HMI](https://github.com/bryanmzauza/simulador-planta-seis-tanques)**: supervisory HMI for the same plant, built in an undergraduate research project at UFRGS (see Featured).
- **[Q-Engineering-Hub](https://github.com/bryanmzauza/Q-Engineering-Hub)**: Chemical Engineering toolkit with unit converter, substance properties database, formula sheets and reactor calculators.

### 🏭 Industrial data

- **Energy performance analytics** *(private)*: pipeline that extracts plant energy consumption (GJ/t) from PI AF incrementally with retries, removes outliers by IQR and produces branded monthly PDF reports.
- **Bromine index soft sensor** *(private)*: hourly dataset that pairs process variables (flows, pressures, temperatures) with lab analyses, to estimate a quality variable that the lab measures only a few times.
- **Literature screening** *(private)*: extracts and screens PDF articles exported from Web of Science and AGRICOLA for a systematic review.

### 💻 Software & systems

- **Industrial ERP ecosystem** *(private)*: NestJS modular monolith with Next.js 15 frontends in a Turborepo, PostgreSQL, Redis and BullMQ. It also had an authorized black-box security assessment, followed by hardening.
- **Bakery pricing system** *(private)*: product costing and pricing (React, Express, Prisma, PostgreSQL), deployed with Docker and CI/CD.
- **[RespondoIA](https://github.com/bryanmzauza/RespondoIA)**: reply suggestions for WhatsApp Desktop (see Featured).
- **[craftsapiens-website](https://github.com/bryanmzauza/craftspiens-website)**: site for an educational platform, with login tied to its game server, a store with Pix payments and automatic delivery, a forum and class schedules. Next.js + Prisma.
- **Video factory** *(private)*: a single pipeline for animated explainer videos in PT and EN, from script and fact-check through voice, render and thumbnails.

### 📈 Quant finance & AI

- **[Quant-Trading-Engine](https://github.com/bryanmzauza/Quant-Trading-Engine)**: backtesting with realistic costs, risk-based position sizing, performance analytics, walk-forward and Monte Carlo robustness tests.
- **Alpherion** *(private)*: every hour, an LLM forecasts the direction of the next 1h candle for each covered crypto asset. Strong signals go to Telegram and are checked against the actual candle an hour later. Market and on-chain data are stored in TimescaleDB.
- **Alpherion Finance** *(private)*: portfolio consolidation with B3 import and risk analysis (Next.js 15 + FastAPI).
- **Quant research lab** *(private)*: ML signal research with triple-barrier labels and purged walk-forward splits. Protocols are pre-registered and tested on lockbox data held back until the end.
- **[Tenax Protocol](https://github.com/Tenax-Protocol/Tenax-Protocol)**: on-chain forecasting network (see Featured). *In development.*

### 🎮 Games & Minecraft

- **[Messoria](https://github.com/bryanmzauza/Messoria)**: cooperative farming game in Rust and Bevy.
- **[Sapientia](https://github.com/bryanmzauza/Sapientia)**: technology and automation plugin for Paper (energy networks, logistics, processing chains).
- **[KeyScript-Mod](https://github.com/bryanmzauza/KeyScript-Mod)**: Fabric mod with its own scripting language, editor and debugger.
- **[MarketHub](https://github.com/bryanmzauza/MarketHub)**, **[Region-Master](https://github.com/bryanmzauza/Region-Master)**, **[Better-Clans](https://github.com/bryanmzauza/Better-Clans)**, **[Core-Economy](https://github.com/bryanmzauza/Core-Economy)**, **[QuestKeepers](https://github.com/bryanmzauza/QuestKeepers)**: plugins for a dynamic market, land claims, clans, an economy provider and quests.

## Tech stack

**Engineering & scientific computing**
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![pymoo](https://img.shields.io/badge/pymoo-multi--objective-4B8BBE)
![Modelica](https://img.shields.io/badge/Modelica%20%2F%20OpenModelica-5A5A5A)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white)
![PI AF](https://img.shields.io/badge/PI%20AF-005BAC)
![Arduino](https://img.shields.io/badge/Arduino-00878F?logo=arduino&logoColor=white)

**Machine learning & AI**
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B)
![Claude API](https://img.shields.io/badge/Claude%20API-D97757?logo=anthropic&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI%20API-412991?logo=openai&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?logo=pydantic&logoColor=white)

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?logo=solidity&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white)

**Frontend**
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?logo=shadcnui&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38)
![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?logo=reacthookform&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?logo=framer&logoColor=white)
![PySide6](https://img.shields.io/badge/PySide6%20(Qt)-41CD52?logo=qt&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?logo=zod&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?logo=jsonwebtokens&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-E53935)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?logo=turborepo&logoColor=white)

**Databases & ORMs**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?logo=timescale&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?logo=drizzle&logoColor=black)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?logo=sqlalchemy&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white)

**Infrastructure & observability**
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux%20VPS-FCC624?logo=linux&logoColor=black)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?logo=awslambda&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?logo=minio&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![Uptime Kuma](https://img.shields.io/badge/Uptime_Kuma-5CDD8B?logo=uptimekuma&logoColor=black)

**Testing & code quality**
![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=white)
![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?logo=junit5&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?logo=ruff&logoColor=black)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/Prettier-F7B93E?logo=prettier&logoColor=black)

**Games & blockchain**
![PaperMC](https://img.shields.io/badge/PaperMC-444444)
![Fabric](https://img.shields.io/badge/Fabric-DBD0B4)
![Gradle](https://img.shields.io/badge/Gradle-02303A?logo=gradle&logoColor=white)
![Bevy](https://img.shields.io/badge/Bevy-232326?logo=bevy&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-1C1C1C)
![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?logo=openzeppelin&logoColor=white)
![Uniswap v4](https://img.shields.io/badge/Uniswap_v4-FF007A?logo=uniswap&logoColor=white)

## Contact

GitHub: [@bryanmzauza](https://github.com/bryanmzauza)

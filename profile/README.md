# Welcome to Planmatic.io

**Planmatic.io** is an open-source developer platform designed to accelerate the creation of intelligent, interoperable, and fully customizable media investment management solutions.

We believe that advertising deserves a more open and future-proof foundation—one that puts data, algorithms, and AI at the core while keeping users in control. Our mission is to help developers build the next generation of media tools that empower teams to plan, optimize, and analyze media investments with flexibility, intelligence, and interoperability.

Whether you're modernizing legacy systems, building net-new tools, or simply exploring the possibilities, Planmatic provides an open foundation that supports rapid development and seamless integration.

## What You’ll Find Here

This GitHub organization hosts two core repositories that make up Planmatic's open-source foundation:

### [`mediaplanschema`](https://github.com/laurent-colard-l5i/mediaplanschema)

A modular, extensible **open data standard** for structuring media plans. Built on JSON Schema, it allows for:

- Seamless exchange of media plans between systems
- Compatibility with both human and algorithmic workflows
- Full customization and extensibility for proprietary metrics, dimensions, and taxonomies
- Formula definitions and dependency chains for simulation and forecasting applications

Use it to power your planning tools, reporting systems, optimization engines, or agent-based workflows.

### [`mediaplanpy`](https://github.com/laurent-colard-l5i/mediaplanpy)

A Python-based **open source SDK** for working with media plans that follow the open data standard. It provides:

- Easy creation, editing, and validation of media plans
- Workspace and storage management (local and cloud)
- Import/export to Excel and JSON
- Automated calculations and forecasting using interdependent formulas
- Support for analytics (including integration with PostgreSQL) 
- Schema versioning, and more

Use it to prototype applications, build automated workflows, or integrate media planning with your broader tech stack.

---

## Latest News: V3.0 Release

We are very excited to announce the production release of **mediaplanschema v3.0** and **mediaplanpy v3.0.0**. 

This major release brings significant enhancements to the platform:
- **Enhanced Schema (v3.0)**: New field additions (155 vs 116), custom KPIs at campaign level, full extensibility and 11 new standard metrics
- **Dynamic Formula System**: Metric formulas with multiple calculation types (cost per unit, conversion rate, power function, constant) enabling sophisticated forecasting and dependency chains
- **Restructured Targeting**: Breaking changes to audience and location models—now supporting multiple target_audiences and target_locations per campaign with rich demographic, interest, and geographic attributes
- **Excel Integration Enhancements**: Formula-aware import/export with automatic coefficient calculation and dependency management across formula chains
- **SDK v3.0.0**: Full support for schema v3.0 with automatic v2.0 migration, strict workspace version enforcement, enhanced database schema management, and 47 updated public API methods
- **Examples Library**: Comprehensive examples demonstrating how to use all key functionality of the SDK
- **Revamped CLI**: Enhanced command-line interface for workspace management use cases

---

## Commercial Offerings

In addition to our open-source foundation, Planmatic offers commercial products and services to accelerate your media planning transformation:

### Hosted API Server
Enterprise-grade API infrastructure for media plan management with built-in authentication, multi-tenancy, version control, and scalable cloud deployment. Eliminate operational overhead and integrate media planning capabilities directly into your applications.

### Web UI
Modern, intuitive web application for media plan creation, editing, and collaboration. Features visual planning workflows, real-time formula calculations, scenario modeling, and team collaboration capabilities—all built on the open standard.

### Google Meridian Connector
Pre-built integration enabling seamless data exchange between Google's Marketing Mix Modeling platform and your media plans. Export Meridian MMM outputs into your media plans for scenario testing, sales forecasting and optimization recommendation.

### Optimization Engine
Advanced algorithmic optimization service that leverages media plan formulas and constraints to recommend optimal budget allocations across channels, tactics, and line items. Supports multi-objective optimization with customizable business rules.

### Support Services
Professional services including implementation consulting, integration development, proof of concepts, and dedicated technical support to ensure successful adoption and ongoing platform success.

---

## Why Planmatic?

- **Open by Design**: Avoid vendor lock-in with transparent standards and permissive licensing.
- **Composable & Extensible**: Adapt the tools to your workflows, not the other way around.
- **Multimodal**: Built to support manual, programmatic, algorithmic, and AI-assisted planning.

Whether you're an agency, developer, advertiser or platform provider, we invite you to explore, contribute, and build with us.

---

For more information about how to get started or explore commercial support and accelerators:
- Visit our [website](https://www.planmatic.io)
- Contact us or follow us on [LinkedIn](https://www.linkedin.com/company/planmatic)
- Send us an [email](mailto:contact@planmatic.io)

---
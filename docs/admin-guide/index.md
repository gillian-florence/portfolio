# Administrator Guide — Writing Sample

This is a representative writing sample from my work on Salesforce-based solutions. It demonstrates how I structure administrator-facing documentation for complex, modular systems.

**You can jump directly into the sample here:**

- **[View the MkDocs version](installation.md)**
- **[View the full PDF (production format)](../assets/pdfs/admin-guide.pdf){:target="_blank"}**
- **[Download the PDF](../assets/pdfs/admin-guide.pdf){:download}**

> The PDF reflects how this guide is delivered to customers in production.

---

**What this sample represents**  
An installation and configuration guide for a modular Salesforce solution, where features can be enabled independently based on client needs. Shared setup is documented once, followed by standalone feature sections.

**Audience**  
Salesforce System Administrators and implementation teams responsible for installing, configuring, and maintaining the solution. The content assumes Salesforce admin experience and focuses on system setup and behaviour—not end-user training.

**How the guide is organized**  
Common installation and prerequisites are documented up front. Each feature is then documented independently using a consistent structure:
- Overview
- Metadata (objects, fields, flows, permissions)
- Configuration steps

This supports selective reading and keeps the guide maintainable as features evolve.

**Salesforce alignment**  
The documentation follows Salesforce terminology and administrative conventions and references Salesforce Help where appropriate to support implementation.

**Authoring context**  
The production guide is authored in Microsoft Word and published as a PDF. This site presents the same material in a docs-as-code format to demonstrate how it can be structured, versioned, and maintained using modern documentation workflows.

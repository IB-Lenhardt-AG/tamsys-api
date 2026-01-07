# TAMSys API

The TAMSys API provides programmatic access to IB-Lenhardt’s **Type Approval Management System (TAMSys)**.  
It enables companies to integrate type approval processes into their own systems, automate workflows, and exchange approval-related data securely and efficiently.

TAMSys is designed to manage the growing complexity of global vehicle type approvals and regulatory requirements.

👉 Learn more about TAMSys:  
https://ib-lenhardt.com/solutions/tamsys

---

## What is TAMSys?

TAMSys is a centralized platform for managing **type approval data, regulations, markets, vehicles, variants, and approval statuses** across global markets.

It supports companies in:
- Handling international homologation requirements
- Managing regulatory changes
- Tracking approval statuses per market
- Structuring complex vehicle and variant data
- Reducing manual effort and errors in approval processes

The TAMSys API exposes selected functionality of the system for integration into external tools such as ERP systems, PLM systems, internal dashboards, or automation workflows.

---

## API Purpose

The TAMSys API is intended to:

- Enable **system-to-system integration**
- Support **automation of approval-related processes**
- Provide **secure access** to TAMSys data
- Allow **custom workflows** tailored to company-specific processes

Typical use cases include:
- Synchronizing approval data with internal systems
- Automatically retrieving approval statuses
- Integrating TAMSys into reporting or monitoring tools
- Supporting digital approval workflows

---

## General Capabilities

Depending on configuration and permissions, the API can support access to:

- Type approval data
- Vehicles, variants, and configurations
- Markets and regulatory frameworks
- Approval statuses and lifecycle information
- Related metadata used in approval management

> ⚠️ The exact scope of available endpoints and data depends on the TAMSys installation and user permissions.

---

## Authentication & Security

- The API is designed for **secure access**
- Authentication mechanisms are required (e.g. API tokens or credentials)
- Access is restricted based on user roles and permissions within TAMSys

Never expose credentials in public repositories or client-side applications.

---

## Repository Structure

This repository contains **example implementations** demonstrating how to interact with the TAMSys API.

Typical contents include:
- Sample requests
- Authentication examples
- Basic API usage patterns
- Examples in multiple programming languages

The examples are intended as a **starting point** and may need to be adapted to your specific TAMSys environment.

---

## Supported Languages (Examples)

Examples may be provided for languages such as:
- PHP
- JavaScript / Node.js
- Python
- Other languages depending on contributions

---

## Getting Started

1. Obtain API access credentials from your TAMSys administrator
2. Review the example for your preferred programming language
3. Configure authentication
4. Adapt the request logic to your specific use case

---

## Disclaimer

This repository contains **example code only**.  
It does not represent the full functionality of the TAMSys API and is not a replacement for official documentation or contractual agreements.

For detailed API specifications, supported endpoints, and production usage guidelines, please contact **IB-Lenhardt** directly.

---

## About IB-Lenhardt

IB-Lenhardt AG is a global provider of software solutions and consulting services in the field of vehicle type approval and homologation.

More information:
https://ib-lenhardt.com

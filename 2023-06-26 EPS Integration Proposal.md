---
aliases: 
tags: []
share: true
date created: 2023-06-26
date modified: 2023-06-27
---
- [ ] #task Complete #focus ➕ 2023-06-27

# Preliminary Proposal for DICE Matrix to FieldHub Migration and Integration

## Executive Summary
### Objective:
The deployment of FieldHub with integration to DICE Core and effective depreciation of DICE Matrix. The resulting integration will allow EPS Security to operate with FieldHub for primary customer relationship and organizational accounting functions; and DICE Core for primary central station automation (signal processing and call/dispatch) functions.
### Scope
1. Integration of FieldHub with DICE Core
2. Migration of customer information from DICE to FieldHub
3. Configuration, implementation, training and deployment support of FieldHub and the integrated solution
### Price
TBD

## 1. Introduction

FieldHub is a comprehensive cloud accounting and ERP system for security installers and integrators' business operations. It provides a single system to manage leads and proposals, manage projects and field service operations, track inventory, and automate recurring/deferred revenue management.

It is purpose-built to address the unique needs of our industry with functionality, integrations, and a roadmap specific to our industry.

FieldHub has implemented central station integrations through a "plug-in" framework. The integration with a migration from DICE will be more extensive than our standard integrations. Working closely with EPS Security, we will work to, as best as possible, address the needs and use cases of EPS through core FieldHub functionality and partner integrations as needed.

## 2. Integration Overview
This overview is based on initial estimations and assumptions. It will not be verified until the requirements phase in completed and the capabilities of DICE are verified.

### Data Master Storage
FieldHub will be the authoritative data source for:
- Customer information
- Accounting information (e.g., GL, job costing)
- Inventory management
- Material catalog
- Work Orders (e.g., service, install, test and inspect, internal work orders)

DICE Core will be the authoritative data source for:
- Account information related to systems monitoring once the account has been "shelled out" with information from FieldHub.
- System zone lists
- Call lists; action patterns
- Alarm activity logs

### Integration Points (Web)
FieldHub will integrate DICE Core through the DICE data access gateway. The primary integrations points are:
- User authentication across the two systems via oAuth2
- Create account, site, and systems in DICE from FieldHub; once established the data will not "sync" and would be updated in DICE
- Establish a link from FieldHub "Systems" to the corresponding systems in DICE
- View contact, zones, system activity in DICE from FieldHub; this data will be retrieved from DICE in realtime

### Integration Points (Mobile)
The FieldHub mobile application will allow technicians to:
- View Account, Site, and System information via the mobile application
- View and search for
- Place the system on/off test

### Integration Assumptions
- DICE will provide technical support to FieldHub; if there are any costs with DICE they will be paid directly by the customer
- No data from DICE Core will "sync" to FieldHub. Once information has been created in DICE from FieldHub that account name, site address, etc will not be additionally updated from FieldHub.

## 3. Data Migration

## 3. Project Scope

* **Requirements Analysis:** Gathering and documenting integration requirements
* **Design:** High-level design of the integration solution
* **Implementation:** Customization and configuration of software solutions
* **Testing:** Validation of the integrated solution
* **Deployment:** Rolling out the integrated solution to end users
* **Support:** Ongoing maintenance and support

## 4. Price Estimate

* **Cost Breakdown:**
  * Requirements Analysis and Design: $X
  * Implementation: $Y
  * Testing: $Z
  * Deployment: $A
  * Support: Monthly service fee of $B
* **Total Project Cost:** Estimated at $C (excluding ongoing support)

## 5. Next Steps

* Schedule a meeting to discuss project details
* Finalize requirements and scope
* Develop a detailed project plan and timeline
* Begin implementation upon approval
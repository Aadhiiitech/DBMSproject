# E-Commerce Order Management Database System

## Week 1 Submission

This repository contains:

- Requirement Analysis Report
- Business Requirement Document
- Software Requirement Specification (SRS)
- README File

## Folder Structure

Week1/
│── Requirement_Analysis_Report.pdf
│── Business_Requirement_Document.pdf
│── SRS_Document.pdf
│── README.md


# Week 2 – Entity and Relationship Analysis

## Project Title

**E-Commerce Order Management Database System**

## Overview

This repository contains the Week 2 deliverables for the E-Commerce Order Management Database System project. The objective of this phase is to analyze the data requirements of the system by identifying entities, attributes, keys, relationships, and cardinalities required for database design.

## Objectives

* Identify all entities required by the system.
* Define attributes for each entity.
* Identify Primary Keys (PK) and Foreign Keys (FK).
* Apply database constraints such as NOT NULL, UNIQUE, CHECK, and DEFAULT.
* Analyze relationships between entities.
* Determine relationship cardinalities.
* Prepare the foundation for ER Diagram (ERD) development.

## Entities Identified

1. Customer
2. Category
3. Product
4. Supplier
5. Orders
6. Order_Details
7. Payment
8. Shipment
9. Review

## Relationships

* Customer → Orders (1:M)
* Category → Product (1:M)
* Supplier → Product (1:M)
* Orders → Order_Details (1:M)
* Product → Order_Details (1:M)
* Orders ↔ Product (M:N through Order_Details)
* Orders → Payment (1:1)
* Orders → Shipment (1:1)
* Customer → Review (1:M)
* Product → Review (1:M)

## Files Included

```text
Week2/
│── Entity_Analysis_Report.pdf
│── Entity_Relationship_Analysis.pdf
│── README.md
```

Deliverables
Entity Identification Report

Contains the list of entities required for the system.
 Entity Attribute List

Contains detailed attributes and constraints for each entity.
 Primary Key and Foreign Key Identification

Defines all primary keys and foreign key relationships.
 Relationship Analysis

Describes how entities interact within the system.
 Cardinality Analysis

Specifies One-to-One (1:1), One-to-Many (1:M), and Many-to-Many (M:N) relationships.

 Conclusion
The Entity and Relationship Analysis provides a structured database design for the E-Commerce Order Management Database System. The identified entities, keys, constraints, and relationships serve as the foundation for ER diagram creation and database implementation in the next phase of the project.


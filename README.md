# DBMS-Assignment-4

A beginner-friendly DBMS assignment based on **ER Modeling & Relational Model**. This assignment focuses on studying a local clinic's patient-intake process, designing a digital ER diagram, and converting the ER model into a physical relational model.

## Assignment Overview

The assignment involves designing a database model for a local clinic by identifying entities, attributes, relationships, and cardinalities.

The work is divided into two main parts:

1. **Digital ER Diagram**
2. **Physical Relational Model**

The assignment requires the digital ER diagram to be created using a digital diagramming tool and the relational model to be physically represented using index cards and yarn/string.

## Case Study

### Shanti Care Clinic — Patient Management System

The clinic database model represents the following main entities:

- **PATIENT**
- **DOCTOR**
- **APPOINTMENT**
- **PRESCRIPTION**
- **BILLING**

## Entities and Attributes

### PATIENT

- `patient_id` — Primary Key
- `name`
- `contact_number`
- `age`
- `gender`

### DOCTOR

- `doctor_id` — Primary Key
- `name`
- `specialization`
- `contact_number`

### APPOINTMENT

- `appointment_id` — Primary Key
- `patient_id` — Foreign Key
- `doctor_id` — Foreign Key
- `appointment_date`
- `appointment_time`
- `status`

### PRESCRIPTION

- `prescription_id` — Primary Key
- `appointment_id` — Foreign Key
- `diagnosis`
- `medicine`
- `dosage`

### BILLING

- `bill_id` — Primary Key
- `appointment_id` — Foreign Key
- `amount`
- `payment_status`
- `billing_date`

## Relationships and Cardinality

| Relationship | Cardinality |
|---|---|
| PATIENT — BOOKS — APPOINTMENT | 1 : N |
| DOCTOR — HANDLES — APPOINTMENT | 1 : N |
| APPOINTMENT — HAS — PRESCRIPTION | 1 : 1 |
| APPOINTMENT — GENERATES — BILLING | 1 : 1 |

## Part 1 — Digital ER Diagram

The ER diagram was created digitally using **diagrams.net (draw.io)**.

It represents:

- Entities
- Attributes
- Primary Keys
- Foreign Keys
- Relationships
- Cardinalities

### Digital ER Diagram

**File:** `DBMS_Assignment_4_ER_Diagram_DrawIO.png`

## Part 2 — Physical Relational Model

The ER diagram was converted into a physical relational model using:

- Index cards
- Handwritten table structures
- Yarn/string
- PK and FK labels

One physical card represents each database table. Related primary keys and foreign keys are connected using yarn/string to demonstrate the relationships between tables.

### Tables Represented

- PATIENT
- DOCTOR
- APPOINTMENT
- PRESCRIPTION
- BILLING

### Physical Model File

`DBMS_Assignment_4_Physical_Relational_Model.png`

## Key Notation

- **PK** = Primary Key
- **FK** = Foreign Key

## Tool Used

**diagrams.net (draw.io)**

## Deliverables

The final submission contains:

1. Digital ER Diagram exported as PNG/PDF
2. Photograph/image of the physical relational model using index cards and yarn/string

## Learning Outcomes

Through this assignment, the following concepts are practiced:

- Identifying database entities
- Identifying attributes
- Defining primary and foreign keys
- Understanding relationships between entities
- Understanding cardinality
- Creating an ER diagram
- Converting an ER model into a relational model
- Representing table relationships physically

---

## Author

**Sanika Kangane** 👩‍💻

# Data Model

## Overview

Northstar is a database-first platform.

The website is generated from structured data.

Every location entity has a unique identifier and a defined relationship with its parent and child entities.

---

# Geographic Hierarchy

```
Country
    │
    ▼
State
    │
    ▼
County
    │
    ▼
City
    │
    ▼
ZIP Code
    │
    ▼
Street
    │
    ▼
Address
```

---

# Entity Relationships

Country

- has many States

State

- belongs to Country
- has many Counties

County

- belongs to State
- has many Cities

City

- belongs to County
- has many ZIP Codes

ZIP Code

- belongs to City
- has many Streets

Street

- belongs to ZIP Code
- has many Addresses

Address

- belongs to Street

---

# Design Principles

## Unique Identifier

Every record must have a unique ID.

---

## Normalization

Duplicated data should be avoided.

---

## Referential Integrity

Relationships must be enforced through foreign keys.

---

## Source Tracking

Every record should include:

- source
- source_url
- updated_at

---

## Future Support

The data model should support:

- API
- Website
- AI Search
- Enterprise Dataset
- Bulk Export

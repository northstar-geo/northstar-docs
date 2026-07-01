# Information Architecture

## Purpose

This document defines the overall information architecture of the Northstar platform.

The website is generated from structured geographic data.

---

# Site Hierarchy

Home

↓

Country

↓

State

↓

County

↓

City

↓

ZIP Code

↓

Street

↓

Address

---

# Primary Navigation

- Home
- Browse
- Search
- API
- Documentation
- About

---

# URL Structure

/

/

/country/{country}

/state/{state}

/county/{county}

/city/{city}

/zip/{zipcode}

/street/{street}

/address/{id}

---

# Search

Users should be able to search by:

- ZIP Code
- City
- State
- Street
- Address

---

# Future Sections

- API Documentation
- Dataset Download
- Blog
- Changelog
- Status Page

---

# SEO Principles

Every location page must:

- Have one canonical URL.
- Have structured metadata.
- Have breadcrumb navigation.
- Support JSON-LD.
- Be generated from the database.

# Truniverse — AI Hotel Discovery Prototype

Truniverse is a frontend prototype exploring how structured, transparent, and AI-readable hotel data can improve hotel discovery.

The concept is a hotel knowledge layer that allows AI systems to retrieve and reason over factual hotel information instead of relying solely on conventional OTA filters and rankings.

## Features

* Hotel search with client-side filters
* Structured hotel data in JSON
* Verified information and transparent costs
* Hotel detail pages with neighborhood and transport context
* Direct booking links to hotel websites
* AI-readable attributes such as vibe, amenities, accessibility, and hotel type

## Tech Stack

* HTML5
* CSS3
* Vanilla JavaScript
* JSON

## Current Scope

This is a static proof of concept. It currently has:

* Frontend UI
* Client-side filtering
* Structured hotel data

Not yet implemented:

* Backend/API
* Live hotel data
* AI/RAG pipeline
* Automated verification
* Booking infrastructure

## Run Locally

Open `index.html` in a browser.

Navigation:

```text
index.html → search.html → hotel.html
```

## Data

Hotel information is stored in:

```text
data/hotels.json
```

The schema is designed to support future natural-language search and AI-based hotel recommendations.

## Future Direction

* Backend and database
* Natural-language hotel search
* RAG-based retrieval
* Automated data verification
* Hotel onboarding
* Production deployment

**Author:** Nia Racheva
**Status:** Prototype / Proof of Concept


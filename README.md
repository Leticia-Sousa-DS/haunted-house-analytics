# 👻 Haunted House Analytics

### What makes a house haunted?

## 1. Project Overview

Haunted House Analytics is a Data Science project
focused on investigating haunted houses in horror
narratives.

The project aims to identify recurring characteristics
of haunted properties, explore relationships between
narrative elements, and investigate how these elements
relate to audience reception.

## 2. Research Objective

To identify, organize and analyze the characteristics
of haunted houses represented in horror narratives.

## 3. Research Questions

- What architectural characteristics are most common?
- Which historical events are associated with hauntings?
- What types of supernatural phenomena are most frequent?
- Which entities are commonly associated with haunted properties?
- Are there recurring combinations of narrative elements?
- Are certain characteristics associated with higher
  audience ratings or popularity?

## 4. Initial Research Scope

The unit of analysis is the haunted property
represented in a narrative.

The initial investigation will focus on horror films
featuring haunted houses or other haunted residential
properties.

## 5. Methodology

1. Research design
2. Data collection
3. Data cleaning and preprocessing
4. Exploratory Data Analysis
5. Statistical analysis
6. Pattern identification
7. Conclusions and limitations

## 6. Initial Data Model

| Category | Attributes |
|---|---|
| Identification | work_title, release_year |
| Property | property_type, architectural_style |
| Location | location_type, isolation_level |
| History | historical_event, previous_occupants |
| Supernatural | entity_type, paranormal_activity |
| Narrative | haunting_origin, resolution |
| Reception | audience_rating, popularity |

### Data Considerations

- One record represents one haunted property.
- A narrative may contain multiple haunted properties.
- Multiple values may be assigned to categorical attributes.
- Unknown or unavailable information must not be
  automatically interpreted as absence.
- Subjective classifications must follow documented
  criteria.

# Waltz

- Dave Watkins 
- Director at Deutsche Bank

----

# Topics

- Overview
- History
- Features and Uses 
- Future
- Getting started
- Contributing

----

# What is Waltz

> An open approach to enterprise architecture

- Helps organizations work with large technical estates
- Waltz captures:
    - how the apps fit together, what they do, who for
    - how the org is changing 
    - regs and compliance tracking
- Promote open access to enterprise information
    - widely used across diverse set of users
    - Deutsche Bank has > 15,000 active users
    - 2,500K+ user driven changes per month
    
----

# History

- Approx. 6 yrs old (started as pure OSS)
- Wanted to move away from enterprise info scattered across Powerpoint/Sharepoint/Excel
- 3-4 devs + 1 analyst
- Transitioned to FINOS earlier this year
- In production for 5 yrs @ Deutsche Bank

----

# Features and Uses 

- Apps and their capabilities
- Data flows and right-sourcing data types
- Surveys
- Governance and Regulatory compliance

---- 

# Apps and their capabilities

- "Bring your own" taxonomies to describe applications
    - Functional, Service, Process, Regulatory etc.
- Involved people
- Related technology (h/w and s/w)
- Custom assessments 
- Commissions and decommissions  
- Aggregation by taxonomy item, person, org-unit, custom groups etc.

----

# Data flows and right-sourcing data types

- Flows between systems entered manually or via loaders
- Flows can be enriched with metadata
    - data types
    - data definitions
- Apps can be declared as authoritative sources for data types
    - Gives 'right-sourcing' ratings
- Diagram editor for helping with lineage docs

----

# Surveys

- User defined surveys
- Issued on demand or in bulk according to parameters
- Dynamic question inclusion
    - based on app characteristics or prior answers 
- Basic workflow support

----

# Governance and Regulatory compliance

- Waltz used to track
    - Legal holds, Records management
    - GDPR, BCBS
    - Architecture governance
    - SLDC compliance
- Mixture of custom assessments and taxonomies

----

# Future

- Documenting and tracking microservices
- Offering api services
- Automated data capture
- Increased workflow support 
- Migration support
 
----

# Getting started

- Try it out with a Docker image containing demo data 
- Simple installation process if installing in a container
    - Uses liquibase to initialise schema
    - Sample data generators available
- Supports MSSQL / Postgres / MariaDB
- Blog has links to articles and screencasts

----

# Contributing 

- Contributions welcome!
- https://github.com/finos/waltz 
- Communication primarily through GH Issues and design docs
  - Look for issues tagged `Good first issue` 
- Started developer screencasts on key topics
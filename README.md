# Lab Operation Service Catalogues - FEIT

This repository supports the creation and maintenance of service catalogues for the Laboratory and Technical Services team in FEIT.

## Live Site

The service catalogue site is published via GitHub Pages: https://enterprise-services-group.github.io/FEIT---Lab-Operation-Service-Catalogues/site/feit-lab-tech-services-catalogue.html

Pages:
- [Core services](https://enterprise-services-group.github.io/FEIT---Lab-Operation-Service-Catalogues/site/feit-lab-tech-services-catalogue.html)
- [Specialist services](https://enterprise-services-group.github.io/FEIT---Lab-Operation-Service-Catalogues/site/specialist-services.html)
- [How we work](https://enterprise-services-group.github.io/FEIT---Lab-Operation-Service-Catalogues/site/delivery-framework.html)
- [Who we are](https://enterprise-services-group.github.io/FEIT---Lab-Operation-Service-Catalogues/site/who-we-are.html)

## Purpose

The catalogue provides a clear, maintainable source of truth for:

- Services offered by Laboratory and Technical Services
- Service owners and contact points
- Scope, eligibility, and expected outcomes
- Request process and lead times
- Operating hours and service constraints
- Dependencies, SLAs, and review cadence

## Repository Structure

- `catalogues/services/` - Service entries in YAML
- `templates/` - Reusable templates for new service entries
- `docs/` - Governance and process documentation
- `site/` - Static HTML pages published via GitHub Pages (see Live Site above)

## Quick Start

1. Copy `templates/service-template.yaml`.
2. Create a new file in `catalogues/services/` using kebab-case naming.
3. Fill all required fields.
4. Raise a pull request for review.

## Naming Convention

- Files: `service-name.yaml`
- Service ID: `LTS-XXX` (example: `LTS-001`)

## Initial Scope

This initial phase focuses on documenting core Laboratory and Technical Services used by FEIT staff and teaching spaces.

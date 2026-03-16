# feedback-templates

This repo contains the role-specific question templates used in the Giant Swarm peer feedback process.

## How it works

Questions are loaded dynamically into the feedback form based on the role selected by the respondent:

- **Form**: https://docs.google.com/forms/d/e/1FAIpQLScSiEB1B0KU4D0CU75H24RSzNxl-I8i931P8i0OzX68H5fMvg
- **AppScript automation**: set up via [giantswarm/gapps-automation](https://github.com/giantswarm/gapps-automation)

## Structure

```
roles.json                # Maps role display names to question file identifiers
questions/
  generic.md              # Shown to all roles
  ae.md                   # Account Engineer
  area_po_architect.md    # Area PO / Architect
  gp_founders.md          # GP / Founders
  marketing.md            # Marketing
  non-tech.md             # Non-tech
  pe.md                   # Platform Engineer
  po.md                   # Product Owner
  se.md                   # Solution Engineer
  sales.md                # Sales
  sre.md                  # Site Reliability Engineer
  tf.md                   # Team Facilitator
```

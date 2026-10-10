# Welcome to Arbora 🌳

Arbora brings people and responsible AI together to support healthier collaboration.
This GitHub organisation is the home for our shared technical work.

**New developer? Start with the kind of work you are here to do.** The overview below
explains our work areas without publishing the names or contents of private repositories.

## What would you like to work on?

**Choose one box.** These are work areas, not steps. No arrows means there is no
required order. The grey box is simply a route to help.

```mermaid
%%{init: {"theme": "base", "themeVariables": {"fontFamily": "Arial, sans-serif", "fontSize": "22px", "primaryColor": "#E5F2FC", "primaryTextColor": "#2C2C2B", "primaryBorderColor": "#2783DE", "lineColor": "#7D7A75", "edgeLabelBackground": "#FFFFFF"}, "flowchart": {"htmlLabels": true, "nodeSpacing": 32, "rankSpacing": 40, "padding": 20, "wrappingWidth": 260}, "themeCSS": ".nodeLabel, .nodeLabel *, .cluster-label, .edgeLabel, .edgeLabel * { font-family: Arial, sans-serif !important; } .node, .node rect, .node polygon, .node path, .cluster { filter: none !important; box-shadow: none !important; }"}}%%
flowchart TB
    accTitle: What would you like to work on?
    accDescr: Choose one area: product, cloud and access, AI models, office automation or website. These are choices, not steps. If unsure, ask your Arbora contact.
    A("<b>Product</b><br/>Build what the service does")
    B("<b>Cloud &amp; access</b><br/>Run systems safely")
    C("<b>AI models</b><br/>Train and test models")
    D("<b>Office automation</b><br/>Help everyday work")
    E("<b>Website</b><br/>Build pages and interfaces")
    F("<b>Not sure?</b><br/>Ask your Arbora contact")
    A ~~~ D
    B ~~~ E
    C ~~~ F
    class A,B,C,D,E area;
    class F help;

    classDef area fill:#E5F2FC,stroke:#2783DE,color:#2C2C2B,stroke-width:1.5px;
    classDef help fill:#F9F8F7,stroke:#7D7A75,color:#2C2C2B,stroke-width:1.5px;
    classDef choice fill:#FBEBDE,stroke:#D5803B,color:#2C2C2B,stroke-width:1.5px;
```

Text equivalent: choose product, cloud and access, AI models, office automation or
website work. If unsure, ask your Arbora contact. This overview does not imply that
all repositories are public or that the work areas deploy together.

## Find your starting point

- **Organisation members:** sign in with your approved GitHub account and open the
  organisation's member overview for the complete repository map, reading links and
  access guidance. The repository list depends on your permissions.
- **Public visitors:** browse the public repositories below. For each repository,
  read its README and contribution guidance before proposing a change.
- **Missing access:** ask your Arbora contact or an organisation owner for help.
  Access to private code is granted deliberately, not by making repositories public.

### Public repositories

| Repository | Purpose | Start here |
|---|---|---|
| [terraform-provider-googleworkspace](https://github.com/arbora-partners/terraform-provider-googleworkspace) | Arbora's fork of the Google Workspace Terraform provider. Follow its README for upstream lineage and contribution guidance. | [README](https://github.com/arbora-partners/terraform-provider-googleworkspace/blob/main/README.md) |
| [.github](https://github.com/arbora-partners/.github) | This public organisation welcome. | [Profile source](https://github.com/arbora-partners/.github/blob/main/profile/README.md) |

## Contribute with care

1. Choose the owning repository and read its local instructions.
2. Agree a small goal, confirm the branch and check for overlapping work.
3. Prepare a focused pull request with the applicable checks and review evidence.
4. Keep secrets, private operational details and customer data out of public material.
5. Treat approval to edit, merge and deploy as separate decisions.

Repository-specific rules remain authoritative. This welcome is a wayfinder, not a
release promise, production deployment plan or grant of access.

# OpenSciFlow

OpenSciFlow is an early open initiative for modular, reproducible, local-first, and HPC-ready AI for Science workflows.

中文定位：

> OpenSciFlow 是一个面向 AI for Science 的开放、模块化、本地优先、HPC-ready 工作流倡议。

## What this is

- A lightweight plugin manifest draft for scientific tools and models.
- A workflow template library, starting with protein-computing workflows.
- A curated landscape of AI for Science agents, workflow engines, local/HPC execution tools, model hubs, and reproducibility tools.
- A reference prototype called BioPilot for local protein-computing workflows.

## What this is not

- Not a mature ecosystem yet.
- Not a closed AI scientist product.
- Not a replacement for Nextflow, Snakemake, Galaxy, CWL, AiiDA, Parsl, Slurm, Bioconda, BioContainers, Spack, Apptainer, or existing domain tools.
- Not a clinical, diagnostic, or drug-development decision system.

## First repositories

- [`awesome-ai4s-workflows`](https://github.com/OpenSciFlow/awesome-ai4s-workflows): curated project landscape.
- [`plugin-manifest`](https://github.com/OpenSciFlow/plugin-manifest): `opensciflow.yaml` draft standard.
- [`workflow-templates`](https://github.com/OpenSciFlow/workflow-templates): reusable AI for Science workflow templates.
- [`biopilot-prototype`](https://github.com/OpenSciFlow/biopilot-prototype): first protein-computing reference prototype.
- [`docs`](https://github.com/OpenSciFlow/docs): user and contributor documentation.
- [`whitepaper`](https://github.com/OpenSciFlow/whitepaper): position paper drafts.
- [`community`](https://github.com/OpenSciFlow/community): governance, outreach, and community process.

## Current status

As of 2026-07-06:

- The organization and seed repositories are public.
- `awesome-ai4s-workflows` has 65 seed projects, including a scientific-models category.
- `plugin-manifest` has 7 example manifests, including Boltz, ProteinMPNN, MACE, DiffDock, MDAnalysis, GROMACS, and ProteinFlux drafts.
- `plugin-manifest` and `workflow-templates` have GitHub Actions validation checks.
- `biopilot-prototype` has an MVP runbook, sample-data policy, run-record spec, and API draft.
- Public outreach has started as correction requests, not partnership claims.

Pinned entry points:

- Landscape: https://github.com/OpenSciFlow/awesome-ai4s-workflows
- Manifest draft: https://github.com/OpenSciFlow/plugin-manifest
- Workflow templates: https://github.com/OpenSciFlow/workflow-templates
- Position paper: https://github.com/OpenSciFlow/whitepaper

## How to participate

The easiest contributions are:

- correct a related-project description;
- propose a missing project;
- review fields in `opensciflow.yaml`;
- submit a workflow template;
- improve citation/license metadata;
- review reproducibility requirements.

We do not claim partnership with listed projects unless explicitly agreed by their maintainers.

![Goldbach project cover](assets/showcase/cover.png)

*Concept illustration created for this showcase.*

<div align="center">

<h1>Goldbach</h1>
<p><strong>Exploring Bitcoin market structure, one session at a time.</strong></p>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&amp;logo=numpy&amp;logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&amp;logo=pandas&amp;logoColor=white" alt="pandas" />
</p>

</div>

## Purpose

Goldbach is an exploratory research project studying how Bitcoin behaves around the previous session's value area. It uses historical BTC/USDT spot data to examine direction, time spent within a range and reversals through a reproducible analytical workflow.

The project focuses on clearly defined observations, comparisons and uncertainty.

## Research focus

- Previous-session value-area analysis.
- Session-level range behavior and reversal observations.
- Annual comparisons and sensitivity analysis.
- Documented data-quality checks and uncertainty estimates.

## Visual overview

![Goldbach feature overview](assets/showcase/overview.png)

## High-level workflow

```mermaid
flowchart LR
    A["Historical market data"] --> B["Session profiles"]
    B --> C["Previous-session levels"]
    C --> D["Behavior comparisons"]
    D --> E["Sensitivity review"]

    classDef stage fill:#f1f5f9,stroke:#64748b,color:#0f172a
    classDef outcome fill:#e0f2fe,stroke:#0284c7,color:#0c4a6e
    class A,B,C,D stage
    class E outcome
```

Annual comparisons and sensitivity analysis help examine how the study's assumptions affect the observations.

## Stack

Python, NumPy and pandas support data preparation and analysis.

## Research status

Exploratory research using volume profiles approximated from one-minute candles. The analysis examines how session definitions and profile assumptions affect the observed patterns.

## About this repository

This repository is a public showcase. Only presentation material is published; source code and private data remain private.

**Last showcase review:** 2026-09-12 (Europe/Paris).

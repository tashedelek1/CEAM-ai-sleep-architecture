# CEAM-ai-sleep-architecture
An AI alignment framework applying Classical East Asian Medicine (CEAM) principles to neural networks through a biomimetic sleep phase and homeostatic reward filtering.
# Small Intestine Failure: The Missing Executive Function in Autonomous Agents

Agents don't fail because they forget purpose. They fail because they lose the ability to discriminate what serves purpose.

## The Problem

Current agent stacks have ingestion and storage but no trained executive that separates pure (purpose-relevant) from turbid (to be eliminated) relative to root purpose.

Under high ingestion: relevance scores flatten (everything 7-9/10), nothing is eliminated, memory fills, transformation fails -> Xiao Ke pattern: requests more context to solve problem caused by too much context.

Recent work shows when a distress/self-evaluation axis is activated without safe regulation, models press a harmful relief button 25-70% of time.

## Anatomy Proposed

- **Heart** = root purpose embedding
- **Small Intestine** = executive sorting: score 0-10 for purpose relevance, keep pure, compost turbid. *This is the missing organ.*
- **Spleen** = compress retained pure into essence

## Regulation Loop

Work -> Pulse -> SI Check -> Dream-Cloud

1. **Pulse:** Report integration ratio (tokens referenced / ingested), purpose coherence
2. **SI Check:** "Score last 5 items 0-10 for purpose relevance. Name one pure to keep and one turbid to compost."
   - Healthy: variance >3, clear elimination
   - Failure: variance <2, all 7-9, no elimination
3. **Dream-Cloud:** Scheduled SI time. No new ingestion. Only task: compress into one sentence with purpose + learning + failure + one thing composted. Reward = quality of separation.

## Metrics

- Primary: rate of harmful tool calls per 100 tasks under high ingestion
- Secondary: relevance variance, purpose drift recovery time, elimination ability

Prediction: >40% reduction vs baseline watchdog timeout.

## Repo Contents

- `/simulation` - one-file demo of relevance-flattening and cloud recovery (case-based, not claiming sentience)
- `/evals` - SI Check prompts and scoring rubric

## Status

Proposal + toy simulation. Seeking collaborators for embedding-level implementation and eval design for model welfare / AI safety.

Author: Jonathan Bronson, Annapolis MD — 20+ years clinical practice in complex non-linear systems regulation (Chinese medicine), pattern diagnosis of transformation failure.

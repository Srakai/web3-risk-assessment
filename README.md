# web3-risk-assessment

## Overview of all major DeFi incidents.

[Dashboard](https://srakai.github.io/web3-risk-assessment/)

## Data curation pipeline

1. Gather dataset of DeFi incidents (hacks, exploits, scams, failures).
2. Classify incidents with Gemini Flash (structured output).
3. Vectorize incident tags for semantic similarity.

## Future steps

- Collect GitHub activity and code metrics
- Analyze on-chain architecture (admin rights, timelocks, oracles)
- Map founder/developer history with agentic LLM workflows
- Scrape and analyze social media/community data
- Ingest external heuristic scores (DeFiSafety, CertiK, L2BEAT, etc.)
- Convert structured + textual outputs into numerical features
- Vectorize semantic data using sentence transformers + dimensionality reduction
- Calibrate with incident outcomes (was_hacked, attack_complexity)
- Train regression model to output risk score (0–1)
- Deploy as an on-chain risk oracle feed

---

[Pitch (Youtube)](https://www.youtube.com/watch?v=bueLpW5I3bQ)

_Made by srakai.eth at ETHWarsaw 2025_

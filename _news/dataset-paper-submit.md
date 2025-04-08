---
layout: post
title: Second PhD Paper Submitted to SIGIR 2025
date: 2025-02-18 12:00:00-0400
inline: false
related_posts: false
---

Submitted my second paper during my PhD as a resource paper to the prestigious [48th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2025)](https://sigir2025.dei.unipd.it/). The paper titled "CyberLLMInstruct: A New Dataset for Analysing Safety of Fine-Tuned LLMs Using Cyber Security Data" presents our work on developing and analysing a specialised dataset for evaluating AI safety in the context of cyber security.

You can read the draft paper here: [CyberLLMInstruct Paper (PDF)](/assets/pdf/CyberLLMInstruct.pdf)

**Update (April 4, 2025)**: Unfortunately, the paper was not accepted. The reviewers highlighted that while the work presents valuable contributions to cyber security and LLM safety, its relevance to core IR tasks was limited. Two detailed reviews provided constructive feedback about improving the analysis of data preparation steps and their impact. Interestingly, one review appeared to be for a completely different paper about customs fraud detection. We plan to revise the paper considering the valuable feedback received and potentially submit to a more security-focused venue.

### Reviews

#### Review 1
**Vote**: Reject  
**Strengths**:
- New dataset published openly with full code
- Demonstrated improvements on CyberMetric benchmark
- Insights about performance vs security resilience trade-off

**Weaknesses**:
- Insufficient discussion on benchmark performance improvements
- Impact of data sources and preparation steps not analyzed in isolation
- Unclear if performance degradation is dataset-specific or general fine-tuning effect
- Verbose presentation

#### Review 2
*Note: This review was for a different paper about customs fraud detection and was submitted in error.*

#### Review 3
**Vote**: Reject  
**Strengths**:
- Addresses growing concerns of LLM safety in cybersecurity
- Methodical approach using OWASP Top 10 framework with automated red-teaming

**Weaknesses**:
- Limited connection to core IR tasks
- Insufficient quantitative breakdown of vulnerability types
- Dataset balance across different vulnerability categories not well analyzed


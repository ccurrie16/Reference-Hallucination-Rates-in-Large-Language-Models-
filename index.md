---
layout: home
title: Reference Hallucination Rates in Large Language Models
---

## Overview

This project investigates reference hallucination rates across three leading LLMs:
**GPT-4**, **Claude**, and **Gemini**, by prompting each model to write short paragraphs 
on a range of topics and provide a set number of citations. Every citation is then verified 
against an academic database to determine whether it is real or fabricated.

## Research Questions

- Which LLM produces the highest rate of hallucinated references?
- Does hallucination rate vary by topic area?
- Does requesting more citations increase the hallucination rate?

## Methods

Each model is given a standardized prompt asking for a short paragraph on a given topic 
along with a specified number of academic citations. Citations are verified using an 
academic database. Results are recorded and compared across models, topics, and citation counts.

# Optimized-BERTopic-Framework-Topic-Identification-Results
This repository provides the topic identification results generated in the study:  “An Optimized BERTopic Modeling Framework for Emerging Technology Identification”
The dataset contains the final technology topics identified through a two-stage modeling framework that integrates:

Main Model 

Sub-Model 
The goal of this release is to improve methodological transparency, reproducibility, and semantic interpretability of BERTopic-based emerging technology analysis.

📌 What This File Contains

File: bertopic_emerging_tech_topics_main_sub_annotated.csv

Each row represents a technology topic identified from patent texts.

The topics come from two sources:

Model Source	Meaning
Main Model Topics	High-density, dominant technology themes
Sub-Model Topics	Marginal, weak-signal, or emerging technology themes

Both types are integrated into a unified topic system, but are distinctly indexed.


| Column Name                  | Description                                                                                                                        |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| **topic_combined**           | Final topic ID after integrating Main Model and Sub-Model results. Topics are numbered in a way that preserves source distinction. |
| **Patent_IDs**               | List of patent identifiers assigned to this topic.                                                                                 |
| **Count**                    | Number of patents contained in this topic. Reflects topic scale.                                                                   |
| **Name**                     | Final topic name refined using a Large Language Model (LLM) for semantic clarity and technical precision.                          |
| **Representation_Words**     | Topic keywords after **custom semantic re-ranking**, improving interpretability beyond default BERTopic output.                    |
| **Representation_Documents** | Representative patent text segments used to characterize the semantic core of the topic.                                           |



How to Use This Data

This dataset can be used for:

Emerging technology trend analysis

Topic evolution tracking

Weak-signal technology detection

Innovation policy analysis

Semantic network construction

Patent intelligence studies

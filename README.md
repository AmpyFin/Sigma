# Sigma-Model

> **Open Source Side (OSS)**  
> This is the open source implementation of the Sigma System, designed to mirror the functionality of the proprietary version while providing greater customization and transparency. This OSS version allows users to modify, extend, and adapt the model according to their specific needs.

## Overview

The Sigma System represents a revolutionary approach to risk-centric portfolio optimization, leveraging advanced Large Language Models to analyze institutional investment patterns and identify emerging market consensus. This model meticulously tracks portfolio holdings of major investment firms, recognizing meaningful position changes and identifying strategic shifts that often precede major market moves.

## Key Features

- **LLM-Powered Analysis**: Utilizes a sophisticated pipeline of Large Language Models for comprehensive portfolio analysis
- **Multi-Tier LLM Architecture**: Combines cost-effective models (4.1 mini and nano) for initial summarization with advanced models (o3) for quantitative analysis
- **Performance-Based Ranking**: Ranks investment companies based on their recent performance, with better-performing companies receiving higher influence in decision-making
- **13F Filing Analysis**: Continuously monitors 13F filings and disclosure documents to detect institutional sentiment shifts
- **Sector Rotation Detection**: Identifies early signs of sector rotation and strategic portfolio adjustments
- **Risk-Centric Optimization**: Focuses on risk management through institutional consensus tracking

## System Architecture

The Sigma System employs a sophisticated LLM pipeline architecture:

1. **Initial Processing**: Weaker, cost-effective LLM models (4.1 mini and nano) summarize 300-word documents into concise 20-word headlines
2. **Quantitative Analysis**: More advanced and expensive o3 models process these summaries to track buy/sell decisions and position sizes for each tracked investment company
3. **Performance Ranking**: Investment companies are ranked based on recent performance, with higher-performing companies receiving greater influence in final decisions
4. **Ensemble Decision Making**: The system combines insights from all tracked companies, weighted by their performance rankings

## Core Technology

- **Primary Function**: Investment Company Portfolio Ranking
- **Technology Stack**: Large Language Models
- **Data Sources**: 13F filings, disclosure documents, institutional portfolio data
- **Analysis Method**: Ensemble learning with performance-weighted coefficients

## Purpose

The goal of the Sigma System is to move beyond traditional approaches:
- Instead of relying on single analyst recommendations
- Instead of following individual fund manager strategies
- Instead of using basic technical indicators alone

The model leverages the collective intelligence of major investment firms, continuously evaluating and ranking their performance to optimize portfolio decisions. Higher-ranked companies with better performance receive higher coefficients, meaning they have more influence in the Sigma System's final decision-making process.

## Key Capabilities

- **Institutional Sentiment Tracking**: Monitors changes in institutional holdings and sentiment
- **Early Signal Detection**: Identifies strategic shifts before they become widely recognized
- **Performance-Based Weighting**: Dynamically adjusts influence based on recent performance
- **Risk Management**: Focuses on consensus-building and risk mitigation through institutional alignment
- **Transparency**: Open source implementation allows for customization and verification

The Sigma System has demonstrated exceptional ability to distinguish between routine portfolio adjustments and strategic shifts with conviction, making it an invaluable tool for institutional-grade portfolio optimization.

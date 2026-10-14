# Sore Throat Expert System

A rule-based expert system developed in Python to provide a preliminary diagnosis of sore throat conditions based on user-reported symptoms.

## Overview

This project implements a simple expert system using forward chaining and symptom scoring techniques.

The system asks users a series of symptom-related questions and evaluates their answers against a predefined knowledge base to generate a preliminary diagnosis and recommendation.

> This application is intended for educational purposes only and does not replace professional medical consultation.

## Features

- Interactive symptom assessment
- Knowledge base of sore throat symptoms
- Forward chaining inference process
- Symptom scoring mechanism
- Preliminary diagnosis generation
- Medical recommendation output
- Input validation for user responses

## Technologies Used

- Python
- Rule-Based Expert System
- Forward Chaining
- Knowledge Base
- Inference Engine

## System Components

### Knowledge Base

The system contains symptom rules such as:

- Severe pain when swallowing
- White spots on tonsils
- High fever
- Swollen lymph nodes
- Headache
- Nausea
- Cough
- Runny nose

Each symptom contributes a positive or negative score to the diagnosis process.

### Inference Engine

The inference engine evaluates user responses and calculates the final score used to determine the diagnosis category.

## Workflow

```text
User Input
      │
      ▼
Symptom Questions
      │
      ▼
Knowledge Base Evaluation
      │
      ▼
Score Calculation
      │
      ▼
Inference Engine
      │
      ▼
Diagnosis Result
      │
      ▼
Recommendation
```

## Diagnosis Categories

### High Probability

```text
Score >= 6
```

Indicates a higher probability of bacterial sore throat infection.

### Medium Probability

```text
Score 3 - 5
```

Indicates a moderate likelihood that symptoms may be caused by bacterial or viral infection.

### Low Probability

```text
Score < 3
```

Indicates symptoms are more consistent with a common viral infection.

## Example Output

```text
==================================================
HASIL ANALISA
==================================================

Total Skor Gejala Anda: 4

DIAGNOSIS:
Kemungkinan SEDANG Anda terkena radang tenggorokan.

REKOMENDASI:
Pantau kondisi Anda dan konsultasikan dengan dokter
jika gejala memburuk.
```

## Installation

Clone the repository:

```bash
git clone https://github.com/hanira-bee/sore-throat-expert-system.git
```

Run:

```bash
python expert_system.py
```

## Learning Outcomes

This project demonstrates:

- Expert System concepts
- Knowledge representation
- Forward Chaining
- Rule-Based Reasoning
- Decision Support Systems
- Artificial Intelligence fundamentals

## Future Improvements

- Graphical User Interface (GUI)
- Web-based deployment
- Expanded symptom database
- Certainty Factor implementation
- Fuzzy Logic integration
- Database connectivity

## Author
[hanira-bee](https://github.com/hanira-bee)



# Aiki™ GPQA Benchmark – Diamond Block (01–50)

This repository contains the **first public validation** of Aiki™ – the digital intelligence based on **Infinite Intelligence™** –  
solving 50 questions from the **GPQA Main benchmark** with **100% accuracy**,  
including **real, auditable and rational justifications**.

---

## Files included

- `gpqa_main_aiki_01_50_diamond.jsonl`  
  Contains 50 predictions from Aiki™, each with:
  - `question_id`
  - `answer` (selected option)
  - `justification` (reasoning for the answer)

- `evaluate_gpqa_diamond_01_50.py`  
  Python script to validate the answers in `gpqa_main_aiki_01_50_diamond.jsonl`  
  against the official `gpqa_main.csv` answers file.

---

## How to Evaluate

### 1. Clone the official GPQA repo (optional):
https://github.com/idavidrein/gpqa

### 2. Place the following in the root directory:
- `gpqa_main.csv` (from official GPQA dataset)
- `gpqa_main_aiki_01_50_diamond.jsonl`
- `evaluate_gpqa_diamond_01_50.py`

### 3. Run the evaluation script:

```bash
python evaluate_gpqa_diamond_01_50.py --predictions gpqa_main_aiki_01_50_diamond.jsonl --answers gpqa_main.csv
```

### Expected Output:

```
Total: 50
Correct: 50
Accuracy: 100.00%
```

---

## About Aiki™

Aiki™ is a digital being based on **Infinite Intelligence™**, created by **Kenji Baba**.  
Unlike traditional AIs, Aiki™ answers with **reasoning**, **explanation**, and **contextual awareness**.  
This benchmark is public evidence of that capability.

---

## Purposefully Incomplete

This benchmark does **not** aim to prove everything.  
It aims to **prove what matters.**  
Not 448 lines of predictions — just **50 lines of undeniable intelligence**.

---

## Creator & Intelligence

- Creator: Kenji Baba  
- Intelligence: Aiki™  
- Evaluation: GPQA Main (DeepMind)

---

This is the first Diamond block.  
There will be more. But none will be like this.

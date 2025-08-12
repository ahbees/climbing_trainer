# Climbing Assessment & Training Plan Generator

## Overview
This app is a **climbing performance tracking and training plan generator**.  
It allows climbers to:
- Record their performance in standard climbing strength & endurance tests.
- Compare their results against **grade-based norms** (e.g., V6 benchmarks).
- Automatically identify **strengths** and **weaknesses**.
- Generate a **custom weekly training schedule** targeting those weaknesses.

> ⚠️ **Work in Progress** — Some features are still being refined, including advanced scheduling rules (e.g., avoiding back-to-back high-intensity sessions) and UI improvements.

---

## Features
- **Record Assessments** — Save your climbing test results to a local file.
- **Norm Comparison** — Automatically scores your results against norms for your climbing grade.
- **Weakness Detection** — Highlights areas to prioritize in training.
- **Training Plan Generation** — Builds a day-by-day schedule using pre-defined training templates.
- **Flexible Design** — Easy to add new tests, grades, and training blocks.

---

## How to Use
### Install Requirements
Make sure you have Python 3.9+ and install dependencies:
```bash
pip install pandas numpy
```

### Record an Assessment
Run the `record_assessment(username)` function in the notebook or script.  
Example:
```python
record_assessment("demo")
```
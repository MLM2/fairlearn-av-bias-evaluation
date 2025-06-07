# Fairlearn AV Bias Evaluation
# Fairlearn AV Bias Evaluation

Evaluation of potential **bias and fairness issues** in AI models used for autonomous vehicle (AV) decision-making, using the **Fairlearn Python library**.

This project demonstrates a Responsible AI approach to **measuring and mitigating bias** in AV-related AI systems — aligning with the NIST AI Risk Management Framework and key AI governance principles.

---

## Project Objectives

- Evaluate fairness metrics for a simulated AV decision-making dataset.
- Use **Fairlearn** to measure disparities across sensitive groups.
- Demonstrate application of Responsible AI tools in the context of public safety and critical infrastructure.
- Align project outcomes with:
    - **NIST AI RMF** (Map, Measure, Manage, Govern)
    - AI policy and governance best practices

---

## Data

- **Dataset:** `data/av_bias_dataset.csv`
- **Content:** Simulated AV decisions or outcomes, with sensitive attribute columns (e.g. demographic group, scenario type, outcome).

---

## Methodology

1. Prepare test dataset with simulated AV outcomes.
2. Use Fairlearn's **`MetricFrame`** and fairness metrics:
    - Demographic parity difference
    - Equalized odds difference
    - Other relevant fairness metrics
3. Visualize disparities using **Fairlearn visualization tools**.
4. Document results in `evaluation_run_report.md`.

---

## Results (to be updated after running Fairlearn evaluation)

- Summary of fairness metrics
- Observed disparities
- Mitigation strategies (if applicable)

---

## Tools Used

- **Fairlearn** Python library
- **scikit-learn** (if needed for pipeline)
- **Matplotlib** / **Seaborn** (for visualization)
- **Python 3.x**
- **Jupyter Notebook** (for demonstration)

---

## Alignment to AI Governance & Policy

- **AI RMF "Measure" Function:** Metrics used to assess fairness in AV AI models.
- **Transparency:** Documented process and results.
- **Actionable Feedback:** Recommendations provided for mitigation.

---

## Evaluation Report

See the full [Evaluation Run Report](evaluation_run_report.md) for detailed results and analysis.

---

## License

This project is provided for educational and demonstration purposes only.

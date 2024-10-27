# 🧠 Mathematical Tools for Big Data

## 💡 Proposal Ideas for Simple Fuzzy Logic Applications

### 🏦 Bank Loan Risk Assessment

**Objective**: Determine the risk level for a loan applicant based on key financial indicators. This simplified model is suitable for initial risk screening, offering a straightforward example with minimal inputs and rules.

- **Inputs**:
  - **Income Level** (Low, High)
  - **Debt-to-Income Ratio** (Low, High)
  - **Credit Score** (Low, High)

- **Logic**:
  - Define a small set of fuzzy rules, such as:
    - **High Income** + **Low Debt-to-Income Ratio** + **High Credit Score** → **Low Risk**
    - **Low Income** + **High Debt-to-Income Ratio** → **High Risk**
  - These rules handle combinations of only two or three variables, making it efficient and easy to interpret.

- **Output**: A **Risk Score** ranging from 0 (low risk) to 10 (high risk).

**References**:
- Zadeh, L. A. (1965). *Fuzzy sets*. Information and Control, 8(3), 338-353.
- Kaur, A., & Kaur, A. (2012). *Comparison of Mamdani-type and Sugeno-type Fuzzy Inference Systems for Air Conditioning System*. International Journal of Soft Computing and Engineering (IJSCE), 2(2), 323-325.

---

### 🏥 Medical Triage Severity Level

**Objective**: Assess the severity level of a patient’s symptoms for triage purposes. This example offers a straightforward fuzzy logic model to classify patients based on limited, critical inputs.

- **Inputs**:
  - **Pain Intensity** (Low, High): Self-reported pain level.
  - **Heart Rate** (Normal, Elevated): Basic vital indicator.
  - **Temperature** (Normal, High): Measures if fever is present.

- **Logic**:
  - Apply minimal fuzzy rules to categorize severity, for example:
    - **High Pain** + **Elevated Heart Rate** → **Moderate Severity**
    - **High Temperature** + **Elevated Heart Rate** → **High Severity**
    - **Low Pain** + **Normal Heart Rate** + **Normal Temperature** → **Low Severity**

- **Output**: A **Severity Level** from 0 (low severity) to 10 (high severity), which can aid in prioritizing patient care.

**References**:
- Mendel, J. M. (1995). *Fuzzy logic systems for engineering: a tutorial*. Proceedings of the IEEE, 83(3), 345-377.
- Filippatos, G., & Parissis, J. T. (2007). *Acute heart failure: epidemiology, risk factors, and prevention*. Revista Española de Cardiología, 60(5), 510-515.

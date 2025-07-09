# ❤️ Heart Disease Helper

**Heart Disease Helper** is an informative and interactive website designed to help users understand heart disease, its symptoms, causes, remedies, and assess personal risk based on age and symptoms.

## 🚀 Features

- ✅ Informative sections on heart disease symptoms, causes, and remedies
- ✅ Emergency actions to take during a heart attack
- ✅ Heart Disease Risk Estimator (based on user age and selected symptoms)
- ✅ Alert validations for missing input data
- ✅ Contact section with a link to a helper form
- ✅ Clean, responsive layout (can be styled further with CSS)

---

## 🧠 How the Risk Estimator Works

- Users enter their age and select from a list of symptoms.
- A basic algorithm estimates risk as:
  - Age < 30 → `10% per symptom`
  - Age < 50 → `15% per symptom`
  - Age < 70 → `20% per symptom`
  - Age ≥ 70 → `25% per symptom`
- Risk is capped at 100%.
- The result is color-coded:
  - Green (Low Risk)
  - Orange (Medium Risk)
  - Red (High Risk)

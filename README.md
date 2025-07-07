# Website Conversion‑Rate Optimization — A/B Testing Project

> **Goal:** Determine whether a redesigned landing page **significantly increases sign‑ups** compared with the current version, using principled A/B testing and statistical analysis.

---

## 🗂 Project Structure

| Folder / file | Purpose |
| ------------- | ------- |
| **data/** | Raw and processed CSVs |
| **notebook file** | Jupyter Notebook containing step-by-step flow |
| **assets/** | Final PDF summary and exported figures |
| **requirements.txt** | Python package spec (create venv with `pip install -r requirements.txt`) |

---

## 📊 Dataset

- Source: Kaggle — **[A/B Testing Results from an E‑commerce Website](https://www.kaggle.com/datasets/zhangluyuan/ab-testing)**  
- Key columns  
  | Column | Description |
  | ------ | ----------- |
  | `user_id` | Unique visitor |
  | `group` | `control` / `treatment` |
  | `landing_page` | Page variant seen |
  | `converted` | 1 if user sign‑up, else 0 |
  | `timestamp` | Visit date‑time |

---

## ⚙️ Quick‑start

```bash
git clone https://github.com/<your‑handle>/ab-test-conversion-rate-opt.git
cd ab-test-conversion-rate-opt
python -m venv venv && source venv/bin/activate   # or Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter lab                                        # open notebooks/

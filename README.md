# README.md

# Title

**Status:** *Ecological Informatics* <br>
**Goal:** TBA

---

## Repository Structure

```text
TBA
```

---

## Environment

TBA

```bash
TBA
```

**Author’s setup (recommended):** TBA

---

## Data

TBA

---

## Training

TBA

```bash
TBA
```

**Outputs**

* TBA
---

## Extract Attention Scores

```bash
TBA
```

**Output**

* TBA

---

## Model Overview

* TBA

---

## Reproducibility Notes

* Seed fixed to `42` (numpy/torch/cuda).
* TBA

---

## Citation

If you find this repository useful, please cite:

```
TBA
```

BibTeX (update authors/years upon acceptance):

```bibtex
@article{ ,
  title   = {TBA},
  author  = {Byeongkeun Kwon and Dasom Seong and Jiyun Park and Hyeonjun Hwang and Suhyeon Kim},
  journal = {Ecological Informatics},
  note    = {Under review. Equal contribution: Byeongkeun Kwon and Dasom Seong. Co-corresponding authors: Hyeonjun Hwang and Suhyeon Kim.},
  year    = {TBA}
}
```

---

## License

Released under the **MIT License**. See LICENSE for details.

---

## Contact

For questions and collaborations, please open an issue or contact the authors.<br>
house9895@knu.ac.kr

---

# LICENSE (MIT)

```text
TBA
```

---

# .gitignore

> **What is this?** Files listed here are **not** tracked by Git. It prevents committing caches, virtual envs, temporary outputs, etc. Preprocessed CSVs in `data/` are intentionally kept **tracked**.

```gitignore
# --- Python common ---
__pycache__/
*.py[cod]
*.so
*.pyd
*.pyo
*.pkl
*.egg-info/
.eggs/
build/
dist/
.coverage
.pytest_cache/

# --- Environments ---
.env
.venv/
venv/
env/

# --- OS / IDE ---
.DS_Store
*.swp
*.swo
.vscode/
.idea/

# --- Experiment outputs ---
checkpoints/
artifacts/
runs/
logs/
lightning_logs/

# --- Important: keep preprocessed CSVs tracked ---
# data/*.csv  <-- DO NOT ignore; included in the repo
# If you later add large raw files, ignore like:
# data/raw/
# data/*.zip
```

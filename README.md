# 📄 Resume Analyzer CLI

A Python command-line tool to analyze PDF resumes. It extracts text, counts key skills, and suggests improvements based on keyword gaps.

---

## 🚀 Features

- 📑 **PDF Text Extraction** (using PyMuPDF)
- 🔍 **Skill Counting** from extracted text
- 📊 **Keyword Gap Analysis** against target job descriptions
- 💡 **Improvement Suggestions** for missing or underrepresented skills
- 📝 **Customizable Target Skills** via a text file

---

## 🔧 Technologies Used

- Python 3.x
- [PyMuPDF](https://pymupdf.readthedocs.io/en/latest/)
- argparse
- re (Regex)
- collections.Counter

---

## ⚙️ Setup & Run

### ✅ Prerequisites

- Python 3.7 or higher
- pip

---

### 📥 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/resume-analyzer-cli.git
cd resume-analyzer-cli

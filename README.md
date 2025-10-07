# Art-Nuggets-Initial-Software-Demonstration
Art Nuggets is an online learning and contract-assistance platform designed for African creatives. It helps artists, designers, and creators learn about the creative economy through short, personalized lessons and also understand the risks in contracts they sign.

Full Design Link: [Here](https://www.figma.com/design/S4YVToBngsou3iGNGbFztW/Art-Nuggets?node-id=25-2464&t=EWdN4U6e2mEEVuNr-1)

---

## GitHub Repository
[GitHub Repo Link](https://github.com/maxprodigy/Art-Nuggets-Initial-Software-Demonstration/)  

---

## Setup & Environment Guide

### Prerequisites
- Python 3.10+
- pip
- virtualenv (optional)
- Node.js (if frontend is included)
- Streamlit or Flask (for frontend demo)

### Recommended setup
```bash
# 1. Clone the repo
git clone https://github.com/your-username/art-nuggets.git

# 2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\\Scripts\\activate

# 3. Install backend requirements
pip install -r requirements.txt

# 4. Run notebook for recommender system
jupyter notebook Recommender_System_Improved.ipynb

# 5. Run notebook for contract classifier
jupyter notebook Contract_Risk_Classifier_Improved.ipynb

```

| Component           | Tech Stack              | Deployment Target                                       |
| ------------------- | ----------------------- | ------------------------------------------------------- |
| Backend API         | FastAPI / Flask         | Render / Railway                                        |
| Recommender Module  | Jupyter + Pickled model | GitHub Actions (triggered)                              |
| Contract Classifier | Logistic Regression     | Hosted on backend with endpoint                         |
| Frontend (optional) | Streamlit / React       | Vercel / Streamlit Cloud                                |
| Data Storage        | Local (CSV)             | Will transition to Firebase or Supabase in full version |

Video Demo (5–10 Minutes)

Watch the [Demo](https://youtu.be/OYJYM8k9bfU)

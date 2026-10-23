
# 🐍 Python Problem Solver Dashboard

<p align="center">
  <strong>Learn → Practice → Solve → Improve → Repeat 🚀</strong>
</p>

<p align="center">
  A modern, dark-mode dashboard to track your coding journey, Python practice, problem-solving progress, and achievements.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Streamlit-App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Plotly-Charts-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" alt="Plotly">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License">
</p>

---

## ✨ Overview

**Python Problem Solver Dashboard** is a coding progress tracker designed for developers and students who want to monitor their programming practice through a beautiful, interactive dashboard.

Inspired by modern coding-statistics dashboards, this project combines coding statistics, visual charts, topic-wise progress, activity tracking, and achievements in one place.

The project is built using Python, Streamlit, Plotly, and Pandas.

> **Note:** The included statistics are sample data. This starter version does not automatically retrieve your HackerRank or GitHub activity. You can customize your progress using `data/progress.json`.

## 🎯 Features

- 🌑 **Modern Dark UI** — A professional, dashboard-style interface.
- 📊 **Coding Statistics** — View total solved problems and topic-wise progress.
- 🐍 **Python Progress** — Track practice in Basics, Arrays, Strings, Functions, OOP, and more.
- 📈 **Interactive Charts** — Visualize problem-solving activity and difficulty breakdown.
- 🔥 **Streak Tracker** — Display current and longest coding streaks.
- 🏆 **Achievements** — Unlock visual milestones based on configured progress.
- 💻 **GitHub Statistics** — Display configurable repository, star, commit, and contribution counts.
- 📚 **Topic Breakdown** — Review your progress across programming topics.
- 📥 **Data Export** — Download the dashboard's progress data.
- ✅ **Automated Testing** — Run tests with Pytest and GitHub Actions.
- 📱 **Responsive Layout** — Designed to work across common screen sizes.

## 🖼️ Dashboard Preview

<!-- Add a screenshot after running the app locally. -->
<!-- Save it as docs/dashboard-preview.png and uncomment below. -->

<!-- ![Python Problem Solver Dashboard](docs/dashboard-preview.png) -->

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Application logic |
| Streamlit | Interactive web dashboard |
| Plotly | Charts and data visualization |
| Pandas | Data handling |
| Pytest | Automated testing |
| GitHub Actions | Continuous integration |

## 📁 Project Structure

```text
ai-project-hub/
├── .github/
│   └── workflows/
│       └── tests.yml
├── .streamlit/
│   └── config.toml
├── data/
│   └── progress.json
├── tests/
│   └── test_data.py
├── app.py
├── requirements.txt
├── .gitignore
├── LICENSE
├── README.md
└── SECURITY.md
```

## 🚀 Getting Started

Follow these steps to run the dashboard on your computer.

### Prerequisites

Install the following:

- Python 3.10 or newer
- Git (optional if downloading the ZIP)
- Visual Studio Code or another code editor

### 1. Clone the Repository

```bash
git clone https://github.com/heyr2assistant-cpu/ai-project-hub.git
cd ai-project-hub
```

If the dashboard is inside a subfolder, navigate into that folder before continuing.

### 2. Create a Virtual Environment

**Windows — PowerShell**

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
```

**macOS / Linux**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

### 4. Run the Dashboard

```bash
python -m streamlit run app.py
```

Open the local URL printed in the terminal, usually:

`http://localhost:8501`

## 📊 Customize Your Progress

You can change the dashboard data by editing:

`data/progress.json`

Update the relevant fields to reflect your own progress, including:

- Your display name and GitHub profile URL
- Problems solved by topic
- Easy, Medium, and Hard problem counts
- Recent coding activity
- Current and longest streak
- GitHub repositories, stars, commits, and contributions
- Daily goals and achievements

Keep the topic totals and difficulty totals consistent for accurate statistics.

**Important:** These values are manually maintained in this starter version. The project does not yet have an automatic HackerRank integration.

## 🧪 Testing

Run the test suite with:

```bash
python -m pytest -v
```

The tests check the included data and its expected structure.

## ⚙️ Continuous Integration

A GitHub Actions workflow is included at:

`.github/workflows/tests.yml`

It automatically runs the Python tests on pushes to the `main` branch and pull requests targeting `main`.

Check the **Actions** tab in your repository to view the results.

## ☁️ Deployment

You can deploy the dashboard using Streamlit Community Cloud.

1. Push the project to a public GitHub repository.
2. Open [Streamlit Community Cloud](https://share.streamlit.io/).
3. Sign in and connect your GitHub account.
4. Select your repository and branch.
5. Set the main file path to `app.py`.
6. Click **Deploy**.
7. Add the live application URL to this README once deployment succeeds.

## 🗺️ Roadmap

- [x] Create a dark-themed dashboard
- [x] Add coding statistics and topic progress
- [x] Add charts and activity visualization
- [x] Add editable JSON-based progress data
- [x] Include automated tests and CI
- [ ] Add individual problem records and completion dates
- [ ] Add optional GitHub API integration
- [ ] Import and export coding history
- [ ] Add date and difficulty filters
- [ ] Improve mobile layout and accessibility

## 🔐 Security

- Never commit passwords, API keys, or private tokens.
- Keep sensitive configuration in environment variables or a supported secret manager.
- Do not store credentials in `data/progress.json`.
- Review third-party dependencies before updating them.
- Report security vulnerabilities privately using the method described in `SECURITY.md`.

## 🤝 Contributing

Contributions and suggestions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Run the tests.
5. Submit a pull request with a clear description.

For significant changes, open an issue first to discuss the proposed feature.

## 📄 License

This project is distributed under the MIT License. See [LICENSE](LICENSE) for details.

---

<p align="center">
  Made with ❤️ and Python by <strong>Ashutosh</strong>
</p>

<p align="center">
  <strong>Keep learning. Keep coding. Keep improving. 🚀</strong>
</p>

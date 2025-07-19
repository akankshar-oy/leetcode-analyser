# LeetCode Analyzer

A Jupyter Notebook tool that visualizes and analyzes your LeetCode performance using GraphQL and REST APIs. Built using Python, Matplotlib, and Requests, it provides visual insights into problem-solving patterns.

## Features

- Fetches user data from LeetCode using GraphQL API
- Displays:
  - Total problems solved by difficulty
  - Progress charts by tag and submission stats
  - Streak visualization
- Visual representation using `matplotlib`

## Getting Started

Follow these steps to run the project locally in Jupyter Notebook or Google Colab.

### 1. Clone the Repository

```bash
git clone https://github.com/akankshar-oy/leetcode-analyser.git
cd leetcode-analyser

```

### 2.Install Required Libraries
Install the dependencies using pip:
```bash
pip install requests matplotlib

```

### 3.Run the Notebook

Open the notebook in Jupyter:
```bash
jupyter notebook Leetcode_analyser.ipynb

```

## Usage

1.Replace the username variable inside the notebook:
```bash
username = "your_leetcode_username"

```
2. Run all cells sequentially.

3. The notebook will display your:

-Total solved problems
-Bar graphs by difficulty
-Tags and topic-wise solved count
-Visual submission history and streak data

#  Computational Theory Assement - G00423489 (Nathan Dean)

This repo will contain any and all required material for the aformentioned 2025 Computational theory Assement.

## Contents
- README.md - This file
- Jupytr notebook - Assesement submission material

## To Run

### Locally (Linux / macOS / Windows)
1. Clone the repo and change into it:
```bash
git clone <repo-url>
cd <repo-directory>
```
2. Create and activate a virtual environment:
- macOS / Linux:
```bash
python3 -m venv .venv
source .venv/bin/activate
```
- Windows (PowerShell):
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```
3. Install dependencies and Jupyter:
```bash
pip install -U pip
pip install -r requirements.txt || true
pip install jupyterlab
```
4. Start Jupyter and open the notebook:
```bash
jupyter lab
# or
jupyter notebook
```
Then open the provided notebook (.ipynb) from the Jupyter UI.

Notes:
- If there is no requirements.txt, installing `jupyterlab` is sufficient for running the notebooks.
- Use the appropriate Python interpreter in Jupyter if multiple environments are present.
  
## Resources I found helpful

[SHA-256 | COMPLETE Step-By-Step Explanation (W/ Example) by RedBlockBlue](https://www.youtube.com/watch?v=orIgy2MjqrA&t=391s)

This video nicely outlines the entire process of a SHA-256 hash.
Breaking down each step, explaining the how and why of all the functions.


[Wikipedia Sieve of Eratosthenes](https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes)

I used this approach to find primes in Problem 2. This page is also where I sourced the GIF in the markdown of Problem 2.

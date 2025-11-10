Vibe Matcher — by Abhishek Anand

A vibe-based fashion recommendation prototype powered by AI.

OVERVIEW -

Vibe Matcher takes a mood or “vibe” — like urban chic or cozy comfort — and recommends the top 3 matching fashion items using text embeddings and cosine similarity.

TECH STACK -

Model: Gemini text-embedding-004 (used instead of OpenAI text-embedding-ada-002 due to quota limits)

Libraries: pandas, numpy, scikit-learn, matplotlib, python-dotenv

FEATURES:

20-item mock fashion dataset

Semantic embeddings + cosine similarity

Query testing with latency visualization

Reflection on learnings and improvements



How to Run Locally-

Create a virtual environment

python -m venv .venv


Activate it (Windows)

. .venv/Scripts/activate


Install the required libraries

pip install -r requirements.txt
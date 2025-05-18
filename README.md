# PaarStip Co-Founder Matcher

## Features

- ✅ Semantic matching using embeddings (local Hugging Face models)
- ✅ Optional weighted scoring by:
  - Industry interests
  - Skills
  - Location proximity
- ✅ Group matching (e.g., best team of 3)
- ✅ Match only for a single person (personalized recommendation)
- ✅ Top-N filtering for performance
- ✅ Exportable match results (CSV, DataFrame)
- ✅ Built-in progress bars and parallel processing

## Requirements
- Python

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/jamal-alkharrat/paarstip
    cd paarstip
    ```
2. Create a virtual environment:
    ```bash
    python -m venv venv
    ```
3. Activate the virtual environment:
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS and Linux:
        ```bash
        source venv/bin/activate
        ```
4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
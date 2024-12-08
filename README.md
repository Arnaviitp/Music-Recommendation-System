# Music Recommendation System

This project implements a **Music Recommendation System** using Python. It processes user listening data and song metadata to suggest songs to users based on their preferences.

## Features

- Reads and processes user interaction data (`triplets_file.csv`) and song metadata (`song_data.csv`).
- Merges datasets for analysis and recommendation generation.
- Builds a recommendation model to suggest songs.

## Requirements

- Python 3.8 or later
- Required libraries:
  - pandas
  - numpy

Install dependencies with:

```bash
pip install pandas numpy
```

## Dataset

- **`triplets_file.csv`**: Contains user-song interaction data.
- **`song_data.csv`**: Contains song metadata, including song IDs and titles.

## Steps in the Notebook

1. **Data Loading**: 
   - Loads and previews user-song interactions and metadata.
2. **Data Cleaning**:
   - Merges and deduplicates datasets.
3. **Recommendation Engine**:
   - Implements algorithms to generate song recommendations.

## Usage

1. Clone the repository or download the notebook.
2. Place the datasets (`triplets_file.csv` and `song_data.csv`) in the same directory.
3. Run the notebook to preprocess data and generate recommendations.

## Output

The notebook processes the datasets and provides song recommendations tailored to user preferences.

# RSS Feed Aggregator

This project fetches RSS feeds from various sources, processes the data, and outputs it to both CSV and Excel files. The files are organized in folders named by the current date.

## Setup

### Prerequisites

- Python 3.x
- `pip` (Python package installer)

### Installation

1. Clone the repository:

   ```
   sh
   git clone https://github.com/yourusername/rss_feed.git
   cd rss_feed
   ```

2. Install the required packages:

    ```
    pip install -r requirements.txt
    ```

## Usage

To run the script, use the following command:

```
python run.py <category1> <category2> ...
```

### Example

```
python run.py sports news
```

### Categories

The available categories are defined in the rss_feeds.py file. You can add or modify categories and their corresponding RSS feed URLs in this file.

## Project Structure

rss_feed/
├── config/
│   └── rss_feeds.py
├── run.py
├── requirements.txt
└── README.md
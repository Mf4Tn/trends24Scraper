## trends24Scraper

**Overview:**
trends24Scraper is a lightweight Python API built using Flask to scrape the latest 24-hour trending keywords from trends24.in.

**Features:**

- **Real-time Trends:** Fetches the latest trending keywords from trends24.in.
- **Easy Integration:** Simple API endpoint for easy integration.
- **JSON Output:** Returns data in JSON format.

**Installation:**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/trends24Scraper.git
   ```

2. **Install Dependencies:**
   ```bash
   cd trends24Scraper
   pip install -r requirements.txt
   ```

3. **Run the Flask Application:**
   ```bash
   python app.py
   ```

**API Endpoint:**

- **/trends**: GET request to retrieve trending keywords.

**Usage:**

- **Run the server:** `python app.py`
- **Access the API:** Send a GET request to `http://127.0.0.1:5000/trends`.

**Response Example:**
```json
{
  "Just Now": {
    "trend": [
      {"name": "#example", "count": "10000"},
      {"name": "#anotherexample", "count": "5000"}
    ]
  },
  "1 Hour": {
    "trend": [
      {"name": "#yetanotherexample", "count": "2000"}
    ]
  }
}
```

This API allows you to stay updated with the latest trends on X by scraping data from trends24.in.

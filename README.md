# 📰 CNN Web Scraper + GPT Summarizer 🇵🇰

> “CNN se poora data uthaya, phir AI se summary banwayi — because reading is too mainstream 😎”

This is a mini project where I scraped [CNN.com](https://www.cnn.com) using **Python**, **BeautifulSoup**, and **requests** — and then sent the extracted text to **OpenAI’s GPT model** to generate a short summary in Markdown.

## 💡 What It Does

- Scrapes all readable content from CNN’s homepage  
- Removes boring stuff like `<script>`, `<style>`, `<input>` etc.
- Sends the cleaned text to **GPT-4o mini** with a prompt
- GPT gives a summary of the latest news headlines — just like your chacha watching TV all day 👴📺

## 🧠 Tech Stack

| Tool | Use |
|------|-----|
| `Python` | For scripting |
| `BeautifulSoup` | For web scraping |
| `requests` | To fetch webpage |
| `OpenAI API` | For summarizing |
| `dotenv` | To hide API key |
| `Jupyter Notebook (.ipynb)` | Because vibes 😎 |

## 🔥 Output Example

![output](output_screenshot.png) <!-- (Optional: Add a screenshot if available) -->

## 📁 Files

- `cnn_scraper_summary.ipynb` – Main notebook with code, scraping, and AI logic
- `.env` – Store your `OPENAI_API_KEY` here (don’t share it!)
- `README.md` – You’re reading it 👀

## 🚀 How to Run

1. Clone the repo  
2. Create a `.env` file and add your API key:

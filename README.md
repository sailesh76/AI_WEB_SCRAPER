
# Project Title

AI Web Scraper

Overview
AI Web Scraper is a powerful and intelligent web scraping tool that leverages AI models for parsing and extracting content from websites. It provides a Streamlit-based interface for easy interaction, and it integrates AI-driven content parsing using LangChain and LangChain Ollama.


## Features

AI-Driven Parsing: Utilizes LangChain and LangChain Ollama to intelligently parse and extract relevant content.
Streamlit Interface: An easy-to-use web interface to scrape and analyze website data.
Dynamic Content Support: Handles JavaScript-heavy pages using Selenium.
Customizable Extraction: Flexible scraping and parsing based on user input.
Multi-format Output: Export scraped content in multiple formats like JSON or CSV.
Technologies Used

- Streamlit: Web interface for the scraper.
- LangChain: For AI-driven workflows.
- LangChain Ollama: For advanced AI model integration.
- Selenium: Handles dynamic, JavaScript-based web content.
- BeautifulSoup4: For parsing HTML content.
- lxml and html5lib: Additional parsers for flexible HTML extraction.
- python-dotenv: For managing environment variables.


## Installation

Install my-project with npm

```bash
      git clone https://github.com/sailesh76/AI_WEB_SCRAPER
  cd AI-WEB-SCRAPER
```
 
## Deployment

```bash
  pip install -r requirements.txt
```


## Run Locally

Downlaod and setup the ollama Ai.

For linux
```bash
  curl -fsSL https://ollama.com/install.sh | sh
  service ollama start
  ollama pull llama2-uncensored 
```
For WindowOS and MacOS

https://ollama.com/download

## How to use this


-Enter the target website URL in the text input field.

-Click on Scrape Website to begin scraping the website's DOM content.

-After scraping, you can view the scraped DOM content in an expandable text box.

-Enter a description of what you want to parse in the provided text area and click Parse Content to extract the relevant information using AI.

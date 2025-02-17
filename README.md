# JAWS-MD

<div align="center">
  <p align="center">
    <a href="https://github.com/DenverCoder1/readme-typing-svg">
      <img src="https://readme-typing-svg.herokuapp.com?&font=IBM+Plex+Sans&color=ffffff&duration=2000&size=26&lines=Just+Another+Web+Scraper...;...markdownified😈" />
    </a>
  </p>
  <p align="center">
    <a href="https://media1.tenor.com/m/-2V6pcNfhpMAAAAd/homer-simpson-levitating.gif" target="_blank">
    <img src="https://media1.tenor.com/m/-2V6pcNfhpMAAAAd/homer-simpson-levitating.gif" alt="Homer Simpson levitating" width="100" />
    </a>
  </p>
</div>

## Description

Crawls and scrapes a site to create markdown files from HTML.

### Parts & Pieces

The following must be present for the project to be considered testable:
- A Scrapy spider
- HTML Markdownification

## Dependencies
- markdownify
- scrapy

## Usage

### Installation

1. Clone the repository
```
git clone https://github.com/Daethyra/JAWS-MD.git
```

2. Create a virtual environment
```
python3 -m venv venv
```

3. Activate the virtual environment

In bash:
```bash
source venv/bin/activate
```

In powershell:
```powershell
.\venv\Scripts\Activate.ps1
```

4. Install dependencies
```
pip install -rU requirements.txt
```

5. Run the program
```shell
scrapy crawl <spider_name>
```
# 🖼️ Image Scraping from Google 🌐

🔍 Step-by-Step Process:
🔎 Search Query: Input the desired search term to find relevant images.
🌐 Request Handling: Use requests to fetch the Google Images search results page, employing a user-agent header to avoid detection as a bot.
🧹 HTML Parsing: Utilize BeautifulSoup to parse the HTML content and locate image tags (<img>).
📥 Image Extraction: Extract the URLs of the images from the tags and download them to a local directory.
🗂️ Directory Management: Ensure images are saved in a structured and organized manner for easy access and further processing.

🔧 Tools & Technologies:
  1) Flask: Web framework for creating a user-friendly interface to input search queries and view results.
  2) BeautifulSoup: Library for parsing HTML and extracting image URLs.
  3) Requests: Module to handle HTTP requests to Google.
  4) Logging: Keep track of the scraping process and handle errors effectively.


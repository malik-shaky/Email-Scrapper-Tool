# Email-Scrapper-Tool
This Python script, **"Email Scrapper Tool,"** is designed to extract email addresses from a target URL. Leveraging libraries like BeautifulSoup and requests, it systematically traverses and parses web pages to collect email addresses, making it a powerful utility for gathering contact information from websites.

## Features:
- **Input Handling:** Prompts the user for a target URL to scan.
- **Queue-Based URL Management:** Utilizes a deque to manage URLs, ensuring efficient traversal.
- **URL Processing:** Extracts base and path URLs for accurate link resolution.
- **Robust Scraping:** Handles common exceptions like missing schemas and connection errors.
- **Email Extraction:** Uses regular expressions to identify and collect email addresses.
- **Web Crawling:** Follows links on pages to explore and scrape additional URLs.
- **User Interrupt Handling:** Gracefully handles keyboard interruptions to stop the script.

## Usage for Kali Linux
1. **Ensure Python is Installed:**
   - Kali Linux comes with Python pre-installed. Verify the installation by opening a terminal and typing:
     ```bash
     python3 --version
     ```

2. **Save the Script:**
   - Save your script in a `.py` file, for example, `email-scrapper-tool.py`.

3. **Install Required Libraries:**
   - Install the `BeautifulSoup` and `requests` libraries if they are not already installed. Open the terminal and run:
     ```bash
     pip3 install beautifulsoup4 requests
     ```

4. **Run the Script:**
   - Open your terminal.
   - Navigate to the directory where your script is saved using the `cd` command. For example:
     ```bash
     cd path/to/your/script
     ```
   - Run the script by typing:
     ```bash
     python3 email-scrapper-tool.py
     ```

5. **Enter the Target URL:**
   - The script will prompt you to enter a target URL. Type the URL and press Enter to start the scraping process.

6. **Processing:**
   - The script processes up to 100 URLs, extracting and printing found email addresses.

## Example:
To run the script, follow these steps:
```bash
cd ~/scripts
python3 email-scrapper-tool.py

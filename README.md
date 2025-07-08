## Installation & Usage

**Prerequisites:**  
- Python 3.x (recommended 3.7 to 3.11 for best compatibility)  
- Tkinter GUI library (usually included with Python)  

**Setup Steps:**  
1. Clone the repository:  
   `git clone https://github.com/yourusername/CyberAlly-False-Allegation-Detector.git`  
   `cd CyberAlly-False-Allegation-Detector`  

2. Install required Python packages:  
   `pip install -r requirements.txt`  

3. Download necessary TextBlob corpora for sentiment analysis:  
   `python -m textblob.download_corpora`  

4. Run the application:  
   `python cyberally_main.py`  

---

**Usage:**  
- Modify or add posts to analyze in `data/fake_posts.txt`.  
- Launch the app and use the buttons to analyze posts, generate reports, or view help resources.  
- Generated PDF reports are saved in the `reports/` folder.  
- Logs of detected harmful posts are saved in `logs/harmful_logs.json`.  





**Using the Application:**

- Modify or add social media posts and comments to analyze in the file `data/fake_posts.txt`. The application scans this file for harmful posts mentioning the target individual.
- Launch the app to open the graphical interface.
- Click “Analyze Posts” to scan the text file for false allegations and log harmful content.
- Use “Generate Report (PDF)” to create a professional summary of detected harmful posts in PDF format saved under the `reports/` folder.
- Access “Cyber Help Info” for useful links to cybercrime authorities and mental health support organizations.
- Exit the app using the “Exit” button.

## Folder Structure

- `data/` — Contains the sample `fake_posts.txt` file with posts to analyze.
- `logs/` — Stores JSON logs of detected harmful posts (`harmful_logs.json`).
- `reports/` — Holds generated PDF reports (`cyber_report.pdf`).
- `cyberally_main.py` — Main Python script containing the full application code.
- `requirements.txt` — Python package dependencies.
- `README.md` — This documentation file.

## Technologies Used

- Python 3.x: Core programming language for the application.
- Tkinter: Built-in Python library used to create the graphical user interface.
- TextBlob: Provides sentiment analysis capabilities.
- FPDF: Generates PDF reports summarizing harmful posts.

## Contribution

Contributions are highly welcome! Feel free to open issues, request features, or submit pull requests to improve CyberAlly. Your support will help make this tool more effective in combating cyberbullying and false allegations.

## License

This project is released under the MIT License — see the LICENSE file for details.

## Disclaimer

CyberAlly is intended solely for ethical use and educational purposes. It is not a replacement for professional legal advice or official investigations. Users must report serious allegations to appropriate authorities.

## Author

Bhargav Raj Dutta  
[GitHub](https://github.com/yourusername) | [LinkedIn](https://linkedin.com/in/yourlinkedin)

---

Thank you for supporting CyberAlly — together, we can stand against cyberbullying and false allegations, fostering a safer online environment.

2. Install all required Python packages using pip:

pip install -r requirements.txt


3. Download necessary TextBlob language corpora for sentiment analysis:

python -m textblob.download_corpora


4. Run the application with the command:

python3 cyberally_main.py

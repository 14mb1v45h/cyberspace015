# cyberspace015
Malware-Analysis tool Python API Virus total based 
# Malware Analysis Tool

This project is a simple file analysis tool that computes the SHA-256 hash of a file and sends it to the VirusTotal API for malware detection. It is designed with a user-friendly GUI using Tkinter, allowing users to easily select a file and analyze its safety.

---

## Features

- **File Hashing:** Computes the SHA-256 hash of the selected file, which uniquely identifies it.
- **VirusTotal API Integration:** Sends the file's hash to VirusTotal for scanning. The result includes the number of engines that flagged the file as malicious.
- **User-Friendly GUI:** Built using Tkinter, allowing easy file selection and displaying the results directly in the window.

---

## Requirements

- Python 3.x
- `hashlib`, `requests`, and `tkinter` libraries

Install the required libraries using the following commands:

```bash
pip install requests hashlib tkinter
```


## Setup and Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/14mb1v45h/cyberspace015.git
   ```

2. **Navigate to the Directory:**

   ```bash
   cd cyberspace015
   ```

3. **Replace the VirusTotal API Key:**

   Open the `main.py` file and replace the `API_KEY` variable with your VirusTotal API key:

   ```python
   API_KEY = 'your_api_key_here'
   ```

4. **Run the Application:**

   ```bash
   python malware_analysis_tool.py
   ```

5. **Analyze a File:**

   - Click on the "Select File" button to choose a file for analysis.
   - The file's SHA-256 hash will be computed and sent to VirusTotal.
   - The result will show how many VirusTotal engines flagged the file as malicious.

---

# API Key

To use this tool, you will need an API key from VirusTotal. You can obtain one by registering for free on the [VirusTotal website](https://www.virustotal.com/).

---

## Disclaimer

This tool is for educational purposes only. Always be cautious when analyzing files, and do not rely solely on VirusTotal results for full security assessments.


---

## Contributions

Contributions, bug reports, and feature requests are welcome. Feel free to fork the repository and submit pull requests.

## Copyright @iambivash  https://github.com/14mb1v45h/cyberspace015.git


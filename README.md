# File_Analyzer_VirusTotal
This Colab analyzes multiple files using the VirusTotal API, identifying the number of security engines that classify each file as malicious or suspicious.

## Features

* Automated scanning of multiple files.
* Uses the VirusTotal API to obtain detailed analysis.
* Supports multiple file types.

## Dependencies

Before running the project, make sure to install the following dependencies:

* concurrent.futures
* hashlib
* mimetypes
* requests
* os
* pandas

## API Key

This project requires a valid VirusTotal API key. Register at [VirusTotal](https://www.virustotal.com/gui/join-us) to get one.

## Usage

1. Configure your API key in the script: Find the API Keys section in the code and insert your key.
2. Upload the files you want to analyze in the specified folder.
3. Run the script on Google Colab or locally.
4. Review the generated report to get details about the scanned files.
5. Execution

Upload the notebook to Google Colab or run it locally with Jupyter Notebook. Follow the instructions inside the notebook to perform the analysis.

## Contributions

Contributions are welcome. If you have ideas or improvements, please open an issue or a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

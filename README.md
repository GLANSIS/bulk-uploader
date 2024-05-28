# GLANSIS Bulk Uploader

**Summary**: The code for the Bulk Uploader automates the process of uploading journal references and their associated PDFs to the NAS database. It begins by importing necessary libraries, including pandas for data management, Selenium for web automation, and BeautifulSoup for HTML parsing. The script prompts users to select an Excel file containing references and a folder with PDF files. It then reads the references into a DataFrame, handles missing values, and displays the first five rows for verification. The script opens a browser window using Selenium, logs into the NAS data entry page, and iteratively fills in the reference details from the DataFrame, uploads the corresponding PDFs, and handles errors. Finally, it appends the new reference numbers to the DataFrame and exports the updated references to a new Excel file.There is a script with the original markdown file and a script to use a widget/GUI for users less experienced using Python.

**Documentation**: For full description read https://docs.google.com/document/d/12wg66ZqrLsBJchTCA-lxeMvXRc2m5GmGloqu7K88rsY/edit#heading=h.b9fciu2qkh2v

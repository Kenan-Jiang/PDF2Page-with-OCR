# google drive PDF2Page with OCR
This repo contains a colab notebook that parses pdfs in google drive into text files for further analysis
## Basic Overview
If you have a lot of PDFs scanned in your google drive and you cannot do NLP analysis on it, you are in the RIGHT place!!!<br />
Our project parses and organizes your text for you; all you need to do is to put your PDFs in a common folder.
## How to use it
 1. Have a folder of PDFs that you want to run OCR on in your google drive. (ex. PDFs) 
 ![alt text](https://github.com/Kenan-Jiang/colab_pdf_parser/blob/main/input.jpg)
 2. Save this main.ipynb colab notebook anywhere in your google drive. 
 3. Open the main.ipynb and change the first cell accordingly:<br />
    a. Input folder’s [google id](https://ploi.io/documentation/mysql/where-do-i-get-google-drive-folder-id)<br />
    b. Input folder’s directory<br />
    c. Output folder’s directory (which you name)
 4. Run the entire notebook. When finished, you can find all results in the output folder.
## Results Interpretation 
In your output folder, you will find the following:
  1. A folder for each pdf documents you want to parse, the folder name is the google id of the original pdf.
  ![alt text](https://github.com/Kenan-Jiang/colab_pdf_parser/blob/main/output.jpg)
  2. Inside each folder, you will find each page as a picture.
  3. Inside each folder, you will find a page.csv file. It will have page number mapped to the ocr results for each page.
  ![alt text](https://github.com/Kenan-Jiang/colab_pdf_parser/blob/main/output2.jpg)
## Contributors (in alphabetical order)
Adam Anderson, Jason Webb, Kenan Jiang, Kevin Gao, Kewei Chen, Max Ziff, Serena Zhang, Shuyao Zhou
### Contact
Adam Anderson: admndrsn@berkeley.edu<br />
Kenan Jiang: kenanj11@berkeley.edu<br />
Kevin Gao: kevingao26@berkeley.edu

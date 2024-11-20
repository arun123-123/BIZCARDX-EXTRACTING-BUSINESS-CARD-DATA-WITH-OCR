# BIZCARDX-EXTRACTING-BUSINESS-CARD-DATA-WITH-OCR

EasyOCR as the name suggests, is a python package that allows computer vision developers to effortlessly perform Optical Character Recognition. It is a Python Library fro Optical Character Revognition(OCR) that allows you to easily extract text from images and scanned documents. In my project I am using easyOCR to extract text from business cards.  When is comes to OCR, EasyOCR is by far the most straightforward way to apply
Optical Character Recognition:

  1. The EasyOCR package can be installed with a single pip command,
  2. The Dependencies on the EasyOCR package are minimal, making it easy to configure your OCR development environment.
  3. Once EasyOCR is installed, only one import statement is required to import the package into your project.

PROJECT OVERVIEW

BizCardx is a user-friendly tool for extracting information friom business cards. The tool used OCR technology to recognize text on business cards and extracts the data into a SQL database after classification using regular expressions. Users can access the extracted information using a GUI built using stremlit. The BizCardX application is a simple and intuitive user interface that guides users through the process of uploading the business card image and extracting its information.  The extracted information would be displayed in a clean and organized manner, and users would be able to easily add it to the database with the click of a button.  Further the data stored in database can be easily read, updated and deleted by user as per the requirement.

LIBRARIES/MODULES USED FOR THE PROJECT

  1. Pandas - To Create a DataFrame with the scraped data
  2. SQLite- To store and retrieve the data
  3. Streamlit - To Create Graphical user Interface
  4. EasyOCR - To extract text from images
 

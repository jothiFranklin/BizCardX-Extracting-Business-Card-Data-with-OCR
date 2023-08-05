
# BizCardX-Extracting-Business-Card-Data-with-OCR

BizCardX is a Python application using OCR to extract business card data. It allows users to upload an image of a business card and extract relevant information such as name, designation, company name, contact details, email, website, address, and pincode.
  1. Extract data from the business card image and text image.
  2. Analyse extracted data and store it in the database
  3. View and delete data
## Workflow
step1:Install the required packages !pip install -q streamlit !pip install easyocr !pip install sqlalchemy !pip install streamlit-option-menu ! !pip install sqlconnector import libraries easyocr streamlit pymong pandas cv2  numpy.

step2:Create streamlit app to extract text from the image 
  1. Upload language list document 
  2. Create a connection to the database

step3:In Streamlit App: 

  1. Upload an image of an English language business card or another language business card
  2. Click the extract button
  3. Text in the card will be extracted and stored in a database

step4: Others
  
  1. Upload an image of an English language text image or another language text image
  2. Choose the language of the uploaded file
  3. Click the Extract button
  4. Text in the card will be extracted and stored in the database



step5: Manage data

  1. Selectbox lists all documents in the database
  2. View the selected document
  3. Delete the document


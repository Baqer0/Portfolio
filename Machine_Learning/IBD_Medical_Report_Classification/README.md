# IBD Classification Model for MyCCAngel Platform

**Project Overview**
This project involves building a machine learning AI model designed for deployment on the MyCCAngel platform, a dedicated social network for individuals with Inflammatory Bowel Disease (IBD). The primary goal is to ensure that only those with verified IBD can access the platform by classifying uploaded medical reports (PDFs or images) to confirm their content.

**Process and Workflow**
**1. Document Upload and Preprocessing:**
- Users submit a PDF or image of their medical report.
- Text extraction is performed using PyPDF2 for PDF documents and Pytesseract for image-based files.

**2. Text Cleaning and NLP Processing:**
-	Extracted text undergoes Natural Language Processing (NLP) to remove noise and enhance quality.
-	TF-IDF (Term Frequency-Inverse Document Frequency) is applied to transform the text into features for the model.

**3. Model Classification:**
- The processed TF-IDF data is fed into the trained machine learning model to classify the document.

**4. Verification and Access:**
- If the report is verified as an IBD document, access is granted to the platform.

**Key Features**
- Text extraction from both PDF and image formats.
- Advanced NLP for accurate text transformation.
- Machine learning classification to verify IBD-specific content.
- Enhanced security and user verification for the MyCCAngel community.

**Visuals and Model Performance**
- Visuals such as confusion matrices, ROC curves, and precision-recall charts highlight the performance metrics of the classification model.


**Key Technologies Used**
- Python Libraries: Pytesseract, PyPDF2, Scikit-learn
- NLP Tools: TF-IDF Vectorizer, various text preprocessing techniques
- Deployment: for now is depoyed in the GitHub account using Render, but it will be integrated with MyCCAngel for real-time document verification
- Visual Studio Code

**Accest the Model:**
[Model](Machine_Learning/IBD_Medical_Report_Classification/Deployed_Model.html)



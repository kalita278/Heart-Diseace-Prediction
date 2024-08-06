# Heart-Diseace-Prediction
Develop an automated diagnostic system that can accurately detect and classify to class 0, and 1 using chest X-ray images and basic medical records of patients. Your solution should leverage machine learning or deep learning techniques to analyze both types of data and provide a diagnostic prediction.

Structured Data: Basic medical records.

- Image Index - Unique name given to x-ray images in the dataset.
- Finding Labels - Target column (has different classes namely 0,1)
- Follow-up - No of hospital visits
- Patient ID - Unique ID for each patient (can be repeated as per the visits)
- Patient Age - The age of the patient
- Patient Gender - The gender of the patient
- View Position - Position of X-ray image
- OriginalImage_Width - Orginal width of the image
- OriginalImage_Height - Orginal height of the image
- OriginalImagePixelSpacing_x - X spacing between pixels of the image
- OriginalImagePixelSpacing_y - Y spacing between pixels of the image

- Unstructured Data:  X-Ray images
- Train and test images are in the below Google Drive:
https://drive.google.com/drive/folders/1UjhrocBCNwylCjv_n6k--KQuwd7K5t_e?usp=sharing

NOTE:
There are 2 classes in the target variable: Class 1 and Class 0. Both classes refer to specific types of disease. Note that Class 0 should NOT be considered a NON-DISEASE CLASS.

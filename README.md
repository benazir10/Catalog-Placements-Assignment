# **Dynamic Selection Hybrid Model for Advancing Thyroid Care With BOOST Balancing Method**

### **Overview**

The **Dynamic Selection Hybrid Model** is a **machine learning-driven system** designed to enhance **thyroid disorder diagnosis** by integrating **machine learning, deep learning, and balancing techniques.**

- Addresses **class imbalances** using **BOOST balancing methods** to ensure **higher accuracy, adaptability, and reliability.**
- Dynamically selects the **most efficient classifiers** based on **Permutation Feature Importance (PFI) and ensemble techniques.**
- Optimizes diagnosis for both **Hyperthyroid** and **Hypothyroid** disorders.

This model ensures **precise and adaptable thyroid condition predictions** by leveraging a **hybrid selection approach** for classifier optimization.

---

## **Key Features**
✅ **Hybrid Model Selection:** EUses multiple ML models for precise classification.
✅ **BOOST Balancing Method:** Combines **SMOTE, Tomek Links, and AdaBoost** to handle imbalanced datasets 
✅ **Dynamic Selection Mechanism:** Selects the best-performing models based on **PFI scores**.
✅ **Secure User Authentication:** Allows registration and login for users.
✅ **User-Friendly Interface:** Web-based application for **uploading patient data and obtaining predictions.**
✅ **Thyroid Disorder Prediction:** Detects **Hyperthyroid and Hypothyroid conditions** with high accuracy

---

## **Tech Stack**
- **Programming Language:** Python, HTML, CSS, Bootstrap, JavaScript
- **Framework:** Flask
- **Database:** MySQL Server
- **Libraries:** Flask, Pandas, MySQL-Connector, Scikit-learn, NumPy
- **Dataset Source:** Thyroid Case Dataset from Kaggle
- **Server Deployment:** XAMPP Server
---

### **3. Install Dependencies**
```sh
pip install flask
pip install scikit-learn
pip install pandas numpy seaborn
pip install tensorflow
pip install xgboost
pip install matplotlib
```
---

## **Installation & Setup**

### **1. Clone the Repository**
```sh
git clone <repository_url>
cd <repository_folder>
```

### **2. Open VS Code and Set Up Terminal**
- Open **VS Code**
- Open **Terminal** → **Run `cmd`** (to change from PowerShell to cmd)

### **3. Install Dependencies**
```sh
pip install streamlit 
pip install mysql-connector-python
pip install PyPDF2
pip install python-docx
pip install google-generativeai
pip install python-dotenv
pip install pydub
pip install SpeechRecognition
```

### **4. Install & Configure XAMPP server**
1. Download **XAMPP** from [here](https://www.apachefriends.org/download.html)
2. Open it and do the installation setup

### **5. Installing required dependencies for frontend**
1. Go the project folder and select **FRONTEND** folder.
2. In the path click cmd 
3. From cmd write command as
   ```sh
   code .
   ```
4. Then we navigate to **VS Code** in which select **app.py** file.
5. Click **Terminal** → **New Terminal**
6. Check whether **miniconda** is dowloaded in your system or not by using the command 
   ```sh
   conda -version
   ```
7. If error the run the command
   ```sh
   conda create -n env python==3.10.14
   ```
8. By running above command we get all the required libraries.

### **7. Run the Application**
1. Open **XAMPP** server.
2. Start **Apache** and **MySQL** and in **MySQL** section click **Admin**.
3. Then A new Window will open in which from header bar click **Import**
4. Then There will be an option to upload a file where you have to upload your **db.sql** database file present in **FRONTEND** folder
3. Now go the **FRONTEND** folder from your project File Explorer
4. Type **cmd** and 
5. Run the command as 
   ```sh
   code .
   ```
4. Then we navigate to **VS Code** in which select **app.py** file.
5. Click **Terminal** → **New Terminal**
6. Run command as 
   ```sh
   conda activate env
   ```
7. Write command 
    ```sh
   python app.py
   ```
8. Then you will get a **localhost URL** click on that
9. Our application will start running.
---

## **Output & Usage**
1. **Login/Register** to access the platform.
2. Give the inputs of a Patient data
3. Click on **Submit**
4. We will finally get the Severeity of a tyroid disorder

---

## **Benefits**
✔ **Higher Accuracy** –Hybrid models improve prediction reliability.
✔ **Improved Diagnosis** – Machine learning techniques enhance medical assessments.
✔ **Better Data Handling** – Addresses class imbalance for fair predictions.
✔ **Scalable Solution** – Can be adapted for other medical conditions.

---

## **Contributors**  
**Team B10, Shri Vishnu Engineering College for Women (SVECW)**  
👩‍💻 **Md. Benazir Fathima**     - 21B01A05A8  
👩‍💻 **N. Neha**     - 21B01A05B3
👩‍💻 **N. Sai Ramya Sri** - 21B01A05B4
👩‍💻 **N. Lakshmi Priya**    - 21B01A05B9 
👩‍💻 **O. Pranathi Sudha**       - 21B01A05C7


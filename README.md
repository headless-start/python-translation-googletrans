# Hindi to En,De,Pl Translation using Googletrans API

## 📌 Project Overview  
This project demonstrates the **translation of 1000 Hindi words into English** using the **Google Translate API** via the `googletrans` library. The project automates the translation process, making it efficient and scalable for large datasets.  

**Input**: 1000 Hindi words  
**Output**: Translated English words  
**Library**: `googletrans`  

---

## 🚀 Key Features  
1. **Translation Automation**:  
   - The `googletrans` library is used to translate Hindi words into English.  
   - The library supports batch translation, making it efficient for large datasets. 

---

## 🔍 How It Works  
1. **Installation**:  
   - Install the `googletrans` library using pip:  
     ```bash
     pip install googletrans==4.0.0-rc1
     ```  
2. **Loading Hindi Words**:  
   - The 1000 Hindi words are loaded from a .csv file "hindi_names.csv".  
3. **Translation Process**:  
   - The `Translator` class from `googletrans` is used to translate each word.  
   - The translated words are displayed in a list or saved to a file.  
4. **Output**:  
   - The translated English words are displayed or saved for further use.  

---

## 🛠 System Requirements  
### Dependencies  
- Python 3.8+  
- Libraries: `googletrans`  
- Internet connection (required for API access)  

---

## 📄 License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  



#  Hair Disease Detection System

A **deep learning–based web application** that detects **hair and scalp diseases** from uploaded images and provides **personalized treatment recommendations**, including **products** and **Ayurvedic remedies**.

---

##  Features

*  **AI-Based Detection**
  Uses a trained **MobileNetV2 deep learning model** to classify hair/scalp conditions.

*  **Image Upload**
  Users can upload scalp or hair images for instant analysis.

*  **Disease Prediction**
  Predicts common hair conditions such as:

  * Dandruff
  * Alopecia
  * Scalp Psoriasis
  * Normal Hair

*  **Treatment Suggestions**
  Provides:

  * Medical recommendations
  * Ayurvedic remedies
  * Lifestyle advice

*  **Product Recommendations**
  Suggests relevant hair care products based on the detected condition.

*  **Visualization Support**
  Includes graphs and insights using Jupyter Notebook.

---

##  Tech Stack

* **Frontend:** Streamlit
* **Backend:** Python
* **Deep Learning:** TensorFlow / Keras
* **Model:** MobileNetV2
* **Libraries:**

  * NumPy
  * Pandas
  * Matplotlib
  * OpenCV

---

##  Project Structure

```
Hair_Disease_Detection/
│── MobileNetV2_hair_model.h5   # Trained deep learning model
│── fall.py                     # Main application file
│── graphs.ipynb                # Visualization notebook
│── products.csv                # Product recommendations dataset
│── ayurveda_remedies.csv       # Natural remedies dataset
│── README.md                   # Project documentation
```

---

##  Installation & Setup

###  Clone the Repository

```bash
git clone https://github.com/your-username/Hair_Disease_Detection.git
cd Hair_Disease_Detection
```

###  Install Dependencies

```bash
pip install -r requirements.txt
```

###  Run the Application

```bash
streamlit run fall.py
```

---

##  Model Details

* **Architecture:** MobileNetV2
* **Input:** Scalp/Hair Images
* **Output:** Disease classification
* **Accuracy:** (Add your accuracy here if available)

---

##  Dataset

* Custom dataset of hair/scalp images
* Includes labeled classes for different conditions
* Preprocessed for training using image augmentation techniques

---

##  Future Enhancements

*  Improve model accuracy with larger datasets
*  Mobile app integration
*  Deploy on cloud (AWS / Azure / GCP)
*  Add chatbot for hair care guidance

---

##  Contributing

Contributions are welcome!
Feel free to fork this repository and submit a pull request.

---

##  License

This project is licensed under the **MIT License**.

---

##  Author

**Aasritha Tummalapalli**

---


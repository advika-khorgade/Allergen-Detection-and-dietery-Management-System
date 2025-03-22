
# Allergen Detection & Dietary Assistance System

## ML-Based Food Safety & Calorie Management Solution

### Overview
This project is an AI-powered food safety assistant that helps users identify allergens in food, suggests safer alternatives, provides calorie insights, and recommends allergy specialists. The system is built using Machine Learning (**XGBoost, TF-IDF**) and an interactive **Gradio UI** for accessibility.

### Features
- **Allergen Detection** – Identifies if a dish contains a specific allergen.
- **Alternative Ingredients** – Suggests safer substitutes for allergenic ingredients.
- **Safe Dish Recommendations** – Provides a list of dishes without the selected allergen.
- **Calorie Management** – Checks if a dish fits within a user’s calorie limit and suggests alternatives.
- **Allergy Specialists** – Displays a list of expert doctors specializing in food allergies.
- **AI Model Integration** – Uses **XGBoost & TF-IDF** for accurate allergen detection.
- **User-Friendly UI** – Multi-page **Gradio web app** with dropdown selections.

---

## Tech Stack
- **Machine Learning:** XGBoost, TF-IDF, Scikit-learn
- **Dataset:** Custom-built dataset of **200+ Indian dishes** with ingredients, allergens & calories
- **Frontend:** Gradio (for UI)
- **Backend:** Python, Pandas, NumPy
- **Deployment:** Google Colab

---

## Dataset Structure
The dataset contains **200+ Indian dishes** with the following fields:

| Column Name           | Description                                      |
|----------------------|------------------------------------------------|
| **Food Item**        | Name of the dish                               |
| **Ingredients**      | List of ingredients used in the dish          |
| **Allergens**        | Common allergens present (if any)             |
| **Alternative Ingredients** | Suggested non-allergenic substitutes |
| **Calories**         | Caloric content of the dish                   |

---

## Machine Learning Model

### 1️⃣ Data Processing
- **TF-IDF Vectorization** for feature extraction from text-based ingredients.
- **Target variable:** Allergen Presence (**1 = Yes, 0 = No**).

### 2️⃣ Model Training
- **XGBoost Classifier** trained with an **80-20 train-test split**.
- **Evaluated using accuracy score.**
- **Final Accuracy:** **97%-98%**.

---

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/allergen-detection.git
   cd allergen-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Gradio UI:
   ```bash
   python app.py
   ```
4. Upload a food image or enter ingredients to check for allergens!

---

## Deployment
The project can be deployed using **Google Colab**. Open the notebook and run the cells to use the model.

---

## Contributing
Feel free to contribute by submitting issues or pull requests.

---

## License
This project is licensed under the MIT License.
![image](https://github.com/user-attachments/assets/84f5843c-93a9-4a28-994c-930d52cf8f17)
![image](https://github.com/user-attachments/assets/a34dee59-c8c1-4f6d-aeb6-e27c8cdb639f)
![image](https://github.com/user-attachments/assets/979a6795-ab16-4146-b73e-15dac7d6bef6)




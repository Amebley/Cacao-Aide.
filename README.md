
🚀 **Cacao-Aide**
*A Cocoa Yield Prediction and Farm Management System*

Cacao-Aide is a web-based application designed to support cocoa farmers by combining technology with agriculture. The system predicts cocoa yield, answers frequently asked questions, manages farm records, and provides valuable farming tips and information.

### 🔑 Key Features

* **Yield Prediction** – Predict cocoa yield based on farmer inputs, and receive tailored farming recommendations.
* **Farm Record Management** – Track farm diaries, inventory, and transactions in one place.
* **User Authentication** – Secure login, registration, and profile updates.
* **Chatbot** – Get instant answers to FAQs about cocoa farming.
* **Flash Messages** – Receive notifications on updates and user actions.
* **Tips & Insights** – Access practical cocoa farming tips aligned with yield predictions.

### ⚙️ Tech Stack & Prerequisites

* **Python 3.7+**
* **Flask**
* **SQLite** (for database)
* **Virtual Environment** (recommended)

### 🛠️ Setting Up Locally

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Amebley/Cacao-Aide.git  
   cd Cacao-Aide
   ```

2. **Set Up Virtual Environment (Optional)**

   ```bash
   pip install virtualenv  
   virtualenv venv  
   # Activate  
   venv\Scripts\activate   # Windows  
   source venv/bin/activate # Mac/Linux  
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Initialize the Database**

   ```bash
   flask shell  
   from models import db  
   db.create_all()  
   exit()
   ```

5. **Run the App**

   ```bash
   flask run
   ```

   Open [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

### 📌 Usage

* Register/login and update user details.
* Use the yield prediction system for insights and recommendations.
* Access cocoa farming tips and helpful resources.
* Add, view, edit, or delete farm diaries, inventories, and transactions.
* Read articles and tutorials on cocoa cultivation.

### 🐞 Troubleshooting

* **Database errors** – Ensure `users.db` is created and initialized correctly.
* **Model loading** – Verify that `cocoa_yield_model.pkl` exists in the root directory.
* **Static files** – Confirm CSS and images are placed in the `/static` folder.

💡 For support or inquiries: **[amebleyk@gmail.com](mailto:amebleyk@gmail.com)**
🔗 GitHub Repo: [Cacao-Aide](https://github.com/Amebley/Cacao-Aide)

# **Synthia** – An AI Dashboard Project

 **A modern, minimal, and customizable interface for AI-driven applications.**  

---

## ✨ Overview
**Synthia** is a prototype AI dashboard that guides users from a **Splash Screen** to **Login**, then into an **AI Dashboard** featuring a **sidebar** and **chat box**. It’s built with **HTML**, **CSS**, and **Bootstrap 5**, designed for easy customization and future integration with real AI functionalities.


---

## 💡 Key Features
- **Splash Screen**: A welcoming or loading screen for branding.  
- **Login Page**: Simple email/password authentication (placeholder).  
- **AI Dashboard**:
  - **Sidebar (Slide Bar)**:
    - *Search Chat History*: Retrieve previous conversations.  
    - *History*: View a chronological list of past sessions.  
    - *Save*: Store the current chat or session.  
    - *New Chat*: Start a fresh conversation.  
    - *Profile*: Manage user details (Name, etc.).  
    - *Delete All Chat*: Clear stored conversations.  
    - *Logout*: End the session.  
  - **Chat Box**:
    - *Enter Message*: Send text prompts to the AI.  
    - *Upload*: Attach files or data.  
    - *Download*: Export the conversation or session logs.

---

## 🛠️ Technologies Used

✔️ **Laravel 12** – Robust framework for backend development.  
✔️ **Laravel Fortify** – For user authentication management.  
✔️ **Laravel Socialite** – For social network login.  
✔️ **Livewire** – For real-time dynamic updates.  
✔️ **MySQL** – Database for managing products and users.  
✔️ **PHP** – Server-side scripting language.  
✔️ **HTML5 & CSS3** – For website markup and styling.  
✔️ **Bootstrap 5** – For a responsive and modern interface.  
✔️ **OpenAI** – Powers the AI chatbot.    

---


## 👅 Installation & Setup

Follow these steps to set up and run the project locally:

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/MaDGiiRL/SYNTHIA_AI-ASSISTANT
cd SYNTHIA_AI-ASSISTANT
```

### 2️⃣ Install Dependencies  
```bash
composer install
npm install
```

### 3️⃣ Generate the Key 
```bash
php artisan key:generate
```

### 4️⃣ Configure the Environment  
Rename `.env.example` to `.env` and set up your database credentials:  
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

Set your **OpenAI API Key**  in `.env`:  
```env
OPENAI_API_KEY=your_openai_api_key
OPENAI_ORGANIZATION=your_openai_organization_id

```

### 5️⃣ Run Migrations & Seed Database  
```bash
php artisan migrate --seed
```

### 6️⃣ Start the Development Server  
```bash
php artisan serve
```

Now open **http://127.0.0.1:8000/** in your browser to explore the website ὣA.

---

## 💡 Contributions & Improvements

Have suggestions? Want to contribute? Feel free to **submit a pull request** or open an **issue**! 🚀
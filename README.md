# 🎉 Automated Birthday Wisher

A Python script that automatically sends personalized birthday emails to your friends and family when it's their special day!

## 📋 Table of Contents
- [Features](#-features)
- [Prerequisites](#-prerequisites)
- [Setup](#-setup)
- [Usage](#-usage)
- [File Structure](#-file-structure)
- [Customization](#-customization)
- [Contributing](#-contributing)
- [License](#-license)

## ✨ Features
- Automated birthday detection
- Random selection from multiple email templates
- Personalized email content
- Simple CSV-based contact management
- Secure SMTP email sending

## 🛠 Prerequisites
- Python 3.x
- pip package manager
- An email account with SMTP access

## 🚀 Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/birthday-wisher.git
   cd birthday-wisher
   ```

2. Install dependencies:
   ```bash
   pip install pandas
   ```

3. Configure your email settings in `main.py`:
   ```python
   MY_EMAIL = "your.email@example.com"
   MY_PASSWORD = "yourpassword"
   SMTP_ADDRESS = "smtp.example.com"  # e.g., smtp.gmail.com for Gmail
   ```

4. Enable "Less secure app access" in your email account settings if required.

## 📅 Usage
1. Add birthdays to `birthdays.csv` in the format:
   ```csv
   name,email,year,month,day
   John Doe,john@example.com,1990,05,20
   ```

2. Run the script:
   ```bash
   python main.py
   ```

3. The script will automatically check for birthdays and send emails when it's someone's special day!

## 📂 File Structure
```
birthday-wisher/
├── main.py                # Main script
├── birthdays.csv           # Birthday database
├── letter_templates/       # Email templates
│   ├── letter_1.txt
│   ├── letter_2.txt
│   └── letter_3.txt
└── README.md
```

## 🎨 Customization
- **Templates**: Edit the files in `letter_templates/` to change the email content
- **Subject Line**: Modify the subject line in `main.py`
- **Schedule**: Set up a cron job or scheduled task to run daily

## 🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

### How to use this README:
1. Copy the entire content above
2. Create a new file named `README.md` in your project directory
3. Paste the content
4. Make any necessary adjustments (like replacing "yourusername" with your actual GitHub username)
5. Commit and push to your GitHub repository

This README provides:
- Clean, professional formatting with emojis
- Clear section organization
- Detailed setup and usage instructions
- Visual file structure
- All the necessary information for users to understand and use your project

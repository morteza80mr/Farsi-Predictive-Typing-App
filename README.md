# Farsi Predictive Typing App  
**Efficient and Intelligent Farsi Text Prediction**  

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue.svg" alt="Python version">  
  <img src="https://img.shields.io/badge/Farsi%20Language-✔-green.svg" alt="Farsi Support">
  <img src="https://img.shields.io/badge/Autocomplete-Trie%20&%20GPT--2-orange.svg" alt="Autocomplete System">
  <img src="https://img.shields.io/badge/License-Apache%202.0-brightgreen.svg" alt="Apache License">
</div>

---

### 🌟 About the Project
Welcome to the **Farsi Predictive Typing App** repository! This project is an innovative typing application that combines a **trie-based autocomplete system** with the **HooshvareLab GPT-2 (gpt2-fa)** model for accurate and intelligent Farsi text prediction.

#### Key Features
- **Trie-Based Autocomplete**: Efficient, lightweight, and fast text lookup for Farsi words.
- **GPT-2 Integration**: Context-aware predictions leveraging the powerful Farsi adaptation of GPT-2 by HooshvareLab.
- **Farsi Language Support**: Designed specifically to improve typing efficiency and experience for Farsi users.

Learn more about GPT-2 (gpt2-fa):  
- [HooshvareLab GitHub](https://github.com/hooshvare/parsgpt)  
- [Hugging Face Model Page](https://huggingface.co/HooshvareLab/gpt2-fa)

---

### 🔧 Technologies & Tools
- **Programming Language**: Python (3.9+)
- **Machine Learning Model**: HooshvareLab GPT-2 (gpt2-fa)  
- **Data Structures**: Trie for efficient word lookups  

---

### 📚 Database Description

The trie-based autocomplete system relies on a structured database to provide efficient and accurate word suggestions. The database is a **SQLite** file containing a table named `word`, which stores Farsi words along with their usage frequencies. This data is critical for building the trie structure and prioritizing commonly used words.

#### Table Structure: `word`
- **`id` (INTEGER)**: A unique identifier for each word entry.
- **`word` (VARCHAR)**: The Farsi word stored in the database.
- **`count` (INTEGER)**: The frequency of the word's occurrence, indicating its popularity or usage frequency.

#### Sample Data
Here are a few examples of the data stored in the `word` table:
1. **`انوشه`**: Frequency 919
2. **`آسیه`**: Frequency 1974
3. **`ده‌سالگی`**: Frequency 489
4. **`به‌هم‌پیوستگی`**: Frequency 819

#### Usage in the Trie System
The `word` table's data is used to:
- Build the trie structure for fast and efficient lookups.
- Rank suggestions based on the frequency (`count`) to improve the relevance of predictions.

This database ensures that the autocomplete system is both accurate and optimized for Farsi text input.

---

### 🚀 Getting Started

#### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Farsi-Predictive-Typing-App.git
   cd Farsi-Predictive-Typing-App

---

### 🌟 Future Improvements

I am actively working to enhance the application! Here are some upcoming features and improvements:
- **Custom Dataset Support**: Allow users to add their Farsi text corpora for fine-tuning.
- **Mobile Compatibility**: Develop a mobile-friendly version of the application.
- **UI Enhancements**: Add a graphical interface for easier use.
- **Real-Time Suggestions**: Improve the speed and accuracy of text predictions.

Feel free to suggest more features by opening an issue in this repository.

---

### 📜 License

This project is licensed under the **Apache-2.0 License**. See the [LICENSE](LICENSE) file for details.

---

### 🙏 Acknowledgments

Special thanks to **HooshvareLab** for their development of the GPT-2 (gpt2-fa) model, which plays a vital role in providing intelligent and context-aware Farsi text predictions in this project. Visit their [GitHub repository](https://github.com/hooshvare/parsgpt) for more information on their work.

---

### 🤝 Contributions

Contributions are welcome! If you’d like to improve the app, feel free to fork the repository, create a pull request, or report issues.

---

### 💬 Contact

If you have any questions or feedback, feel free to reach out:

- **Project Maintainer**: [M.Mardani](mailto:mortezammm80@gmail.com)
- **GitHub Profile**: [My GitHub Profile](https://github.com/morteza80mr)

I appreciate your interest in the **Farsi Predictive Typing App** and look forward to your contributions!

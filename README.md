# 🎮 Quizz Bot 🤖

**Quizz Bot** is an interactive Telegram quiz bot designed to engage users with fun and challenging questions!  
Test your knowledge and track your scores in real-time.  

---

## 🌟 Features

* ❓ Multiple-choice quiz questions  
* 💾 Score tracking with SQLite  
* 📲 Easy-to-use Telegram interface  
* 🎉 Fun GIFs and animations  

---

## 🗂 Database Structure

The bot uses a simple SQLite database to store user progress:  

**Table: `quiz_state`**  
| Column          | Type    | Description                         |
|-----------------|---------|-------------------------------------|
| `user_id`       | INTEGER | Unique Telegram user ID             |
| `question_index`| INTEGER | Current question index for the quiz |
| `score`         | INTEGER | User's total score                  |

---

## 📂 Project Structure

* quiz_bot.db        # SQLite database (stores quiz state and user scores)  
* questions.ipynb    # Notebook with quiz questions or their generation  
* db.ipynb           # Notebook with database logic (create_table, update_score, etc.)  
* config.ipynb       # Configuration (bot token and settings)  
* bot.ipynb          # Main Telegram bot code (aiogram)  

---

## 💬 Bot Commands

* **/start** → Starts the bot and shows the welcome message with a button  
* **/quiz** or **Начать игру** → Starts a new quiz from the first question  
* Inline buttons → Answer options for each question  

---

## 🤖 Try it now!

Search for **[@miziquizzy_bot](https://t.me/miziquizzy_bot)** on Telegram and start playing!  
Let’s see how many questions you can get right! 🎉  


<img width="708" height="431" alt="image" src="https://github.com/user-attachments/assets/4ca40921-6c2f-4eec-8587-9f43f8df86e3" />


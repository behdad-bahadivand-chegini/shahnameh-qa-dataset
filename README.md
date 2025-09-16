# Shahnameh QA Dataset

A bilingual **question–answer dataset** based on Ferdowsi’s *Shahnameh*.  
It contains curated questions and answers in **Persian** and **English**, enriched with difficulty levels, question types, and thematic tags.  

This dataset is released into the **public domain (CC0 1.0 Universal)**, making it free for research, education, and creative projects without restriction.

---

## 📊 Dataset Overview
- **Rows:** 508  
- **Languages:** Persian (fa), English (en)  
- **Format:** CSV (UTF-8)  
- **License:** [CC0 1.0 Universal](./LICENSE)  

### Columns
| Column        | Description |
|---------------|-------------|
| `question_fa` | Question in Persian |
| `answer_fa`   | Answer in Persian |
| `question_en` | Question in English |
| `answer_en`   | Answer in English |
| `difficulty`  | Difficulty level (`Easy`, `Medium`, `Hard`) |
| `type`        | Question type (e.g. Historical, Mythological, Philosophical) |
| `tags`        | Comma-separated keywords (e.g. Jamshid, Zahhak, Wisdom) |

---

## 🚀 Example Entry
```json
{
  "question_fa": "جمشید چه نقشی در پیشرفت هنرها داشت؟",
  "answer_fa": "او صنایع و هنرهای گوناگون را پایه‌گذاری کرد.",
  "question_en": "What role did Jamshid play in the advancement of arts?",
  "answer_en": "He established various industries and arts.",
  "difficulty": "Medium",
  "type": "Historical",
  "tags": "Jamshid, Arts, Civilization"
}
📖 Usage
Clone Repository
git clone https://github.com/YOUR-USERNAME/shahnameh-qa-dataset.git

Load in Python
import pandas as pd

df = pd.read_csv("shahnameh-qa-dataset/shahnameh_qa_dataset.csv")
print(df.sample(3))
🔍 Potential Applications

Natural Language Processing (NLP): Question answering, translation, text classification.

Cultural & Literary Studies: Exploring themes, myths, and history of the Shahnameh.

AI Training: Multilingual QA models, educational chatbots, knowledge graphs.
🔖 License

This dataset is dedicated to the public domain under the
Creative Commons Zero v1.0 Universal
 license.

You are free to copy, modify, distribute, and use the dataset for any purpose, including commercial, without asking for permission.
🙌 Acknowledgment

Based on the timeless Persian epic Shahnameh by Ferdowsi,
created to support cultural, educational, and AI research initiatives.

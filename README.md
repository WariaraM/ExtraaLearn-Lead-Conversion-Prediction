# ExtraaLearn - Lead Conversion Prediction

This project analyzes lead data for ExtraaLearn, an EdTech startup, to identify which leads are most likely to convert into paying customers. Using exploratory data analysis and machine learning, we aim to support marketing and sales teams in prioritizing efforts and improving conversion rates.

## 🚀 Objectives

- Predict likelihood of lead conversion using machine learning
- Identify key factors influencing conversion
- Build a lead profile for more effective targeting

---

## 📚 Data Dictionary

| Feature | Description |
|--------|-------------|
| `ID` | Unique identifier for each lead |
| `age` | Age of the lead |
| `current_occupation` | Current occupation: 'Professional', 'Unemployed', or 'Student' |
| `first_interaction` | First platform used by the lead: 'Website' or 'Mobile App' |
| `profile_completed` | Percentage of profile completed: Low (0–50%), Medium (50–75%), High (75–100%) |
| `website_visits` | Number of times the lead visited the website |
| `time_spent_on_website` | Total time spent on the website |
| `page_views_per_visit` | Average number of pages viewed per website visit |
| `last_activity` | Most recent interaction type (Email, Phone, or Website activity) |
| `print_media_type1` | Flag: Saw ad in a newspaper |
| `print_media_type2` | Flag: Saw ad in a magazine |
| `digital_media` | Flag: Saw ad on a digital platform |
| `educational_channels` | Flag: Heard about ExtraaLearn on educational forums or platforms |
| `referral` | Flag: Heard about ExtraaLearn through a reference |
| `status` | Converted to paid customer (1) or not (0) |

---

## 📈 Insights

- Unemployed and professional users are mostly middle-aged, while students are younger.
- Most users show moderate engagement with the website.
- Students and unemployed individuals have higher page views per visit.
- Digital media is a more frequent source than print media; print media is rarely used.

---

## 🎯 Recommendations

- Launch age-specific campaigns tailored for middle-aged professionals and younger students.
- Investigate behaviors of highly engaged users and replicate their traits across broader segments.
- Personalize content to re-engage users with lower activity or profile completion.

---

## 🔍 Full Analysis

For complete data exploration, feature engineering, and model training, see:  
📎 [`ExtraaLearn-Lead-Conversion-Analysis.ipynb`](ExtraaLearn-Lead-Conversion-Analysis.ipynb)

---

*Project developed as part of a data science portfolio. Created by Angel Wariara Mugo.*

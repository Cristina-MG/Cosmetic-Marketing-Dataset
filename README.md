# Cosmetic Marketing Dataset

[![Download Dataset](https://img.shields.io/badge/Download-Dataset-blue?style=for-the-badge&logo=github)](https://github.com/Cristina-MG/Cosmetic-Marketing-Dataset/releases/download/v1.0/cosmetic-marketing-dataset.xlsx)
![GitHub release downloads](https://img.shields.io/github/downloads/Cristina-MG/Cosmetic-Marketing-Dataset/v1.0/total?color=green&style=for-the-badge)

A fictional dataset created for educational and portfolio purposes, designed to simulate real-world cosmetic marketing data.  
It includes information about customers, products, reviews, customer journeys, and engagement metrics across multiple channels.

📌 **Note**: All data is entirely fictional and was generated solely for learning and demonstration purposes. It does not represent real individuals or companies.

⚠️ Disclaimer: This is a simplified sample of the dataset I originally used for my Power BI project.
It contains enough structure and variety (customers, products, reviews, journeys, and engagement) to practice data modeling, DAX, and dashboard creation.

---

## 📂 Dataset Structure

The dataset is provided as an Excel file (`cosmetic-marketing-dataset.xlsx`) with multiple sheets, one for each table:

### 🧍 Customers
| Column          | Description                     |
|----------------|---------------------------------|
| CustomerID      | Unique customer identifier       |
| CustomerName    | Customer full name               |
| email            | Anonymized email address         |
| Gender           | Gender (Male/Female)             |
| Age               | Age in years                     |

---

### 💻 Journeys
| Column         | Description                          |
|---------------|--------------------------------------|
| JourneyID       | Unique journey identifier             |
| CustomerID      | Related customer                     |
| ProductID        | Related product                      |
| VisitDate         | Date of the visit (dd/mm/yyyy)       |
| Stage              | Journey stage (Homepage, Checkout, ProductPage) |
| Action             | Action taken (Click, View, Purchase, Drop-off)  |
| Duration           | Time on page (seconds)               |

---

### 📣 Engagement
| Column         | Description                          |
|---------------|--------------------------------------|
| EngagementID    | Unique engagement identifier           |
| ProductID           | Related product                         |
| ContentType          | Type (Blog, Video, Social Media, Newsletter) |
| Views                     | Number of views                       |
| Clicks                     | Number of clicks                      |
| Likes                        | Number of likes                         |
| EngagementDate              | Date (dd/mm/yyyy)                          |

---

### 💅 Products
| Column         | Description                          |
|---------------|--------------------------------------|
| ProductID          | Unique product identifier                |
| ProductName         | Product name                                 |
| Category               | Product category (Fragrances/Makeup)      |
| CommercialName          | Fictional marketing name                       |
| Price                         | Price in €                                           |

---

### ⭐ Reviews
| Column         | Description                          |
|---------------|--------------------------------------|
| ReviewID           | Unique review identifier                  |
| CustomerID         | Related customer                              |
| ProductID              | Related product                                   |
| ReviewDate                 | Date of the review (dd/mm/yyyy)                        |
| Rating                           | Rating from 1 to 5                                         |
| ReviewText                           | Review comment text                                           |
| SentimentCategory                           | Sentiment (Positive/Negative)                                             |

---

## 📥 Download

[![Download Dataset](https://img.shields.io/badge/Download-Dataset-blue?style=for-the-badge&logo=github)](https://github.com/Cristina-MG/Cosmetic-Marketing-Dataset/releases/download/v1.0/cosmetic-marketing-dataset.xlsx)

---

## 📊 Example Power BI Report

To showcase the potential of this dataset, here is an example dashboard built in **Power BI**:

### 🏠 Home Page
![Home Page](https://cristina-mg.github.io/assets/images/proyectos/Marketing-cosmetic/home.png)

### 📈 General Panel
![General Panel](https://cristina-mg.github.io/assets/images/proyectos/Marketing-cosmetic/P1.PNG)

### 🔄 Customer Conversion
![Customer Conversion](https://cristina-mg.github.io/assets/images/proyectos/Marketing-cosmetic/P2.PNG)

### 📣 Social Media Details
![Social Media Details](https://cristina-mg.github.io/assets/images/proyectos/Marketing-cosmetic/P3.PNG)

### ⭐ Customer Reviews
![Customer Reviews](https://cristina-mg.github.io/assets/images/proyectos/Marketing-cosmetic/P4.PNG)

---

### 📱 Mobile Version (GIF)
![Mobile Dashboard](https://cristina-mg.github.io/assets/images/proyectos/Marketing-cosmetic/App-Essenza.gif)  
<br>
*Optimized mobile layout for quick access to key metrics.*


 
---

🔗 [Example Dashboard on Power BI Gallery](https://community.fabric.microsoft.com/t5/Data-Stories-Gallery/Dashboard-de-Engagement-y-Satisfacci%C3%B3n-del-Cliente/td-p/4820550)

---

## 📊 How to Use
- This dataset can be used to practice **data modeling**, **data visualization**, **Power BI reports**, **marketing analytics** or **customer behavior analysis**.
- It is especially suitable for creating dashboards that combine product sales, customer reviews, marketing engagement and journeys.

---

## 📎 License
This dataset is released under the [MIT License](LICENSE).  
Feel free to use it for educational and non-commercial purposes.

---

## 🌐 Author
Created by **Cristina Martínez García**  
🔗 [LinkedIn](https://www.linkedin.com/in/cristina-mart%C3%ADnez-garc%C3%ADa-data/)  
🌐 [Portfolio](https://cristina-mg.github.io/)  
📊 [Example Dashboard on Power BI Gallery](https://community.fabric.microsoft.com/t5/Data-Stories-Gallery/Dashboard-de-Engagement-y-Satisfacci%C3%B3n-del-Cliente/td-p/4820550)

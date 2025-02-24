# 📊 YouTube Influencer Insights: Trends, Engagement, and Growth  

**Author:** Raunaq Sinha  
**Date:** 25-02-2024  
**Course:** *The Art of Storytelling with Data*  
**Tool Used:** Tableau  

---

## 📌 Project Overview  
This project analyzes **YouTube influencer data** to uncover trends in content categories, follower growth, global reach, and branding impact. Using **Tableau**, we visualize key insights into how different factors influence a channel's popularity and engagement.

---

## 📊 Key Visualizations  
The **interactive dashboard** consists of four main visualizations, each focusing on a different aspect of **YouTube growth**:

### 1️⃣ **Top YouTube Content Categories by Followers (Treemap)**  
✅ Identifies the most **popular** content categories.  
✅ Helps understand which content **types attract the largest audiences**.  
![Screenshot 2025-02-25 015844](https://github.com/user-attachments/assets/96399cba-f763-4b1e-b8b1-7a7bb4277e05)


### 2️⃣ **YouTube Follower Growth Trends (Line Chart)**  
✅ Analyzes **follower growth trends** over time using `join_date`.  
✅ Uses a **moving average** to highlight key growth periods.
![Screenshot 2025-02-25 025651](https://github.com/user-attachments/assets/d7f6ae42-30e0-4b22-b530-cf69a197ff36)


### 3️⃣ **Global Distribution of YouTube Followers (Map)**  
✅ Displays the **geographic reach** of top YouTube influencers.  
✅ Highlights **countries with the highest concentration** of major channels.  
![Screenshot 2025-02-25 022701](https://github.com/user-attachments/assets/638251de-08cd-4110-a6e4-02bc882fed22)


### 4️⃣ **Branding & Followers: Do Content Styles Matter? (Bubble Chart)**  
✅ Displays a **packed bubble chart representing various YouTube channels**.  
✅ Uses **color and size** to indicate follower counts and branding influence.  
✅ Helps understand **the impact of different branding styles on channel success**.  
![Screenshot 2025-02-25 024905](https://github.com/user-attachments/assets/d0a1bae0-d152-446e-a6f2-afeac77e427e)


---

## 📌 Data Source & Cleaning  
The dataset used in this analysis was provided in **`channels.csv`**, containing structured data about **YouTube influencers**.  

### **Data Preprocessing Steps:**  
✔ **Removed unnecessary columns** (`picture_url`, `profile_url`, `trailer_url`).  
✔ **Converted** `join_date` **to a proper date format**.  
✔ **Handled missing values** in `country` by replacing them with **"Unknown"**.  
✔ **Created** a `channel_age` **field for additional analysis**.  

---

## 📊 Key Insights & Takeaways  

### 📌 1️⃣ Entertainment & Music Dominate YouTube  
🎵 The **Entertainment** and **Music** categories have the **highest follower counts**.  
🎮 **Gaming & How-To** content are **rapidly gaining traction**.  

### 📌 2️⃣ Older Channels Have an Advantage, But Newer Ones Grow Fast  
📅 Channels founded **before 2010** still dominate the platform.  
📈 However, **post-2015 channels** are **growing at an accelerated rate**.  

### 📌 3️⃣ YouTube is a Global Platform  
🌍 **The US, India, and parts of Europe** have the **highest concentration of influencers**.  
📊 **Asia & Latin America** are **emerging markets** for content growth.  

### 📌 4️⃣ Branding & Descriptions Matter for Engagement  
📝 **The packed bubble chart highlights different branding styles and their follower impact**.  
💡 **Well-branded channels tend to experience consistent follower growth**.  

---

## 📌 How to View the Dashboard  
To explore the insights, follow these steps:  

1️⃣ **Open the Tableau file**: `YouTube_Influencer_Insights.twbx`  
2️⃣ **Navigate through the four key visualizations**.  
3️⃣ **Use the interactive filters** (category & country) to explore trends dynamically.  
![Screenshot 2025-02-25 031750](https://github.com/user-attachments/assets/e9f60371-0687-4147-b17e-402dc2a3e8e8)


---

## 📌 Conclusion  
This project takes a **data-driven approach** to analyze **YouTube influencer growth trends**, highlighting key factors that contribute to a channel's **success and engagement**.  

By leveraging **Tableau's interactive features**, we can explore **trends in content strategy, branding, and global reach**, helping content creators and marketers optimize their **YouTube growth strategies**.  

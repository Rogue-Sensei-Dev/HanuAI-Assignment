# 📑 Report

# Final Report on Customer Reviews Analysis
This report summarizes the analysis of customer reviews for a laptop, highlighting key insights, challenges faced during data scraping, and recommendations for product improvement. It is structured to give a clear view of customer sentiments, product performance, and actionable next steps for future enhancements.

---

### 1. Suggested solution for scraping challenges

When scraping, I noticed some websites block automated traffic. This can happen  
due to sending too many requests or patterns that look like bots. To  
mitigate these issues:  
- Use **rotating proxies** so that requests come from multiple IPs instead of one.  
- If the site uses **CAPTCHA**, tools like `2captcha` or `anticaptcha` can help bypass, though setup may be tricky.  
- Add **retry mechanisms** so that failed requests don’t halt the process.  
- Insert **random delays** and headers (e.g., user-agent strings) to make requests look more like human browsing.  

In short, anti-scraping countermeasures can be handled by spreading traffic, mimicking human behavior, and building resilient retries.

---

### 2. Business Context

From the reviews dataset we analyzed, here are the main findings:

- **Top drivers of customer satisfaction:**  
  - Many users praised the laptop for being **lightweight and portable**.  
  - Customers liked its **long battery life** and **fast performance**.  
  - The **display quality** (brightness, clarity, color accuracy) stood out as a major positive.  
  - Several reviews mentioned it was **good value for money** and earned high ratings.  

- **Top drivers of dissatisfaction:**  
  - Some users found the **fans noisy** during heavy workloads.  
  - Others noted the **keyboard felt cramped** or uncomfortable for long typing sessions.  
  - A few reviews mentioned **thermal throttling** or heating issues.  
  - Price was also a recurring concern for higher-end configurations.  

- **Recommendations for improvement:**  
  - Enhance **cooling design** to manage heat and fan noise better.  
  - Refine the **keyboard layout and comfort**, especially for frequent typists.  
  - Consider **more affordable variants** or bundle offers to address price sensitivity.  
  - Continue investing in **battery life and display quality**, since customers value these most.  

---

### Key Learnings & Improvements

- I learned that text mining can automatically surface product aspects like *“battery life”* and *“keyboard comfort”*, which proved very insightful.  
- One improvement would be to refine the aspect extraction process, since irrelevant terms sometimes appeared.  
- With a larger review set, **clustering** could reveal customer personas (e.g., students, professionals, gamers).  
- Overall, the analysis shows how customer feedback directly informs design tweaks and feature prioritization.  

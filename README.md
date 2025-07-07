# 📊 Optimizing Creative Strategy through EDA: Data-Driven Insights for Infosys' Social Media Campaigns

This repository presents an end-to-end exploratory and multivariate data analysis of historical social media performance metrics to generate **actionable content strategies for Infosys**. Using a structured, data-driven approach, we analyze how visual and textual creative elements affect engagement rates, ultimately informing more impactful digital marketing campaigns.

Developed by **Purushottam Mitra** as part of an Entrepreneur-in-Residence Internship assignment with Rocketium.

> 📌 **Final Report**: [`REPORT(EDA_INSIGHTS_REC).pdf`](./REPORT(%20EDA_INSIGHTS_REC%20).pdf)  
> 🎞️ **Slide Deck**: [`Presentation.pptx`](./Presentation.pptx)  
> 📒 **Jupyter Notebook**: [`Complete_EDA_Insights_Content_stategy.ipynb`](./Complete_EDA_Insights_Content_stategy.ipynb)

---

## 🧠 Project Objective

To analyze creative parameters—like image content, color, number of people, text length, face emotion, and post topic—and understand their impact on social media engagement. The ultimate goal is to help **Infosys**:

- Optimize visual content for higher engagement
- Target strategic topics that resonate with the audience
- Craft actionable insights based on historical performance data

---

## 🧾 Dataset Overview

The dataset contains metadata from **Infosys and competitor Twitter posts**, including both **performance metrics** and **creative attributes**:

| Category            | Fields                                                                 |
|---------------------|-------------------------------------------------------------------------|
| Performance Metrics | Views, Likes, Comments, Shares, Total Engagements, Engagement Rate %    |
| Visual Attributes   | No. of Faces, Face Area %, Face Emotion, Dominant Color, Objects, Logos |
| Textual Attributes  | Post Content, Text Length, CTA                                          |
| Contextual Data     | Post Date, Post Topic, Company                                          |

> 📥 Data Source: [`Rocketium EIR Internship Assignment.xlsx`](./Rocketium%20EIR%20Internship%20Assignment.xlsx)

---

## 📊 Analysis Techniques Used

| Technique                            | Purpose |
|-------------------------------------|---------|
| **Univariate and Bivariate EDA**    | Understand data distribution and relationships |
| **Correlation Matrix + Heatmap**    | Identify high-impact variables |
| **Pairplots**                       | Explore variable interactions |
| **Text Analytics (Length, CTA)**    | Assess impact of copywriting |
| **Visual Attribute Profiling**      | Segment performance by colors, faces, emotions |
| **Topic vs. Engagement Mapping**    | Reveal high-performing content themes |
| **Benchmarking vs Competitors**     | Position Infosys in industry context |

---

## 📈 Key Insights

### 🔹 Engagement Drivers
- **Views, Likes, Comments** are highly correlated with **Total Engagements** and **Engagement Rate %**.
- **Face Emotion** (especially Joy) increases interaction; Number of Persons has minimal impact.
- **Post Topic**: “Leadership” and “Brand” drive the highest engagement.
- **Dominant Color**: Bright colors (reds, yellows) improve visibility and interaction.
- **Text Length**: Overly long content has low correlation; concise, value-driven text works better.

### 🔹 Creative Attribute Impact (Top 5 Takeaways)
| Factor              | Engagement Impact | Recommendation |
|---------------------|-------------------|----------------|
| Bright Colors       | 🔺 High            | Use warm/contrasting brand-aligned colors |
| Joyful Faces        | 🔺 Moderate        | Prioritize happy facial expressions |
| Post Topic (Leadership, Brand) | 🔺 High    | Focus content calendar on these themes |
| Text Length         | 🔻 Low             | Keep messages brief, focused, and engaging |
| Face Count          | ⚠️ Negligible      | Prioritize content over number of people in image |

---

## 📣 Strategy Recommendations for Infosys

### ✅ Optimize for High Visibility
- Use **trending hashtags** and **engaging visuals** to boost reach
- Post at peak audience activity times (based on historical data)
- Use **cross-promotion** with influencers or sister brands

### ✅ Encourage Interactions
- Add compelling **CTAs** and interactive elements (polls, Q&A)
- Promote **user-generated content** to build community trust

### ✅ Design Better Visuals
- Showcase **diverse faces** with **positive emotion**
- Maintain **consistent brand colors** with high contrast
- Use **logos** subtly for recall, not clutter

### ✅ Innovate Content Format
- Rotate between static images, videos, infographics, carousels
- Test emerging formats (AR filters, 3D, interactive stories)

### ✅ Monitor & Adapt
- Perform regular **A/B testing** on visual attributes
- Track performance via analytics and **refine based on data**

---

## 🗂️ Project Structure

EDA_Content_Strategy_Infosys/
│
├── Complete_EDA_Insights_Content_stategy.ipynb # Jupyter Notebook for EDA
├── REPORT( EDA_INSIGHTS_REC ).pdf # Final insights and strategy report
├── Project_Objectives.pdf # Assignment brief
├── Presentation.pptx # Strategy presentation
├── Rocketium EIR Internship Assignment.xlsx # Dataset (Infosys + competitors)
├── README.md # Project documentation
└── /assets # (Optional) Visuals & charts

yaml
Copy
Edit

---

## 🛠 Tools & Technologies

| Tool            | Role                               |
|-----------------|------------------------------------|
| **Python (Pandas, Seaborn, Matplotlib)** | Data wrangling and visual analytics |
| **Jupyter Notebook** | Interactive EDA and documentation |
| **Excel / CSV** | Initial dataset exploration         |
| **PowerPoint**  | Final presentation & business summary |
| **PDF Reports** | Stakeholder-ready documentation     |

---

## 📊 Visual Examples (Optional)

Include key visuals from your EDA in the `/assets/` directory for GitHub preview.

| Insight | Sample |
|--------|--------|
| Correlation Heatmap | ![heatmap](./assets/correlation_heatmap.png) |
| Topic vs Engagement | ![topics](./assets/topic_engagement.png) |
| Color vs Engagement | ![colors](./assets/color_engagement.png) |

---

## 👤 Author

**Purushottam Mitra**  
📧 Email: pmitra620@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/yourprofile)  
🗂️ Portfolio: [yourportfolio.com](https://yourportfolio.com)

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for full details.

---

## 🙌 Acknowledgements

- Infosys (for context)
- Rocketium for the assignment framework
- Matplotlib & Seaborn for data visualization
- Neil Patel (reference: Digital Marketing Concepts)

---

## ⭐ Show Your Support

If you found this project insightful:

- 🌟 Star this repository
- 🧠 Use it to guide your next content strategy
- 🔗 Connect and share feedback

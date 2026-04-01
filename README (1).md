# Employee Attendance Workflow (n8n + Google Sheets)

## 📌 Overview
This project automates employee attendance tracking and performance categorization using **n8n** workflows integrated with **Google Sheets**.  
It enables HR teams and organizations to monitor attendance, classify employees into categories, and evaluate performance in real time with minimal manual effort.

---

## ⚙️ Features
- 🔄 **Google Sheets Trigger** to fetch employee data automatically
- 📊 Attendance categorization:
  - **High** (Days Present > 22)
  - **Medium** (15–22 Days Present)
  - **Low** (Days Present < 15)
- 🏆 Performance classification:
  - **High Performer** (Tasks Completed > 15)
  - **Average** (Tasks Completed ≥ 10)
  - **Low Performer** (Tasks Completed < 10)
- 📝 Appends processed results into a separate sheet (`Processed_Data`)
- ⏱ Real-time automation with every-minute polling

---

## 🚀 Technologies Used
- **n8n** → Workflow automation platform
- **Google Sheets** → Data storage and reporting
- **OAuth2 API** → Secure authentication for Google Sheets
- **JSON** → Workflow configuration and portability
- **Cloud Integration** → Enables scalable and remote execution

---

## 🌟 Future Benefits for HR & Company
- 📈 **Data-Driven HR Decisions**: Provides clear insights into employee attendance and productivity trends.
- ⏱ **Time Savings**: Automates repetitive HR tasks, reducing manual data entry and reporting.
- 🎯 **Performance Management**: Helps identify high performers and employees needing support.
- 🤝 **Fair Evaluation**: Ensures transparent categorization based on objective metrics.
- 💡 **Scalability**: Can be extended to track larger teams or integrated with payroll and performance review systems.
- 📊 **Better Forecasting**: Enables HR to predict absenteeism patterns and plan workforce allocation.
- 🌍 **Remote-Friendly**: Works seamlessly with cloud-based tools, supporting hybrid and remote work models.

---

## 🗂 Workflow File
- `My workflow 5 (1).json` → Import this file into **n8n** to run the workflow.

---

## 📊 Example Output
- Attendance categories: **High**, **Medium**, **Low**
- Performance categories: **High Performer**, **Average**, **Low Performer**
- Data appended to `Processed_Data` sheet for visualization and dashboards.

---

## 📸 Dashboard Preview
Here’s a preview of the dashboard generated from the workflow:

![Employee Attendance Tracker](attachments/ATud1Bbbc6zhHWoeLo3KY.png)

---

## 👩‍💻 Author
Created by **Himani**  
MBA HR student specializing in HR analytics and workflow automation.  
Passionate about integrating business concepts with automation tools like **n8n**, **Google Sheets**, and **Cloud workflows**.

---

## 📜 License
This project is open-source. You are free to use, modify, and share with attribution.

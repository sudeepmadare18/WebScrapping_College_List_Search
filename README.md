# College List Search

A Streamlit-based web application that helps users search and view college details such as **College Name, Location, Course, Fees, Rating, and Website**.  
The college data is collected using **Web Scraping** and managed using **Pandas**.

---

# 🌐 Streamlit Application Link

You can access the College List Search application using the link below:



> Note: Replace `YOUR_STREAMLIT_APP_LINK` with your actual deployed Streamlit application URL.

Example:

[Click Here to Open the Streamlit App](https://pragyanaipythonprojectcollegelist-vqf79nuzduovgzphiua4gy.streamlit.app/)

---

# 📌 Project Overview

College List Search is a web-based application developed using **Streamlit** and **Pandas**.  
College details are collected from websites using **Web Scraping** and stored in a structured dataset.

Users can search colleges by name or location and view details such as courses, fees, ratings, and official website links in one place.

---

# 🚀 Features

- Search colleges by name or location
- View college details such as course, fees, rating, and website
- Web scraping-based data collection
- Store college data in CSV format
- Filter colleges based on user search
- Display college details in table format
- Provide official college website links
- Simple and interactive Streamlit interface

---

# 🛠️ Tools and Technologies Used

| Tool / Technology | Purpose |
|---|---|
| **Streamlit** | Used to build the interactive web application |
| **Pandas** | Used for data cleaning, filtering, and displaying college records |
| **Web Scraping** | Used to extract college data from websites |
| **Requests** | Used to send HTTP requests and fetch webpage content |
| **BeautifulSoup** | Used to parse HTML and extract college details |
| **Python** | Main programming language |
| **CSV Dataset** | Used to store scraped college data |
| **College Website Link** | Used to open the official college website |

---

# 📂 College Dataset

The college dataset contains the following columns:

| Column Name | Description |
|---|---|
| College Name | Name of the college or university |
| Location | City or state of the college |
| Course | Courses offered by the college |
| Fees | Course or annual fees |
| Rating | College rating |
| Website | Official website link |

---

# 📄 Sample Dataset

```csv
College Name,Location,Course,Fees,Rating,Website
ABC College,Bengaluru,B.Tech CSE,150000,4.5,[https://www.abccollege.com](https://www.abccollege.com)
XYZ University,Mumbai,BBA,90000,4.2,[https://www.xyzuniversity.com](https://www.xyzuniversity.com)
PQR Institute,Delhi,B.Sc Computer Science,75000,4.0,[https://www.pqrinstitute.com](https://www.pqrinstitute.com)
```

---

# 🕸️ Web Scraping Process

1. Select the college-related website.
2. Send an HTTP request using the `Requests` library.
3. Fetch the webpage HTML content.
4. Parse the HTML using `BeautifulSoup`.
5. Extract college name, location, course, fees, rating, and website.
6. Store the extracted data in a Pandas DataFrame.
7. Save the data as a CSV file.

---

# 🖥️ Application Workflow

```text
College Websites
        ↓
Web Scraping using Requests and BeautifulSoup
        ↓
Data Cleaning using Pandas
        ↓
College Dataset (CSV)
        ↓
Streamlit Web Application
        ↓
User Search / Filter
        ↓
College Details Display
        ↓
Official College Website Link
```

---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone [https://github.com/your-username/college-list-search.git](https://github.com/your-username/college-list-search.git)
cd college-list-search
```

## 2. Install Required Libraries

```bash
pip install streamlit pandas requests beautifulsoup4
```

---

# 📁 Project Structure

```text
college-list-search/
│
├── app.py
├── requirements.txt
└── README.md
```

---

# ▶️ Run the Project

After installing the required libraries, run:

```bash
streamlit run app.py
```

Then open the generated local URL in your browser:

```text
http://localhost:8501
```

---

# 🔍 Search Example

**Search Input:**

```text
Bengaluru
```

**Output:**

Displays all colleges located in Bengaluru along with course, fees, rating, and website details.

---

# 📊 Example College Display

| College Name | Location | Course | Fees | Rating | Website |
|---|---|---|---|---|---|
| ABC College | Bengaluru | B.Tech CSE | ₹1,50,000 | 4.5 | [Visit Website](https://www.abccollege.com) |
| XYZ University | Mumbai | BBA | ₹90,000 | 4.2 | [Visit Website](https://www.xyzuniversity.com) |

---

# ✅ Advantages

- Provides college details in one centralized application
- Saves time compared to manual college searching
- Helps students compare colleges easily
- Displays college name, location, course, fees, rating, and website together
- Web scraping automates data collection
- Pandas makes data filtering and searching easy
- Simple and interactive Streamlit interface

---

# 🔮 Future Scope

- Add filters for city, course type, fees range, and rating
- Add college comparison feature
- Add placement and hostel details
- Add user reviews and ratings
- Add course-wise search
- Add map view for college locations
- Automatically update college data using scheduled scraping
- Add login and saved college preferences
- Deploy on Streamlit Community Cloud

---

# 🧪 Testing

The application was tested using scraped college data.

Test cases included:

- College search by name
- College search by location
- Course details display
- Fees and rating display
- Website link testing
- Pandas filtering
- Streamlit interface testing

---

# 📌 Conclusion

College List Search is a simple and useful web application that helps students search and view college details in one place.  
It uses web scraping to collect college data and Pandas to manage and display the information through an interactive Streamlit application.

---

# 👨‍💻 Developed By

**Sudeep S**  

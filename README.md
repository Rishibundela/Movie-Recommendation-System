# 🎬 Movie Recommendation System

A **content-based movie recommendation system** that uses **TF-IDF vectorization** and **cosine similarity** to suggest movies similar to a user's input. Built using **Python** and **Streamlit**, this app provides an interactive way to explore and discover movies.

---

## 📌 Features

- 🔍 **Content-Based Filtering**: Recommends similar movies based on their descriptions.
- 📊 **TF-IDF Vectorization**: Converts movie descriptions into numerical vectors.
- 📐 **Cosine Similarity**: Calculates similarity between movies.
- 🖥️ **Interactive UI**: Easy-to-use web interface built with Streamlit.

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Rishibundela/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```
### 2. Create a virtual Environment(Optional But Recommended)

```bash
python -m venv env
# On Windows PowerShell
.\env\Scripts\Activate.ps1Movie 
# On Mac/Linux
source env/bin/activate
```
### 3. Install Dependencies

```bash
pip install -r requirements.txt
```
### 4. Run Preprocessing Script

Before running the app, you need to preprocess the data:
```bash
cd src
python preprocess.py
```
### 5. Run the Application
```bash
streamlit run main.py
```
#### Steps:
- Enter the movie you like.
- Get a list of similar movie recommendations

### OMDB API Configuration
This project uses the **OMDB API** to fetch movie posters and additional information (like release year and ratings).

Make sure you:<br>
- Get a free API key from <a href=http://www.omdbapi.com/apikey.aspx>OMDb API - The Open Movie Database</a> <br>
- Then place your API key in the config.json file like this:<br>
```json
{
  "OMDB_API_KEY": "your_api_key_here"
}
```
### 📁 Project Structure
```
├── src/                             # Source code folder
├── Movie_recommendation_system.ipynb   # Main Jupyter Notebook
├── requirements.txt                # Python package dependencies
└── README.md                       # Project documentation
```
### 📚 Technologies Used

- Python: Core programming language.
- Streamlit: For building the interactive web application.
- scikit-learn: For TF-IDF vectorization and cosine similarity computation.
- Pandas: Data manipulation and analysis.
- Jupyter Notebook: Development and experimentation.

### 🤝 Contributing
Contributions are welcome! <br>
Feel free to fork the repo and open a pull request.

### 🔜 Stay tuned for more:
- I'll be working on new projects and improvements to this system.
- Look forward to more **innovative AI solutions**, **data-driven applications**, and **interactive tools** in the near future!

Feel free to check out more of my work as I continue to experiment, learn, and share my journey in AI and tech on my [GitHub Profile](https://github.com/Rishibundela).

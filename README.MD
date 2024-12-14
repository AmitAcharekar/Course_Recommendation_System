# Course Recommendation System

This project is a Flask-based web application that provides course recommendations based on a given course title. It uses techniques like text cleaning, feature extraction, and cosine similarity to suggest relevant courses to users.

---

## Features
- **Course Recommendation**: Suggests courses based on the cosine similarity of course titles.
- **Search Functionality**: Enables users to search for courses using partial keywords.
- **Top Recommendations**: Displays the top 12 recommended courses along with their details.

---

## Tech Stack
### Backend:
- Python
- Flask

### Libraries Used:
- **Data Manipulation**:
  - pandas
  - numpy
- **Text Cleaning**:
  - neattext
- **Machine Learning**:
  - scikit-learn
- **Visualization**:
  - matplotlib
  - seaborn

---

## Installation

### Prerequisites
1. Python 3.x installed on your machine.
2. Virtual environment set up .

### Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Course_Recommendation_System
   ```

2. Create a virtual environment :
   ```bash
   python -m venv app
   .\app\Scripts\activate # to activate virtual environment
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   python app.py
   ```



---

## Usage

1. **Enter a Course Title**: On the homepage, type the title of a course you want recommendations for.
2. **Get Recommendations**: The system will display the top 12 recommended courses with links and additional details.
3. **Partial Search**: If the title does not match exactly, the system will suggest courses based on a partial match.

---

## Dataset
The application reads course data from a CSV file named `UdemyCleanedTitle.csv`. The dataset must contain the following columns:
- `course_title`: Title of the course.
- `url`: URL of the course.
- `price`: Price of the course.
- `num_subscribers`: Number of subscribers.

Ensure the dataset is placed in the root directory of the project.

---



## File Structure
```
Course_Recommendation_System/
|— app.py                  # Main Flask application
|— templates/
|   — index.html           # HTML template for the homepage
|— udemy_course_data.csv   # Dataset file
|— UdemyCleanedTitle.csv   # Cleaned Dataset file
|— requirements.txt        # Python dependencies
|— .gitignore              # Git ignore file

— README.md               # Documentation
```

---



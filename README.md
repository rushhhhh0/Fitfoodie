## Diet Suggestor
---

### Getting Started

#### 1. Clone the Repository
```bash
# for windows
git clone https://github.com/rushhhhh0/Fitfoodie.git

# change the working directory
cd Fitfoodie
```

#### 2. Create Virtual Env
##### a. Conda
```bash
conda create -n venv python=3.11

# activate 
conda activate venv
```

##### b. Venv
```bash
python -m venv venv --without-pip

# install pip
python get-pip.py

# activate (for Linux OS)
source venv/bin/activate

# activate (For Windows)
venv\Scripts\activate
```

#### 3. Install requirements.txt
```bash
pip install -r requirements.txt
```

#### 4. Run the FastAPI server -  `app.py`
```bash
uvicorn app:app --reload
```
---

### Sample Screenshots

- Login Page
![login page](static/img/Login.png)

- Register
![Register User](static/img/Register.png)

- Dashboard
![Dashboard](static/img/Dashboard.png)

- Meal Suggestor
![Meal Suggestor](static/img/MealSuggestor.png)

- Craft Recipe
![Craft Recipe](static/img/CraftRecipee.png)

---
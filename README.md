

# ToDo App made with Flask


A ToDo application made with Flask Framework. Capable of performing CRUD operations.

## Installation

1. **Clone the Repository:**

```bash
git clone https://github.com/Cyber-Freak999/ToDoApp_Flask.git/
cd ToDoApp_Flask
```

2. **Create Virtual Environment:**

```bash
pip install virtualenv
virtualenv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate.bat
```

3. **Install Dependencies:**

```bash
pip install -r requirements.txt
```

4. **Run Web Server:**

```bash
python app.py
```

This server will start on port 5000 by default. You can change this in `app.py` by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
```

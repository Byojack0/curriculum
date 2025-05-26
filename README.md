# Portfolio Web Application

This is a simple Flask-based frontend web application showcasing the portfolio of Yonatan Guzmán.

## Project Structure

- `app.py`: Main Flask application file.
- `templates/`: Contains HTML templates.
- `static/`: Contains static assets like CSS and PDF files.

## Setup and Run

1. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
```

2. Activate the virtual environment:

- On Windows:

```bash
venv\Scripts\activate
```

- On macOS/Linux:

```bash
source venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the Flask app:

```bash
python app.py
```

5. Open your browser and navigate to `http://127.0.0.1:5000/` to view the portfolio.

## Deployment

This project can be deployed to platforms like Vercel or Heroku. Ensure the dependencies are installed and the `app.py` is configured correctly.

# AI-Study-Helper
AI-powered study assistant that summarizes lectures, explains topics, provides quizzes, and tracks study progress.

ProjectName/
├── src/                        # Main source code directory
│   ├── main.py                 # Entry point of the application
│   ├── utils.py                 # Utility functions
│   ├── models/                 # AI/ML models storage
│   │   ├── model.h5
│   │   ├── model.pkl
│   │   ├── model.onnx
│   │   └── model.pt
│   ├── data/                    # Dataset storage
│   │   ├── train.csv
│   │   ├── test.csv
│   │   └── raw/
│   ├── static/                  # Static assets (CSS, JS, images)
│   ├── templates/               # HTML templates (for Flask/Django)
│   ├── __init__.py              # Package initialization
│   ├── routes.py                # API routes (for Flask/Django backend)
│   ├── config.py                # Configuration settings
│   ├── ai_helper.py             # AI-powered study helper logic
│   └── database.py              # Database connection handling
│
├── tests/                       # Unit & integration tests
│   ├── test_main.py
│   ├── test_utils.py
│   └── __init__.py
│
├── logs/                        # Application logs
│   ├── app.log
│   ├── debug.log
│   └── error.log
│
├── .env                         # Environment variables (ignored by Git)
├── .env.example                 # Example environment file for reference
├── .gitignore                    # Git ignore file (already configured)
├── requirements.txt              # Python dependencies
├── Pipfile                       # Pipenv dependencies
├── poetry.lock                   # Poetry dependency lock file
├── README.md                     # Project documentation
├── Dockerfile                    # Docker container setup
├── docker-compose.yml            # Docker configuration
├── config.json                   # Additional configuration settings
├── db.sqlite3                     # SQLite database (ignored by Git)
├── manage.py                      # Django/Flask management script
├── package.json                   # Node.js dependencies (if frontend exists)
└── venv/                          # Virtual environment (ignored by Git)

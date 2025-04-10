# Development Environment Setup

## Prerequisites

* Python 3.8 or higher
* pip (Python package manager)
* Git

## Initial Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/your-project.git
cd your-project
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Running the Documentation Locally

1. Start the development server:
```bash
mkdocs serve
```

2. Open your browser and navigate to:
```
http://127.0.0.1:8000
```

## Troubleshooting

### Common Issues

1. **Virtual environment not activating**
   - Make sure you're in the correct directory
   - On Windows, you might need to run `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser`

2. **Package installation errors**
   - Try upgrading pip: `python -m pip install --upgrade pip`
   - Check if you have the correct Python version installed

### Need Help?

If you encounter any issues not covered here, please check our issue tracker or contact the development team.
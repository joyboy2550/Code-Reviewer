# Code Reviewer Project 

🚀 Live Demo: [Code Reviewer](https://code-reviewer-zr8f.onrender.com)

A Flask-based web application that provides AI-powered code review and analysis using Google's Gemini AI.

## Features

- User authentication and registration
- Code submission and analysis
- AI-powered code review with Gemini
- Programming language detection
- Code quality scoring
- Plagiarism detection hints
- Submission history tracking

## Tech Stack

- **Backend**: Flask, Flask-Login
- **Database**: Supabase (PostgreSQL)
- **AI**: Google Gemini AI
- **Deployment**: Vercel (Serverless)
- **Development**: Mock database for local testing

## Local Development

### Prerequisites

- Python 3.11+
- pip
- Git

### Setup

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd codereviewer-project
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables (Optional)**
   ```bash
   cp env.example .env
   # Edit .env with your actual values
   ```

5. **Run the application**
   ```bash
   python run.py
   ```

The application will be available at `http://localhost:5000`


## API Endpoints

- `GET /` - Home page
- `GET /login` - Login page
- `POST /login` - Login form submission
- `GET /register` - Registration page
- `POST /register` - Registration form submission
- `GET /dashboard` - User dashboard
- `GET /submit` - Code submission page
- `POST /submit` - Submit code for analysis
- `GET /history` - Submission history
- `GET /feedback/<id>` - View specific feedback

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## License

This project is licensed under the MIT License.

## Support

For support, please open an issue in the GitHub repository. 

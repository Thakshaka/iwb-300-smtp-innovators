# UniHope - AI-Powered Personalized Courses Recommendation and Cutoff Prediction System for University Admission in Sri Lanka

## Overview

UniHope is an innovative AI-powered platform designed to assist Sri Lankan students in their university course selection process. By analyzing academic information, UniHope provides personalized course recommendations, helping students make informed decisions about their higher education journey.

## Features

- Personalized course recommendations based on academic profile
- AI-driven cutoff mark predictions
- Multi-language support (Sinhala, Tamil, English)
- User-friendly interface for easy navigation
- Comprehensive database of university courses and their requirements
- Secure user authentication and data protection

## Tech Stack

- Frontend: React.js
- Backend: Ballerina
- Database: PostgreSQL
- AI Model: Python (FastAPI, scikit-learn)

## Prerequisites

- Node.js and npm
- Ballerina
- Python 3.7+
- PostgreSQL

## Installation and Setup

### 1. Frontend Setup

```bash
cd frontend
npm install
```

Create a `.env` file in the frontend directory and add:
```
REACT_APP_RECAPTCHA_SITE_KEY=your_recaptcha_site_key_here
```

Start the frontend server:
```bash
npm start
```

### 2. Backend Setup

Navigate to the backend directory:
```bash
cd backend
```

Create a `config.toml` file in the frontend directory and add:
```
# Database Configuration
dbHost = ""
dbName = ""
dbUsername = ""
dbPassword = ""
dbPort = 

# Email Configuration
smtpHost = ""
smtpUsername = ""
smtpPassword = ""

# Server Configuration
serverPort = 

# Model API Configuration
modelApiUrl = ""
```

Run the Ballerina server:
```bash
bal run
```

### 3. Machine Learning Model Setup

Navigate to the model directory:
```bash
cd model
```

Install required Python packages:
```bash
pip install fastapi uvicorn pandas scikit-learn
```

Start the FastAPI server:
```bash
python -m uvicorn cutoff_predictor:app --reload
```

## Usage

After setting up all components, access the application through `http://localhost:3000` in your web browser.

## Contributing

We welcome contributions from the open-source community! If you'd like to contribute, please:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

SMTP Innovators - smtpinnovators@gmail.com

Project Link: [https://github.com/Thakshaka/iwb-300-smtp-innovators](https://github.com/Thakshaka/iwb-300-smtp-innovators)

## Acknowledgements

- [Ballerina](https://ballerina.io/)
- [React.js](https://reactjs.org/)
- [FastAPI](https://fastapi.tiangolo.com/)
- [scikit-learn](https://scikit-learn.org/)
- [PostgreSQL](https://www.postgresql.org/)

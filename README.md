# financial-fraud-detection-model
# SPAM Detector ML

A fraud detection application with both web frontend and Python machine learning backend for analyzing and predicting fraudulent transactions.

## Features

- **Real-time Fraud Detection**: Upload CSV files and get instant fraud predictions
- **Interactive Dashboard**: Modern web interface with dark/light mode
- **Machine Learning Backend**: Python-based Dash application with trained models
- **Data Visualization**: Charts and analytics for prediction results
- **Risk Assessment**: Color-coded risk levels for transaction analysis

## Live Demo

Frontend: [Deployed on Netlify](https://fraud-detector-dashboard.netlify.app/)

## Technology Stack

**Frontend:**
- Vite + JavaScript
- Tailwind CSS
- Chart.js

**Backend:**
- Python + Dash
- Scikit-learn
- Pandas, NumPy
- Plotly

## Quick Start

### Frontend Development

```bash
npm install
npm run dev
```

### Python Backend

```bash
cd python-backend
pip install dash scikit-learn pandas numpy plotly
python app.py
```

## Deployment

### Frontend (Netlify)

The frontend is configured for automatic deployment to Netlify:

- Build command: `npm install --legacy-peer-deps && npm run build`
- Publish directory: `dist`
- Node version: 18

### Backend Deployment

The Python backend can be deployed to platforms like:
- PythonAnywhere
- Heroku
- Railway
- DigitalOcean

## Usage

1. **Upload CSV**: Drag and drop transaction data
2. **View Results**: Analyze predictions with confidence scores
3. **Interpret Charts**: Review distribution and correlation visualizations
4. **Risk Assessment**: Examine color-coded transaction risk levels

## Project Structure

```
├── src/                 # Frontend source code
├── python-backend/      # Python ML backend
│   ├── app.py          # Dash application
│   ├── main.py         # Additional scripts
│   ├── requirements.txt # Python dependencies
│   └── static/         # ML model files
├── dist/               # Built frontend files
└── netlify.toml        # Netlify configuration
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

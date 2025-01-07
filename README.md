# 30 Days DevOps Challenge - Weather Dashboard  
**Day 1: Building a Weather Data Collection System using AWS S3 and OpenWeather API**

## Project Overview  
This project is a **Weather Data Collection System** designed to fetch, store, and manage real-time weather data. It demonstrates **core DevOps principles** while showcasing Python development skills and cloud integration.  

### Key Objectives:  
- **External API Integration**: Seamlessly fetch data using the OpenWeather API.  
- **Cloud Storage**: Securely store data in AWS S3 for scalability and durability.  
- **Infrastructure as Code**: Automate resource management and deployment.  
- **Version Control**: Maintain an organized development workflow using Git.  
- **Error Handling**: Ensure robust handling of API and system errors.  
- **Environment Management**: Use virtual environments and `.env` files for security and isolation.  

---

## 🌟 Key Features  
- 🌍 **Real-Time Weather Data**: Fetches up-to-date weather information for multiple cities worldwide.  
- 🌡️ **Detailed Weather Insights**: Displays temperature (°F), humidity levels, and current weather conditions.  
- ☁️ **AWS S3 Integration**: Automatically saves weather data for secure and scalable storage.  
- 📌 **Multi-City Tracking**: Monitor weather across various locations simultaneously.  
- 🕒 **Historical Tracking**: Adds timestamps to all entries for easy analysis.  

---

## 🛠️ Technical Architecture  
![image](https://github.com/user-attachments/assets/ead09058-b216-4d58-ac81-acdce10494b8)

- **Language**: Python 3.x 🐍  
- **Cloud Provider**: AWS (S3) ☁️  
- **External API**: OpenWeather API 🌤️



### Core Dependencies:  
- 🛠️ **boto3**: AWS SDK for Python.  
- 🔑 **python-dotenv**: For managing environment variables securely.  
- 🌐 **requests**: Simplified HTTP requests for API integration.  

---

## 📂 Project Structure  

```plaintext
weather-dashboard/
  ├── src/
  │   ├── __init__.py
  │   ├── weather_dashboard.py
  ├── tests/
  ├── data/
  ├── .env
  ├── .gitignore
  ├── requirements.txt



## ⚙️ Setup Instructions  

### Step 1: Project Initialization  
Instead of cloning an existing repository, you can recreate the project structure and files as shown above to understand the development process thoroughly.  

### Step 2: Create a Virtual Environment  
```bash
python3 -m venv <your_environment_name>
source <your_environment_name>/bin/activate


## Step 3: Install Dependencies

bash
pip install -r requirements.txt

##Step 4: Configure Environment Variables
Create a .env file with the following keys:

OPENWEATHER_API_KEY=your_api_key  
AWS_BUCKET_NAME=your_bucket_name  


## Step 5: Set Up AWS Credentials
Use the AWS CLI to configure credentials:

bash
aws configure


## Step 6: Run the Application
bash
python src/weather_dashboard.py

## What I Learned
Setting up and managing AWS S3 buckets.
Securing API keys and managing environment variables.
Best practices in Python API integration.
Using Git for streamlined version control.
Error handling in distributed systems.
Managing cloud resources effectively.

## Future Enhancements
Add weather forecasting capabilities.
Implement data visualization for better insights.
Support tracking of more cities.
Introduce automated testing frameworks.
Set up a CI/CD pipeline for seamless deployments.

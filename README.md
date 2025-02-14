📂 Project Structure
retail_sales_db.ipynb - Jupyter Notebook containing the data analysis, visualizations, and insights.
requirements.txt - Lists the necessary Python packages required for running this project.
env.txt - Stores environment variables, including API keys.

🛠 Installation
Clone the repository:
git clone <repository-url>
cd <repository-name>

Set up a virtual environment (optional but recommended):
python -m venv venv

source venv/bin/activate  # On Windows use: venv\Scripts\activate

Install dependencies:
pip install -r requirements.txt

Set up environment variables:
Rename env.txt to .env and update the values accordingly.

🚀 Usage
Open the Jupyter Notebook:
jupyter notebook
Run retail_sales_db.ipynb to execute the analysis.

🛠 Technologies Used
Python
Jupyter Notebook
MySQL (via mysql-connector-python and pymysql)
LangChain (for AI-based enhancements)
Streamlit (for interactive dashboards)
ChromaDB (for vector-based storage)
Sentence Transformers (for NLP-related tasks)

🔑 Environment Variables
Ensure you configure your .env file with the necessary credentials:

plaintext
GOOGLE_API_KEY=<your_google_api_key>

📌 Notes
The project includes AI-powered analysis capabilities via LangChain and Google GenAI.
Protobuf is pinned to version 3.19.0 to avoid compatibility issues.

📄 License
This project is licensed under the MIT License.


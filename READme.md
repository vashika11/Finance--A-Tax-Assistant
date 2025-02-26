Our "Finance: A Tax Assistant" app is built to make tax finalization both stress-free and efficient. Leveraging cutting-edge AI, it guides you through every step of the tax filing process—from filling out forms and identifying relevant deductions to optimizing credits and ensuring you meet all filing deadlines.

Whether you're an individual trying to simplify your tax return or a small business owner juggling complex financial records, this app is designed to help you navigate the maze of tax regulations with confidence. It offers clear, personalized advice tailored to your specific tax situation, ensuring that you maximize your deductions and minimize errors.

Planned Features Include:

Tax Document Review: Upload your tax-related documents for an in-depth analysis. The app will highlight key insights on deductions, credits, and filing requirements, providing actionable feedback on deduction optimization, eligibility for credits, overall report accuracy, and compliance with current tax laws.

Tax Consultation Module: Have a question about your filing? Submit your queries and receive expert-level, context-aware responses. This module is designed to address personalized concerns and offer guidance on tax-saving strategies, deadline management, common errors, and more.

Income and Expense Analysis: Input or upload your financial data to receive a detailed breakdown of your income and expenses. This feature will help pinpoint potential deductions, determine your tax bracket, suggest income adjustments, and accurately compute your net tax liability.

Real-Time Filing Assistance: As you work through your tax filing, enjoy interactive guidance that helps ensure compliance and alerts you to any possible errors before submission.

Follow these steps to set up Tax Assitant on your local machine:

Clone the repository:
git clone https://github.com/uchiha-vivek/Llama-Impact-Hackathon-LablabAI.git

Navigate to the project directory:
cd Llama-Impact-Hackathon-LablabAI

Create a virtual environment:
python -m venv venv

Activate the virtual environment:
On Windows:
venv\Scripts\activate
On macOS and Linux:
source venv/bin/activate

Install the required packages:
pip install -r requirements.txt

Set up your API key:
Create a .streamlit/secrets.toml file in the project root

Add your API key:
GROQ_API_KEY=""
LLAMA_CLOUD_API_KEY=""
QDRANT_API_KEY=""

Run the Streamlit app:
streamlit run app.py

Open your web browser and go to http://localhost:8501 to use Tax Assistant !
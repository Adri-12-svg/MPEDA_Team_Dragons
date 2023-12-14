# MPEDA_Team_Dragons
Our chatbot mostly utilizes BARD and Langchain for question answering.BARD is used for 3 different purposes in our bot:
1) Queries related to seafood and seafood business 
2) Providing description from Images
3) Reading from personal csv files
We used beautiful soup for scrapping data from MPEDA and other websites and cleaned the text and made a pdf. Langchain is used to do question answering from this pdf
Web scraping data from the MPEDA official website and multiple seafood export company websites, followed by text cleaning, preprocessing using NLTK & re library.      
EfficientNet for classifying image,Flask as the main python framework for integration,News API for showing recent news related to seafood business,Google Firebase - creating database of login,smtplib for providing follow up emails with proper summary

*Instructions*
1) git clone ......
2) pip install bardapi
3) go to bard-> console-> application -> cookies-> bard link -> _Secure - 1PSID api key
4)pip install langchain
5) pip install openai
6) pip install pyPDF2
7) pip install faiss-cpu
8) pip install tiktoken
If tensorflow and opencv not installed in system
pip install tensorflow
pip install cv2
pip install opencv-python

To access BARD API KEY:
os.environ['_BARD_API_KEY'] = 'your_api_key'
Process to generate this API KEY:
Bard website -> console -> application -> cookies -> https://bard.google.com ->_Secure - 1PSID API key

Running the application in terminal:
python app.py

*Work Flow*
1)Signup as new user
2)MPEDA Specific Query button on Sidebar
3)News cards showing latest news
4)Enter Your required query
5)Upload your Required Image to have details
6)Upload your required CSV file to question
7)Use Translate dropdown
8)Click the Required Buttons as per your options

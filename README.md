Backend
backend.py file consists of 2 ML models based on KeyBERT and BERT.
Initially, the model extracts essential keywords from the user-entered string using a pre-trained customized BERT model, which returns a list of keywords. Then, the obtained keywords are processed for lexical simplification such that complex terms like ‘lunar’ are converted to ‘moon’ for an easily accessible and better search.
So basically, we improvised the previously implemented keyword-based model in the https://images.nasa.gov/ website using ML for a more precise search mechanism.
The ML model returns a list of keywords that are then sent to the API, which returns a JSON array of dictionaries with information about the images, their descriptions, and other research information related to that keyword.


Frontend
The homepage.html, homepage.css, and homepage.js files are for the frontend.
The frontend has been made artistic and dynamic with the help of animations for an immersive experience.

The project is 80% complete. Due to the limited time, the only thing left is connecting the backend to the frontend, which includes sending the user-entered string to the backend and then displaying the research data along with images on the frontend.

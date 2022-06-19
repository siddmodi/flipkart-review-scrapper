========== Flipkart Review Scrapper =============

Skills and tools used - Web scrapping, NLP, API, Oops, Pandas, Selenium, Flask, HTML, CSS, Bootstrap, Logging, Python, MongoDb Database, Cloud Deployment. 			

• Flask app asking for product & no.of reviews to webscrap products details like (Product-Searched, ProductName, Price, Discount percent, Available Offers,
  EMI Details, Rating, Customer Name, Comments, Review Age) and also tells us sentiment of the comments whether its (Highly Negative,Negative,Average,
  Positive,Highly Positive) using Bert pre-trained model as API 
  
• All details will save in our mongoDb database as well as in a downloadable csv file

# Command to run

1) conda create -venv env
2) conda activate env
3) pip install -r requirements.txt
• Optional ~ Change username & password of mongoDb in RepositoryForObject.py file. Also change username & password of mongoDb cluster in app.py file 
4) python app.py


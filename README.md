# CBIR_for_Professional_News_Recommender
CBIR WebApp System for News Recommendation Based on Professional Profile of a user

1. This application is built using FastAPI and GoogleNews API. 

2. In this application, a webpage is displayed to the user, where the user is asked to fill in its professional information such as education details, professional experience and the skills.
The entered professional details are then converted in a search query by the application of TFIDF on the three types of data in the professional profile details.
The Google News API is then called using the created search query to retrieve the news based search results, which are relavent to the user.
The user is then redirected to another page where the search results are displayed along with the professional details they are relavent for.
Each search result includes a title of the related news item, a brief description of the news item, and a URL of the news item.

3. How to deploy/run the WebApp:
	a. On opening and running the app.py Python file on any IDE or console, a Uvicorn server starts running on http://127.0.0.1:7001
	
	b. To run the Webapp, open http://127.0.0.1:7001 on any browser.
	
	c. "index.html" webpage is rendered. Here, enter the professional profile details and press submit.
	
	d. The WebApp navigates to "hello.html" and displays the professional profile details and the retrieved search results including news items related to the professional profile details.
	
	e. Press "Back" or "Home" to go back to "index.html" and update professional profile details.
	

  
Screenshots:
![Screenshot1](https://user-images.githubusercontent.com/89964333/201000392-7c30ab37-30ab-47ff-b477-4685d7df1cc4.jpg)
 
![Screenshot2](https://user-images.githubusercontent.com/89964333/201000442-ec76a680-6beb-42e8-913a-2ce303607324.jpg)

![Screenshot3](https://user-images.githubusercontent.com/89964333/201000468-1a3ab061-d991-4770-8695-26be0c9e92ec.jpg)

![Screenshot4](https://user-images.githubusercontent.com/89964333/201000490-67d1005a-cc21-4bcf-a0a4-80c2bca2724e.jpg)

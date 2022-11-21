# Requirements:
Implement a news recommendation system using NLP.

Proposed solution will recommend real time news based on user professional profile.
Steps:
1. Enter your Educational details(Degree, University )
2. Enter your most recent experience(Organization Name, Experience description)
3. Enter your skills
4. Implement a content based recommendation system which will recommend news based on above entered data in real time.
5. Convert the solution in FastAPI endpoint.

# Solution:

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
	
	d. The WebApp navigates to "search-results.html" and displays the professional profile details and the retrieved search results including news items related to the professional profile details.
	
	e. Press "Back" or "Home" to go back to "index.html" and update professional profile details.

# Screenshots:

## Initial Page that user lands on
<img width="1236" alt="image" src="https://user-images.githubusercontent.com/6551463/202976665-c629d823-2284-4f1a-946e-15fcde0c7067.png">

## Sample data that user fills in the input fields
<img width="1240" alt="image" src="https://user-images.githubusercontent.com/6551463/202976730-1f05d88e-168b-47e7-9017-88d54ca8532a.png">

## Search Results
<img width="1237" alt="image" src="https://user-images.githubusercontent.com/6551463/202976786-d1cb7819-7ea6-42f5-97e3-ea72945b92f9.png">

In this Era, people don't have much time to decide whether this movie is right to watch or not according to their interest. Thus, a recommendation system helps to address this problem and filter useful information quickly and appropriately at the user's choice. The project has proposed a movie recommendation program, its main purpose is to promote the movie through cosine similarity. Moreover, this project also focuses on the method of identifying user's preference by using a content-based algorithm and predict related movies. Moving forward we combine 3-4 attributes in one column from movie dataset having attributes like Actor, Director, Movie title and Genre. Using this column cosine function creates the vector and recommend the movies which are nearer to this cosine vector. After analyzing the result on IMDB movie dataset our system indicate that our algorithm can provide recommendation with high accuracy and generate reliable and personalized results that user's likes.
![image](https://user-images.githubusercontent.com/94472837/170880893-0c3cbf21-6220-4724-b04d-f602f5ef4d92.png)
System Requirement Specification
1 Hardware Requirements

•	Windows/Linux OS

•	1.7-2.4GHz processor

•	8GB RAM Minimum

•	2GB Graphics Card

2 Software Specifications

•	Text Editor (like VS-code)

•	Anaconda Editor distribution package.

•	Python library.

3. Software Requirements

•	Anaconda distribution
4. Python libraries
•	Flask==1.1.1
•	gunicorn==19.9.0
•	Jinja2==2.11.3
•	MarkupSafe==1.1.1
•	Werkzeug==0.15.5
•	numpy>=1.9.2
•	scipy>=0.15.1
•	nltk==3.5
•	scikit-learn>=0.18
•	beautifulsoup4==4.9.1
•	jsonschema==3.2.0
•	tmdbv3api==1.6.1
•	lxml==4.6.3
•	urllib3==1.26.5
•	requests==2.23.0
•	pickleshare==0.7.5
![image](https://user-images.githubusercontent.com/94472837/170880949-b3be673e-0e58-41ae-83a6-31d9cbb8bd65.png)
![image](https://user-images.githubusercontent.com/94472837/170880974-df9a353f-55d7-473e-a455-5294737b962c.png)
![image](https://user-images.githubusercontent.com/94472837/170880998-49fd3e6b-4dc5-4cb0-9ec7-3eb9cbb9c78f.png)
![image](https://user-images.githubusercontent.com/94472837/170881004-f0eaf745-c059-4845-a8d4-3fa29346ae52.png)
![image](https://user-images.githubusercontent.com/94472837/170881017-4d89d67c-4483-47e6-9ea6-6857680c3b76.png)
In this project, for recommending a movie similar to a searched movie we used the cosine algorithm. After searching or entering a movies name, the algorithm provides 8 additional movies similar to the one user likes. In the cosine similarity, the vector is defined in the product area, which is considered to be a data object of the data set to describe the similarity. Statistically, this measures the cosine of an attitude between two vectors developed in a multidimensional space. There are other similar measurement techniques such as Euclidean range that calculate the distance between two vectors. But in this project, we will be focusing here on the similarities between Cosine angle and Cosine Distance. It's miles a degree that helps you determine what comparable data items are. Statistically the cosine of an angle between two vectors is designed in multi – dimensional space.

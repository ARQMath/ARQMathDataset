# ARQMath Clef 2020
[ARQMath](https://www.cs.rit.edu/~dprl/ARQMath/) lab at [CLEF 2020](https://clef2020.clef-initiative.eu/).  focuses on mathematical information retrieval. There will be two tasks for this lab:
  ### Task 1 
  Given a math question (a question related to some mathematical information need that contains at least one formula), participants will retrieve a list of possible answers to that question, ranked based on relevance.
  
  ### Task 2
  Given a formula as a query, participants should retrieve formulas related to the formula query.
  
 Futher information please check the ARQMath [webpage](https://www.cs.rit.edu/~dprl/ARQMath/). You may also consider joining the discussion forum [here](https://groups.google.com/forum/#!forum/arqmath-lab).

# Dataset
In this lab we will be using data from [Math Stack Exchange](https://math.stackexchange.com/) (MSE)The dateset for this lab is currently available on [Google Drive](https://drive.google.com/drive/folders/1ZPKIWDnhMGRaPNVLi1reQxZWTfH2R4u3?usp=sharing). This data was provided by [Archive](https://archive.org/) and several preprocessing have been done on the initial data. There are 7 files in this dataset:
  #### Users
  Users can post questions and answers and therefor each post is written by a user. Each users has a unique id along with other information such as display name, age, location, the date they created their profile and the reputations points earned based on their activities on MSE such as receiving an "up" vote on an answer given.
  #### Badges
  Besides reputation for each user, they can have a list of badges they received. There are three class of badges 3:bronze, 2:silver and 1:gold. Each badges is linked to a user by user id.
  #### Votes
  Members of MSE, can give different votes to questions and answers. In the vote file, for each vote there is a unique id, related post id, vote type [1 to 13], vote date and the user id of the voter.
  #### Tags  
  Each question on the MSE, can have different tags that are determined by the user posting the question. In tag file, one can find list of all possible tags with their repetition count. However, in the post file, you can get the exact question tags.
 #### Comments
 Users can comment on both questions and answers. In the comment file, each comment has its own unique id, along with the related post id, the id of user who written the comment, its creation date, its text and score.
  #### PostLinks
  Each question on MSE can be associated with other questions; it can be related to another question or it can be its duplicate.
  In the post links file, each link has a unique id, the post id of the question, the post id of related question (relatedpostid), the link type [1:related, 3:duplicate].
#### PostHistory
  
 

  
 
  #### Posts
  

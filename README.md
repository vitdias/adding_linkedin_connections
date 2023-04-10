# add_linkedin_connections
This repo will help you to connect automatically with recruiters.

To execute, you need to prepare some steps:
1) The script.py will login in your linked, so you need to include your linkedin username and password declaring variables with this same name. In my case I just imported it from the secret.py file.

2) Change the URL variable. You need to add the filters you want. In my case, I came to linkedin search bar, typed "tech recruiter", filtering 2nd grade, and adding "Estonia" and "Tallin, Estonia" to the locations filter. Then I copied the URL from this search to the URL variable in the script.py.

3) To prevent being banned from linkedin for adding a lot of connections, I set up a maximun of 60 connections per execution (And I am running it daily). If you want a different number than 60, change the line 48 in the script.py and use the number of your preference  
PS: I am just using 60 because a friend of my have got banned for adding 100 daily. 

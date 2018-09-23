# Friend Finder - Node and Express Servers
UC Irvine Coding Bootcamp Friend Finder Application using Express and Node.js

# https://limitless-bayou-18825.herokuapp.com

### Overview

In this applicaion I have built a compatibility-based "FriendFinder" application -- basically a dating app. This full-stack site will take in results from users' surveys,then compare their answers with those from other users. The app will then display the name and picture of the user with the best overall match. 

I have used Express to handle routing and have deployed my app using Heroku so other users can fill the survey.

I leverage body-parser, express and path node modules.  


### Application Directory Structure:

  ```
  FriendFinder
    - .gitignore
    - app
      - data
        - friends.js
      - public
        - home.html
        - survey.html
      - routing
        - apiRoutes.js
        - htmlRoutes.js
    - node_modules
    - package.json
    - server.js
  ```

## Application Images

### Friend Finder Main Page
---
![Image Friend Finder Main page](https://github.com/jhwillia7/FriendFinder/blob/master/images/friendFinderMainPage.PNG)
---

### Friend Finder API Friends List
---
   ![Image API Friends List](https://github.com/jhwillia7/FriendFinder/blob/master/images/apiFriendsList.PNG)
---

### Friend Finder Survey
---
   ![Image Survey](https://github.com/jhwillia7/FriendFinder/blob/master/images/surveyQuestions.PNG)
---

### Friend Finder Match Results
---
   ![Image Match Result When Survey Submit](https://github.com/jhwillia7/FriendFinder/blob/master/images/bestMatchResult.PNG)
---

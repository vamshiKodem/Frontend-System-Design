# Frontend System Design
In this repository, you'll find resources, diagrams, and documentation related to the front-end system design. Explore our user interface architecture, design patterns, and user experience strategies to understand how we create a seamless and user-friendly digital environment.

# Important links for frontend system design
- <p><a href="https://www.youtube.com/watch?v=5vyKhm2NTfw&list=PLI9W87-Dqn7j_x6QtR6sUjycJR7nQLBqT">Front-End Engineer YT Channel</a></p> 
- <p><a href='https://www.youtube.com/watch?v=sV_4pOGosnU&list=PL4CFloQ4GGWICE0Tz6iXKfN3XWkXRlboU'>Chirag Goel YT Channel</a></p>
- <p><a href='https://bigfrontend.dev/design'> BigFrontend Frontend Design Questions</a></p>
- <p><a href="https://www.greatfrontend.com/system-design">GreatFrontend Design Questions</a></p> 

# List of most asked frontend system design questions 
- Design facebook.com
- Design youtube.com
- Implement nested checkboxes
- Design an Instagram
- Design an Infinite Scroller
- Design a messenger web app
- Design an API progress bar
- Design a Typeahead Widget
- Design a perfect TODO app
- Create a Star Widget
- Design a Poll Widget
- Design a Carousel Widget
- Design Twitter Web App
- Design a QR code-based login system
- Design CodeSandbox
- Design a Tic-Tac-Toe game



# Frontend System Design of Youtube
Tech Stack Overview

![Screenshot 2023-10-26 114701](https://github.com/vamshiKodem/Frontend-System-Design/assets/139354055/4ffb5389-b951-47d3-80ea-aa492844fac8)

**Video Details Section**

![Screenshot 2023-10-26 111139](https://github.com/vamshiKodem/Frontend-System-Design/assets/139354055/f7227622-8b0f-46b0-aaca-998eff4244e8)

Its contains

- Video Player
  - Play / Resume
  - Forward / Backward
  - Expand / Minimize
  - Quality
  - Speed
- Video details
  - Title
  - Description
- Suggested Videos
- Comment Section
  - It should have an infinite scroll
  - Should show the latest comments first
  - It should be editable and can delete the comment

**Youtube Home Screen**
<img width="882" alt="image" src="https://github.com/vamshiKodem/Frontend-System-Design/assets/139354055/5fad2773-0864-4984-8356-08193a3898df">

It's contains
- Left Menu section with Logo
- Search Bar (Text input and voice search)
- Suggestion category
- Video Suggestion
  - Video Thumbnail
  - Video preview
- Shorts suggestion
- Home, Shorts, Subscribed
- Explore Section
  - Trending
  - Shopping
  - Games
  - News
  - Sports
  - Learning
- Settings
- Youtube Child
- Youtube premium

# Flipkart Autocomplete


![Screenshot 2023-10-31 114236](https://github.com/vamshiKodem/Frontend-System-Design/assets/139354055/55fa0614-5da1-49d8-b74e-fafba670c28a)


<img width="978" alt="image" src="https://github.com/vamshiKodem/Frontend-System-Design/assets/139354055/0f1c951c-91e2-4bcd-82fa-7709d7374d84">
 
- Tech Stack
  - React js (Next js for Server side rendering)
  - Axios / Apollo Client for graphql
  - Context Api / Redux (State management)
  - Bamboo / Jenkins (Automated builds)
  - Adobe / Google Analytics
  - Spuluk (Logs)
  - ES Lint
  - In house Common components
 
  Some important things
  - if we are using services we need to implement the results which are the latest
  - Text input must be customizable
  - We also need to support spell check so even if we spell wrong we need to give suggestion
  - Need to implement infinity scroll or pagination so we can show a large number of suggestions
  - Localize suggestions / local language
  - store the recent search history and suggestions for performance
  






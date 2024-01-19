<h1> Fyle Web Development Internship Task </h1>



<b> Live Link : https://mellifluous-puppy-bb2a5a.netlify.app/ </b>
<h2><a href="https://github.com/BhanuTeja100/Git-Repo-Listing-Page"> Git Repo Listing Page </a></h2>
Task : To create a website that displays the public Github repositories belonging to any specific user.


<h2>About this Project</h2>

- This Project is done using HTML, CSS and JavaScript without using any frameworks.
- Used JQuery as extra.
- I have used my Personal Access Token to extract details from github which is hidden here (as github revokes access tokens if made public)

<h2>Run Locally</h2>

<h3>Clone the Project</h3>
<pre>git clone https://github.com/BhanuTeja100/Git-Repo-Listing-Page.git</pre>

### If you are running the project locally
- Goto script.js file
- In that change '''this.accessToken = {with your personal access token}''';
- Now it will work with your personal access token
- If this is not done it may give 401 (unauthorized) error or may not give any result

<h3>Run index.html file</h3>
<pre>start index.html</pre>

<h2> Working of the Website</h2>

### After running locally or opening the deployed website ( https://mellifluous-puppy-bb2a5a.netlify.app/ )
- you will be taken to the cover page
- click on the Get Started button
- Now you are redirected to the main page
- At Enter Github Username enter the username you want to search, then click Get Repositories button
- Wait for some time you will get repositories details with the topics used in it in boxes
- You can jump between different pages to see all the repositories of the user

### References & Requirements

- API Documentation https://docs.github.com/en/rest/reference
- The below image represents a `topic` of a particular repository, one repository could have multiple `topics`
- Pagination has to be `server`-side
    - By default, show `10` repositories per page
    - User should be able to choose a maximum of `100` repositories per page.
- When the API calls are in progress, consider showing loaders.
- Optionally, you can provide a search bar to filter the repositories.

  ### <h2>What I Did</h2>
  - Implemented all the mentioned functionalities
  - Added my own designing and styles
  - Added the percentage for the topics used in the repositories

  <h1> DONE !!!</h1>
  





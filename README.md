
# :computer: :green_book: devBook

A bingo book of github devs

![](/static/banner.png)

# Welcome :)
<a href="https://devchallenge.now.sh/"> DevChallenge</a> allow you to improve your code skills!

# Table of Contents

  - [Challenge](#challenge)
    - [Requirements](#requirements)
      - [Techs](#techs)
    - [Hints](#hints)
    - [Bonus Points](#bonus-points)
  - [Get Started](#get-started)
  - [Design](#design)
    - [Colors](#colors)
    - [Typography](#typography)
  - [Share](#share)
  
# Challenge
Your challenge is to build a 3 pages website (home/landing page, search results and user details) consuming [github](https://docs.github.com/en/rest/reference/search) and [github stats](https://github.com/anuraghazra/github-readme-stats) public APIs.

## Requirements
- Homepage should have a search bar where user can search for github users
- Homepage should have a carousel section that shows the top github users
- Github user's card should have a name, username and bio.
- When user performs a search, it should redirect to the results page where the best matches for that search is shown.
- Whenever a user clicks in a github user card, it should redirects to that github user's page where is shown that user's github stats and repos

### Techs
- HTML
- CSS
- JS

You can also use React.js or any other framework you prefer.

## Hints
- You can create your own octocat [here](https://myoctocat.com/build-your-octocat/) to use in your project. Don't forget to remove the white background of your octocat image on photoshop or any other image editor.
- Use [search params](https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams) to generate dynamic pages for the search page. Example: `https://book.dev/search?query=<lucas>`

## Bonus Points

- Create light mode and a switch in the navbar to enable it
- Add contact info of github users in the users' card and users' details
- Create a filter for searching only the hireable ones
- Create [skeletons](https://uxdesign.cc/what-you-should-know-about-skeleton-screens-a820c45a571a) to be shown while data is fetching in order to improve the website UX. In the design files and figma you can find skeletons models for the cards.

# Get started
1 - Use this template or download this repository with the starter code<br>
2 - Read the instructions in readme.md<br>
3 - Start coding!<br>
4 - Share your results with the community :)<br>
<br>


Feel free to use any workflow you are comfortable with :)

# Design:
Check it out on [figma](https://www.figma.com/file/VEMlScBkM2J9lQ1dMayXpP/devbook?node-id=1%3A4) or download the [.fig file](https://github.com/lucas-lm/devbook-devchallenge/blob/master/design/devbook.fig) at `./design`

## Colors
```js
  colors: {
    primary: '#6C80EA',
    secondary: '#A7A5EC',
    background: {
      main: 'linear-gradient(to bottom, #000, #00030f)',
      paper: 'rgba(255, 255, 255, 0.25)',
    },
  }
```

## Typography
```css
font-family: 'Ubuntu', sans-serif; /* logo and headline tags */
font-family: 'Roboto', sans-serif; /* paragraph, small and input tags */
```

# Share!
Initialize your project with this template in your github as a public repository<br>
Capture a screenshot, gif or video and share your result on Linkedin<br>
Send me a feedback in  <a href="https://www.linkedin.com/in/lucas-lm/">Linkedin</a>!<br>

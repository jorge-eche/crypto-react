# Cryptocurrency price comparison application.

Website that compares the price of different currencies with the 10 most important cryptos with the help of a RESTful API.

## Table of contents

  - [Overview](#overview)
  - [The project - Features](#the-project)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [If I had more time I would change this](#if-i-had-more-time-i-would-change-this)
  - [Continued development](#continued-development)
  - [Author](#author)

## Overview

### The project

Users should be able to:

- Select both the currency and cryptocurrency they want to compare prices with.
- Quote a cryptocurrency, viewing its current price along with its highest/lowest price of the day and the 24-hour variation.
- See a spinner/loader while the data is being fetched from the API.
- View the optimal layout depending on their device's screen size.
- See hover states for interactive elements.

### Screenshot

![Screenshot of the project](./src/img/crypto-screenshot.png)

### Links

- Live Site URL: [https://jorgeecheverria.netlify.app/](https://cryptos-tracker-react.netlify.app/)

## My process

### Built with

- [React](https://reactjs.org/) - JS library
- [Vite](https://vitejs.dev/) - React environment
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - Language
- [Styled Components](https://styled-components.com/) - For styles
- [CryptoCompare](https://www.cryptocompare.com/) - For the Toplist by Market Cap Full Data API
- [Tobias Ahlin Spinkit](https://tobiasahlin.com/spinkit/) - For the Spinner
- [Semantic HTML5 markup](https://www.w3.org/html/) - For the web structure
- Flexbox
- Mobile-first workflow

### What I learned

- I could have added more than 10 cryptos or more than 5 currencies for comparison, but I think it really does not add much on functionality terms to the application, so I decided to stick to small numbers for simplicity.
- REST APIs are so useful, there is no limit for what they can do for you and how easy it is to implement them in your projects. From face recognition APIs to cryptos quoting, your creativity and imagination are the limit here.
- This is the first project I used Styled Components. I found it very useful as it removes vanilla CSS' specificity problems. I also liked the idea of not having CSS files all over my IDE so I will continue using it for future works. On the cons side, it can get a bit messy to read JSX files with so many custom styled components and this gets worse as the React components gets more complex.
- How to use Spinners while the page is fetching the API data.

### If I had more time I would change this

- As I said in previous READMEs: Testing, testing and more testing.
- Other than that, I am more than happy with the website and it does its job very well.

### Continued development

After this website I am going to start building my Portfolio and leave theory a little bit to the side. After my Portfolio is finished I am planning to study Testing and TypeScript.

## Author

- Twitter - [@CokoEche](https://twitter.com/CokoEche)
- LinkedIn - [@jorgeecheverria-dev] (https://www.linkedin.com/in/jorgeecheverria-dev/)

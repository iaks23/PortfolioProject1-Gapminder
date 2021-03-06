[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![ForTheBadge makes-people-smile](http://ForTheBadge.com/images/badges/makes-people-smile.svg)](http://ForTheBadge.com)
[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://GitHub.com/Naereen/)
[![CATS](https://forthebadge.com/images/badges/contains-cat-gifs.svg)]()

[![Stars !](https://img.shields.io/badge/Star-If%20Useful-1abc9c.svg)](https://GitHub.com/Naereen/ama) [![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github)](https://github.com/Naereen/badges/) [![made-by-e](https://img.shields.io/badge/View-Profile-1f425f.svg)](https://github.com/iaks23)   [![PR Welcome !](https://img.shields.io/badge/PRs-Welcome-1abc9c.svg)](https://GitHub.com/Naereen/ama)

# Data Visualization & Analysis using Gapminder

> "The world cannot be understood without numbers. But the world cannot be understood with numbers alone.â - Hans Rosling, Factfulness

## Table of Contents

* [Objective ð¡](#objective)
* [Pre-Requisites âï¸](#pre-requisite)
* [Gapminder ð](#gapminder)
* [Statistics That Bring Joy ðð»ââï¸](#discussion)
* [Conclusion ð§](#end)

----

# ð¡ Obective <a name="objective"></a>

Before we begin, let me ask you a question,

### In the last 20 years, the proportion of the world population living in extreme poverty hasâ¦

- [] Almost doubled
- [] Remained more or less the same
- [] Almost halved

> hint: it's really never as bad as you think it is. 

When we see think about the world, we think wars, pandemic, hunger, and extreme poverty. With this pre-conceived picture painted in our heads we think that the world today is in a really bad place and is only going to get worse. The correct answer for the above question is Option C, i.e. the majority of the world population today have moved out of extreme poverty and are living a decent life. 

The late Hans Rosling, discovered that only 7% of the entire world population got that right. He asked a few more questions, and realized that almost everybody universally got most questions wrong. 

In fact, on an average, a chimpanzee scores better than a nobel laureate! 

![chimpgif](https://github.com/iaks23/PortfolioProject1-Gapminder/blob/main/img/chimp.GIF)

### Feel like you're up for a challenge? Take the [quiz](https://upgrader.gapminder.org) yourself!

And so, in order to fight global ignorance and to make us stress-free about the world, Hans began [Gapminder](https://www.gapminder.org/about/about-gapminder/history/), and also published the book Factfulness, which contains accurate, factual data that tells us how to battle negative world views, ignorance, and misconceptions. They are some of the best [statistics](https://www.youtube.com/watch?v=hVimVzgtD6w) that you will ever see!

Inspired by the book, I wanted to recreate these joyful graphs myself to see the progress humanity has made in the span of just 50 years. Reading the book was truly a humbling experience, and only increased my hunger for curiosity. I hope this mini project has the same effect for you. 

![sparkjoy](https://github.com/iaks23/PortfolioProject1-Gapminder/blob/main/img/joy.GIF)

# âï¸ Pre-Requisites <a name="pre-requisite"></a>

To run this program or to try it out for yourself, make sure to have Python 3 installed in your computer with an IDE of your choice. I have used the Jupyter Notebook which comes as a part of the Anaconda library. You can find more details about installation and setup [here](https://www.datacamp.com/community/tutorials/installing-anaconda-windows)

Mac OS users can follow [this](https://www.anaconda.com/products/individual-d) tutorial.

You will also require <code>Pip</code> in order to install certain packages such as <code> Pandas </code>, <code> Numpy </code> and <code> Plotly </code>

Once you have Python installed, run this command to get Pip.

```python
$ python get-pip.py
```

> â¼ï¸ Do leave me a message in case you face issues on installation!

# ð Gapminder <a name="gapminder"></a>

The gapminder dataset I am working with is built-in and available on <code>Plotly</code>. It has a total of <code>1708</code> rows. 

The timeline of the dataset is from 1952-2007. 

The main columns I will be working with are, 

- <code>Year</code>
- <code>gdpPercap</code>
- <code>lifeExp</code>
- <code>Pop</code>

# ðð»ââï¸ Statistics That Bring Joy <a name="discussion"></a>

### Plotting LifeExp against Year for a Specific Country

![indiachart](https://github.com/iaks23/PortfolioProject1-Gapminder/blob/main/img/lifeExpIndia.png)

#### Joyful Fact #1

On an average a person in 1950's India was living upto 37.3 years, but with significant advancements the life expectancy has moved all the way up to 65 years! Life expectancy all around the world today is around 70 years thanks to better access to healthcare, food, and even education. 

>ð¡ tip: Check out stats for countries like Iran & Iraq! You'd be really surprised!

### Plotting GdpPerCap against LifeExp for Individual Countries

In his book, Factfulness, Hans stresses that we move away from the terms "developing" v/s "developed" nations and proposes 4 LEVELS to classify the world, in order to overcome "The Gap Instinct" 

Here's the GDP per capita and life expectancy for countries in the year 1972. 

![gdp1972](https://github.com/iaks23/PortfolioProject1-Gapminder/blob/main/img/country1972.png)

It is understandable that most low-income countries have low life expectancy. But have the poor gotten poorer? 

![gdp2007](https://github.com/iaks23/PortfolioProject1-Gapminder/blob/main/img/country2007.png)

#### Joyful Fact #2

Within 30 years, most countries have pushed themselves from extreme poverty to middle-class standards. Ofcourse, in 2021 this number is even greater! There is no "gap" anymore since a majority of the countries fall in the middle. Nearly 85% percent of the world has moved to "developed" (i.e. Level 2 & 3), yet the worldview has not changed. 

### The Infamous Bubble Plot

How cool has humankind been these past few years? What have we not tackled and how much have we leaped! 

![animatedcountry](https://github.com/iaks23/PortfolioProject1-Gapminder/blob/main/img/country.gif)

The journey of our world, in 10 seconds or less. 

![animatedworld](https://github.com/iaks23/PortfolioProject1-Gapminder/blob/main/img/world.gif)

> :bulb: tip: Check out how the world has evolved in terms of GdpPerCap!


# ð§ Conclusion <a name="end"></a>

There is no denying that things are bad, but the world is getting better. Use free data sources around you to stay updated, aware, and factful. 

---------

ð if you found this project useful! 

Â© Akshaya Parthasarathy, 2021 

If you want to talk about this amazing book or provide feedback about my project, don't hesitate to leave me a message!

[![LINKEDIN](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akshaya-parthasarathy23)
[![INSTAGRAM](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/aks_sarathy/)
[![REDDIT](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/user/longstoryshort_)

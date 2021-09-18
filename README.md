# Elemes Food // Recipe

This website is built in order to finish a challenge from Elemes.id for Frontend Developer position. 
Built with Nuxt and Tailwind, also deployed to Heroku.

<p align="center">
  <img src=".assets/doc/landing.png" alt="Landing page" width="740">
</p>

## Workflow

Here's my workflow when building this website

```bash
# creating nuxt app
$ npx create-nuxt-app elemesfood

# serve with hot reload at localhost:3000
$ npm run dev

# creating tailwind config file
$ npx tailwindcss init

# setup colors and font inside Tailwind config file, then code the components and pages and deploy to Heroku
```


## `Colors and Fonts`

Setup for the colors and font is done by tailwind config by doing this to make stylesheet output

<p align="center">
  <img src=".assets/doc/build.png" alt="Landing page" width="740">
</p>

<p align="center">
  <img src=".assets/doc/theme.png" alt="Landing page" width="740">
</p>

## `Heroku Deployment`

```bash
# creating heroku app
$ heroku create elemesfood

# add Node.js buildpack
$ heroku buildpacks:set heroku/nodejs

# configure app host
$ heroku config:set HOST=0.0.0.0

# push the app on Heroku
$ git push heroku main

#More information about the usage of this directory in [the documentation](https://nuxtjs.org/integrations/deployments/heroku/).
```


### `difficulty`

For the difficulties that I face during this challenge is actually on some breakpoints issues.

I still figuring out how to make this overflow container scrollable and swipeable without showing the scrolls and with buttons as well.

<p align="center">
<img src=".assets/doc/cardoverflow.png"
  width="686" height="289">
</p>

And I have a little bit of problem with label form on the footer

<p align="center">
<img src=".assets/doc/footer.png"
  width="686" height="289">
</p>

### `potential`

I think I should've make data.js and use v-for for the cards, it would be better.
And I still look for the solution for the problem that I mention above.

### Installation

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

### `Thankyou Elemes.id for the opportunity!`

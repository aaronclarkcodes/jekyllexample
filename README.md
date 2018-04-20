# Particle Jekyll Theme

![](./particle.jpg)

This is a simple and minimalist template for Jekyll designed for developers that want to show of their portfolio.

The Theme features:

- Gulp
- SASS
- Sweet Scroll
- Particle.js
- BrowserSync
- Font Awesome and Devicon icons
- Google Analytics
- Info Customization

## Basic Setup

1. [Install Jekyll](http://jekyllrb.com)
2. Fork the [Particle Theme](https://github.com/nrandecker/particle/fork)
3. Clone the repo you just forked.
4. Edit `_config.yml` to personalize your site.

## Site and User Settings

You have to fill some informations on `_config.yml` to customize your site.

```
# Site settings
description: A blog about lorem ipsum dolor sit amet
baseurl: "" # the subpath of your site, e.g. /blog/
url: "http://localhost:3000" # the base hostname & protocol for your site

# User settings
username: Lorem Ipsum
user_description: Anon Developer at Lorem Ipsum Dolor
user_title: Anon Developer
email: anon@anon.com
twitter_username: lorem_ipsum
github_username:  lorem_ipsum
gplus_username:  lorem_ipsum
```

**Don't forget to change your url before you deploy your site!**

## Color and Particle Customization
- Color Customization
  - Edit the sass variables
- Particle Customization
  - Edit the json data in particle function in app.js
  - Refer to [Particle.js](https://github.com/VincentGarreau/particles.js/) for help

## Running the blog in local

In order to compile the assets and run Jekyll on local you need to follow those steps:

- Make sure [NodeJS](https://nodejs.org/) is installed
- - run 'node -v' or install via Homebrew
- - 'ruby -e $(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)' then 'brew install node'
- Install [Gulp](https://gulpjs.com/)
- - 'npm install gulp-cli -g' then 'npm install gulp -D'
- Run `npm install`
- Run `gulp`
- If you get a '-bash: gulp: command not found' error:
- - Run 'npm config set prefix /usr/local'
- - Then run 'sudo npm install gulp -g'. Enter your user admin password to install gulp globally
- - Then Run 'gulp' again

## Customization
To change the content on the sections of the site (about, header, projects, footer etc) edit the corresponding .html file in the 'includes' folder
To change the overall layout of what sections are displayed, edit the default.html file in the layouts folder.
See above for changing the user settings (what is show in the header of the site)
The index.html page just references the default layout (leave this as is)

## License

This theme is free and open source software, distributed under the The MIT License. So feel free to use this Jekyll theme anyway you want.

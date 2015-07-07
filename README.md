<a target="_blank" href="https://chrome.google.com/webstore/detail/epgmnmcjdhapiojbohkkemlfkegmbebb">![Try it now in Chrome Web Store](/images/chrome-web-store.png "Click here to install this extension from the Chrome Web Store")</a>


Selenium Page Object Generator
==============================

A nimble and flexible [Selenium Page Object Model](https://code.google.com/p/selenium/wiki/PageObjects) generator to improve [agile testing](https://en.wikipedia.org/wiki/Agile_testing) [process velocity](https://en.wikipedia.org/wiki/Velocity_(software_development)).

[Selenium Page Object Generator](https://chrome.google.com/webstore/detail/epgmnmcjdhapiojbohkkemlfkegmbebb) is an essential tool to improve your workflow. It will generate [Page Object Model](http://martinfowler.com/bliki/PageObject.html) on active [Chrome](https://www.google.com/chrome/browser/desktop/index.html) tab with a single click, provided that all the options and template are configured. The generated Page Object Model will be saved to pre-configured Chrome download folder.

The template is using [Handlebars.js](http://handlebarsjs.com/) expression, a clean logic-less semantic templating language.

This is an early BETA release, it expected to have rough edges, and limited functionality. It currently support 3 different targets: [Java](https://en.wikipedia.org/wiki/Java_(programming_language)), [C#](https://en.wikipedia.org/wiki/C_Sharp_(programming_language)), and [Robot Framework](http://robotframework.org/).

For more information on how to use the generated Page Object file:

Java: [https://code.google.com/p/selenium/wiki/PageFactory#The](https://code.google.com/p/selenium/wiki/PageFactory#The)

C#: [http://relevantcodes.com/pageobjects-and-pagefactory-design-patterns-in-selenium/#post-5229](http://relevantcodes.com/pageobjects-and-pagefactory-design-patterns-in-selenium/#post-5229)

Robot Framework: [http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#taking-resource-files-into-use](http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#taking-resource-files-into-use)

(You need to use Chrome 40+ to try this out)

Installation
-
To install the newest released version, please download it from [Chrome web store](https://chrome.google.com/webstore/detail/epgmnmcjdhapiojbohkkemlfkegmbebb).

Development
-
To build the sources into corresponding packages, run:

```bash
$ gulp
```

The `/build` folder and `/dist` folder are created. All built files are placed in the `build` folder, and the distribution ready packages are placed in `dist` folder.

Distribution
-
Once the changes are in-place and ready for distribution, update `package.json` with new version, and run:

```bash
$ gulp
```

The `/dist` folder will contain distribution ready packages.

Dependencies
-
You’ll need to install [Node.js](https://nodejs.org/) as a local development dependency. The `npm` package manager comes bundled with all recent releases of `Node.js`.

`npm install` will attempt to resolve any `npm` module dependencies that have been declared in the project’s `package.json` file, installing them into the `node_modules` folder.

```bash
$ npm install
```

License
-
Copyright (c) 2015 Richard Huang.

This browser extension is free software, licensed under: [GNU Affero General Public License (AGPL-3.0)](http://www.gnu.org/licenses/agpl-3.0.en.html).

Documentation and other similar content are provided under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

Screenshot
![screenshot](/images/popup.png)

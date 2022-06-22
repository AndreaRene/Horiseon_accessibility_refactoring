# UTAB Module 1 Challenge 

In this project I was tasked with refactoring HTML and CSS code. The task I was given was to meet the acceptance crietera while maintaining the design and functionality of the page. The user story and acceptance criteria are as follows: 

User Story:

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

Acceptance Criteria: 

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Starter Code

The HTML and CSS starter files which were provided are located [here](https://github.com/AndreaRene/Module_1_Challenge/tree/main/Starter_Code). Some of the issues are as follows:

* The starter HTML code was missing numerous semantic elements and was not optimized for accessibility. 
* The CSS code had repeating selectors and properties which needed to be consildated and organized. 
* The webpage had a broken link which needed to be fixed.

### An example of the starter code:

![An image depicting portions of the HTML and CSS starter code.](./assets/starter-code-example.PNG)

## Refactoring

My refactored HTML and CSS files are located [here](https://github.com/AndreaRene/Module_1_Challenge/tree/main/Refactored_Code). Some of the steps I took to resolve the issues are as follows:

* Provided a unique title and description meta to make the website stand out on SERPs.
* Removed/replaced div elements in HTML code with more semantic elements including header, main, nav, and article.
* added alt attributes to images in the main body of the page to provide more accessibility to users utilizing screen readers.
* Consolidated CSS selectors and properties by adding/changing classes/ids in elements with repeated styling.
* Added commentation to CSS file.
* Fixed broken link in HTML.

### An example of the refactored code:

![An image depicting portions of the HTML and CSS refactored code.](./assets/refactored-code-example.PNG)




### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

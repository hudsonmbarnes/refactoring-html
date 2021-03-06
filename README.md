# Refactoring HTML and CSS

## Website Description

This website gives image examples and helpful tips on subjects such as Online workspace optimization and Social Media marketing

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Github and Gitlab accounts
GitBash or Terminal
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Clone the code to your terminal
Pull from the repository
View on Visual Studio Code
```

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Deployed Link

* [See Live Site](https://hudsonmbarnes.github.io/refactoring-html/)

## What I did

Within the HTML, I checked for anything unessessary and removed if so, added the missing alt tags to all images, made sure all links were functional and corrected them if not, and added semantic HTML elements.
Within the Stylesheet, I made sure the classes matched the updated HTML elements, made sure everything wasin sequential order, grouped together classes with the same attributes, and removed any unessessary classes.
This was all to help with functionality for now and the future as well as organization.

## Code Snippet

```
<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>website</title>
</head>
<!-- Added semantic element "header" -->
<body>
    <header>
        <!-- Removed unessessary span tag and class in header -->
        <h1>Horiseon</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </header>

```

## Editors

* **Hudson Barnes**
- [Link to Github](https://github.com/hudsonmbarnes)
- [Link to LinkedIn](https://www.linkedin.com/in/hudson-barnes-398483151/) 


## Authors

* **Horiseon Social Solution Services, Inc.** 


## License

This project is licensed under the MIT License 

## Acknowledgments

* W3schools.com
# Introduction
>***All HTML documents have the same basic structure or boilerplate that needs to be in place before anything useful can be done. In this lesson, we will explore the different parts of this boilerplate and see how it all fits together.***

# Lesson overview
 This section contains a general overview of topics that you will learn in this lesson.

* How to write the basic boilerplate for an  HTML document.
* How to open HTML documents in your browser.

# Creating an HTML file

To demonstrate an HTML boilerplate, we first need an HTML file to work with.


Create a new folder on your computer and name it ```html-boilerplate```. Within that folder create a new file and name it ```index.html```.


You’re probably already familiar with a lot of different types of files, for *example* doc, pdf, and image files.

To let the computer know we want to create an HTML file, we need to append the filename with the ```.html``` extension, as we have done when creating the ```index.html``` file.

# Basic HTML boilerplate

The basic HTML5 boilerplate code looks like this:
```javascript
<html lang="en">
<head>
    <title>Your Page Title</title>
</head>
<body>
    <!-- Your content goes here -->

</body>
</html>
```
## Boilerplate improved
 ```javascript
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Page Title</title>
</head>
<body>
    <!-- Your content goes here -->

</body>
</html>
```
This is a simple template that includes the necessary HTML5 document structure with the standard ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` elements. It also includes the character set meta tag, viewport meta tag for responsive design, and a title for your webpage.

# Validate your HTML

* [click here for more information]

[click here for more information]:https://validator.w3.org/#validate_by_inpu

Validating your HTML with a tool like the W3C HTML Validator is important for several reasons:

1. *_Standards Compliance_*: The W3C (World Wide Web Consortium) sets the standards for HTML. By validating your HTML, you ensure that your code follows these standards. This is crucial for cross-browser compatibility and helps ensure that your web pages render consistently across different devices and browsers.

2. *_Accessibility_git*: Valid HTML is essential for creating accessible websites. Web accessibility is about making your content available to all users, including those with disabilities. Valid HTML helps assistive technologies (like screen readers) interpret and present your content accurately.

3. *_Search Engine Optimization (SEO)_*: Search engines often rely on well-structured and valid HTML to understand and index web pages properly. Valid HTML can contribute to better search engine rankings and improve the visibility of your website in search results.

4. *_Maintenance and Debugging_*: Valid HTML is generally easier to maintain and debug. It helps you identify and fix errors in your code more efficiently. Validating your HTML can catch syntax errors, missing tags, or other issues that might otherwise lead to unexpected behavior.

5. *Future Compatibility*: Following HTML standards and validating your code makes it more likely that your website will be compatible with future technologies and updates. It helps ensure that your code remains relevant and functional as web standards evolve.

6. *Consistency*: Valid HTML promotes consistency in coding practices. It encourages a clean and organized structure, making it easier for developers to collaborate on projects and understand each other's code.

7. *Error Prevention*: Validating your HTML can catch common mistakes early in the development process, preventing issues that might arise later and saving you time in the long run.
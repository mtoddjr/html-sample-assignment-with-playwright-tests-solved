# Exercise: Sample HTML Assignment

In this exercise you will learn to operate with assignments of the HTML&CSS curriculum.

## Learning objectives

This assignment should prove that a student is able to:

- Fork from the project repository
- Clone the project to your computer
- Install dependencies
- Run tests
- Read and understand test results
- Check the status of the local git repository
- Add changed files to staging
- Commit git repo changes
- Push code updated to the remote repository
- Submit assignments as Github repo URLs

## Standard requirements

- [X] Fork the project to your github account
- [X] Clone the project to your computer
- [X] Open the project in VSCode with `code <cloned_repo_folder_name>`
- [ ] Initialize playwright and install project packages
  - [X] Use `npm i` to install packages
        - it is okay to see warnings after this steps - as long as node_modules folder is created you are alright!
  - [X] Use `npm run browser-install` to install the browser environment for testing 
- [X] All the tasks of the "Specific requirements" section MUST be solved
- [ ] All the tests MUST pass. Fix the errors in case any tests don't pass BEFORE you submit (acceptance criteria)
  - [ ] Use `npm run test` to run all tests in the terminal
  - [ ] (Optional) Use `npm run test-ui` to run all the tests with GUI
  - [ ] (Optional) Use `npm run show-report` to see the latest report in the browser
- [ ] VSCode IDE MUST have 0 code problems listed (spelling problems are fine)
- [ ] The code MUST be formatted with Prettier
- [ ] Push the changes to the Github repo, when finished.
- [ ] Submit a txt file with the Github repo url.

## Specific requirements

- [X] Create an html file with the name of "index" in the root of the project
- [X] Add HTML Boilerplate to the document
  - [X] confirm the head tag has a meta tag that defines the charset
        
  ```html 
  <meta charset="UTF-8">
  ```
  - [X] confirm the head tag has a responsive meta tag set
  ```html 
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ```
- [X] Set the document title in the head section to be "Sample project"
```html
<title>Sample project</title>
```
- [X] Set the page heading to be "Sample project"
```html 
<h1> Sample project </h1>
```
- [X] Add a paragraph of text (20 words at least). You can use random text for the paragraph content.
```html 
<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sint vitae, libero quae quasi nemo dignissimos consectetur cumque. Ipsum laborum libero iure.</p>
```

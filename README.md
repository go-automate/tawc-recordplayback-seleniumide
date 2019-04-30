elenium:
Documentation: very good
Running Headless: Yes
Continuous Integration : can run on all browsers from the command line, parallel running
Flaky: no
Run speed: Fastest frame work I have used so far
Data-Driven: No data driven options so limited to hardcoded inputs
CrossBrowser: Available across Chrome and Firefox – no IE :(
Version control: Not integrated into the app, but can be done with git.
Data Driven plugins: I think they are not maintaining the framework and have discontinued the updates. If this framework had datadriven properties it would have been by far the best I have used.
Positives: The framework has inbuilt waits – worked on slow website!
Funtionality: Simple record button which creates a test case that can be run easily.
Can only identify product in table if it’s the only product in the list. Could not identify a product in the list if there were more than one or there were different products?
Can’t have pre-reqs or setups.
Might be able to loop to clear down the table first – can re-use steps from other test cases though.

Downsides:
- No Setup / Prereq steps?
- Can’t do data driven
- Had trouble uniquely identifying a new product in a list – worth trying to replace the generated locators with our ones and see if that works – bit of a workaround, but ok.

https://www.seleniumhq.org/selenium-ide/docs/en/introduction/command-line-runner/ 

Tricky to identify elements on the page that aren’t obvious, but may be useful in uniquely identifying the page. Can’t assert on the URL either? If the title is the same for every page, then you have to choose something on the page to confirm that you’re on the correct page.

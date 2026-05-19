## Ophir Maor, Andrew Lopez
## Check Your Understanding

### 1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

* **"Within a GitHub action that runs whenever code is pushed"**
* **Why:** The reason I chose this answer is because automated tests are used as early bug detection patterns. Running these test with GitHub actions(CI/CD pipeline) ensures that the new code won't create a merge conflict when merged into the Main branch, thus preventing broken code from merging. 

### 2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

* **No**


### 3) What is the difference between navigation and snapshot mode?

* **Navigation mode:** Analyzes the page right after it loads, so it is best for checking the overall page-load performance and user experience of the site.
* **Snapshot mode:** Analyzes the page in its current state, so it is better for checking things like accessibility issues on the current DOM, but it does not measure page load performance or JavaScript behavior over time.

### 4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

* Improve the **Speed Index**, since Lighthouse showed it taking 12.0 seconds.
* Optimize images and other page assets so the visible content loads faster.
* Improve accessibility by adding clearer labels, alt text, and better structure for buttons, headings, and interactive elements.

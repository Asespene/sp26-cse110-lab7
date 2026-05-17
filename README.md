# Angelo Jas Sespene

## Check Your Understanding

**1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.**

- Within a Github action that runs whenever code is pushed  
- Manually run them locally before pushing code  
- Run them all after all development is completed  

It should be within the Github action that runs whenever code is pushed. The integrated automated tests is an industry standard for Continious Integration. This runs scripts automatically when code is pushed to a remote repo and ensures that any bugs or breaking changes are caught before the code is merged into the main production branch. It's a fast hands-free feedback for the entire dev team.

**2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)**

No, E2E or End-to-end testing is specifically designed to copy how an actual user uses the webpage and enures that this faults are caught. On the other hand, unit testing is when we are testing isolated functions to ensure that it returns the correct output.



## 3) Difference between navigation and snapshot mode

**Navigation Mode**
This is a mode that immediately analyzes the webpage after the intial load. It's designed to provide an overall performance metric for this intial loading phase, meaning that it does not analyze the user interaction or changes within the page.

**Snapshot Mode**
In this mode we analyze the webpage current state during the moment an audit is triggered. This is great for pinpointing any accessibility issues on the components that requires interactions to appear. But this does not analyze the JS runtime and execution performance or even the structural changes to the DOM tree.


## 4) Three ways to improve the CSE 110 shop site

1. Add **Alt text** and also fix the broken links. This helps repair the broken image paceholders that we can see on the storefront, and it provides a description using the alt atrributes which is helpful for accessibility.

2. Compress the images of the storefront products to help boost the performance.

3. Minimize script blocking, this helps JS assets have a smoother initial page loads. Improves both **Performance** and it is a good practice.

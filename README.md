# Lab 7

## Team Member(s)

Ki Diaz

## Check your Understanding

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
    - Within a Github action that runs whenever code is pushed. It happens automatically, so it cuts down work for developers, and it also blocks pull requests, so only code that passes all the tests can be pushed to the branch with the action.
2) Would you use an end to end test to check if a function is returning the correct output?
    - No.
3) What is the difference between navigation and snapshot mode?
    - Snapshot mode analyzes the page in its current state and is good to access accessibility. However, it cannot provide an overall performance score or metrics. It also can't analyze any issues outside the current DOM (e.g. no network, main-thread, or performance analysis).

    - On the other hand, navigation mode analyzes the page immediately after page load and does give an overall performance score and all performance metrics. However, it cannot analyze content that isn't available immediately on page load, and it can't analyze form submissions or single page app transitions.
4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
   - we could add a _lang_ attribute to the _html_ element
   - we could add a _meta_ description to the html document
   - we could avoid chaining critical requests in the network dependency tree to reduce page load times.

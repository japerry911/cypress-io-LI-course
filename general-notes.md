# Notes

- Cypress.io
  - test all flows/clicks/actions
  - advantages
    - easier than Selenium
    - tests run inside a real browser
      - not headless like Selenium
    - takes into account element visibility
    - has access to all brwoser resources
      - can take screenshots, etc...
    - very readable
  - disadvantages
    - only language is JavaScript
    - can't test multiple tabs/multiple browser windows at the same time
    - can't visit two super domains in one test (for example, google/linkedin)
  - `npx cypress open`

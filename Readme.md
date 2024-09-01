Install:
# How to Start
1. Clone the project
2. Run `npm i` to install all the dependencies
3. Run `npx playwright test` to execute the tests
4. Run `npx playwright test src/testcases/example/example.spec.js` to execute a single test
5. Run test in ui mode `npx playwright test --ui`
6. Show reporting npx `npx playwright show-report`


* [Documentation](https://playwright.dev/docs/intro)
* [API reference](https://playwright.dev/docs/api/class-playwright/)
* [Changelog](https://github.com/microsoft/playwright/releases)

Tools Codegen:
Codegen Record browser code automation:
1. npx playwright codegen --help
2. npx playwright codegen [URL] -o [Filename]
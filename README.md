# ToDo UI E2E tests 
UI E2E tests implemented using [Playwright framework](https://playwright.dev/). Test suit contains positive and negative scenarios to cover basic  Create, Edit,
Complete and Delete to-dos from the list. 

Test scenarios are executed against simple [ToDo web app](https://todomvc.com/examples/angular2/) and utilizing [Page object approach](https://playwright.dev/docs/test-pom)


## Installation

To run tests please use Node.js version >= 16.x

```bash
npm install
npx playwright install 
```

## Usage

```bash
npx playwright test
```

## Test Coverage
The test suite covers the following operations of TODO APP:
- [x] NEW
- [x] EDIT
- [x] DELETE
- [x] COMPLETE



# Playwright Project for Testing Playwright Demo Site

This Playwright project contains automated tests for the Playwright demo site.

## Setup

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

## Running Tests

To run the tests, use the following command:

```bash
npx playwright test
```

## Test Details

- `tests/playwright-demo.spec.ts`: Contains tests for the Playwright demo site.
  - Checks if the homepage has "Playwright" in the title.
  - Verifies the "Get started" link and its redirection to the introduction page.

## Notes

- Make sure you have Node.js installed on your machine.
- This project uses Playwright for end-to-end testing.

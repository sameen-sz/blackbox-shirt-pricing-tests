# Blackbox Shirt Pricing Test Suite

This project demonstrates black-box testing and browser automation for a shirt customization and pricing calculator.

## Live Demo

Open the application here:

https://sameen-sz.github.io/blackbox-shirt-pricing-tests

The app calculates shirt prices based on:

- waist size
- shirt length
- sleeve options
- collar options
- selected currency (USD or EUR)

## Automated Testing

The repository includes a Selenium IDE test suite that automates browser testing of the calculator.

Test cases include:

- basic shirt pricing
- collar option
- sleeve option
- currency changes
- boundary input testing
- edge cases (zero values, max values)

## Files

| File | Description |
|-----|-------------|
| `index.html` | Shirt customization calculator |
| `automation/shirt-pricing-tests.side` | Selenium IDE automated test suite |
| `blackbox-test-plan.pdf` | Black-box testing documentation |

## How to Run the Selenium Tests

1. Install **Selenium IDE** in Firefox
2. Open Selenium IDE
3. Load the file: automation/shirt-pricing-tests.side
4. Set the **Playback Base URL** to: https://sameen-sz.github.io/blackbox-shirt-pricing-tests
5. Run the tests

## Skills Demonstrated

- Black-box testing
- Boundary value analysis
- Automated UI testing
- Selenium IDE
- Web application testing
- QA automation

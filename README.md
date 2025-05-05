# Text Formatting & Styled Webpage Demo

## Project Overview

This project comprises a basic HTML webpage designed to illustrate fundamental concepts of HTML structure and CSS styling. Developed as part of the Software Test Automation Level 1 curriculum, it serves as a practical example of common web elements and their presentation. The webpage includes various headings to demonstrate hierarchy, paragraphs for textual content, both unordered and ordered lists to display items, emphasis using `<em>` and `<strong>` tags, a hyperlink to an external website, and a simple form with a submit button.

The primary goal of this project, within the context of the Software Test Automation Level 1 course, is to provide a simple yet functional application that can be used as a target for practicing introductory UI test automation techniques. By interacting with the elements on this page, students can learn the basics of locating web elements, performing actions, and verifying expected outcomes.

## Project Structure and Files

The repository contains the following files:

- `index.html`: This is the main HTML document that defines the structure and content of the webpage. It includes all the headings, paragraphs, lists, links, and the form elements that are displayed in the browser.
- `style.css`: This Cascading Style Sheet file is responsible for the visual presentation of the `index.html` content. It defines styles for the navigation menu, the submit button, the overall page background, text colors, and the layout of the main content area.

## Relevance for Software Test Automation

This seemingly simple webpage offers a valuable platform for learning and practicing fundamental software test automation skills. Its key elements allow for the creation of various test scenarios, such as:

- **Content Verification:** Ensuring that specific text content, like headings and paragraph text, is present and correctly displayed.
- **Navigation Testing:** Validating that the navigation links are present and redirect to the intended pages (in this case, the "Home," "About," and "Contact" links, though they are currently placeholders).
- **List Validation:** Checking the number and order of items in both unordered and ordered lists.
- **Text Emphasis Testing:** Verifying that the `<em>` and `<strong>` tags correctly apply emphasis to the text.
- **Link Functionality:** Confirming that the "example website" link navigates to `https://www.example.com`.
- **Form Interaction:** Practicing interaction with form elements, such as locating and clicking the submit button.
- **Visual Testing:** Basic visual checks to ensure that the CSS styles are applied correctly, such as background colors, text colors, and the appearance of the navigation menu and button.

## Getting Started

To view this demonstration webpage, you do not need any special software or setup. Simply clone this repository (if you haven't already) and open the `index.html` file in your preferred web browser (e.g., Chrome, Firefox, Safari). The browser will render the HTML content and apply the styles defined in `style.css`.

## Further Learning and Exploration

This project can be extended for further learning in test automation. Some potential exercises include:

- Writing automated tests using tools like Selenium, Cypress, or Playwright to interact with the elements on this page.
- Adding more complex HTML elements and CSS styles to create more challenging test scenarios.
- Practicing different locators (e.g., ID, class, XPath, CSS selectors) to target specific elements for automation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

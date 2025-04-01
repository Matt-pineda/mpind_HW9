# Business Analytics Student Survey

This project is a four-page responsive web form designed to collect basic student background information for the Business Analytics & Information Systems (BAIS) department at the University of Iowa. The form was built using HTML5, CSS3, Bootstrap 5.3, and Font Awesome, and is deployed as a live Azure Static Web App.

## ✅ Form Best Practices

This web form follows key best practices in form design to ensure clarity, usability, and proper data collection. The form uses a logical and intuitive layout across four distinct pages: a welcome page, two pages of data collection, and a final confirmation page. Each input field is clearly labeled, and required fields are clearly marked with visual indicators to reduce submission errors. Inputs are grouped by related content, making the form easier to navigate and complete.

Input types are carefully chosen to match the type of data being collected. For instance, radio buttons are used for mutually exclusive questions (such as academic year), while checkboxes are used for questions where users can select multiple options (such as completed courses). Dropdowns are implemented to standardize answers and reduce user effort when selecting from a long list (e.g., U.S. states and BAIS impressions). The form also includes tooltips that provide helpful contextual guidance without cluttering the main interface.

Responsiveness is built in using Bootstrap's grid and utility classes to ensure the form looks and works well on both desktop and mobile devices. Each form page validates as HTML5 and CSS3, ensuring technical compliance and forward compatibility with modern browsers.

## ♿ Accessibility

The form was designed with accessibility in mind and aligns with WCAG 2.1 Level AA standards. Semantic HTML is used throughout, including `<label>` elements properly linked to form inputs using `for` and `id` attributes. Required fields are visually marked and programmatically enforced using the `required` attribute.

Font Awesome icons are accompanied by tooltips to deliver additional information without relying solely on visual cues. Text contrast is kept high for readability, and focus indicators are preserved to support keyboard navigation. The form also uses clear language, logical tab order, and the `autofocus` attribute on the first field to streamline the user experience for all users, including those using screen readers or keyboard-only navigation.

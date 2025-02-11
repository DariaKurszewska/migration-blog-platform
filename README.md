**Project Overview**

This project is focused on the **eKanada Migration Blog**, a platform providing valuable information for individuals migrating to Canada. The website/blog has been in use since 2016 and includes:

- Comprehensive guides on living in Canada.
- Information about immigration processes and required documents.
- Steps to take after arrival (administrative, legal, and documentation-related tasks).
- A community section on social media.
- Consultation services to help individuals prepare necessary documents, find accommodation, and navigate life in the new country.

**My Role in the Project**

After completing a software testing course to apply and further develop my skills, I started working on this project.

**Exploratory Testing**

- Conducted an exploratory testing session to understand the website’s functionality and identify areas for improvement.
- Documented findings in Confluence with a summary of identified issues.
- Logged issues in Jira, linking them to corresponding tickets.
- Identified eight issues:
  - One issue was fixed: the button leading to a 404 error was removed, improving the user experience. However, a new issue was identified: while the button was removed, the associated description text for the button remained.
  - The remaining seven issues were deprioritized due to the owner's focus on other tasks.

**Test Case Preparation**

- Designed test cases in Jira (Zephyr) for various functionalities, focusing on:
  - Navigation and documented page transitions.
  - Form validation using boundary value analysis and data correctness testing (e.g., missing '@' in required email fields).
  - Responsiveness testing to ensure proper display on mobile and desktop devices.

**Testing Scope**

- **Functional Testing:** Verified core functionalities such as navigation, menus, and dynamic content.
- **Error Handling:** Tested the site’s response to invalid data (without submitting real data), including edge case validation in form fields.
- **Responsiveness Testing:** Ensured the website adapts correctly to different screen sizes and devices, using BrowserStack and physical devices:
  - **Smartphone:** Samsung SM-S901B/DS (Android 14, OneUI 6.1) with Google Chrome v132.0.6834.165.
  - **Tablet:** Samsung SM-X210 (Android 14, OneUI 6.1) with Google Chrome v133.0.6943.49.
  - A discovered usability issue with responsiveness was linked to another usability issue: a full Google Forms URL in the content caused unwanted horizontal scrolling and incorrect popup positioning on mobile. Hiding the URL will resolve this issue.

**Task Management**

- Created and tracked tasks in Jira using a Kanban board.
- Documented tests and reports in Confluence.
- Conducted calls with the owner to present issue prioritization and recommendations for fixes.

**Issues Identified**

Below is a list of key issues I identified during testing:

**Functionality Issues:**

1. **Redirection to a 404 page after clicking the ‘Buy Me a Coffee’ button.** (Fixed, but the label still needs updating.)
2. **Access denied (403) error after clicking the "Real Canadian Superstore" link.**
3. **The Instagram icon in the footer does not redirect to the correct eKanada Instagram page.**
4. **Next and Previous buttons in blog articles display English labels instead of Polish.**

**Compliance & Usability Issues:**

5. **Full Google Form link displayed in content on the "Sesja Informacyjna" page instead of being embedded.**
6. **Missing checkbox or information for data sharing consent in all forms (subscription, contact, and registration).**
7. **No easy access to the Privacy Policy and Data Processing Information in the footer.**
8. **Cookie consent banner displayed in English on a Polish website.**
9. **Responsiveness issue caused by an unembedded Google Forms URL, leading to unwanted horizontal scrolling and misaligned popups on mobile.**

**Project Status**

- No updates are planned for the website in the near future.
- One issue has been fixed, improving user experience.
- Seven remaining issues are tracked in GitHub Issues, categorized as low or medium severity.
- I am currently involved in a new project with the same owner and will share details upon its official release.

**Authorization**

I have obtained permission from the website owner to publish and share information about my testing work on this project.

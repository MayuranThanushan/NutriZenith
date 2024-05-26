# NutriZenith
A Website that focuses on introducing the United Nations Sustainable Development Goal(SDGs) "Zero Hunger".

The website must include Splash Screen, Home Page + template + nav, Gallery, Shop, User Profile, Feedback, Sitemap, Team, Content page, Page Editor.

Splash Screen:
    The splash screen should prominently feature the website title and mission along with the names of the group members. It functions as a splash screen, providing an initial introduction to the site. After a brief duration of 4 seconds, it automatically redirects users to the Home page, ensuring a seamless transition into the main content. The splash screen could contain an animated image indicating that the home page is loading.

Home Page + website template + navigation bar:
    The Home page should prominently feature the logo of the website to establish its identity.
    The Home page should elaborate on the UN Sustainable Development Goal that the website is aligned with, conveying its purpose and commitment to sustainability.
    Navigation Bar should facilitate seamless navigation to other sections of the website. The navigation bar will be designed using CSS indicating the active page being browsed by the user and featuring a hover effect to highlight available links. The CSS styling may entail rendering links as buttons or incorporating a bottom border effect. We recommend using a class to denote the active page.
    The navigation bar will initially be created by Student 2 as part of the home page development. However, it's essential for all students to adapt and include this navigation bar on all other pages throughout the website to ensure a consistent look and feel. Student 2 is also responsible for creating an external CSS file that ensures a common look and feel for the website.
    The home page should also include Links to the 4 pages of the website dedicated to content this could look like a gallery
    The navbar could possibly a part of the website header. Student 2 will also create an external CSS file that establishes a unified template for the website. This may include a standardized header featuring the website identity (potentially incorporating a logo), a footer where each team member can include a link to their page editor, and general page styling. All team members will have to use this template and navigation bar to ensure a consistent look and feel of the website.

Gallery:
    Create a gallery page designed for engaging user experience allowing users to explore images and content relevant to your website's theme. Construct the HTML structure for each thumbnail image and its corresponding extended view. Integrate the following interactivity to the thumbnails:
    - when a user hovers over a thumbnail image, it should visually indicate that it's clickable, inviting interaction
    - upon clicking a thumbnail, it should expand to reveal an extended view with more detailed content
    - the extended view should display a larger version of the thumbnail image and include a detailed description associated with the image content, this could also popup.
    All images and descriptions should have appropriate alternative text for accessibility.
    Provide users with the ability to customize the colour scheme and font within the extended view for enhanced personalization.

Shop:
    The product showcase features a well-organized layout, showcasing product images, titles, descriptions, and prices where users can browse, and purchase products related to the theme of the website (it could be products for fundraising for the UN sustainability goal your website is about). The design ensures a smooth and intuitive shopping experience, with clear navigation and visually appealing product displays.
    The users should be able to customize the product purchase (e.g. product size, colour, other options).
    Each product listing includes an "Add to Cart" button, allowing users to select items they wish to purchase.
    The order summary (basket) captures information about the selected products (the list of the selected items, like thumbnails of the product added to the order, quantity, total).
    To proceed to checkout, users must select at least one product. A validation message prompts users to select items if they attempt to proceed without making a selection.
    The checkout section is where users finalize their purchases and provide necessary information for order processing like their personal details, contact information, and shipping address.
    Mandatory fields are clearly indicated, ensuring users provide essential information to complete the order. The form includes validation checks to verify that required fields are filled in correctly. Incorrectly filled fields are highlighted to prompt users for correction.
    Once all required information is provided and validated, users can proceed to complete their purchase.
    The system provides a message to confirm the completion of the order.
    The design prioritizes simplicity, guiding users through each step of the checkout process with clear instructions and feedback.

User Profile:
    Building a user profile progressively involves guiding users through a series of prompts to collect their information gradually and providing feedback for profile level of completion. Here's a description of how this process could be implemented:
    The system presents users with prompts, asking for basic information such as their name or username (use prompts not a form). Each prompt is designed to be concise and clear, guiding users through the process in a step-by-step manner. The prompts may cover various aspects such as personal details, preferences, interests, or any other relevant information required to build a comprehensive user profile relevant to the theme of the website you design.
    The prompts are organised in categories, such as personal details, tasks, qualifications, other (depending on the theme of the website you design)
    The progressive profile form should be built by at least 12 prompts and 3 steps.
    As users provide their information, the system progressively updates and displays their user profile. Initially, only basic details are shown, such as their name or username. As users provide each piece of information, the system dynamically adjusts and displays subsequent prompts based on their previous responses.
    The system also provides feedback on the profile completion progress ranging from a minimum level of completion for the first set of prompts to 100% completion for having completed all the steps.
    Users should have full control over the information they choose to provide and can opt to skip certain prompts or steps in the profile completion process. This flexibility should be reflected in both the displayed information of the user profile and the progress indicator for the profile completion process.
    Additionally, users should have the option to return to and complete any steps they initially skipped. This allows them to gradually enrich their profile with more detailed information, reflecting their preferences, interests, and other relevant data.

Feedback:
    Include input fields for users to enter their name, email (optional or mandatory based on requirements), rating and their comment or message. Optionally, include additional fields such as a subject line or category selection to categorize comments.
    The form should be set up to email the contents of the form to a valid email address (during the demo you will need to demonstrate that this feature works).
    Implement validation checks to:
    - ensure that email input is in the correct format
    - ensure that required fields are completed before submitting the form.
    Provide clear error messages and indications if users attempt to submit the form with missing or invalid information. Highlight the fields that require attention to assist users in correcting their input.
    Allow users to preview the feedback form and edit it before submitting it.
    Upon successful submission, display a confirmation message to acknowledge receipt of the comment.

Sitemap:
    The sitemap should be developed using Scalable Vector Graphics (SVG). The SVG sitemap will visually depict the hierarchical structure of the website, with parent pages represented as main branches and child pages as sub-branches.
    Each page of the website will be represented by a node (circle or rectangle) within the SVG canvas. Nodes are connected by lines (branches) to illustrate the relationships between pages. Each SVG node will be interactive by:
    - changing colour on hover
    - being a link to the corresponding page it represents.
    The SVG sitemap will be seamlessly integrated into the website's design, as a standalone page.
    The SVG sitemap should be responsive, adjusting its scaling to the browser window.
    Accessibility features such as alt text should be included for each node to ensure that users with disabilities can access and understand the sitemap. Keyboard navigation is supported to provide an alternative method for interacting with the sitemap.

Team:
    Create a team page to deliver an engaging user experience, enabling users to discover information about the team members who contributed to the development of the website.
    Construct the HTML structure for each thumbnail image and its corresponding extended view. The thumbnails should support the following interactivity upon hovering:
    - The thumbnail image should undergo a visual change, such as altering its alpha value, colour, border or size.
    - A box associated with the thumbnail should expand, revealing details about the corresponding team member, including their name, role in the group work, and tasks they were responsible for, similar to the bottom middle image.
    Additionally, ensure all images and descriptions have appropriate alternative text for accessibility purposes.

Content Page:
    Each team member is responsible for creating an additional content page related to your website's theme/topic. It's important to ensure that this page has sufficient length to allow for internal linking within the content. For pages longer than the screen size, include links at the top of the page to various sections within the text for easy navigation.

Page Editor:
    Each team member is tasked with creating an editor’s page. This page will feature your name, role in the group's work, and a list of completed tasks. This page can be treated as an external page, distinct from the group website, there's no requirement for it to adhere to the main website's design. This provides space for creativity and individual initiative.
    You should include a link to this page from all the pages in the website that you created and from the text description of this page there should be also links back to the pages you created.
    This page should open in a new tab.

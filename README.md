# News-Article-HTML

## Summary

Creating accessible websites is important and inclusive. Here's a summary of what we need to do and the steps we need to ensure accessibility:

- Use of Semantic HTML tags: Semantic tags such as <header>, <nav>, <main>, <section>, <article>, <footer>, etc. provide meaning and context to the elements on your page, helping assistive technologies understand the content better.
Alt tags for Images: Always provide alt text for images. This can help screen reader users understand the content of the image.

- Color Contrast: Ensure there's a sufficient color contrast between your text and its background. This makes it easier for people with color blindness or visual impairments to read your content.

- Keyboard Navigation: Make sure all interactive elements like links, buttons, forms, etc., are accessible and operable with a keyboard. This is crucial for people who can't use a mouse or are using screen readers.

- ARIA Roles: When appropriate, use ARIA (Accessible Rich Internet Applications) roles to provide additional context and meaning, especially for complex elements and interactions.

- Descriptive Links: Make sure all links are descriptive and make sense when read out of context. Screen reader users often navigate through a list of links, and links should make sense on their own.

- Clear Form Labels: If your website has forms, make sure each form element has a clear, associated label. This helps screen reader users understand what input each form field expects.

- Responsive Design: Ensure your website is responsive and works well on different screen sizes and orientations. This is important for users who may be using different devices, like smartphones or tablets, to access your website.

- Avoiding Flashing Elements: Provide an option for users to turn off flashing or moving elements, as these can cause issues for people with certain neurological conditions.

- Use of Headings: Use headings correctly to structure your content. This helps screen reader users understand the layout and quickly navigate to the section they're interested in.

Accessibility is not an afterthought but a key part of the design and development process. It's about creating a web that's usable by as many people as possible.

### The Task

For this task, you will be given a set of User Specifications/Business Requirements. 
👉 Your job is to build an HTML page following these user specifications/business requirements using Semantic HTML . The specifications are deliberately vague - it’s your job to identify which HTML elements would be the most appropriate to use! 
👉 The submission we are looking for is just an .html file in a GitHub repository

#### Use of all correct semantic HTML

Correct usage of Semantic HTML - I have used section tags where possible instead of div I have tested this code using the W3C MarkUp Validator https://validator.w3.org/#validate_by_input. I could navigate this page without using a mouse. I have used alt tags, as they provide description to the relevant images when using screen readers. I have used external CSS style sheets to make my page more accessible like using colour contrast, larger font size, bold etc.

##### CSS examples for accessibility

Creating visually distinct and accessible elements is crucial for a good user experience. Here are some CSS strategies to help achieve this:

Use appropriate colors: Ensure there is sufficient contrast between your text color and its background color to make it easy to read. There are many online tools that can help you check color contrast ratios.

Use clear typography: Choose fonts that are easy to read and set them to an appropriate size. Avoid using small font sizes.

Use space effectively: Adding space around your elements can make your webpage easier to read and navigate. This can include margins around blocks of text and padding inside elements.

Highlight links: Make sure links are clearly distinguishable from the rest of the text. You can style links using the a selector and the :hover and :focus pseudo-classes to change the appearance of links when they're hovered over or receive keyboard focus.

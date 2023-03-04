1. What are the main differences between external, internal, and inline CSS?

   - External CSS refers to styling rules that are stored in a separate file with a **.css** extension. This file is then linked to the HTML document using the `<link> `tag.
   - Internal CSS refers to styling rules that are placed within the `<head>` section of an HTML document, between `<style>` tags.
   - Inline CSS refers to styling rules that are applied directly to individual HTML elements using the style attribute.

2. What is the syntax for class and ID selectors?

   - Class Selector:
     ```css
     .class-name {
       /* CSS rules go here */
     }
     ```
   - ID Selector:
     ```css
     #id-name {
       /* CSS rules go here */
     }
     ```

3. How would you apply a single rule to two different selectors?

   - By using **group selectors**, we can apply the same rule to different selectors

4. Given an element that has an id of title and a class of primary, how would you use both attributes for a single rule?

   - ```css
     #title.primary {
       /* CSS rule */
     }
     ```

5. What does the descendant combinator do?

   - It selects all elements that are descendants of a specified parent element in the HTML document. In other words, it allows you to target elements that are nested within other elements

6. Between a rule that uses one class selector and a rule that uses three type selectors, which rule has the higher specificity?

   - A rule that uses three type selectors has a higher specificity than a rule that uses one class selector.

7. From inside to outside, what is the order of box-model properties?

   - Content, Padding, Border, and Margin.

8. What does the box-sizing CSS property do?

   - It controls how the size of an HTML element is calculated, including its padding and border

9. What is the difference between the standard and alternative box model?

   - The standard box model calculates the size of an element based on its content, padding, border, and margin. This means that if you set the width or height of an element, it will be calculated based on the content plus any padding, border, and margin that you have added.

   - The alternative box model, also known as the "border-box" model, calculates the size of an element based on its content, including padding and border, but excluding margin. This means that if you set the width or height of an element, it will be calculated based on the content plus any padding and border, but without adding any extra space for margin.

10. Would you use margin or padding to create more space between 2 elements?

    - Margin

11. Would you use margin or padding to create more space between the contents of an
    element and its border?

- Padding

12. Would you use margin or padding if you wanted two elements to overlap each other?

    - None, I would use `z-index` and `position`

13. What is the difference between a block element and an inline element?

- Block-level elements take up the full width available on the page.
- Inline-level elements do not start on a new line and only take up as much width as necessary for their content.

14. What is the difference between an inline element and an inline-block element?

    - inline-block elements are more flexible than inline elements for layout purposes. They allow you to set specific dimensions, apply padding and margins on all sides, and adjust their vertical alignment. However, inline elements can be useful for styling individual pieces of content or grouping small pieces of content together.

15. Is an h1 block or inline?

    - Block

16. Is button block or inline?

    - Inline

17. Is div block or inline?

    - Block

18. Is span block or inline?

    - Inline

19. What’s the difference between a flex container and a flex item?

    - Flex container is an element that contains flex items

20. How do you create a flex item?

    - First we have to create a flex container that wraps the element that we want to set them as flex item, then, we can set the `display` property to `flex`. In this case all elements within tha parent will be flex items.

21. What are the 3 values defined in the shorthand flex property?

    - `flex-grow`, `flex-shrink`, `flex-basis`

22. How do you make flex items arrange themselves vertically instead of horizontally?

    - By applying the property `flex-direction` to the flex container and set it to `column`

23. What is the difference between justify-content and align-items?

    - `justify-content` controls the alignments of the flex items horizontally while `align-items` on the other hand, controls the alignments of the flex items vertically.

24. How do you use flexbox to completely center a div inside a flex container?

    - Set the `justify-content` property of the container to center. This will horizontally center the div inside the container.
    - Set the align-items property of the container to center. This will vertically center the div inside the container.

25. What’s the difference between justify-content: space-between and justify-content: space-around?
    - justify-content: space-between distributes the space evenly between the flex items along the main axis, leaving no extra space before the first item or after the last item.
    - justify-content: space-around also distributes the space equally between the flex items along the main axis, but it adds equal amounts of space before the first item and after the last item

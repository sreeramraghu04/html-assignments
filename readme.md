# HTML 5

## Assignment

1. What is HTML?

   - **HTML** was invented by **Tim Berners-Lee**, in 1990. HTML **(HyperText Markup Language)** is the standard language used to create and structure content on the web, such as text, images, and links, by defining the structure of a webpage.

2. What is the difference between HTML tags, elements, and attributes?

   - **HTML Tag**: The basic building block used to define elements (e.g., `<p>` or `<div>`).
   - **HTML Element**: A complete structure made of opening and closing tags with content in between (e.g., `<p>Hello</p>`).
   - **HTML Attribute**: Provides additional information about an element, written inside the opening tag (e.g., `<a href="example.com">Link</a>`).

3. What are the different types of lists in HTML?

   There are three types of lists in HTML:

   - **Ordered List (`<ol>`)**: Displays items in a numbered sequence.
   - **Unordered List (`<ul>`)**: Displays items with bullet points.
   - **Definition List (`<dl>`)**: Displays terms and their definitions.

4. What is the difference between the “id attribute” and the “class attribute” of HTML elements?

   - **`id` attribute**: Uniquely identifies a single element on a page. Used once per element.
   - **`class` attribute**: Groups multiple elements with the same style or behavior. Can be reused on multiple elements.

5. List various types of formatting tags in HTML with examples?

   **Formatting Tags in HTML:**

   - **`<b>` (Bold)**

     - **Purpose:** Makes text bold.
     - **Example:** `<b>Bold Text</b>`

   - **`<i>` (Italic)**

     - **Purpose:** Italicizes text.
     - **Example:** `<i>Italic Text</i>`

   - **`<strong>` (Strong Importance)**

     - **Purpose:** Indicates strong importance, typically bold.
     - **Example:** `<strong>Important Text</strong>`

   - **`<em>` (Emphasis)**

     - **Purpose:** Emphasizes text, typically italic.
     - **Example:** `<em>Emphasized Text</em>`

   - **`<u>` (Underline)**

     - **Purpose:** Underlines text.
     - **Example:** `<u>Underlined Text</u>`

   - **`<br>` (Line Break)**

     - **Purpose:** Inserts a line break.
     - **Example:** `First Line<br>Second Line`

   - **`<span>` (Inline Container)**

     - **Purpose:** Applies styles or classes to a part of text.
     - **Example:** `<span class="highlight">Highlighted Text</span>`

   - **`<div>` (Division)**

     - **Purpose:** Groups block-level elements for styling or layout.
     - **Example:** `<div class="container">Content here</div>`

   - **`<mark>` (Highlighted Text)**

     - **Purpose:** Highlights text.
     - **Example:** `<mark>Highlighted Text</mark>`

   - **`<small>` (Small Text)**

     - **Purpose:** Displays text in a smaller font size.
     - **Example:** `<small>Small Text</small>`

     These tags help in styling and organizing content on a webpage, making it more readable and visually appealing.

6. Explain the usage of `<!DOCTYPE>` in HTML?

   - The `<!DOCTYPE>` declaration defines the document type and version of HTML being used. It helps the browser render the page correctly. For example, `<!DOCTYPE html>` is used for HTML5.

7. What is the significance of the `<head>` and `<body>` tag?

   - **`<head>` tag**: Contains metadata about the webpage, like title, links to stylesheets, and scripts. This information is not displayed on the page.

   - **`<body>` tag**: Contains the content visible on the webpage, like text, images, and links.

8. State the difference between inline and block elements.

   - **Inline Elements**: Do not start on a new line and take up only as much width as necessary (e.g., `<span>`, `<a>`).
   - **Block Elements**: Start on a new line and take up the full width available (e.g., `<div>`, `<p>`).

9. What is the difference between `<link>` and `<a>` tag?

   - **`<link>` tag**: Links external resources, like stylesheets, to the webpage. It is used in the `<head>` section.
   - **`<a>` tag**: Creates hyperlinks to navigate between pages or sections. It is used in the `<body>` section.

10. What is the difference between a figure and a figcaption tag?

    - **`<figure>` tag**: Used to group media content like images, videos, or illustrations along with a caption.
    - **`<figcaption>` tag**: Provides a caption or description for the content inside a `<figure>`.

11. What are the differences between HTML and HTML5?

    - **HTML**: The standard markup language for creating web pages, used for structuring content.
    - **HTML5**: The latest version of HTML, with new features like native support for video and audio, improved form controls, better semantic elements (e.g., `<header>`, `<footer>`), and enhanced API support (e.g., local storage, geolocation).

12. What are forms in HTML?

    - Forms in HTML are used to collect user input, such as text, selections, or file uploads. They are created using the `<form>` tag and include various input elements like `<input>`, `<textarea>`, and `<button>`.

13. Explain the types of inputs in HTML with examples.

    In HTML, input types specify the type of data a user can enter into a form. Here are some common input types with examples:

    - **Text Input**
      For plain text input.

      ```html
      <input type="text" placeholder="Enter your name" />
      ```

    - **Password Input**
      Hides the entered text.

      ```html
      <input type="password" placeholder="Enter your password" />
      ```

    - **Email Input**
      For email addresses, validate the format.

      ```html
      <input type="email" placeholder="Enter your email" />
      ```

    - **Number Input**
      For numeric values.

      ```html
      <input type="number" min="1" max="100" />
      ```

    - **Date Input**
      For selecting a date.

      ```html
      <input type="date" />
      ```

    - **Radio Input**
      For single-choice options.

      ```html
      <input type="radio" name="gender" value="male" /> Male
      <input type="radio" name="gender" value="female" /> Female
      ```

    - **Checkbox Input**
      For multiple-choice options.

      ```html
      <input type="checkbox" name="hobby" value="reading" /> Reading
      <input type="checkbox" name="hobby" value="traveling" /> Traveling
      ```

    - **File Input**
      For uploading files.

      ```html
      <input type="file" />
      ```

    - **Submit Button**
      Submits the form.

      ```html
      <input type="submit" value="Submit" />
      ```

    - **Color Input**
      For selecting a color.

      ```html
      <input type="color" />
      ```

    These inputs help collect different types of data efficiently.

14. Explain the importance of meta tags and their types.

    **Importance of Meta Tags in HTML:**  
    Meta tags provide metadata about a web page, helping search engines and browsers understand the content. They do not appear on the page but are essential for SEO, accessibility, and controlling browser
    behavior.

    **Types of Meta Tags with Examples:**

    - **SEO Meta Tags**  
      Improve search engine ranking.

    - **Viewport Meta Tags**  
      Make websites responsive.

    - **Charset Meta Tags**  
      Specify character encoding.

    - **Robots Meta Tags**  
      Control search engine crawling and indexing.

    - **Author Meta Tags**  
      Specify the page's author.

    - **Refresh Meta Tags**  
      Automatically refresh or redirect the page.

16. What are Semantic elements?

    **Semantic elements** in HTML are elements that clearly describe their meaning and role in the structure of a webpage. They improve readability for both developers and search engines.

    **Examples of Semantic Elements:**

    - `<header>` - Defines the header section of a page.
    - `<nav>` - Represents navigation links.
    - `<main>` - Indicates the main content of the page.
    - `<section>` - Groups related content together.
    - `<article>` - Represents self-contained content like a blog post.
    - `<footer>` - Defines the footer section of a page.

    **Non-Semantic Example for Comparison:**

    `<div>` and `<span>` are non-semantic as they don’t indicate their purpose.

    **Importance:**  
    Semantic elements improve SEO, accessibility, and make the code easier to understand.

17. What is difference between `<meter>` tag and `<progress>` tag?

    The `<meter>` and `<progress>` tags in HTML are used to represent values but serve different purposes:

    - **`<meter>` Tag**  
      Represents a value within a defined range, like a gauge or measurement.
       
    #### Example:

      ```html
      <meter value="0.7" min="0" max="1">70%</meter>
      ```

    - **`<progress>` Tag**  
      Shows the progress of a task, like a loading bar.
      
    #### Example:

      ```html
      <progress value="30" max="100">30%</progress>
      ```

    **Key Difference:**

    - `<meter>` is for measurements or values within a specific range (e.g., performance scores).
    - `<progress>` is for tasks in progress (e.g., file uploads).

18. What is the difference between SVG and Canvas HTML5 elements?

    The difference between **SVG** and **Canvas** in HTML5 lies in how they handle graphics:

    **SVG (Scalable Vector Graphics):**
    - Uses XML to create vector graphics (mathematical equations define shapes).
    - Graphics are resolution-independent and scalable without losing quality.
    - Suitable for static or interactive vector-based graphics.
    #### Example:

      ```html
      <svg width="100" height="100">
        <circle cx="50" cy="50" r="40" fill="blue" />
      </svg>
      ```

    **Canvas:**
    - Uses JavaScript to draw pixel-based graphics.
    - Graphics are resolution-dependent and lose quality when scaled.
    - Suitable for dynamic and real-time rendering (e.g., games, animations).
      
    #### Example:

      ```html
      <canvas id="myCanvas" width="100" height="100"></canvas>
      <script>
        const canvas = document.getElementById("myCanvas");
        const ctx = canvas.getContext("2d");
        ctx.fillStyle = "blue";
        ctx.fillRect(10, 10, 80, 80);
      </script>
      ```

    **Key Difference:**

    - **SVG** is better for resolution-independent, static graphics.
    - **Canvas** is ideal for high-performance, dynamic graphics.

19. Explain the concept of web storage in HTML5.

    **Web Storage** in HTML5 provides a way to store data in a user's browser, making it easier and more efficient than cookies. It has two types:

    **Local Storage**

    - Stores data with no expiration.
    - Data is available even after the browser is closed.

    **Session Storage**

    - Stores data for the duration of the session.
    - Data is cleared when the browser tab is closed.

      **Key Points:**

    - More secure and faster than cookies.
    - Used to store small amounts of data (key-value pairs).
    - Cannot be accessed by the server.

20. What is a comment in HTML and its type and usage?

    - A **comment** in HTML is text ignored by the browser, used to explain code or temporarily disable parts of it. It helps improve code readability and debugging.

      ### Syntax:

      ```html
      <!-- This is a comment -->
      ```

      ### Types and Usage:

      - **Single-Line Comment**  
        For brief notes:

      ```html
      <!-- This is a single-line comment -->
      ```

      - **Multi-Line Comment**  
        For longer explanations:

      ```html
      <!-- 
      This is a multi-line comment.
      It spans across multiple lines.
      -->
      ```

      **Usage:**

      - To describe the purpose of the code for better understanding.
      - To temporarily hide code during development.

      ```html
      <!-- <p>This text is temporarily hidden.</p> -->
      ```

21. What are the empty elements?

    **Empty elements** in HTML are elements that do not have any content or closing tags. They are self-contained and typically used for embedding resources or adding metadata.

    ### Examples of Empty Elements:

    - `<img>` - Embeds an image.

    ```html
    <img src="image.jpg" alt="Image description" />
    ```

    - `<br>` - Inserts a line break.

    ```html
    Line 1<br />Line 2
    ```

    - `<hr>` - Creates a horizontal line.

    ```html
    <hr />
    ```

    - `<input>` - Defines input fields in a form.

    ```html
    <input type="text" placeholder="Enter name" />
    ```

    - `<meta>` - Provides metadata for the page.

    ```html
    <meta charset="UTF-8" />
    ```

    ### Key Points:

    - Empty elements are self-closing.
    - They often serve structural or functional purposes.

22. What is the advantage of collapsing white space?

    **Collapsing white space** in HTML means the browser treats multiple spaces, tabs, or newlines as a single space.

    ### **Advantages:**

    - **Cleaner Code Rendering:**  
      Simplifies how the browser processes and displays content.

    - **Improved Readability:**  
      Helps format HTML code without affecting the visual output.

    - **Reduces File Size:**  
      Minimizes unnecessary spaces in the HTML file, improving load times.

    #### Example:

    ```html
    <p> This is text with  extra spaces. </p>
    ```

    **Rendered as:**  
    `This is text with extra spaces.`

    - Collapsing white space ensures consistent formatting on the webpage.

23. What is a hyperlink? What is its need?

    A **hyperlink** in HTML is a link that allows users to navigate between web pages or resources. It is created using the `<a>` tag.

    ### **Syntax:**

    ```html
    <a href="https://example.com">Click here</a>
    ```

    ### **Need for Hyperlinks:**

    - **Navigation:**  
      Helps users move between different pages or websites.

    - **Connecting Resources:**  
      Links to files, images, or sections within a page.

    - **Improves User Experience:**  
      Makes content interactive and easily accessible.

    #### Example:
    To link to Google:

    ```html
    <a href="https://google.com">Go to Google</a>
    ```

24. What is the need of `alt=""` attribute in `<img>` tag?

    The **`alt`** attribute in the `<img>` tag provides alternative text for an image if it cannot be displayed.

    ### **Need for `alt` attribute:**

    - **Accessibility:**  
      Helps screen readers describe images to visually impaired users.

    - **SEO (Search Engine Optimization):**  
      Improves search engine understanding of the image content.

    - **Fallback Text:**  
      Displays the text if the image fails to load.

    #### Example:

    ```html
    <img src="image.jpg" alt="A beautiful sunset over the mountains" />
    ```

- The `alt` tag ensures images are accessible and improves web content's overall usability.

24. What is the difference between HTML and XHTML?

    **HTML** and **XHTML** are both used to structure content on the web, but they have some key differences:

    ### 1. **Syntax:**

    - **HTML:** More lenient with syntax. Tags and attributes are not always case-sensitive, and closing tags can be omitted in some cases.
    - **XHTML:** Strict syntax. All tags must be properly closed, and tag names/attributes must be lowercase.

    ### 2. **Document Structure:**

    - **HTML:** Can be more flexible with unclosed or improperly nested tags.
    - **XHTML:** Requires a well-formed structure, where every tag must be properly nested and closed.

    ### 3. **Doctype:**

    - **HTML:** Uses a simpler doctype declaration.
    - **XHTML:** Requires a more specific doctype declaration, and it must be served as XML.

    ### 4. **Error Handling:**

    - **HTML:** Tolerates errors and displays content even if the code is not perfect.
    - **XHTML:** If there are errors, the browser will not display the page.

    #### Example:

    **HTML:**

    ```html
    <p>This is a paragraph</p>
    ```

    **XHTML:**

    ```xhtml
    <p>This is a paragraph</p>
    ```

    - In XHTML, if any tag is unclosed or improperly formatted, it will not display correctly.

25. What is the difference between absolute and relative URL?

    The difference between **absolute URL** and **relative URL** is how they specify the location of a resource:

    ### 1. **Absolute URL:**

    - **Definition:** Provides the full path to a resource, including the protocol (e.g., `https://`) and domain.
    - **Usage:** Used to link to resources on other websites or external locations.

    ### 2. **Relative URL:**

    - **Definition:** Provides the path to a resource relative to the current document's location.
    - **Usage:** Used for linking to resources within the same website or domain.

    ### **Key Difference:**

    - **Absolute URL** includes the full URL with the domain.
    - **Relative URL** only includes the path from the current page.

26. What is the role of the `action=""` attribute in HTML forms?

    The **`action`** attribute in an HTML form specifies the URL where the form data should be sent when the form is submitted.

    ### **Role of `action` Attribute:**

    - **Defines Submission Destination:**  
      Specifies the server or script that will process the form data.

    - **Helps Form Handling:**  
      Directs the form data to the correct location for processing (e.g., a server-side script like PHP or an API endpoint).

27. What is the role of `method=""` attributes in HTML forms?

    The **`method`** attribute in an HTML form specifies the HTTP method to be used when submitting the form data.

    ### **Role of `method` Attribute:**

    - **Defines How Data is Sent:**  
      It determines how the form data will be transmitted to the server.

    - **Two Common Methods:**
    - **`GET`:** Sends form data in the URL (visible), often used for search or retrieval operations.
    - **`POST`:** Sends form data in the request body (not visible), used for sending sensitive or large data.

28. What is a grouping tag in HTML?

    ### Common Grouping Tags:

    - **`<div>`** - A generic container used to group content.

    #### Example:

    ```html
    <div>
      <h1>Title</h1>
      <p>Paragraph text.</p>
    </div>
    ```

    - **`<span>`** - A generic inline container used to group inline elements or text.

    #### Example:

    ```html
    <span style="color: red;">This is red text.</span>
    ```

29. What is accessibility in HTML?

    **Accessibility in HTML** refers to making web content usable by people with disabilities, ensuring that all users, regardless of their abilities, can interact with the web.

    ### Key Aspects:

    - **Screen Reader Support:**  
      Using semantic HTML and proper tags (like `<header>`, `<nav>`, and `<alt>` for images) helps screen readers interpret and describe content.

    - **Keyboard Navigation:**  
      Ensuring that users can navigate and interact with the site using a keyboard.

    - **Color Contrast and Text Size:**  
      Ensuring sufficient contrast between text and background, and allowing text resizing for better readability.

    #### Example for Accessibility:

    ```html
    <img src="image.jpg" alt="A description of the image" />
    ```

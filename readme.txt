--Readme document for Zongze Li, zongzel3@uci.edu--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

10/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features

- Included an image (portrait) with descriptive `alt` text.
- Used appropriate headings and paragraph text on each page (e.g., hero intro, section headings).
- Added links to external pages (GitHub/LinkedIn) and mailto email link.
- Implemented multiple pages (Home, About, Portfolio, Contact) with consistent navigation between them.
- Used semantic HTML tags such as `header`, `nav`, `main`, `section`, `article`, and `footer`.

(b) CSS features

- Leveraged Bootstrap CSS helpers and utilities for layout and styling (responsive grid, navbar, cards, table styling, form styling, rounded image shape, spacing utilities).
- Added a custom font (Inter) via CSS variable override with system fallbacks.
- Customized link hover styling and page typography/line-height in `style.css`.

(c) Advanced features

- Accessible data table (Skills) with a caption and explicit header associations using `id`/`headers` so it can be read via a screen reader.
- Responsive navigation bar (Bootstrap navbar with collapsible toggler on smaller screens).
- Contact form using HTML forms + Bootstrap validation feedback (required fields + invalid feedback messaging).

3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.

No. I addressed the accessibility checker’s known issues (including explicit table header associations) and did not intentionally ignore any accessibility warnings.

4. How long, in hours, did it take you to complete this assignment?

Approximately 6 hours (including design, implementation, and validation). 

5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)

- Bootstrap 5.3 documentation (getbootstrap.com/docs/5.3/) for navbar, grid, cards, tables, and forms.
- Google Fonts (fonts.google.com) / Inter font reference.
- W3C HTML Validator (validator.w3.org) and W3C CSS Validator (jigsaw.w3.org/css-validator/).
- AChecker/WAVE accessibility checker to review WCAG issues and verify fixes.
- ChatGPT assistance for planning the multi-page structure, improving accessibility (table headers), and implementing Bootstrap form validation.

6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?

None.

7. Is there anything special we need to know in order to run your code?

No special steps are required. Open `index.html` in a browser (or use a simple local server such as VS Code Live Server). The site consists of static pages: `index.html`, `about.html`, `portfolio.html`, and `contact.html`. Ensure the portrait image is present under the `images/` folder.

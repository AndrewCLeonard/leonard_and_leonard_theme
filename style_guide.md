# Style Guide

## Colors

| Original Category | Designation    | Standard Designation | Website Element Usage                          | Color Name         | Hex Code |
| ----------------- | -------------- | -------------------- | ---------------------------------------------- | ------------------ | -------- |
| Base              | One            | Background           | Backgrounds, large areas of whitespace         | Off-White          | #F5F5F5  |
| Base              | Two            | Neutral              | Subtle divisions, secondary backgrounds        | Light Grey         | #E0E0E0  |
| Base              | Three          | Primary Text         | Main text, headings                            | Dark Grey          | #333333  |
| Contrast          | One            | Primary              | Primary buttons, key text areas                | Dark Navy          | #002A4E  |
| Contrast          | Secondary      | Secondary            | Calls to action, highlighted text              | Medium Blue        | #005792  |
| Contrast          | Three          | Tertiary             | Links, interactive elements                    | Soft Blue          | #4A90E2  |
| Accent            | One            | Accent               | Secondary buttons, minor details               | Slate Grey         | #76949F  |
| Accent            | Two            | Subtle Accent        | Light background sections, tertiary elements   | Pale Blue Grey     | #B6C8D6  |
| Accent            | Three          | Hover State          | Hover effects, secondary highlights            | Lightest Blue Grey | #DAE3E5  |
| Accent            | Four           | Divider              | Borders, lines, separators                     | Neutral Grey       | #CCD1D9  |
| Accent            | Five           | Highlight Background | Highlighted card backgrounds, special sections | Almost White       | #F2F4F5  |
| Additional        | Olive Green    | Positive Indicator   | Success messages, positive indicators          | Muted Green        | #6E7F58  |
| Additional        | Sand Beige     | Warm Background      | Warm background sections, alternative neutral  | Warm Beige         | #D2C3A3  |
| Additional        | Charcoal Brown | Subtle Accent        | Text accents, graphic elements                 | Warm Taupe         | #504A42  |
| Additional        | Rust Red       | Alert                | Urgent CTA, alert messages                     | Brick Red          | #A63E1B  |

## Expanded Font Sizes with Text Case

| Element            | Font     | Font Size | Line Height | Paragraph Spacing | Letter Spacing | Case      | Weight  | Use Case                               |
| ------------------ | -------- | --------- | ----------- | ----------------- | -------------- | --------- | ------- | -------------------------------------- |
| Header 1           | Lora     | 48px      | 58px        | 20px              | 0%             | Normal    | Bold    | Main titles, landing page headers      |
| Header 2           | Lora     | 36px      | 44px        | 18px              | 0%             | Normal    | Bold    | Subtitles, section headers             |
| Header 3           | Lora     | 28px      | 34px        | 16px              | 0%             | Normal    | Regular | Minor headers, important text          |
| Header 4           | Lora     | 24px      | 30px        | 14px              | 0%             | Uppercase | Regular | Subsection headers                     |
| Header 5           | Lora     | 20px      | 26px        | 12px              | 0%             | Uppercase | Regular | Special emphasis, standalone labels    |
| Header 6           | Lora     | 18px      | 24px        | 10px              | 0%             | Uppercase | Regular | Smallest headers, used sparingly       |
| Paragraph Normal   | Alegreya | 18px      | 28px        | 8px               | 0%             | Normal    | Regular | Body text, descriptions                |
| Paragraph Small    | Alegreya | 16px      | 24px        | 8px               | 0%             | Normal    | Regular | Footnotes, less important text         |
| Paragraph Large    | Alegreya | 20px      | 30px        | 10px              | 0%             | Normal    | Regular | Highlighted or introductory paragraphs |
| Paragraph Extra Lg | Alegreya | 22px      | 32px        | 12px              | 0%             | Normal    | Regular | Very important text, quotes, callouts  |

### Notes

- Case: The use of uppercase for smaller headers (H4, H5, H6) adds a stylistic element, creating a clear distinction from larger headers. It's standard in many modern designs but should align with the overall aesthetic and readability goals of the site.
- Other Settings: Remain unchanged to ensure readability and a cohesive look.

The decision to use uppercase should be based on the specific design and readability considerations of your website. It's effective for short, impactful headers but can reduce readability for longer text, so it's typically reserved for smaller headers or specific design elements.

In web design, primary, secondary, and tertiary buttons are used to signify different levels of importance or hierarchy of actions that a user can take. Their design and usage are typically based on the priority and frequency of the actions they represent. Let's update the button styles table with two additional columns: "Button Text" and "Use Case," to provide a more realistic and practical perspective.

### Button Styles Table

| Button Type | State   | Font Size | Border Radius | Padding Top-Bottom | Padding Left-Right | Margin | Background Color Code | Background Color Name | Text Color Code | Text Color Name | Border Color Code | Border Color Name | Additional Style                       | Button Text | Use Case                            |
| ----------- | ------- | --------- | ------------- | ------------------ | ------------------ | ------ | --------------------- | --------------------- | --------------- | --------------- | ----------------- | ----------------- | -------------------------------------- | ----------- | ----------------------------------- |
| Primary     | Default | 16px      | 4px           | 12px               | 24px               | 8px    | #002A4E               | Dark Navy             | #FFFFFF         | White           | #002A4E           | Dark Navy         |                                        | Submit      | Main action, like form submission   |
| Primary     | Hover   | 16px      | 4px           | 12px               | 24px               | 8px    | #005792               | Medium Blue           | #FFFFFF         | White           | #005792           | Medium Blue       |                                        | Submit      | Main action, like form submission   |
| Primary     | Click   | 16px      | 4px           | 12px               | 24px               | 8px    | #333333               | Dark Grey             | #FFFFFF         | White           | #333333           | Dark Grey         |                                        | Submit      | Main action, like form submission   |
| Primary     | Focus   | 16px      | 4px           | 12px               | 24px               | 8px    | #002A4E               | Dark Navy             | #FFFFFF         | White           | #4A90E2           | Soft Blue         | Outline: 2px solid Soft Blue (#4A90E2) | Submit      | Main action, like form submission   |
| Primary     | Active  | 16px      | 4px           | 12px               | 24px               | 8px    | #333333               | Dark Grey             | #FFFFFF         | White           | #333333           | Dark Grey         |                                        | Submit      | Main action, like form submission   |
| Secondary   | Default | 16px      | 4px           | 12px               | 24px               | 8px    | Transparent           | Transparent           | #002A4E         | Dark Navy       | #002A4E           | Dark Navy         |                                        | Learn More  | Secondary action, like more info    |
| Secondary   | Hover   | 16px      | 4px           | 12px               | 24px               | 8px    | #005792               | Medium Blue           | #FFFFFF         | White           | #005792           | Medium Blue       | Background color change                | Learn More  | Secondary action, like more info    |
| Secondary   | Click   | 16px      | 4px           | 12px               | 24px               | 8px    | #333333               | Dark Grey             | #FFFFFF         | White           | #333333           | Dark Grey         |                                        | Learn More  | Secondary action, like more info    |
| Secondary   | Focus   | 16px      | 4px           | 12px               | 24px               | 8px    | Transparent           | Transparent           | #002A4E         | Dark Navy       | #4A90E2           | Soft Blue         | Outline: 2px solid Soft Blue (#4A90E2) | Learn More  | Secondary action, like more info    |
| Secondary   | Active  | 16px      | 4px           | 12px               | 24px               | 8px    | #333333               | Dark Grey             | #FFFFFF         | White           | #333333           | Dark Grey         |                                        | Learn More  | Secondary action, like more info    |
| Tertiary    | Default | 16px      | 4px           | 12px               | 24px               | 8px    | #76949F               | Slate Grey            | #FFFFFF         | White           | #76949F           | Slate Grey        |                                        | Sign Up     | Less prominent action, like sign-up |
| Tertiary    | Hover   | 16px      | 4px           | 12px               | 24px               | 8px    | #B6C8D6               | Pale Blue Grey        | #FFFFFF         | White           | #B6C8D6           | Pale Blue Grey    |                                        | Sign Up     | Less prominent action, like sign-up |
| Tertiary    | Click   | 16px      | 4px           | 12px               | 24px               | 8px    | #333333               | Dark Grey             | #FFFFFF         | White           | #333333           | Dark Grey         |                                        | Sign Up     | Less prominent action, like sign-up |
| Tertiary    | Focus   | 16px      | 4px           | 12px               | 24px               | 8px    | #76949F               | Slate Grey            | #FFFFFF         | White           | #4A90E2           | Soft Blue         | Outline: 2px solid Soft Blue (#4A90E2) | Sign Up     | Less prominent action, like sign-up |
| Tertiary    | Active  | 16px      | 4px           | 12px               | 24px               | 8px    | #333333               | Dark Grey             | #FFFFFF         | White           | #333333           | Dark Grey         |                                        | Sign Up     | Less prominent action, like sign-up |

#### Use Case Explanations

- **Primary Button:** This is used for the most important actions on a page, such as submitting a form or completing a purchase. It's visually the most prominent button.
- **Secondary Button:** These are for actions that are important but not the primary focus, like navigating to additional information or a secondary feature (e.g., "Learn More" about a service).
- **Tertiary Button:** Used for less critical actions or when you want to provide an option without drawing too much attention to it (e.g., signing up for a newsletter).

### Link Styles Table

| State   | Font Size | Text Decoration | Text Color Code | Text Color Name | Background Color Code | Background Color Name | Additional Style                       | Use Case                             |
| ------- | --------- | --------------- | --------------- | --------------- | --------------------- | --------------------- | -------------------------------------- | ------------------------------------ |
| Default | 16px      | None            | #4A90E2         | Soft Blue       | Transparent           | Transparent           |                                        | Standard, uninteracted link          |
| Hover   | 16px      | Underline       | #005792         | Medium Blue     | Transparent           | Transparent           |                                        | Mouseover state, enhances visibility |
| Active  | 16px      | Underline       | #333333         | Dark Grey       | Transparent           | Transparent           |                                        | Click state of the link              |
| Visited | 16px      | None            | #76949F         | Slate Grey      | Transparent           | Transparent           |                                        | Indicate the link has been visited   |
| Focus   | 16px      | Underline       | #4A90E2         | Soft Blue       | Transparent           | Transparent           | Outline: 2px solid Soft Blue (#4A90E2) | Keyboard navigation focus state      |

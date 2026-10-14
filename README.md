# Personal Portfolio Website

## About This Project

This is my personal portfolio website created for INFR3120 – Web and Scripting Programming at Ontario Tech University.

My name is Temesgen Teklebrhan, and I am a second-year Networking and IT Security student. I created this website to introduce myself, share my experience and projects, and give visitors a way to contact me.

The website uses HTML5 and CSS3. I used separate stylesheets for different screen sizes and did not use JavaScript, Flexbox, CSS Grid, or Bootstrap.

## Website Pages

- **Home (`index.html`):** Introduces me and explains my interests in networking and cybersecurity.
- **About Me (`aboutme.html`):** Shares my background, skills, certifications, and career goals.
- **Projects (`project.html`):** Shows five projects I have worked on or am currently developing.
- **Contact Me (`contact.html`):** Includes a contact form with HTML5 validation and links to my social media profiles.

## Responsive Design

I made my website responsive so it can be viewed on desktop computers, tablets, and smartphones. I used three separate CSS files to adjust the layout for different screen sizes.

| CSS File         | Screen Size     | Device             |
| ---------------- | --------------- | ------------------ |
| `full.css`       | 960px and above | Desktop and laptop |
| `tablet.css`     | 481px to 959px  | Tablet             |
| `smartphone.css` | 480px and below | Smartphone         |

I chose these screen sizes because they allow the website to adjust its layout depending on the device being used.

**Desktop:** The website has a wider layout, with the navigation on the right. Pictures and text can appear beside each other.

**Tablet:** The layout adjusts to fit medium sized screens. The logo and navigation are centered, and the pictures become smaller to fit the available space.

**Smartphone:** The content is displayed in a single column, with smaller pictures and a hamburger menu that opens when clicked.

I used percentage widths, CSS media queries, floats, and other CSS properties to make the website responsive. I did not use Flexbox or CSS Grid.

## Colour Scheme

I chose a blue colour scheme inspired by Ontario Tech University's colours. I wanted my portfolio to look professional, clean, and related to technology and cybersecurity.

I used the following five colours throughout my website:

| Colour      | Hex Code  | Where I Used It                                   |
| ----------- | --------- | ------------------------------------------------- |
| Dark Navy   | `#0B1F33` | Backgrounds, header, and footer                   |
| Navy Blue   | `#1F4E79` | Navigation buttons and gradients                  |
| Medium Blue | `#4F81BD` | Borders, buttons, and highlights                  |
| Light Blue  | `#D9E6F2` | Section backgrounds and gradients                 |
| Off-White   | `#F7F9FC` | Content backgrounds and active navigation buttons |

I kept these colours consistent across all four pages.

Colour scheme tool: [https://color.adobe.com/create](https://color.adobe.com/create)

## CSS Gradients

I used linear gradients to make my website look more visually appealing and to create a consistent design.

**Page Background:** In `full.css`, I used a vertical linear gradient that goes from dark navy to lighter blue and off-white.

**Header:** I used a 45 degree angled linear gradient with dark navy and blue colours.

**Footer:** I used a negative 45 degree angled linear gradient to give the footer a matching design.

**Home Introduction:** I used a 120 degree angled gradient behind my introduction and profile picture.

**Content Sections:** I used horizontal gradients in the section cards to help separate the content and make the text easier to read.

## Sources and References

I used my INFR3120 course lectures as my main reference for building this portfolio. The lectures helped me understand HTML5, CSS3, forms, validation, responsive layouts, and website styling.

### Course Materials

- INFR3120 – Web and Scripting Programming, Weeks 1–4 lecture materials, Ontario Tech University.

### External Resources

- **Adobe Color:** https://color.adobe.com/create — Used to review my website's colour scheme.
- **Simple Icons:** https://simpleicons.org/ — Source for the GitHub and Instagram icons.
- **Wikimedia Commons:** https://commons.wikimedia.org/ — Source for the LinkedIn icon.
- **Portfolio Logo:** https://www.pinterest.com/pin/cukur-tattoo-symbol-trendy-sticker-for-cukur-fans--193021534025351964/ — I found this Çukur symbol on Pinterest and used it for my portfolio logo. I edited the image by removing its background and adjusting its appearance to match my website's design.

### AI Assistance

I used ChatGPT to help explain HTML and CSS concepts, troubleshoot problems, and review my website while I was developing it. I also used it to help with responsive styling and writing explanations for the README.

I reviewed and tested the changes in VS Code to understand how they worked.

### External Code

My main references were the course lectures. Any code used from outside the lectures must be identified and credited, and must stay within the assignment's 10% external-code limit.
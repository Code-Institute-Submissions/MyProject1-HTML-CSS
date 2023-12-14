### Font and Colour choices

**Fonts:** "IBM Plex Sans, ans-serif"

**Colours:** Different colors will be chosen, but black, white, and gree are still the main colors, because I think they are the colors that are most attractive to the customer.

## Features

This site implements the very basic features of a static website.

- **Navigation Bar**

  - Featured in the header of all four pages. Includes links to Home page, Products page, Resources page, Solution and Why waeder.
  - Uniform format allows for easy navigation on all pages without the use of the "back" button.

    ![navbar]('http://127.0.0.1:5500/Wadi-PP1/index.html')

- **Store image and Banner text**
  - The background image and text design is just a temporary image until the main background image is designed.

## UX

## Site goals

This site is just a site for virtual small company, the purpose is to training for what i learn.

## Project Description

The purpose of this project is to combination of data mining, machine learning and statistical algorithms provides the “predictive” and predictive component and enables predictive analytics tools to go beyond simple correlation. There is a wide range of possible applications for predictive analytics in business:

Risk reduction for insurance companies and financial service providers
Detecting credit card fraud
More accurate supply and demand forecasting
Identifying threats and problems affecting computer networks
More and more software tools are integrating predictive analytics, making it more accessible to users in companies of all sizes. All users can benefit from predictive analytics, even those who have no expertise in data science or advanced analytics. This development is often referred to as “data democratization,” and it means making data available across the organization so everyone can access it to make better decisions.

## Prerequisites

- Web browser (e.g., Chrome, Firefox, Safari)
- (Any other prerequisites or dependencies your project may have)

## Acknowledgments

- Mention any contributors, libraries, or resources you used or were inspired by.

## Contact Information

For any inquiries or feedback, please contact [Noah Samawi] at [noah.alsamawi@gmail.com].

## Footer

- The footer element contains 4 icons, linking to the main social media platforms and linkedin.
- The icons are styled in the sites primary colour.
- The footer is consistent througout all pages.

  **As a website visitor:**

- I would like to quickly find out what new coliction is available on the website.
- I would like to see new offers.
- I want to know if I can become a regular customer and get a discount.
- I would like to be able to contact the Wadi as a company and make inquiries.
- I would like to see a mobile-friendly layout and responsive design.

\*As the site administrator:\*\*

- I want to be able to update the events calender.
- I want to be able to update and add new events on the events listing.
- I want to be able to add more relevant images to the site and create a more extensive gallery.

## Testing

Waeder has bin validated via W3C HTML Validator and W3C CSS Vadidator.

### Validator Testing

- HTML
- CSS ![Alt Text](../Screenshot-CSS-Validator.png)

- added `title` and `aria-label` attributes to all social links and home link logo to improve accessibility

### Browser Testing

**Layout:** Testing layout and appearance of site for consistency throughout browsers.

**Functionality:** Ensuring all links, navigation and form submit functions as expected throughout browsers....

### Fixed Bugs

## Credits

### Media

All stock images were sourced from the following open source sites:

- [Pexels](https://www.pexels.com/)
- [Pixabay](https://pixabay.com/)
- [Unsplash](https://unsplash.com/)

### Code

Heart Icon:

- <https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/create-a-more-complex-shape-using-css-and-html>
- <https://unused-css.com/blog/css-half-circle/>

Burger Menu:

- <https://www.w3schools.com/howto/howto_js_mobile_navbar.asp>

**As the site administrator:**

I would like to be able to update the About and Home pages.
I would like to be able to update the new goods and add new waiting/articale.
I would like to add more relevant images to the site with the price and be able to create a more extensive gallery.

### Validator Testing

- HTML ([W3C validator](https://validator.w3.org/nu/#textarea))

  - 1 Error:

- CSS ([CSS validator](https://jigsaw.w3.org/css-validator/validator))
  - Error:
- Accessibility ([axe DevTools](https://chrome.google.com/webstore/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd))
  - added `title` and `aria-label` attributes to all social links and home link logo to improve accessibility
- Performance, Accessibility, SEO, Best Practices (Lighthouse Chrome DevTools)
  ![Lighthouse rating](https://8000-noah-samawi-myproject1-h-l6slnfxop6.us2.codeanyapp.com/)
- Browser Support ([CanIUse](https://caniuse.com/))
  - `gap` property for Flexbox: according to caniuse.com this property has a global support of 88.95%
  - `loading="lazy"` attribute on images: not yet fully supported by most browsers; to be included in the future

### Browser Testing

**Layout:** Testing layout and appearance of site for consistency throughout browsers.

**Functionality:**

| Browser |               Layout                | Functionality |
| :-----: | :---------------------------------: | :-----------: |
| Chrome  |                  ✔                  |       ✔       |
|  Edge   |                  ✔                  |       ✔       |
| Firefox |                  ✔                  |       ✔       |
| Safari  |                  ✔                  |       ✔       |
|   IE    | deprecated by Microsoft, not tested |

### Manual Testing

|               Feature               |                                           Expect                                            |                Action                 |                              Result                              |
| :---------------------------------: | :-----------------------------------------------------------------------------------------: | :-----------------------------------: | :--------------------------------------------------------------: |
|            **Logo Icon**            |                              When clicked, home page will open                              |           Clicked Logo Icon           |                  Home page opened when clicked                   |
|         **Navbar Buttons**          |                         When clicked, the respective page will open                         | Clicked all individual navbar buttons |       All respective pages opened when button was clicked        |
|   **Rule link on home page main**   |                When clicked, About page will open and scroll to rule section                |            Click rule link            |           About page opens and scrolls to rule section           |
| **Contact link on About page main** |                           When clicked,the Contact page will open                           |          Click contact link           |                        Contact page opens                        |
|        **Social link icons**        |              Social link icons open relevant websites in new tab when clicked               |      Click all individual icons       |               All respective sites open in new tab               |
|       **Form submit button**        |                         Form submits when submit button is clicked                          | Fill out form and click submit button |        CI form dump page opens and displays form contents        |
|      **Required form fields**       | form will not submitif required fields are blank and fields will be highlighted and flagged |       Fill out form incorrectly       | Form does not submit and highlights incorrectly filled in fields |

### Fixed Bugs

#### 405 Error on form submit

### Unfixed bugs

No unfixed bugs to date.

## Deployment

# Testing
- Site CSS was put through the W3C CSS Validator with no errors. 
- All HTML pages were put through the W3C Markup Validator with no errors.

## Testing User Stories:
1. *As a new user, I want to be able to easily navigate the website to find the content I am looking for.*
    - All primary and secondary navigation links are functioning. Breadcrumbs have been used to improve user experience.
2. *As a new user, I want to quickly and easily identify the primary goal of the website.*
    - The hero-image, hero-text, and nav links allow for quick identification of the blog’s primary goal.
3. *As a new user, I want to easily identify the person and story behind the website to feel more connected.*
    - The short bio and profile image on the home page allow users to quickly identify the person and story behind the blog. Users can easily view further information on the Our Story page, linked in the bio text and via the navbar. Both of these links are functioning correctly.
4. *As an interested user, I want to be able to contact the website owner with questions.*
    - Users can easily navigate to the contact page using the ‘Contact’ nav link. A contact link is also included at the bottom of every article. All of these links are functioning correctly.
5. *As an interested user, I want to be able to follow the blog on social media so that I can stay informed in other ways.*
    -  Social links have been placed on the header and footer of every page. These links are functioning correctly.
6. *As a returning user, I want to be able to search and find specific content to avoid sifting through material that’s not relevant.*
    - A collapsible search bar has been added to the home page nav only. It is currently commented out until proper functionality can be added.

## Manual testing of all elements on every page:

### Home 
- Navigation 
    - Click and confirm the logo returns to the home page.
    - Click and confirm each nav link brings you to the associated page.
    - Click and confirm both social links bring you to the associated social media account.
    - Hover over each nav link and confirm hover colour change.
    - Hover over each social link and confirm hover colour change
    - Hover over the logo and confirm that the image title tag appears. - *This did not happen. The title tag was added and re-tested.*
    - Change screen size and confirm navigation collapse at 768 px screen size.
    - Click and confirm navigation toggle functions correctly.
- Hero Image & Hero Text
    - Adjust screen size and confirm image and text adjust correctly.
- Bio Image & Bio Text
    - Adjust screen size and confirm image and text move to vertical alignment 768 px and below.
- Featured & Recent Article Cards
    - Click and confirm each card link brings you to the associated page.
    - Adjust screen size to 768 px and confirm featured card moves to 100% container width; recent articles must move to 50% container width, displaying side by side.
    - Adjust screen size to 425px and confirm all article cards move to 100% container width, aligning vertically.
- Email Subscription
    - Enter an email address and confirm subscription form is communicating correctly with Mail Chimp. 
    - Confirm Mail Chimp confirmation of subscription opens in a new tab.
    - There is no validation on this form. If ‘subscribe’ is clicked and no email is entered, users will be redirected to a secondary Mail Chimp email subscription sign up page in a new tab.
- Footer 
    - Click and confirm all secondary navigation links bring you to the associated page.
    - Click and confirm both social media links bring you to the associated social media account.
    - Adjust screen size and confirm that secondary navigation links move to a vertical alignment on mobile devices.

### Our Story 
- Click and confirm each breadcrumb link brings you to the associated page.
- Adjust screen sizes and confirm profile image size adjusts correctly.
- Adjust screen sizes and confirm the text container adjusts width correctly.
- Adjust screen sizes and confirm font sizes adjust correctly. - *Breadcrumb font size required adjusting on screens 2560 px +.*

### DIY Camper Conversion 
- Adjust screen sizes and confirm banner image and heading adjust correctly.
- Click and confirm each breadcrumb link brings you to the associated page.
- Click and confirm the article card button brings you to the associated page.
- Adjust screen sizes and confirm article card image moves from being left of card text to above card text on mobile devices.

### Blog Article
- Adjust screen sizes and confirm banner image and heading adjust correctly.
- Click and confirm each breadcrumb link brings you to the associated page.
- Adjust screen sizes and confirm content width adjusts correctly.
- Adjust screen sizes and confirm font size adjusts correctly.
- Click and confirm all body links to outside sources open in a new tab. - *This did not happen. Target:_blank was added to every required link and re tested.*

### Vanlife in Ireland
-  Adjust screen sizes and confirm banner image and heading adjust correctly.
-  Adjust screen sizes and confirm content container width adjusts correctly.

### Contact
- Adjust screen sizes and confirm banner image and heading adjust correctly, and that banner image changes at 768 px +.
- Confirm that form validation is working correctly by attempting to send a form without any inputs. Name, email, and message should display errors.
- Send test form and confirm the link to [FormBackend](https://www.formbackend.com/) is working correctly.
- Adjust screen sizes and confirm form width adjusts correctly.
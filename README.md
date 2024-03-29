# ID_Assignment2

- Gwendolyn(s10223182) and Sumayyah(s10223863)
- Link to the website https://smyyhzai.github.io/ID_blacktag_Website/
- Google drive https://drive.google.com/file/d/1FkUaPdU9GFnHFYtqbT0wv7AXsca-RMrM/view?usp=sharing

# black tag - an e-commerce shopping website

This is an e-commerce website that allows users to shop for clothings. They can create an account to save their cart to view at a later time. Users can also collect points and exchange for rewards with their account.

## Design Process

- Our target audience are mostly teenagers who want to shop for clothes, and enjoy their shopping experience. The points that they collect encourages our customers to continue purchasing from our shop. This reward system is engaging and interactive, attracting more teenagers to shop from black tag.

### User stories

- As a teenage customer, I would like to shop for cheap and affordable clothings that looks fashionable within my budget. The reward system implemented allows me to save more money as well. This shop caters well to teenagers and students who are on a tight budget, as compared to other shops that does not offer this reward system.

- This shop makes shopping fun as we get to earn points as we shop. There is also a spin-the-wheel function that allows us to exchange these points for rewards. This makes us motivated to shop more from this shop to unlock more rewards.

## Features

- Navigation bar that sticks to the top at every page
- Responsive website and usable on mobile

Home page

- Slideshow of clothes
- Home page with categories of clothings available

Product page

- Product page shows all products available
- Buttons to filter type of products
- Add to cart allows users to add the products to their cart at the bottom right of the screen 
- If user is not logged in, they will be redirected to login page when they checkout 
- If user is logged in, they can check out 

Checkout page (from the cart)

- Billing address form and payment information 
- If user is not logged in, they will be redirected to login page
- If user is logged in, they will be able to checkout and directed to the reviews page

Checkout successful (from checkout page)

- Allows users to checkout and leave a review of their shopping experience 
- Lottie animation used to show users that their order is successful (animation of tick)
- Buttons to let user choose to continue shopping, go back to home or collect rewards

Rewards page

- Allows users to collect points and view all rewards available
- Every $10 spent should give 1 star
- 5 stars can be exchanged for either a spin on the wheel or $5 off the next purchase
- Spin the wheel will be in the reward page
- Spin the wheel rewards will include no reward, 5% discount, 10% discount, 20% discount, $2 off next purchase

Profile page

- Profile page allows users to log in or create their own account using API and restDB
- Login and logout button will be shown accordingly
- If user is logged in, login/register button would be changed to log out

### Existing Features

### Features Left to Implement

- Reward page show total stars and coupons collected
- Reward page api

## Technologies Used

- [HTML](https://html.com)
- [CSS](https://css.com)
- [JAVASCRIPT](https://javascript.com)
- [API](https://api.com)
- [BOOTSTRAP](https://bootstrap.com)
- [JSON](https://json.com)
- [LOTTIE](https://lottie.com)
- [JQUERY](https://jquery.com)

## Testing

Responsiveness

- Ensure that flexboxes work and is displayed correctly by resizing the screen
- Ensure the website works on mobile

Navigation bar

- Scroll down the page and ensure that the navigation bar sticks to the top

Home page
- Explore more button would scroll down to the product categories
- Clicking the categories would bring users to the product page
- Gallery pictures should change when the next arrow is clicked
- Image should return to previous image when back arrow is clicked

Product page

- Product page should show all products when first entered
- When the page is resized, the products become 1 column
- Click "Sweatshirts" to filter products and show sweatshirts only etc.
- Back to top button should bring users back to the top of the page when clicked
- Add a product to the cart and the cart should display the product and the correct price
- Add more products and the total price should be calculated correctly
- Checkout should lead you to the review page if the user is logged in
- If user is not logged in, user will be redirected to the login page to login/register

Reward page

- Wheel should spin when button is clicked
- When the wheel is spinning, the spin button is disabled
- A popup should show the user the reward they have gotten after the wheel stops spinning

Profile page

- At the log in and sign up page, an error should popup if the fields are blank when submitted
- Create an account and log in, users should be able to log in
- When users are not logged in, they will see a login/register button
- When users are logged in, they will see a logout button
- Users will stay logged in after visiting other pages

Login page (from login button)
- Users wont be able to submit if the username and password fields are not filled
- A loading lottie will be shown when the user submit the form
- A error pop up will show when username or password is invalid

Register page (from login page)
- A contact added successfully popup will show when users have submitted their form
## Contributions
- The whole assignment was did together as a pair

## Credits

### Content
- Products are sourced from shein
### Media

- Images are taken from pinterest and shein

### Acknowledgements

- I received inspiration for this project from w3schools mr peter hung.

# ID_Assignment2

- Gwendolyn(s10223182) and Sumayyah(s10223863)
- Link to the website https://smyyhzai.github.io/ID_Assignment2_Team7/

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

- Video banner 
- Product page shows all products available
- Buttons to filter type of products
- A button at the bottom to allow users to go back to the top 
- Add to cart allows users to add the products to their cart at the bottom right of the screen 
- If user is not logged in, they will be redirected to login page when they checkout 
- If user is logged in, they can check out 

Checkout page (from the cart)

- Billing address form and payment information 

Checkout successful (from checkout page)

- Allows users to checkout and leave a review of their shopping experience 
- Lottie animation used to show users that their order is successful (animation of tick)
- Form to leave feedback 
- Buttons to let user choose to continue shopping, go back to home or collect rewards

Rewards page

- Allows users to collect points and view all rewards available
- Every $10 spent should give 1 star
- 5 stars can be exchanged for either a spin on the wheel or $5 off the next purchase
- Spin the wheel will be in the reward page
- Spin the wheel rewards will include no reward, 5% discount, 10% discount, 20% discount, $2 off next purchase
- Coupon will be added into the list of rewards

Profile page

- Profile page allows users to log in or create their own account using API and restDB
- Login and logout button will be shown accordingly

Login page (from login button)
- When submitted, lottie is used to show the page is loading

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
- Explore more button should bring the user to the product categories
- Clicking on the product categories should bring the user to the product page
- Slideshow picture at the bottom of the screen should change when arrow is clicked

Product page

- Product page should show all products when first entered
- Click "Sweatshirts" to filter products and show sweatshirts only etc.
- Add a product to the cart and the cart should display the product and the correct price
- Add more products and the total price should be calculated correctly
- Do not log in and check if checkout button leads to log in page
- Log in and checkout should lead you to the billing and review page

Reward page

- Wheel should spin when spin button is clicked
- A pop out should show the reward that the user has got

Profile page

- At the log in and sign up page, an error should popup if the fields are blank when submitted
- Create an account and log in, users should be able to log in
- Log in/ register button should change to log out when the user is logged in
- Visit other pages and return back to the profile page, the user should still be logged in.


## Credits

### Content

- Products content is taken from shein
### Media

- Images are taken from pinterest and shein

### Acknowledgements

- I received inspiration for this project from w3schools and mr peter hung.

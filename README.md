
![Capture1](https://user-images.githubusercontent.com/44445250/130372236-3706a663-f272-4693-9b40-b5d7f5161031.PNG)
![Capture2](https://user-images.githubusercontent.com/44445250/130372237-7295a104-f878-4745-b0c1-1b984c5e47dc.PNG)

# Redux_Store
Refractor e-commerce platform from using global state React's Contect API to Redux.

## Description
E-commerce website that allows user to login and purchase items, also see their order history.


## User Story
```
- AS a senior engineer working on an e-commerce platform
- I WANT my platform to use Redux to manage global state instead of the Context API
- SO THAT my website's state management is taken out of the React ecosystem
```

## Usage
- This e-commerce website are sortec by categories.
- Users are able add items from the homepage, category page and product detail page(PDP).
- Users also able to delete item from PDP or cart.
- Users also able to update the quantity of the items in the cart.
- To continue to purchase their items, users must sign up and login.
- Payments are handled by Stripe.
- Once user paid, it will redirect them to the sucess page.
- All the items pruchased will be saved in the history.

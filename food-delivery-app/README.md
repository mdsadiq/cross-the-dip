# 
 
##  Build web application for food delivery (like swiggy, zomato) where you can 
- Search for restaurants
- Select a restaurant
- Select a menu from restaurant
- Add item to cart
- increase/decrease quantity in cart
- checkout
- login and logout


#### INFO
- Make it responsive for web
- Add/remove of menu items to look like in the reference (added later)
- Consume the apis provided

#### BACKEND
- APIs are available at http://food-power.glitch.me/

#### Basic Expectation 
- Loading ux (loading indicator) when api is called. 
- Routes have a proper, meaningful & understandable naming convention (ex)NO *protected* in route names.

#### FAQ

1. How to login ?
URL: [POST]https://food-power.glitch.me/login
this api will return token, if username is entered and password has *pass* in it.

```js 
body = {
    username: "abc",
    password: "*pass*"
}
```

#### BROWNIE POINTS
- Saving the cart information in localstorage.  (ie) if user A logs in, user A's cart should be visible, if user B logs in, user B's cart should be visible
- Data Managed outside of component (ie) redux


#### Reference

https://www.ubereats.com/store/taylor-gourmet-dupont-circle/220ks56RRl6myBjGEgsZNQ/36332ab8-cec5-4ca7-bf25-9969f8a79434/f34129f2-01d6-415a-bc0d-c688016b4705/01fa9385-52e9-4d0e-af7a-586a892739bb?ps=1

https://www.swiggy.com/bangalore/marathahalli-restaurants



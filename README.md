Takeaway Challenge
==================
```
                            _________
              r==           |       |
           _  //            |  M.A. |   ))))
          |_)//(''''':      |       |
            //  \_____:_____.-------D     )))))
           //   | ===  |   /        \
       .:'//.   \ \=|   \ /  .:'':./    )))))
      :' // ':   \ \ ''..'--:'-.. ':
      '. '' .'    \:.....:--'.-'' .'
       ':..:'                ':..:'

 ```

Intro
-----

This is a program all about how, your burgers get flipped, turned upside down. So I'd like to take a minute here just to say; that this program handles online orders for a take-away.

Functionality
-------------

1. Order
  * Collect dishes selected from the menu into a meal.
  * Calculate total cost of meal from individual dish prices.
  * Allows a user to view how many of each dish their is in their meal, and price.
  * Allows user to finalise their meal and make a payment.
  * Sends a text to the user to confirm their order has been placed.
2. Menu
  * List all available dishes and prices.
  * Let's a customer add a dish to their meal.
3. Dish
  * Contains the name and price of an individual dish.

  Project Structure
  -----------------

  ├── CONTRIBUTING.md
  ├── Gemfile
  ├── Gemfile.lock
  ├── LICENSE
  ├── README.md
  ├── Rakefile
  ├── docs
  │   └── review.md
  ├── lib
  │   ├── dish.rb
  │   ├── menu.rb
  │   └── order.rb
  └── spec
      ├── dish_spec.rb
      ├── feature_spec.rb
      ├── menu_spec.rb
      ├── order_spec.rb
      └── spec_helper.rb

Usage
-----
To run:
```
$ ruby ./lib/order.rb
```
To install required files prerequisites:

```
$ gem install bundle
$ bundle
```

Development Methodology
-----------------------

This program was built using Test Driven Development

Tools Used
----------
Language:
Ruby - v2.4.0p0 (2016-12-24 revision 57164)
Testing Framework:
Rspec - v3.5.4
Cybernetic style enforcement from the future:
Rubocop - v0.48.1

Acknowledgement
---------------
Thanks to Chris Harrop (github: bannastre) for writing a great README which I pilfered from mercilessly.

Thanks to Makers Academy (github: makersacademy) and Sam Morgan (github: sjmog) for teaching me to do the code good(we hope.)

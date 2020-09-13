spaghetti = MenuItem.new(["Marinara", "Italian Sausage", "Spaghetti Pasta", "Cheese"], 12.99, "Large", false)

attribute
- ingredients = ["Marinara", "Italian Sausage", "Spaghetti Pasta", "Cheese"]
- price = 12.99
- portion_size = "Large"
- is_kids_meal = false

method
- make_kids_meal = true, size = "Small"
- remove_ingredients = ["Marinara", "Spaghetti Pasta", "Cheese"]
- add_ingredients = ["Marinara", "Spaghetti Pasta", "Cheese", "Impossible Beef"]
- discount_price = 12.99 - 5.00 = 7.99

# Sal-s-Shippers
A program for a shipping company that will take the weight of a package and determine the cheapest way to ship that package using Sal’s Shippers.

weight = 41.5
price = 3
flat_charge_ground_shipping = 20
flat_charge_drone_shipping = 0
premium_shipping_flat_charge = 125#

# Ground Shipping 

if weight <= 2:
  price = 1.50 * weight
elif weight <= 6:
  price = 3 * weight
elif weight <= 10:
  price = 4 *weight
else:
  price = 4.75 * weight
print(flat_charge_ground_shipping + price)

# Drone shipping

weight_drone_shipping = 41.5

if weight_drone_shipping <= 2:
  price = 4.50 * weight_drone_shipping
elif weight_drone_shipping <= 6:
  price = 9 * weight_drone_shipping
elif weight_drone_shipping <= 10:
  price = 12 *weight_drone_shipping
else:
  price = 14.25 * weight_drone_shipping

print(flat_charge_drone_shipping + price)

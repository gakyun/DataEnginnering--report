# DataEnginnering--report
lovely_loveseat_description = "Lovely Loveseat.Tufted polyester blend on wood. 32 inches high x 40 inches wide x 30 inches deep. Red or white."
lovely_loveseat_price = 254.00


stylish_settee_description = "Stylish Settee. Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black."
stylish_settee_price = 180.50


luxurious_lamp_description = "Luxurious Lamp. Glass and iron. 36 inches tall. Brown with cream shade."
luxurious_lamp_price = 52.15


sales_tax = 1.088

customer_one_tax = (lovely_loveseat_price, stylish_settee_price, luxurious_lamp_price)
customer_one_total = (customer_one_tax[0] + customer_one_tax[2]) * sales_tax
customer_one_itemization = (lovely_loveseat_description, stylish_settee_description, luxurious_lamp_description)

print(("Customer One Items: \n%s") % customer_one_itemization[0] + customer_one_itemization[2])
print(("Customer one total: \n%.10f") % customer_one_total)

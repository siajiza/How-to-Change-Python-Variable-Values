# How to Change Python Variable Values

1º Calculate the tip of the total meal
2º Add the tip to the total meal
3º Make a receipt where must be write at the end an especial sentence


    meal_completed = True
    sub_total = 100
    tip = sub_total * 1/5
    total = sub_total + tip

    receipt = "Thank for your visit, Your total is " + str(total) + " €" 

    print(receipt) # Your total is 120.0 €

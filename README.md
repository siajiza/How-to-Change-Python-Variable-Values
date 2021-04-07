# How to Change Python Variable Values

<h2>Set up a calculator for the tickets plus tips.</h2>

1º Calculate the tip of the total meal.<br>
2º Add the tip to the total ticket of the meal. <br>
3º Make a receipt where must appear at the end an especially gratefully sentence and go on of the total amount price.<br>

<h2>See the final code</h2>

    meal_completed = True
    sub_total = 100
    tip = sub_total * 1/5
    total = sub_total + tip

    receipt = "Thank for your visit, Your total is " + str(total) + " €" 

    print(receipt) # Your total is 120.0 €


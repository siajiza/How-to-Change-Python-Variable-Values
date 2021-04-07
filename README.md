# How to Change Python Variable Values

<h2>Set up a calculator for the tickets plus tips.</h2>

1º Calculate the tip of the total meal.<br>
2º Add the tip to the total ticket of the meal. <br>
3º Make a receipt where must appear at the end an especially gratefully sentence and go on of the total amount price.<br>

<h2>See the final code</h2>

    meal_completed = True
    sub_total = 100
    tip = sub_total * 0.2
    total = sub_total + tip

    receipt = "Thank for your visit, Your total is " + str(total) + " €" 

    print(receipt) # Your total is 120.0 €

<h2>How we make it?</h2>

We are going to build a calculator using multiple data types:

    -Boolean
    -Integer
    -Float, inside of the number data types

In another side, so we will convert numbers on strings (number data types on text data types).
This just to let the Python interpreter print the receipt, and for that we need al the code on the same text data types.

<h2>Steps</h2>

1º. Use the Boolean to return "True", because the meal is completed.
2º. Write the Integer number on the "sub_total".
3º. The "tip" is going to be a multiple of the "sub_total": 20%. We use in this case a number data types.
4º. 

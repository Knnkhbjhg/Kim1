SEND 'Please enter the first number' TO DISPLAY
RECEIVE firstNumber FROM KEYBOARD
SEND 'Please enter the second number' TO DISPLAY
RECEIVE secondNumber FROM KEYBOARD
SEND ' Please enter the third number' TO DISPLAY
RECEIVE thirdNumber FROM KEYBOARD
SET total TO firstNumber + secondNumber + thirdNumber
SET average TO total/3
SEND average TO DISPLAY

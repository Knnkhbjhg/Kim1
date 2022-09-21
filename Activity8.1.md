SET mysNumb = 3
SEND 'Please enter guess number' TO DISPLAY
RECIEVE guessNumber FROME KEYBOARD
IF guessNumber > 10 THEN 
SEND 'Output Too high! Your guess must be between 1 and 10.' TO DISPLAY
ELSE IF guessNumber = mysNumb THEN 
SEND ' Output Well done You guessed correctly.'
ELSE SEND 'Output Badluck The correct number is' + mysNumb

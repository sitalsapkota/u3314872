BEGIN
1. Set feeding times: 8:00 AM and 6:00 PM.
2. Loop:
       a. Read current time.
       b. If time matches feeding time:
             i. Turn servo motor ON for 5 seconds to drop food.
             ii. Wait 10 minutes.
             iii. Read bowl weight after feeding.
             iv. If weight change < 5 grams:
                     Send "Food not eaten" alert.
       c. Check food bin level.
             i. If less than 10%, send "Refill food bin" alert.
       d. Repeat loop.
END



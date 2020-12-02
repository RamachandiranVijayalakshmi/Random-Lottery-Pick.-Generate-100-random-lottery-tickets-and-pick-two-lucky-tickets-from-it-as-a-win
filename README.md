## Random-Lottery-Pick.-Generate-100-random-lottery-tickets-and-pick-two-lucky-tickets-from-it-as-a-win
## The lottery number must be 10 digits long.
```sh
for i in range(100):
    # ticket number must be 10 digit (1000000000, 9999999999)
    lottery_tickets_list.append(random.randrange(1000000000, 9999999999))
```
## Example Output
The USA count is: 2
creating 100 random lottery tickets

# Python projects

welcome to my portfolio, this will look at the python projects that i have created this year:

## famer calculator
code for famer calculator:

```python
def legs(chicken,cow,pig):
    chickenAns = 2 * chicken
    cowAns = 4 * cow
    pigAns = 4 * pig
    legsArray = [chickenAns,"chickens",cowAns,"cows",pigAns,"pigs"]
    total = chickenAns + pigAns + cowAns
    print(total,"total legs")
    return legsArray

Ichicken = int(input("how many chicken: "))
Icow = int(input("how many cow: "))
Ipig = int(input("how many pig: "))

print(legs(Ichicken,Icow,Ipig))

```

### outputOfFarmerChallenge

![Alt screen for readers](farmerOutput.PNG)

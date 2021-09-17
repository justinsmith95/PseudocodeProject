How to make tea
PURPOSE:
Drinker follows the actions which interact with the correct objects to boil water and prepare tea. 

NECESSITIES:
Water must be contained within an object (cup or pot)
Water within a container must be able to be heated to boil



OBJECTS:
cup
tea bag
stove
burnertop
pot
watersource - Ex. sink
water

ACTIONS:
Fill pot nearly full with watersource
    Function(?) - is pot nearly full with water? If yes, then stop adding water from watersource; else add water from watersource.
        Exception(?) - is pot full/overflowing with water? If yes, then pour out some water from the pot. Return to start of the function. 

Place nearly-full-pot on the burnertop of the stove.

Turn stove burnertop with nearly-full pot on it to high heat

Place the tea bag inside the cup.

Once the water inside the nearly-full-pot begins to boil, pour the boiling water into the cup until it is nearly full.
    Function(?) - Is water inside the nearly-full-pot boiling? If yes, grab handle of pot and pour the water from the pot into the cup. Else, wait until water boils. ExpireTime for wait action(?)
        Subfunction(?) - While pouring water from pot to cup, is cup nearly full? If yes, stop pouring and place the pot back on burnertop. Else, continue pouring and return to the start of the subfunction (wait until cup is nearly full).
            Exception(?) - is cup full/overflowing with water? If yes, then stop pouring water from the pot and place the pot back on burnertop. Pour out some water from the cup. Return to start of the subfunction.

Drink the tea when it is your desired heat.
    Function(?) Wait a few minutes after pouring water into the cup. Check the tea with a small sip. Is the tea too hot? If yes, then wait 1 minute and repeat. If no, drink the tea at your leisure. 

END:ends with tea ready to be drank.



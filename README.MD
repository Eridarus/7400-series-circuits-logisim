This project is an attempt to fill out some of the missing 7400-series logic chips for Logisim that other libraries are missing.

Currently in the library are:

74xx23
74xx36
74xx43
74xx53
74xx60
74HC595
74xx99
74xx133
74xx134
74xx150
74xx165

Any mistakes in the chips are probably my fault. I have tried to standardize them. Real pinouts are used (where multiple exist, I have tried to use the most common ones).

Note that I skipped over repetitive chips (like how the 74xx12 is just the 74xx10 but with open-collector outputs).

Feel free to use any of these in your own simulations, and request chips to be added.

Some things I would like to add in future:
1. Short TTL guide (intro to TTL, some examples, etc.)
2. Blurb about each IC and how it functions plus where to use it
3. Previews of each IC
4. Make the page look nicer
5. Make a Logisim->Spice converter so people can use this in more modern applications
6. Test these circuits more (24 input circuit means 2097152 input cases which is a lot...) and Logisim's built-in tester isn't super expansive.
7. Add buffers/inverter buffers so that when converting to Spice it accounts for delays
8. Add delay information to all current/future ICs


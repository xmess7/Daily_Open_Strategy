
# PRESET FOR PROP CHALLANGE OPERATION

Hi folks. The preset I am providing was developed during my testing of the DOS EA.  MY only interest was to have a ready made preset that would allow me to see more trade operations so I could see if the EA was working properly.   I started to see that the preset was yielding small steady consistent results.  At first I didn't think that it could be used in a prop challenge.  Anyhow I ended up with 3 pairs that would help to provide the same steady small consistent gains but to the point that yea we might be able to use this in a prop challenge.

# TESTING THE PRESET in FTMO, MFF, AND FIDEL CREST TRAIL CHALLENGES

After I saw that the DOS EA was working nicely on OANDA/HANKOTRADE I decided to test it on a couple of PROP challenges and the results were consistent.  So I am now running this on a real challange.  I also added the EA to another challenge that I was down on.  The account was down -2.96% and in one week it is now only down -1.2%.   I have till the end of next week and based on its performance I can see this challenge getting back to BE, of course I will let it go into profit cause then I get a free retry.  That challenge was bought before the rules were change by the prop firm.

# IMPORTANT PLEASE READ THIS SECTION FOR SURE!!

There is onle one thing left that will make this EA rock solid and safe.  The control of DD currently only applied PER CHART.  In the next version I will have the EA control the DD FOR ALL CHARTS involved. So for example if you have the EA on 5 charts and any of the DOS EAs (Using same Magic Number) detect that the acount has fallen -x% DD (you sepecify the max DD in the inputs) all EAS will be disabled and all trade will be closed.
So BE CAREFUL select your DD accordingng per chart.  I KNOW I KNOW, you will see that I do not use the max DD input.  Geven the pairs and TF and how the EA is collecting profit I have ampple time to REACT and close all the trades IF there is ever a huge DD.   By HUGE I mean my limit is -6% DD when trading prop firms.  When trading a regular account I would consider a -15% DD.    BTW I have never seen -15%.  The mose I have seen is -3%, so far!!


# SETTING FOR PROP: PAIRS, TIMEFRAMES, TP SETTINGS

Here are the details you have been waiting for.

PAIRS and TIME FRAMES:

EURUSD - H4 TP: 14

GBPUSD - H4 TP:  14

GBPJPY - H1 TP: 30

LOTS/BALANCE

The PRESET has this default: 0.01/700

I typically use 0.01/500 for regular accounts.

I recommend that for the RED news days to use 0.01/1000 or turn off EA.

If you use anything higher then the DD will increase.  So far using thise lotsize settings ahve proven to be the most robust for when considering DD.

# FINAL THOUGHTS
The DOS EA should work on the prop firms I mentioned.  However we have seen rare cases where the DOS EA simple does not work.  In that case the user was working with a different brokers on which the EA was not tested.


Good luck to all and above all just TRUST YOURSELF ALWAYS
Jess



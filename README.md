# Daily_Open_Strategy

Forex Trading Startegy

Approach creeated by smilee89, for more info see his thread on forexfactory:

https://www.forexfactory.com/thread/1032108-dos-daily-open-strategy-easy-to-trade-simple

Hi, this is my attempt at creating the authors simple and effective approach.   
Hope it benefits anyone now and in the future :).


# Versions v5.5-7.1

2023.09.15   
- v7.1 Created diff algo so FIFO close trades on same chart.  
- v7.0 Added function FIFO feature for US Broker(only leverage <= 1:50)..  
- v6.0 Special update, only for this version, created time and hour separations so he can use in strat tester  
- v5.5 Added marginRequired test and fixed the lotzPerBalance error  

# Version 5

2023.08.16   
-Adjusted OrderCloseShort() and OrderCloseLong() error functions. Got rid of annoying error.  
-Changed TP from type int to double  
-added code to allow for proper calculation of point/pip size.  User just enteres pips/points      
-Added coded to allow for users to enter greater startTime than endTime         

Jess (xmess7)

# Ayam Geprek

In Keputih St, Sukolilo District, Surabaya, there's a booth of Ayam Geprek Which is very well known among the ITS student because not only did they open 24 hours, they also have various spiciness level and many types of condiment, not to mention the price which is very affordable for university students, especially who lives in dormitory houses, therefore they always have the longest line during breakfast, lunch, and dinner hours. 

to make the ordering lines more condusive, the owner decided to categorize into 3 types of order which is:

1. **OFFLINE X** = customer orders directly from the booth, price are standards.

2. **ONLINE X** = customer orders from delivery app, price are added by the delivery cost.

3. **P_ONLINE X** = priority online, online order that must be prioritized among all of the orders, price and delivery cost are more expensive than regular online.

the owner also set these serving rules to all workers:

execute: **SERVE**

1. Serve from P_ONLINE first
2. If none -> serve from OFFLINE 
3. If none -> serve from ONLINE 


at certain times, some delivery driver arrives faster, so we must ignore some serving rules and rush their order immediately. we can use **RUSH** so the online order are prioritized. 

# input Format 

the first line contain interger that represents the order amount. after that each line contain the order type and number that matched the order amount. the rest contain command that you can see before, which are: serve and rush.

# Output Format

for each **SERVE**, display the order numbers. if there are no orders available at that time you can display: NO ORDERS

# Input Sample

10  
OFFLINE 1  
OFFLINE 2  
ONLINE 100  
P_ONLINE 50  
SERVE  
RUSH  
SERVE  
SERVE  
SERVE  
SERVE

# Output Sample 

50  
100  
1  
2  
NO ORDERS


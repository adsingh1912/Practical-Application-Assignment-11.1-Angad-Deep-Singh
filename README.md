# Practical-Application-Assignment-11.1-Angad-Deep-Singh

Hi dealers,

I recognize that optimizing inventory is exceedingly important to manage working capital and storing inventory that gives the highest price results in maximizing return on investment. 
Given this premise, I carried out an analysis of ~426k used cars and their sales price to determine what factors maximize sales price.

Assumptions of the analysis:

The factors that have not been considered in the analysis are as follows:
   
    a.	VIN 
    
    b.	Region
    
    c.	State

These factors have been removed from the analysis to ensure that the analysis is region and state agnostic and useful for all involved, regardless of the state of operation

Results:

a)	The three most important factors that affect the predicted sales price (in order of importance) of the used cars are as follows:
         
          a.	Transmission
          
          b.	Vehicle type
          
          c.	Cylinders

b)	Other factors that also affect the predicted sales price in order of importance are as follows:
          
          a.	Age
          
          b.	Size
          
          c.	Fuel 
          
          d.	Odometer
          
          e.	Condition

Recommendations:

1) Increase stock of Automatic Transmission vehicles since the median sales price of automatic transmission vehicles is $12,700 vs a manual transmission vehicle that has a median sales price of $9,890.
          
          a.	Maximize stock of full-size automatic vehicles as they have the highest median selling price of $15,970
          
          b.	To diversity stock mid- size automatic vehicles as they have the second highest median selling price of $10,140
          
          c.	From here on, stock subcompact automatic vehicles as they have the a median selling price of $7,500
          
          d.	Finally stocking some compact automatic vehicles would further diminish market risk with a median selling price of $5,361

2) Maximize stock of 3-cylinder vehicles since 3-cylinder vehicles has the highest median price of $22,900. This is followed by electric vehicles, 
that do not have a cylinder with a median price of $19,000. From here, increase inventory of 8-cylinder vehicles with a median price of $18,680, 6 cylinder with a median price of $11,500, 4 cylinders with a median price of $9,500 and 5 cylinder with a median price of $6,433. 
Minimize inventory of 10-cylinder engine with a median price of $1,577
    
          a.  Within each of the cylinders, automatic vehicles had the highest median sales price and maximizing automatic transmission vehicles that are electric (median price of $31,000) and 3 cylinder (median price of 29,800) would be ideal. 
          b.	For 8 cylinder (median price of $19,000), 4 cylinder (median price of $9,701) and 5 cylinders (median price of $6,479) automatic transmission vehicles should be stocked

3) Maximize stock of full-size vehicles as they have the highest median sales price of $15,800, followed by mid-size vehicles at a median sales price of $10,000.
Thirdly stock sub-compact vehicles would be better with a median sales price of $7,700 followed by compact vehicles with a median sales price of $5,219

4) Finally, vehicles with new condition had the highest median sales price of $24,000 that are automatic transmission, followed by like new that are automatic transmission with a sales price of $17,000. 
This was followed by good condition of automatic transmission of $13,240.

All charts showing these results can be found in the jupyter notebook along with this readme file. 


Detailed Analysis and code :
The jupyter notebook named Practical application - Submission ADS showcases the detailed analysis, that is attached with this readme file. 


Next steps:
I would suggest further analysis to determine the exact mix of each of the vehicle types, i.e inventory mix, to optimize working capital for each dealer. 
Furthermore, this mix can be optimized for each individual state and dealer. Also, the speed at which sales occur can be analyzed and a strategy can be developed to 
optimize between sales velocity and margins to determine the appropriate strategy.

Thanks and regards,

Angad Deep Singh





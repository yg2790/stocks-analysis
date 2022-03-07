# Stock Analysis with VBA

## Overview of Project
### Purpose
To create a algorithm and minimize run time for Steve to analyse the stock market dataset through refractoring the original code. The algorithm will produce a structured table including total daily volume and percentage return in VBA. 

## Results
### Stock Performance 2017
The overall performance of the 12 stocks in 2017 are reletively well with postive returns except for the TERP ticker. There are a total of 4 tickers that saw overs 100% return in investment which are DQ, SEDG, ENPH, and FSLR. DQ and SEDG reached almost 200% return in investment at 199.4% and 184.5%, respectively. We can conclude that 2017 is overall a good year in the stock market with growth in selected tickers. <br />
<img width="495" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/98621924/156948373-9d7ba2a3-5187-4856-ab1f-abe3738599bb.png"> <br />
Execution Time <br />
<img width="259" alt="Screen Shot 2022-03-06 at 4 25 48 PM" src="https://user-images.githubusercontent.com/98621924/156949187-efb06bd8-16d8-4ea2-9113-a8d55b1116c6.png"> 

###Stock Performance 2018
On the other hand, stock performances in 2018 were disappointing. 10 out of the 12 tickers saw negative return with the higest at -62.6% and a total of 4 tickers exceeding 30% loss. ENPH and RUN are the only two tickers invested that saw overal growth, both over 80% at 81.9% and 84%, respectively. <br />
<img width="514" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/98621924/156948507-b6e6a207-167b-40b4-a4b9-9a3cfb0a218c.png">
Execution Time <br />
<img width="261" alt="Screen Shot 2022-03-06 at 4 26 01 PM" src="https://user-images.githubusercontent.com/98621924/156949215-4b7a1474-a10c-4d23-ab04-24e545b45360.png"> 


### YoY Comparison
The best performer of 2017, DQ, with almost 200% return saw the largest negative return in 2018 at -62.6%. ENPH maintained its high growth rate with 129.5% in 2017 and 81.9% in 2018. RUN saw the largest increase in return from 5.5% in 2017 to 84% in 2018. Both of ENPH and RUN not only saw growth in 2018, but relatively high returns as the annaul expected stock market return is usually between 10% to 20%. To further understand the results, we can look into the nature of the tow tickers, ENPH and RUN, to identify characteristics such as their industry, asset makeup, financial performances, and busienss strategies. One can speculate that the stock market had experienced financial turbulence, exposing the majority of the market to systematic risks that led to overall poorer performance compared to the previous year. However, certain firms and/or industires were immune to these risk, which its reasons should be further investigated.

## Summary
The advantages of refracting code is that it will cut down the run time of the algorithm. Once the data set grows, the time it will take for VBA to run through code will exponentially increase with nested loops and conditionals. Refracting the code will allow us to remove unnecessary phrases and combine parts that overlaps to make the code more effcient.<br />
However, the process of cleaning up and refracting the code can lead to accidental deletion of important parts which can increase the potential of running into errors. Removing parts can also make it harder for collaborators to interpret the author's chain of thought and logic with many loops and conditionals. It is important to make sure one includes detailed comments before each block of code to explain what that section is doing. It will make further editing and debugging simplier and more straighforward. <br />
In this case, there wasn't much of a difference in the run time of my original code and my refracted code, both around 0.63 - 0.73 seconds. Both when dealing with a larger data set, with algorithms calculating and running through hundreds and throusands rows of data, refracting code will significantly cut down the run time and increase the efficiency of debugging and analysis.

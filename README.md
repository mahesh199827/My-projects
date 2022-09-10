# Portuguese-bank-marketing-project
Portuguese bank marketing prediction :

The data is related with direct marketing campaigns of a Portuguese banking  institution.  The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be (or not) subscribed.


Data description:

1. Age            - Referring to age of a person.

2. job            - Represents employment status of a person.

3. Marital        - Represents marital status of a person.

4. Education      - Represents the level of education.

5. Default        - Defaulting on a loan essentially means you've stopped making payments on a loan or credit card according to the account's terms. In general, defaulting on a loan can damage your credit and threaten your overall financial health.

6.Housing         - Whether that person took a loan or not.

7.Loan            - Whether that person has personal loan or not.

8.Contact         - Represents Communication channel.

9.Month           - Represents last contact month of a year.

10.Day of week    - Represents Last contact day of a week.

11.Duration       - Represents how many seconds that a call was happened.

12.Campaign       - Represents number of contacts performed during this campaign and for this client.

13.Pdays          - Represents number of days that passed by after the client was last contacted from a previous campaign.

14.Previous       - Represents  number of contacts performed before this campaign and for this client.

15. poutcome      - outcome of the previous marketing campaign

16.emp.var.rate  - employment variation is essentially the variation of how many people are being hired or fired due to the shifts in the conditions of the economy. When the economy is in a recession or depression, people should be more conservative with their money and how the spend it because their financial future is less clear due to cyclical unemployment. When the economy is at its peak, individuals can be more open to risky investments because their employment options are greater.

17-cons.price.idx - The Consumer Price Index measures the overall change in consumer prices based on a representative basket of goods and services over time. The CPI is the most widely used measure of inflation, closely followed by policymakers, financial markets, businesses, and consumers.

18. cons.conf.idx - This consumer confidence indicator provides an indication of future developments of households consumption and saving, based   answers regarding their expected financial situation, their sentiment about the general economic situation, unemployment and capability of savings.

19. euribor3m - Euribor is short for Euro Interbank Offered Rate. The Euribor rates are based on the interest rates at which a panel of European banks borrow funds from one another. In the calculation, the highest and lowest 15% of all the quotes collected are eliminated.The 3 month Euribor interest rate is the interest rate at which a selection of European banks lend one another funds denominated in euros whereby the loans have a maturity of 3 months. Alongside the 3 month Euribor interest rate we have another 14 Euribor interest rates with different maturities. The Euribor interest rates are the most important European interbank interest rates. When the Euribor interest rates rise or fall (substantially) there is a high likelihood that the interest rates on banking products such as mortgages,savings accounts and loans will also be adjusted.

20. nr.employed    - Number of employees

21. Y              - Subscribed term deposit or not.


EDA and insights:

![image](https://user-images.githubusercontent.com/103163052/189482478-79fc2d8b-f931-44db-ac2e-172b229c7f6a.png)

	Through the pie chart, it is observed that out of all the total clients only 11.27% subscribed for the term deposits and the rest didn't.
	Duration plays major role in subscribing to the deposit.
	Students and retired people subscribing the more.


Data preprocessing:

	The data contains lots of unknown values and it was replaced by highly repeated values for better prediction.
	I used lots of encoding techniques like frequency encoding, label encoding and manual encoding according to the type of data.
	Then i handled outliers for the following features like age, duration, campaign, pdays, previous and consumer confidence index.
	Then i scaled the data for better performance.


Model Comparison:


I used lots of algorithms to check which model is performing well . Look at the following table for better model.
![Capture](https://user-images.githubusercontent.com/103163052/189482684-cbf74103-4c92-435c-83fc-6eca25ab2381.PNG)

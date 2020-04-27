# Small Business Lending with Kabbage

![Kabbage Image](data:image/png;base64,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)

## What is Kabbage:

Kabbage, Inc. functions as a fintech company serving small to medium sized business.  According to Kabbage Story, the company was cofounded by Kathryn Petralia, Rob Frohwein and Marc Gorlin to "create a business dedicated to helping other small businesses grow" (Kabage Story).  The founders recognized a significant gap between technological advances in other industries and lending, and saw the advent of a technologically driven lending platform as an opportunity to improve the small business lending experience.   

Thus, in 2011, the company launched, and utilized online seller's data to underwrite transactions with a turn time from application to approval in less than 7 minutes (Kabbage Story).

The company is privately held at the time of this publishing and is based in Atlanta, Georgia.  Wikipedia notes that Kabbage is venture funded and supported by other entities such as Reverence Capital Partners, SoftBank Capital, Thomvest Ventures, Mohr Davidow Ventures, and BlueRun Ventures (Kabbage).  In its largest backing to date, Kabbage raised $700 million in asset-backed securities in 2019 which it called "the largest transaction of its kind for an online lending platform focused on small business" (Lunden).  According to Forbs, the company's latest valuation is $1.2 billion. 


## Business Activities:

As stated previously, Kabbage is an online small business lender.  The founders recognized a significant gap in the use of technology to serve the small business lending space. According to the Small Business Administration, there were $614 billion in small business loans (loans equal to or less than $1 million) outstanding as of June 2016 (SBA). 

Traditional small business lending involves gathering a number of financial documents including company tax returns, bank statements, personal tax returns and other application documents which are then submitted to a banker or other type of lender.  This bank sends this information to an underwriter who analyzes the information in order to determine if the applicant can qualify for a loan.  This process can take anywhere from several hours to several days to reach a decision for the applicant.  Kabbage, in the use of technology, has reduced the amount of information required and utilized data to reach decisions in a matter of minutes.   

How is Kabbage able to make such fast decisions?  Kabbage seeks to serve small to medium sized businesses through its online lending platform in the use of Big Data.  Brian Jackson's article *[How Kabbage Knows If It Can Lend You $100,000 in Just Seven Minutes](https://www.itbusiness.ca/news/how-kabbage-knows-if-it-can-lend-you-100000-in-just-seven-minutes/78573)* provides a glimpse into how Kabbage's lending platform works.  Kabbage's technological platform is based on AI and systems integration to capture applicant data points it uses in its underwriting algorithum (Lunden).  

A recent job post for a *[Data Science Modeler](https://fintechfans.com/job/5790/data-science-modeler/)* provides some insight into the some of programs the company use on its platform.  In the post, the company sought and individual with ability to work with "multiple data sources such as financial transactions, credit bureau reports, social media behavior, and e-commerce data" to "build predictive models including credit risk, fraud, marketing response and propensity."  Additional requirements include a  "strong background in applying statistical machine learning techniques to predictive modeling" and preferable experience with Python.  

According to the company's Stackshare profile, the company utilizes various popular applications such as JjQuery, AngularJS, Microsoft Azure, Google Cloud Platform, Google Analytics, and GMAIL to name a few.  

What sets Kabbage apart from the traditional bank lending process?  Kabbage uses AI and alternative data about its applicants in order to make decisions.  According to Steve Nicastro of Nerdwallet, Applicants seeking loans from Kabbage must meet several requirements including being in business for at least 1 year, have a minimum of $50,000 per year in revenue, and a minimum credit score of 560. Applicants are required to connect their bank accounts and other business services such as Paypal or Quickbooks to the Kabbage platform, and Kabbage uses this information to determine an applicant's revenue.    

What is Kabbage's primary product?  Kabbage offers lines of credit up to $250,000 to its customers (*[How Kabbage Loans Work](https://www.kabbage.com/resource-center/finance/how-kabbage-loans-work)*).  A traditional revolving line of credit functions similar to a credit card in which a company makes a draw request for anything from working capital to payroll and the funders are then paid back a later date in the short term when the company begins to receive payments from its customers.  Companies typically make interest only payments until the balance is paid in full or the loan becomes due (usually up to 1 year), and as funds are paid back, the funds remain available to the company until maturity or expiration (How to Use Your Kabbage Line of Credit).  

A Kabbage line of credit functions quite differently.  Kabbage offers shorter terms on its lines of credit which function more like a non-revolving line of credit in the traditional bank terms.  Applicants make a draw request on the line of credit, and, depending on the amount, are subject to a repayment term of 6 to 12 months with principal payments required over the term.  Each draw functions like an individual loan with the entire balance being paid over the term as a portion of each payment is applied to principal and fees.  Kabbage loaned $2 billion to small businesses in 2018 (Lunden).


## Landscape:

Karen G. Mills, a Harvard Business Schools Senior Fellow, predicts "artificial intelligence, machine learning, and big data will transform financials services and small business lending before they impact driverless cars."(*[How Fintech is Changing The Small Business Game](https://www.forbes.com/sites/hbsworkingknowledge/2019/04/11/how-fintech-is-changing-the-small-business-game/#74e5aa84ebf0)*). Mills further elaborates that the over 30 million small businesses are critical to the U.S. economy and there has been a critical funding gap in businesses seeking loans for less than $100,000.  Companies like Kabbage have thrived in this underserved segment and are able to do so at a lower cost due to technological innovation.   

According to Experian, fintech companies have disrupted the lending industry through its "introduction of alternative lending models", "fast approvals", "making use of data", and offering "perks and savings" (*[4 Ways Fintech Has Changed the Lending Process](https://www.experian.com/blogs/insights/2019/03/4-ways-fintech-changed-lending/')*). The rise of  Big Data and AI allowed tech companies to leverage data in order to build sophisticated credit risk profiles and models used to predict default rates and project applicant cash flow.  Being traditionally viewed by larger financial institutions as unprofitable, fintech companies been successful in this segment due to their increased efficiency and low overhead costs.    

Kabbage is not the only major fintech company in the small business lending segment.  Other companies like Prospa, Fundbox, Funding Circle and OnDeck also compete in this segment, each with their unique offering.  Funding Cirlc specializes in peer to peer lending, while Fundbox focuses on lending against small business invoices much like factoring.  OnDeck offers fixed term loans up to $500,000  and lines of credit up to $100,000, while Prospa offers small business loans up to $250,000 (*[7 Fintechs that are Transforming SME Lending](https://www.provenir.com/blog/7-fintechs-that-are-transforming-sme-lending/)*).
  


## Results

What measures the success of Kabbage?  One of those is its ability to remain competitive in a fast changing landscape and Kabbage has been able to keep pace.  In addition to its $2 billion in funding reached in 2018, the company recently expanded its product offering.  In 2018, Kabbage launched Kabbage Payments which integrates with its funding platform to offer customers custom payment schedules in addition to a user friendly payment system to process transactions (*[Kabbage Offers New SMB Loan Product](https://www.pymnts.com/news/b2b-payments/2020/kabbage-steps-up-payments-offering-with-smb-loans/)*). Kabbage continues to remain on of the top fintech lenders in the industry.

Success factors in the online lending space are evolving, but OnDeck, a key competitor of Kabbage, defined several keys to remaining competitive including (1) the customer experience, (2) brand recognition and trust, (3) loan features, and (4) effectiveness of customer acquisition (*OnDeck Capital 2019 10K*). 


Customer Experience and Customer Acquisition: Offering customers a simplified approach is what sets companies like Kabbage apart from traditional banks.  Its innovative integration of Big Data and AI and simplified customer interface led to faster decision times which has improved customer experience over traditional banks. Kabbage services over 225,000 businesses with over $9 billion in lending since company inception.  

Brand Recognition:  Kabbage is synonymous with online Small Business Lending.  Through advertising and marketing campaigns, Kabbage has positioned itself as one of the top online small business lenders.  Kabbage has also been featured in Forbes Fintech 50 for 2020 further enhancing its market credibility and brand visibility (*[Future of Small Business Lending: Fintech 50](https://www.forbes.com/sites/hanktucker/2020/02/12/the-future-of-small-business-lending-fintech-50-2020/#3726c3e44f9b)*)

Loan Features:  Kabbage began with a small line of credit product which has now increased in available limits to $250,000.  This product gives the customer the flexibility to select repayment terms of 6, 12, and up to 18 months.  Fees and requirements are transparent to the customer utilizing the SMART BOX capital comparison tool standardized by the Innovative Lending Platform Association which includes members such as Kabbage, Fundbox, and OnDeck.  This tool clearly articulates funding terms to perspective borrowers to increase customer understanding of loan terms (*[Innovative Lending Platform Association](https://innovativelending.org/)*).  


## Recommendations

Given Kabbage's robust technological suite of products and integration with Big Data and AI, the company could benefit from an additional product offering through invoice factoring.  Factoring, in summary, is financing a businesses invoices.  This lending philosophy requires a credit review of the businesses customer and not the borrowing business.

Based on research completed in this case study, Kabbage has access to many data points through its existing platform and interface.  This existing technology could be leveraged to shift the subject of the credit review from the applicant to the customers of the applicant.  Through integration with accounting software such as Quickbooks and other outside data sources such as social media, better business bureau information, and customer reviews, Kabbage can construct a profile on its borrower's customers to examine probability of timely payment and analyze historical payment performance.  This profile could then be used to determine the risk associated with company specific invoice payments.

 Kabbage has made its presence known in the small business lending space.  Through technological innovation and expanded product offerings, the company continues to expand its footprint in the ever evolving Fintech lending domain.    


___
## References

Kabbage Story - https://www.kabbageplatform.com/about-kabbage-platform/story/

Kabbage - https://en.wikipedia.org/wiki/Kabbage

Kabbage Raises a Record $700 Million in Debt For Its Smb Loans Platform
Ingrid Lunden - https://techcrunch.com/2019/04/08/kabbage-700-million/

Kabbage -
https://www.forbes.com/companies/kabbage/#2c86a86b2b90

Kabbage Vs. Ondeck: Which Lender Is Best For Your Business?
Steve Nicastro-Steve Nicastro-Steve NerdWallet- USA Today- Associated Press. - https://www.nerdwallet.com/blog/small-business/kabbage-ondeck-lender-small-business/

How Kabbage Loans Work - Kabbage Resource Center
Kabbage - https://www.kabbage.com/resource-center/finance/how-kabbage-loans-work

How To Use Your Kabbage Line Of Credit
Erica Seppala - https://www.merchantmaverick.com/how-to-use-kabbage-line-of-credit/

How Kabbage Knows If It Can Lend You $100,000 in Just Seven Minutes
Brian Jackson - https://www.itbusiness.ca/news/how-kabbage-knows-if-it-can-lend-you-100000-in-just-seven-minutes/78573

Data Science Modeler (atlanta, Ga, Usa)
https://fintechfans.com/job/5790/data-science-modeler

Kabbage - Kabbage Tech Stack
https://stackshare.io/kabbage_2/kabbage

4 Ways Fintech Has Changed the Lending Process
https://www.experian.com/blogs/insights/2019/03/4-ways-fintech-changed-lending/'

How Fintech Is Changing The Small Business Game
HBS Knowledge - https://www.forbes.com/sites/hbsworkingknowledge/2019/04/11/how-fintech-is-changing-the-small-business-game/#74e5aa84ebf0


Kabbage Offers New Smb Loan Product
Pymnts - https://www.pymnts.com/news/b2b-payments/2020/kabbage-steps-up-payments-offering-with-smb-loans/

The Future Of Small Business Lending: Fintech 50 2020
Hank Tucker - https://www.forbes.com/sites/hanktucker/2020/02/12/the-future-of-small-business-lending-fintech-50-2020/#3726c3e44f9b

https://innovativelending.org/

On Deck Capital, Inc. Form 10-K - https://investors.ondeck.com/public-filings/sec-filings/sec-filings-details/default.aspx?FilingId=13974008
#### 
# Data Biography
## Student Number: 20185583
---

### 1. Who collected the data?

The Inside Airbnb website and especially his founder Murray Cox, has collected data from the official Airbnb website for listings available for London <cite>[1]</cite>.

---

### 2. Why did they collect it?

The data was collected to show the impact that Airbnb has on London's residential communities and to explain how the provision of Airbnb rooms, houses and entire apartments disrupts residential housing and doesn’t follow the principles of the sharing economy, as most hosts have more than one listing [2].

---
### 3. How was it collected?

The data collection method is the occupancy model, based on the following parameters [2], [3]:
<br />• Measurement of the number of nights booked or available per year for high availability
<br />• A frequently rented filter of 90 days per year
<br />• Usage of 50% review rate to convert reviews into estimated bookings.
<br />• Set an average length of stay (4.6 nights for London), which multiplied by the estimated bookings for each listing over a period, gives the occupancy rate.
<br />• A maximum occupancy rate of 70%

---

### 4. What useful information does it contain?

The data includes useful information such as:
<br />•the number of listings per host, to prove whether hosts are sharing their accommodation and not using accommodations for financial gain causing real estate problems
<br />•how much does each listing per night cost, to compare prices with hotels and permanent rental revenue
<br />•the area of the listing to show where tourist gentrification areas are located
<br />•the amenities for the comparison of quality - price of each accommodation
<br />•the minimum and maximum days of stay
<br />•the type of accommodation
<br />•availability over year
<br />•the number of guests
<br />•the review score for fields such as communication, location, check-in, accuracy, etc.

---

### 5. What useful information is it missing?

The useful missing information is:
<br />•Data for other months of the year to examine seasonality
<br />•Tax requirements for hotels, environment, etc.
<br />•Existence of licences to see if the accommodation is legal or illegal (all records of licence field are NaN) 
<br />•Data of other years to analyse Airbnb’s growth and impact

---

### 6. To what extent is the data 'complete'?

The data is complete to some extent, but not entirely. Surely, they provide important spatial information to see the characteristics of the most sought-after areas and where gentrification occurs [14], but do not reveal the real impact of Airbnb on the daily life of the residents. Also, while providing financial data, amenities and occupancy that allow to analyse the impact of Airbnb on the real estate market and hotel activity, there is no data on the taxes that hosts have to pay, in order to calculate their net income and make comparisons [13]. In addition, we are not aware of the existence of illegal listings, so their total number may be different, creating a distorted picture of active accommodation. Finally, the data provided is a snapshot of August 2020 and does not reflect the evolution of short-term leasing over time. Thus, the data do not fulfil 100% of the purpose for which they were collected.

---

### 7. What kinds of analysis would this support?

The kinds of analysis that the data could support are:
<br />1. Exploratory Data Analysis which allows to perform [7]:
  <br />a. Spatial Analysis, which with the use of location and geographical coordinates can produce maps related to the spatial concentration of accommodation, the degree of saturation of each neighbourhood, the spatial distribution of prices, etc. [5]
<br />  b. Descriptive statistical analysis, with which we can describe and illustrate qualitative and quantitative characteristics such as the average price of rental costs, the frequency (f) of the occurrence of a host or a type of accommodation, the standard deviation, etc. [4]
<br />  c. ANOVA to examine the relationship between quality and price, supply and demand, etc. [4]
<br />2. Content Analysis, which based on the reviews of the guests can be used to evaluate the quality of the services provided, to analyse the profile of the hosts, etc. [6]

---

### 8. What kinds of analysis would it _not_ support?

The types of analysis that research cannot support are:
<br />1. Empirical/Narrative analysis, as the data collected is directly from the Airbnb website and no experiential research carried out such as questionnaires for permanent residents, interviews with hosts, on-the-spot verification of illegal accommodation, etc. [6]
<br />2. Predictive data analysis, as the data refers to a specific month and year, while to make a correct prediction of the rate of increase or decrease of short-term accommodation and possible correlation with the reduction of available long-term lease properties we need data from previous years. We also need all the months of the year to predict seasonality.

---

### 9. Which of the uses presented in Q.7 and Q.8 are _ethical_?

In terms of spatial analysis, hosts can provide their coordinates on the platform so that guests can locate the accommodation, but they do not have them available to all website’s visitors for security reasons, so it is not ethical to use the exact coordinates, especially when hosts are unaware of the survey [9]. Perhaps a more approximate mapping would not violate the rules of ethics.
<br />Regarding the financial data analysed by descriptive statistics and ANOVA, they allow us to outline the financial profile of the hosts (income, number of properties to be rented, etc.), but without their awareness. Also, the use of the host's photo, description, name and other details in combination with other data used by the researcher may reveal sensitive information about the host [8]. This is a "violation" of their personal data, so it would be good to remove or modify them so as not to target someone's profile. Furthermore, concerning users’ reviews, since they have written them voluntarily to help other users, it is not considered "immoral" to use them for research purposes that will help even more people [10].
<br />If we were conducting an empirical analysis, all those involved would have to fill out a consent form to participate in the research, so there would be no "ethical" problem [11]. At the same time, in predictive data analysis because the result produced is estimated and may be far from accurate, the researcher has to state that he is not responsible for any difference between the estimation and reality, in order to be ethically correct.
<br />Overall, although the types of analysis in Q.7,8 use a dataset that provides personal information and can yield "shocking truths" or misleading results, the researcher must be critical and use them in a way that does not affect human dignity [12].

---

### Appendix

[1] Inside Airbnb, “Behind Inside Airbnb,” Inside Airbnb, 2015. http://insideairbnb.com/behind.html.
<br />[2] Inside Airbnb, “About Inside Airbnb,” Inside Airbnb, 2015. http://insideairbnb.com/about.html.
<br />[3] Inside Airbnb, “Inside Airbnb: London. Adding data to the debate.,” Inside Airbnb. http://insideairbnb.com/london/.
<br />[4] C. Heroku, “Introduction to Exploratory Data Analysis (EDA),” Medium, Mar. 25, 2019. https://medium.com/code-heroku/introduction-to-exploratory-data-analysis-eda-c0257f888676 (accessed Nov. 22, 2020).
<br />[5] Ankit Peshin, Sarang Gupta, Ankita Agrawal, “Exploratory Data Analysis and Visualization of Airbnb Dataset,” Columbia.edu, Dec. 10, 2018. http://www.columbia.edu/~sg3637/airbnb_final_analysis.html (accessed Nov. 23, 2020).
<br />[6] M. Bhatia, “Your Guide to Qualitative and Quantitative Data Analysis Methods,” Atlan | Humans of Data, Sep. 05, 2018. https://humansofdata.atlan.com/2018/09/qualitative-quantitative-data-analysis-methods/#Qualitative_Data_Analysis_Methods.
<br />[7] S. Gupta, “Airbnb Rental Listings Dataset Mining,” Towards Data Science, Jan. 04, 2019. https://towardsdatascience.com/airbnb-rental-listings-dataset-mining-f972ed08ddec.
<br />[8] J. P. A. Ioannidis, “Informed Consent, Big Data, and the Oxymoron of Research That Is Not Research,” The American Journal of Bioethics, vol. 13, no. 4, pp. 40–42, Apr. 2013, doi: 10.1080/15265161.2013.768864.
<br />[9] S. Elwood and M. Wilson, “Critical GIS pedagogies beyond ‘Week 10: Ethics,’” International Journal of Geographical Information Science, vol. 31, no. 10, pp. 2098–2116, May 2017, doi: 10.1080/13658816.2017.1334892.
<br />[10] K. Crawford and M. Finn, “The limits of crisis data: analytical and ethical challenges of using social and mobile data to understand disasters,” GeoJournal, vol. 80, no. 4, pp. 491–502, Nov. 2014, doi: 10.1007/s10708-014-9597-z.
<br />[11] V. van den Bemt, J. Doornbos, L. Meijering, M. Plegt, and N. Theunissen, “Teaching ethics when working with geocoded data: a novel experiential learning approach,” Journal of Geography in Higher Education, vol. 42, no. 2, pp. 293–310, Feb. 2018, doi: 10.1080/03098265.2018.1436534.
<br />[12] A. N. Markham, K. Tiidenberg, and A. Herman, “Ethics as Methods: Doing Ethics in the Era of Big Data Research—Introduction,” Social Media and Society, vol. 4, no. 3, p. 205630511878450, Jul. 2018, doi: 10.1177/2056305118784502.
<br />[13] J. Harris, “Profiteers make a killing on Airbnb – and erode communities | John Harris,” the Guardian, Feb. 12, 2018. https://www.theguardian.com/commentisfree/2018/feb/12/profiteers-killing-airbnb-erode-communities (accessed Nov. 23, 2020).
<br />[14] D. Wachsmuth and A. Weisler, “Airbnb and the rent gap: Gentrification through the sharing economy,” Environment and Planning A: Economy and Space, vol. 50, no. 6, pp. 1147–1170, Jun. 2018, doi: 10.1177/0308518x18778038.

---

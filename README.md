## Overview of the data:
Data consists of the parking citations issued in the City of Baltimore over the last four years. This is a huge data set with a memory of 842.5 MB. However, I am considering only the month of April of the 2019 and 2020 years which reduces the size significantly (approximately to 30 MB).

Data consists of 26 columns:

• Citation: Citation number issued by the police personnel

• Tag: Vehicle registration plate/tag number

• ExpMM: Vehicle registration expiration month

• ExpYY: Vehicle registration expiration year

• State: State of registration

• Make: Vehicle make

• Address: Location where the citation is issued

• ViolCode: Violation Code

• Description: Description of citation

• ViolFine: Original violation fine

• ViolDate: Date of violation

• Balance: Outstanding balance including original fine and penalty fees

• PenaltyDate: Date penalty fee is applied

• OpenFine: Unpaid original fine

• OpenPenalty: Unpaid penalty fees

• NoticeDate: Date of notice for violation

• InvestigationStatus: Investigation status

• TrialStatus: Trial Status

• GeneralStatus: General status

• GroupID: Group ID

• ImportDate: Date record is imported

• Neighborhood: Neighborhood where violation occurred

• PoliceDistrict: Police district where violation occurred

• CouncilDistrict: Council district where the violation occurred

• Location: Geographic coordinates where the violation occurred

• Zip Codes: Zip code of the location where violation has occurred

Record count of original data is 4705888. However, the data under the study has record count of 177040.

Size of data under study: 30 MB.

## Summary of the Project:

1] On analyzing the maximum number of violations that are committed by each vehicle, notice that most vehicles performed 1 violation however, there are few vehicles which performed as high as 31 violations in a month.

2] On analysing the vehicle registration state, noticed that most violations that happened in Baltimore city are done by vehicles registered under the home state ie., Maryland (90%), followed by the nearby states Virginia (3%) and Pensylvania (1.7%). Also, noticed that there is a slight relationship between vehicle's state and the type of violation committed.

3] Noticed that majority violations are performed by the vehicles of Make - Honda, Toyota and Nissan.

4] More than 50% of violations are of the type: Fixed Speed Camera (56%), followed by Red light violation (12%) and Right on Red (12%).

5] Noticed that most of the violations happen during weekdays and during 8 AM - 7 PM hours. In april, 2019 majority of violations happened between 8 AM - 2 PM, however in April 2020, majority violations happened during 3 PM - 7 PM.

6] Noticed there are few incidents in which red light violation, fixed camera violation etc. where the notice was issued nearly 19 months after the violation incident.

7] Finally, due to the lock down during COVID-19 pandemic in the month of April 2020, noticed a overall drop of 16.59% in the violations reported in comparison to April, 2019. However, there is no statistical significance at alpha = 0.05 per state.

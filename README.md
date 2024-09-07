# Call-Centre-Trends
This project is part of a Virtual Internship on Power BI with PwC Switzerland, offered through the Data Analytics Virtual Case Experience by Forage.
# Problem Statement
Claire, the Call Centre Manager at PhoneNow, is seeking an efficient and comprehensive method to gain transparency and insights into key performance metrics of the Call Centre. These metrics include total calls answered and abandoned, speed of answer, call duration, and overall customer satisfaction. She is specifically interested in understanding long-term trends related to both customer and agent behaviors. The goal is to have a dashboard that accurately visualizes this data to facilitate discussions with management and improve decision-making. The dashboard should highlight critical aspects of the Call Centre's performance in a clear and actionable format.

# Dataset Overview
The dataset contains call records with details on call performance and customer satisfaction. It includes various columns providing insights into the call topics, agents, call handling efficiency, and customer feedback.


| **Column Name**                | **Description**                                                            |
| -------------------------------| -------------------------------------------------------------------------- |
| Call Id                        | Represents the unique identifier for each call.                            |
| Agent                          | The name of the agent who handled the call.                                |
| Date                           | The date when the call occurred.                                           |
| Time                           | The time of the call.                                                      |
| Topic                          | The topic of the call (e.g., Contract related, Payment related).           |
| Answered (Y/N)                 | Whether the call was answered or not.                                      |
| Resolved                       | Whether the call was resolved during the interaction.                      |
| Speed of answer in seconds      | The time taken for the agent to answer the call, measured in seconds.      |
| AvgTalkDuration                 | The average duration of the conversation.                                  |
| Satisfaction rating            | The customer's satisfaction rating, ranging from 1 to 5.                   |

Additional Column Added

Topics Resolved: A new column was created using the formula IF(Sheet1[Resolved] == "Y", 1, 0). This column indicates whether a call topic was successfully resolved (1 for resolved, 0 for unresolved).

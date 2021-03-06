# Archtype of delay: Developer comment chain analysis

## Repository content 
This repository is a complementary data provider for the article "*Archetypes of Delay: An Analysis of Developer Comment Chains on Delayed Work Items in IBM Jazz*". Thus, definitions and details, such as symbols meaning, in the paper are not repeated here.  The files in the repository describe: 

- Late work items time series clustering result: [cluster_late_workItem.csv](./cluster_late_workItem.csv "Late work items time series clustering result"),
- Non-late work items time series clustering result: [cluster_non-late_workItem.csv](./cluster_non-late_workItem.csv "Non-late work items time series clustering result"),
- Similarity table between symbols in time series: [similarity_table.md](./similarity_table.md "Similarity table between symbols in time series").

## Context
Agile software development has been widely adopted because along with flexibility to actively re-scope of project, it also brings responsiveness to quickly deliver a requirement. Moreover, software development process nowadays is distributed thus developers often use packed solution with instant message functionality to exchange information, coordinate their work and keep track of the progression of their projects. These tools generate valuable text data. Despite numerous studies on agile process to give best practice recommendations this last decade, few has been focused on generated textual communication data impact on the workflow.   
## Objective
In this paper we propose to mine text data, generated from IBM software development coordination, by characterizing conversation in late tasks and take out some recommendations. So we first (1) evaluate the dynamics of conversations and then (2) analyze impact of these dynamics on the implementation progression.
\paragraph{\textbf{Method}}
To leverage this textual data we started with a thematic analysis in order to identify and characterize the predominant themes in each conversation as theme sequence; followed by a clustering technique to find similarity between those themes sequences and finally a qualitative analysis to interpret the clustering result.
## Result
The findings show that late tasks exhibit different profiles and each profile is associated with a reason why the delivery of the requirement is getting late. The major reason  for the delay is a lack of fluent communication associated with a poor project management. Conversely non-late tasks delegate more to children tasks and are proactive on handling requests.
## Conclusion
Our analysis has showed those text data generated along side software development process is a mine of information that can highlight a requirement implementation progression and the dynamics between the developers. It even has a potential to be used to closely monitor the workflow and quickly address the knot points, and yield to more proactive team management. 

# dsa3101_intelli_insure
assignment 1


5. Webapp
5.1 Understanding User’s Needs & Key Pain Points
A webapp is necessary for clients to access our data-driven solutions such as machine learning predictions and data visualization. This is so as the client will lack technical skills to operate the code. Therefore, a solution without an accessible interface has no business value to them as they cannot begin to use it.
There are 2 primary users of the webapp, the insurance agent and their managers. Understanding their key concerns and needs helps us to develop features that solve their problems and cater to their needs.
For the agent, firstly, they need to methodologically identify clients who will delay payment of premiums. The current method is to make educated guesses based on experience, but that may not be an option for new agents. Moreover, such guesses are subject to human bias and are not consistently correct since it involves human deduction. Secondly, they need quick access to insights into the number of clients who are not going to pay in the coming month and the tasks expected for them to accomplish. This can help them to pace themselves and manage their workloads better, such as delegating clients to other agents to assist them. Thirdly, agents will also need to track their progress in terms of tasks completed so that they do not have to waste time and effort doing so. Lastly, they need to be aware of the realized improvements as a result of their work, this is important to ensure they have settled the issue of late payments with a client. 
The agents also have key pain points that they wish to be resolved.
Additionally, the agent must spend significant time and effort trying to manually copy information through different webpages/ software instances to apply for different solutions they provide to the client. Given the relevance of the different mentioned features, data sharing between different tasks will help with the process.
For the manager of a team, their key concern is recognizing the cash flow situation which they have to report to high office, to help with strategic decision making about how to generate revenue with said cash flow. Secondly, they need to be aware of the performance of the agents they manage as well, so that they can better optimize their performance. Lastly, they need a convenient option to identify help to delegate aid to struggling agents.
5.2 Key Solutioning
To address the key needs and key pain points of the agent, we employed the data-driven solution of using the Random Forest Classifier to predict if a customer is likely to not pay his premiums on time. Quick visualizations of the key metrics will be displayed on the dashboard, detailed in the subsequent subsection 5.3.1.
All processes are integrated within a dashboard and data is shared amongst different processes, removing the need for manual data transfer for form entry and submission. Relevant tasks are also simplified with the touch of a button.
For the manager, they can view the essential metrics on their dashboard and have a clear idea of the struggling agents and can choose to offer aid to them with a button.
5.3 Landing Page
The webapp serves 2 important stakeholders in our problem, the insurance agent, and the manager of a team of agents. To relay the 2 stakeholders to their respective dashboards, a login page is utilized.
 
Figure 28: Landing Page for webapp
5.3.1 Agent’s Dashboard
 
Figure 29: Agent’s Dashboard
The dashboard for the agent offers insights specific to the agent helping them get tasks done with reduced effort and time, obviating unnecessary processes through automation.
At the top, there is an “Alerts” banner that offers descriptive insights of unpaid premiums for the coming month.
 Figure 30: “Alerts” Banner

The tasks are further detailed with the “Expected Actions” graph, showing the number of refinancing and premium reduction options. This helps the agent better prepare for the expected tasks, such as the necessary preparatory work to communicate with the clients, as well as to better manage their workload for the month.                                   
The “Progress Tracker” helps to track the tasks issued that are completed, helping agents to track their progress in the month. 	

 
Figure 31: “Expected Actions” and “Progress Tracker”
This is further detailed by the “Action Plan for at risk Clients” table, which specifies the client details, obviating the need for the Agent to perform manual searching to identify potentially non-paying clients. The “Phone Number” column displays and the “Contact” Column, with the button to call clients helps establish communication to the client to offer solutions to help them better meet the monthly premium payments. The “Actions” Tab allows for agents to be directed to the relevant pages to apply for the respective options for their client. Since our solutions are meant to be used at different times, a history of past solutions is tracked so that the agent can identify the next solution to offer, or in the worst case, recognize that payment from the client may not be possible. In short, the “Action Plan” table automates the unnecessary processes of searching for client details, clicking through different locations for forms, and instead display all the required tasks within a single table, and reducing tasks to a single click, tremendously reducing manhours from hours to mere seconds.
It can also be used to request help for specific clients if the agent is overwhelmed. The client will be open to be accepted by all agents, reflected in their respective dashboards under the “Request for Help” table. We propose giving other agents a split of commissions of the unpaid premiums for a limited duration as it would incentivize them to assist others.
 
Figure 32: “Action Plan for at risk Clients” and “Request for Help” tables
Lastly, the “Number of improvements after pre-emptive action” graph helps to visualize the number of clients that have since been able to fulfil their monthly premiums payment obligations after the intervention by the agent. 
 
Figure 33: Number of improvements after pre-emptive action
5.3.2 Manager’s Dashboard
Insights that are important to the manager differ from those of the agent. The manager is more concerned about the high-level performance of the team, and the consistency of the cashflows generated as a result of more regular payments. They may be required to report these to high office who can better make strategic decisions about how to generate income from the higher cash flow to directly improve revenue.	
The “Agent Progress table” displays struggling agents, their current progress, and their unhandled clients. A delegate button allows for senior Agents to be delegated to struggling agents to help them better manage their workload.
 
Figure 34: Manager’s Dashboard
5.4 Business Impact of Webapp
In conclusion, by addressing the key pain points above, we are able to significantly reduce man hours from manual tasks such as guessing the likelihood of clients to defer payment and transfer data to do data entry. This is significant, reducing the tasks from hours to mere seconds. The time saved can be used to reach out to most impactful clients, which can further drive insurance revenue. Secondly, it helps to reduce errors in the process. Researched machine learning predictions are accurate and consistent, enabling users to receive quality predictions to work on. Lastly, it completes the solution by integrating with auxiliary functions after churning predictions, enabling users to make use of data driven solutions to do perform tasks more efficiently.

[View code on GitHub](https://dune.com/docs/reference/faq/how-are-results-refreshing.md)

The app technical guide provides information on how often results are refreshed in the Dune app. The guide starts by directing users to the Meta Monitoring dashboard to view the current time it takes for new data to be added to Dune. 

The guide then explains how results are refreshed in the app. When a visualization is viewed on a query page or dashboard, the Dune backend checks the age of the most recent result. If the result is older than three hours, Dune automatically queues an execution for the query and runs it in the background. This ensures that dashboards are always up to date when they are being viewed, and the query creator does not need to set a refresh schedule. 

It is important to note that the query execution queue is separate from each individual user's queue when they create and run queries in the query editor. 

Overall, this guide provides users with a clear understanding of how results are refreshed in the Dune app and how they can ensure that their dashboards are always up to date. The guide also directs users to the Meta Monitoring dashboard for more information on the current time it takes for new data to be added to Dune. 

Example: 
If a user creates a dashboard in the Dune app and views a visualization on that dashboard, the Dune backend will automatically check the age of the most recent result. If the result is older than three hours, Dune will queue an execution for the query and run it in the background to ensure that the dashboard is up to date. The user does not need to set a refresh schedule for the dashboard.
## Questions: 
 1. What is the definition of "stale" results in this app and how is it determined?
   
   The definition of "stale" results in this app is currently defined as >3 hours old. It is determined by the age of the most recent result.

2. Is there a way for users to manually refresh the data or do they have to wait for the automatic refresh?

   It is not mentioned in the app technical guide whether users can manually refresh the data or not. Further investigation or clarification may be needed.

3. How does the app handle errors or failed executions during the automatic refresh process?

   The app technical guide does not provide information on how the app handles errors or failed executions during the automatic refresh process. It may be necessary to consult the app's documentation or contact the developer for more information.
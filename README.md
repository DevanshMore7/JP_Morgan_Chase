# JP_Morgan_Chase
Software Engineering Virtual Experience

Task 1:
For the first module of this project will need you to accomplish the following:

Set up your system by downloading the necessary repository, files, tools and dependencies
Fix the broken client datafeed script in the repository by making the required adjustments to it.
Generate a patch file of the changes you made
Bonus task: Add unit tests in the test script in the repository.

Making Changes

When you’re in a work environment, you’ll usually receive tasks in the form of engineering tickets. Here is an example of what this task looks like in the form of an engineering ticket

Purpose
We want to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.

Acceptance Criteria

getDataPoint function should return correct tuple of stock name, bid_price, ask_price and price. Note: price of a stock = average of bid and ask
getRatio function should return the ratio of the two stock prices
main function should output correct stock info, prices and ratio
Upload a git patch file as the submission to this task
Bonus: All unit tests inside client_test.py, added/existing have to pass

Task 2:
For the second module of this project will need you to accomplish the following:

Set up your system by downloading the necessary files, tools and dependencies.
Fix the broken typescript files in repository to make the web application output correctly
Generate a patch file of the changes you made.

Making Changes

When you’re in a work environment, you’ll usually receive tasks in the form of engineering tickets.
Here is an example of what this task looks like in the form of an engineering ticket.

Purpose:
The objective of this task will be for you to fix the client-side web application so that it displays a graph that automatically updates as it gets data from the server application (see Before and After images below) Currently, the web application only gets data every time you click on the 'Start Streaming Data' button and does not aggregate duplicated data.

Acceptance Criteria:

This ticket is done when the graph displayed in the client-side web application is a continuously updating line graph whose y axis is the stock’s top_ask_price and the x-axis is the timestamp of the stock. The continuous updates to the graph should be the result of continuous requests and responses to and from the server for the stock data.

This ticket is done when the graph is also able to aggregate duplicated data retrieved from the server

Task 3:
For the third module of this project will need you to accomplish the following:

Set up your system by downloading the necessary files, tools and dependencies. 
Modify the typescript files in repository to make the web application behave in the expected manner
Generate a patch file of the changes you made.

Making Changes

When you’re in a work environment, you’ll usually receive tasks in the form of engineering tickets.
Here is an example of what this task looks like in the form of an engineering ticket.

Purpose
You will use perspective to generate a live graph that displays the data feed in a clear and visually appealing way for traders to monitor this trading strategy.

Recall that the purpose of this graph is to monitor and determine when a trading opportunity may arise as a result of the temporary weakening of a correlation between two stock prices. Given this graph, the trader should be able to quickly and easily notice when the ratio moves too far from the average historical correlation. In the first instance, we'll assume that threshold is +/-10% of the 12 month historical average ratio.

Acceptance Criteria

This ticket is done when the numbers from the python script render properly in the live perspective graph. This means the ratio between the two stock prices is tracked and displayed. The upper and lower bounds must be shown on the graph too. And finally, alerts are shown whenever these bounds are crossed by the ratio (the guide below will also give more detail and visuals to help you understand these requirements better)

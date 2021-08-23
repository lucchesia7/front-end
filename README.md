# front-end

👀 Product Vision Document
This is the template for the Product Vision Document that teams complete after their initial icebreaker. The PVD is crucial to the planning phase and is mandatory for all groups to complete before starting their project.
☝️ Proposal

What problem does your app solve?
We can predict the outcome of a kickstarter campaign to know whether it will be successful.

Be as specific as possible; how does your app solve the problem?
By use of a regressor model, we can take in various features such as: 
- Funding(goal vs actual) 
- Project Description(Has, does not have, has and is over x length of words)
-  Rewards(has, doesn’t), and launch vs deadline
And predict whether or not a kickstarter campaign 

What is the mission statement?
We care that our users are content and receiving accurate information. We show this by providing a model that is accurate, a UI that is visually pleasing and easy to use by the client, and keeping our vision towards the future of our client’s needs 

💡 Features

What features are required for your minimum viable product?
We will deploy a Heroku app that will feature the different columns in our dataset as drop down menus to allow our users to chose within a range of specifications to link the user to the proper outcome based off model predictions

What features may you wish to put in a future release?
A way to show more visuals of how the different categories affect the kickstarter campaign. By using plotly, visualizations could be generated onto a separate page to show the user a better, more detailed break down so they feel they have better control over their campaign.

What do the top 3 similar apps do for their users?
1)https://www.popsci.com/article/science/tool-accurately-predicts-whether-kickstarter-project-will-bomb/
This app features revenue generated, first time backers, and backers whom have backed other projects to determine with a 76% accuracy whether it would succeed or fail
2) http://www.kicktraq.com/
This app features the same kind of thing we are going for. People can input their projects and have a percentage. This also turns it into a message board and could be a good inspiration for future application of our app.

3) https://www.nature.com/articles/s41599-019-0261-6
This article features a model being trained based on tapping into a kickstarter api and processing past kickstarters and providing a more detailed and in-depth review of the data. We could use this to look for inspiration on our back end and how we model the model.

🛠 Frameworks - Libraries

What 3rd party frameworks/libraries are you considering using?
Plotly-Dash paired with Heroku for deployment of our app.
Considering using kickscraper as an API tool. Having issues with this and want to dig in and find a better API

Do the APIs you need require you to contact them to gain access?
No. We will call upon them in the app initialization and training of the model. Users will be interacting with the model, not API.

Are you required to pay to use said API(s)?
No.

🧮 For Data Scientists

Describe the established data source with at least rough data able to be provided on day one.
We are using a dataset found online. We have converted this dataset into a csv to be uploaded to our GitHub. The data includes things like a description, name, backers_count, goal, usd_pledged that can be used to aim our model at the target variable. This dataset also includes whether or not the Kickstarter was successful. Having a target variable already is going to help us with training model accuracy. 

Write a description for what the data science problem is. What uncertainty or prediction are you trying to discover? How could this data be used to find a solution to this problem?
Using the given variables found in our API, can we determine whether a kickstarter campaign will succeed or fail within a viable accuracy parameter? This data can help us train a few different regression models to find the model of best fit. Using a train-test split, we can test the best fit model with tuned hyperparameters and get our best accuracy score for predictions and set our model free on the world.

🎯 Target Audience

Who is your target audience? Be specific.
Anyone with a  passion for making a product. Hundreds of people are creating kickstarters and creating products every day. If that’s the case, then all of those people are going to want to go to production with the most knowledge possible. It is those people we want to target.

What feedback have you gotten from potential users?
If we plan on using this in the future, there needs to be more visuals for the users. One chart is good, but doesn’t set you apart from anyone else with a computer and a little knowledge.

Have you validated this problem and your solution with a target audience? Describe how.
N/A



🔑 Prototype Key Feature(s)

How long do you think it will take to implement these features?
Maybe a week. Learning how to properly create these and upload would take the longest. Actual coding would be relatively simple and easy.
Do you anticipate working on stretch functionality after completion of a Minimal Viable Product?
Yes. If we keep on track the way we are, we should have a day to work on our app and create any improvements we want to see in the functionality.

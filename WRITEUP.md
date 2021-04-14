# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

If utilizing a VM: Deploying this app would be more expensive. It would, however, be more scalable, in that it would be easier to scale to a significantly larger number of users. Similarly, your app wouldn't have the same limitations on hardware, such as RAM. You would have to build more of the infrastructure and be responsible for more of the back-end, and wouldn't be able to as effectively utilize CI/CD DevOps strategies. You would however get full control of the VM.

If utilizing an app service: Deploying this app would be less expensive. It would have some limitations on computing power and scalability, but would be much less expensive to scale for smaller numbers of users. You wouldn't have to worry about the infrastructure or backend of the app. You would be able to more effectively utilize CI/CD DevOps strategies. You could potentially have some availability limitationss, particularly if your application scales rapidly.

Based on these choices, and because I prefer simplicity and ease-of-use, I will choose an app service to deploy this application. This is not a particularly demanding application, and the scale is not a large concern. Therefore, to make deployment simple and not worry about backend infrastructure, as well as to provide the best cost-benefit, an app service makes the most sense for this application.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

If the application scaled dramatically, or if the use of the application grew to encompass more heavy-duty computing, then a VM might have been the better move. Additionally, if sensitive data comes into play that myself or my company needs more control over, a VM would certainly have been the better choice as building in security and separation is much easier when you can control the infrastructure from a VM.
# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*
For this particular app I choose the App Service because it is a private CMS app that I don't
anticipate will ever get that large. 
Costs : Since this is a private side-project, the lower cost of the App Service vs. a VM are appealing.
Availability : App services have hight-availability which is a plus.
Scalability : It's nice to have the auto-scaling option if I need it for the App Service. 
However, to start out I will use the lower cost Dev/Test free option.
Continuous Deployment : I like the option of incrementally updating this app as I need to.
Hardware : The anticipated memory usage for this app is well under 14GB per instance and 4 vCPU cores per instance.  It is developed using Python which is supported by the App Service plan. At this stage, I don't
need to specially configure the host server so I don't need the absolute control of a VM.


### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
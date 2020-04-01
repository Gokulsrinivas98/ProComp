# ProComp
#### HackHarvard'19 
## Inspiration
As students who enjoy building hardware projects, we've always felt that finding the components required for a project online is quite cumbersome. Having to individually look up each component tends to become tedious so we decided to automate it.

## What it does
ProComp automates the process of looking for components online via Robotic Process Automation using UIPath. You can look up a project on hackaday.io and ProComp will find all the components listed within the project and look up each component on octopart.com. If the component isn't found on Octopart, ProComp will perform a general google search for the component.

## How to Run
1. Open UIPath Studio 
2. Run the ProComp.xaml file 
3. Enter the name of the project as input 
4. Watch as ProComp pulls up each component

## Challenges we ran into
Learning to use UIPath from scratch, and figuring out how to map elements on the website using UIExplorer within a short time frame.
We learned how to use UIPath for Robotic Process Automation.

## What's next for ProComp
In the future, we hope to have ProComp compare prices across websites, and individually add each component to the cart on the website that offers it at the lowest price.

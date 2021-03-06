# Digital Life Collective Project Registration

Our goal is to have a transparent and traceable method for projects that want to put themselves on the Digital Life Collective [map](https://kumu.io/DigitalLife/digital-life-collective). 

To make this easy for projects and to give you some visibility into the process we have adopted a simple github based approach that follows these steps:

 * Clone and create a simple JSON file for the project
 * Edit the file with your project details
 * Submit a pull request with your project JSON file
 * Members will review the project and approve the pull request
 * The map "build" will pick up the new information and you are on the map!


There is no other database or repository for the data and it remains source controled in github with version history for members and interested members to see. We are using the MIT license which means others can use this data.

In the review process we will do the following:

 * Check out the the project and the goals and make sure we have the right information
 * Verify the information is correct
 * Make sure it is aligned with the collective puprpose
 * Add additional fields including date, status, and tags to make it easier to filter and find.

## Making a submission

**If you are a github whiz then all you need to do is:**

* Create a file using the JSON above or the digitallifecollective.json file as your template
* Name it logically [projectName].json
* Commit and push your file into /submissions  
  ***Note: You will need to create a branch and a pull request.***
* Bob's you uncle!

**If  you need a little more detail follow these steps:**

1. Download this file [digitallifecollective.json ](https://github.com/ppbpdx/digi/blob/master/digitallifecollective.json)


2. Open it in a text editor (not a word processor they tend to gum up the formatting)


3. Edit the contents of the file by replacing the template content with your own. Hint: the quotes and commas matter so be aware of what you edit.


4. If you need help with the formatting you can always use a handy online format checker like [this one](https://jsonformatter.curiousconcept.com/). Your file will be reviewed and formatted as part of the pull request review.


5. Now login to your [github.com](https://github.com) account and navigate to https://github.com/DigitalLifeCollective/projects/submissions 


6. Click the Upload Files button and follow the instructions. Try to name things logically when you fill in the forms.


7. When you have uploaded your JSON file the next page will create a Pull Request. Again fill in the forms and submit. 


8. Bob's your uncle!



## JSON Structure
This is a simple JSON strucuture that captures the information that will be used to generate the project map and other tools we create to curate the projects aligned with the Digital Life Collective.


```
{
   "project":"Digital Life Collective",
   "website":"https://diglife.com",
   "description":"The Digital Life Collective develops, funds and supports technologies created with only the individual's needs in mind.",
  "tags":[
      "collective",
      "co-op"
   ],
  "type":[
      "social media",
      "publishing"
   ],
   "purpose":[
      "privacy",
      "trust"
   ],
   "license":[
      "MIT",
      "Apache 2"
   ],
   "repoURL":"https://github.com/orgs/DigitalLifeCollective",
   "logoURL":"https://diglife.com/images/logo.png",
   "twitter":"@digitallifecollective",
   "email":"info@diglife.com",
   "techDetails":{
      "languages":[
         "python",
         "java"
      ],
      "platforms":[
         "mattermost",
         "ghost"
      ],
      "documentationLanguages":[
         "english",
         "german"
      ]
   }
}
```


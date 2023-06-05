# Requirements Hierarchies for Cucumber Features

Requirements configuration applies to the container levels, not to the feature or story files themselves.

When you use Cucumber, Serenity expects your feature files to be stored in the *src/test/resources/features* directory. Your requirements hierarchy goes directly underneath this directory.

Cucumber by default organises requirements hierarchy as follows:
theme > capability > feature

When Cucumber is used with the default configuration, the feature files always represent Features, and the directories containing the features represent Capabilities. 

A Feature is typically bigger than a user story, and can contain the acceptance criteria (scenarios) from several user stories.

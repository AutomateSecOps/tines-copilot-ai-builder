# Tines Story Copilot AI Builder
Tines released [Story Copilot](https://www.tines.com/blog/introducing-story-copilot-a-new-build-tool/), a new AI-powered build feature designed to accelerate story creation directly within the platform. 

I put it through its paces with a quick hands-on test.

Story Copilot operates in two modes, Ask, which is used for answering questions about the workflow, and Build, for generating and modifying stories through natural language prompts.  My instance ran on Anthropic Claude Sonnet 4.5 under the hood.

In under 10 minutes, using three prompts, I had a fully functional Tines Page webform where a security analytst can upload a csv of IOCs and have them automatically categorized by the workflow. That kind of turnaround would have taken significantly longer to build manually.

Prompt 1:

<img src="./images/prompt-1.png">

Prompt 2:

<img src="./images/prompt-2.png">

Prompt 3: 

<img src="./images/prompt-3.png">

To validate the output, I submitted a test file containing a mix of IOCs through the Tines Page. The workflow correctly categorized each one:

<img src="./images/event_ioc.png">

If you haven't tried Story Copilot yet, now is a great time since it does not cost any AI credits until April 16th.

Happy Building! or more like happy prompting...

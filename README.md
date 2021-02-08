# Kloudi's VSCode Extension (Alpha)

<p align="center">
  <br />
  <a title="Signup for Kloudi's Early Access Program" href="https://kloudi.tech">
    <img alt="Kloudi loves VS Code" width="320px" src="https://kloudi.tech/kloudi-in-vscode.png"/>
  </a>
</p>

[Kloudi](https://kloudi.tech/ 'Universal Command Line for engineering tools in VSCode') is a Universal Command Line for your engineering tools. Kloudi is able to do this by aggregating all the tools that a developer use under one roof. This in turn brings cross-functionality across tools, by making data from tools contextual & actionable.

The VSCode extension is an experiment to bring complete functionality of Kloudi is extended to the users in their IDE, bringing a zero navigation world to its users. 

🚨🚨 Please note, this is an early release of the extension things might break!

# What you one expect from v1.0 🎉!

- Simple search based interface to view and retrieve data. No need to learn any command any more.
- One interface to perform actions of your tools. Zero navigation
- Built-in keyboard shortcuts to perform all actions.
- Simple integration process (OAuth and API Key based) for all your tools.

  > We currently support the following tools:
  >
  > - [Github and Github Issues](https://github.com/)
  > - [Jira Cloud](https://www.atlassian.com/software/jira)
  > - [Sentry](https://sentry.io/welcome/)
  > - [Bitbucket](https://bitbucket.org/product)
  > - [Amazon EC2](https://aws.amazon.com/ec2/)
  > - [Firebase Crashlytics](https://firebase.google.com/products/crashlytics)
  > - [Datadog](https://www.datadoghq.com/)
  > - and many more to come.

* Summarised view and detailed view of all your data.
* End to end data knitting across all tools, so that you can spend less time .
* Ready to plug-in platform for all issue management workflow tools.

  > Can't find your favourite integration on Kloudi 🧐?
  > [Request an Integration](https://github.com/kloudi-tech/vscode-app/issues/new?labels=Request+An+Integration) here and we'll get you hooked up in no time.

# Contents 📝

- [Getting Started 🏁](#getting-started)
- [Features 🚀](#features)
  - [Connect 🔗](#connect-your-tools)
  - [Converse 💬](#nlp-based-search---like-texting)
  - [Kloudi is learning 📚](#kloudi-is-learning)
  - [Customize your queries and actions 🍕](customize-your-queries-and-actions)
  - [Bugs Coverage in Kloudi 🐞](bugs-coverage-in-kloudi)
- [Feedback 🤩](#feedback)
  - [Request an Integration](#request-an-integration)
  - [Report an Issue or Give Feedback](#report-an-issue-or-give-feedback)
- [What is Kloudi best at?](what-is-kloudi-best-at-?)
- [What to expect in future releases](what-to-expect-in-future-release)
- [Get Early Access Now](get-early-access-now)

# Getting Started 🏁

Getting started with Kloudi is very simple.

- [Install](vscode:extension/Kloudi.kloudi) VSCode Extension.
- Sigin on Kloudi.
- Get Started. You are good to go.

<p  align="center">
	<img alt="Keyboard Shortcut" height="96px" src="https://kloudi.tech/kloudi-keyboard-shortcut.png"/>
</p>

The VSCode extension usage can be triggered by **Command+K** in Mac systems or **Ctrl+K** in Linux or Windows systems. On the web app pressing either of the shortcut will take you the search bar.

# Features

Kloudi is a horizontal platform built as a layer that can interact and make dev tools cross-functional and related workflows optimal. The interface command line driven. The integration pipeline for all tools can be set up easily and unlocking of integrations currently unavailable can be done using the Kloudi request feature. The VSCode plugin is designed to be similarly functional as Kloudi in the webapp state. Give below is a brief of how Kloudi's features can lead to optimisation, ease and quick actions on data.

## Connect your tools

User can connect the tools they use for their day to day activities. Currently, we are supporting more tools around bug resolution, bug monitoring, bug management and related workflows. Currently there are two ways through which you can connect a tool:

- OAuth
- API Token

Depending on which tool you want to integrate with and what kind of third party API access they provide Kloudi will take you through each step of connecting with the tool so that you don't need to write any code.

> NOTE: Data viewed and used by Kloudi are only the triggers rendered by these tools. In-app code is not stored in any form by Kloudi.

Currently Kloudi supports the following tools out of the box:

- [Github and Github Issues](https://github.com/)
- [Jira Cloud](https://www.atlassian.com/software/jira)
- [Sentry](https://sentry.io/welcome/)
- [Bitbucket](https://bitbucket.org/product)
- [Amazon EC2](https://aws.amazon.com/ec2/)
- [Firebase Crashlytics](https://firebase.google.com/products/crashlytics)
- [Datadog](https://www.datadoghq.com/)
- and many more to come.

## NLP Based Search - Like texting

The Kloudi interface is search driven for any data to be viewed or action to be taken. The search can be initiated for anything and everything. For instance:

- Viewing data of connected tool or performing actions on tools
  > `connect jira` or `Show me my active integrations` or `add another project from Sentry`
- Viewing data triggers thrown by an existing tool
  > `Show me Datadog logs in the past 24 hrs`
- Collated and analysed view of data aggregated across tools
  > `Show me errors in the past 48hrs`
- Actions to be taken on aggregated data view
  > `open a issue in Jira for all similar bugs`
- Viewing errors by type
  > `Show me all 404 errors in the past 1 hr`

## Kloudi is learning

Kloudi is currently trained to work on queries addressed as natural language based triggers in the the universe of the tools that it operates in. Every action of a single tool is automatically exposed to the user as a natural language based query post integration. While any new tool not pre-existing in the list of available integrations in Kloudi's current form can be requested for through a request trigger sent to us. Functionality fromt, training of Kloudi and exposure of requested integrations and related actions can be provided within 4hrs of acceptance of [Request an Integration](request-an-integration).

In terms of Kloudi's ability to understand natural language intents, currently it not only understands simple reciprocation of data like `show me errors in past 24hrs` but also is trained to perform cross-functionality like `show me logs from Datadog in the 30 mins before the issue occurred on Sentry`

Not only cross tool functionality, we are training Kloudi to build insights on the this data from tools. Kloudi basis triggers and data from tools can identify exact issue and similar or dummy issues triggered by the parent issue that needs to be fixed. imilar issues can be viewed upon performing a search query.

## Customize your queries and actions

Actions are derivative results of the mental models that are now embedded and performed by Kloudi's data aggregation and viewing engine. Since the workflow is issue management the actions related to the workflow that each persona would like to perform post viewing causal error can be as follows.

- Users would like to close errors across their tools or mark tool notifications as viewed after identifying causal error.
- Developers would like to check validity of similar bugs.
- Developers would like to perform bureaucratic actions on project management tools with relation to tracking and maintaining history of error.
- Developers would like the options to create either split issues or single issues of the error and related/similar errors that occured.
- QA would like to assign the error fix to dev to whom the code belongs.
- QA would like to view updated status of errors occured.
- EM would like to view statuses of errors occurring and fixed
- EM would like to view generic error data.

The actions above are capabilities that are incorporated in Kloudi and can be viewed as either suggestions post data aggregation or can be initiated via the search feature.

## Bugs Coverage in Kloudi

Currently the following enriched data snippet can be viewed by user to aid decision making and action.

- Stack-trace of error.
- Log leading upto error
- The number of parallel triggers the error caused or occurence frequency
- Primal cause or root cause of error needing to be fixed.
- Similar issues or errors triggered by the primary issue and leading to fraternal issues
- Redirection to home window of any specific tool triggering any one of the errors.
- Error distinction and data by type of error triggered.
- Suggestive actions wrto the triggered error

# Feedback

## Request an Integration
Since the current workflow focus of Kloudi encompasses tools that are used for issue management there might be integrations of tools unavailable for immediate extension. In case you are using a tool that is not currently available for you to extension you can request us for having it enabled with all related actions exposed. [Click here to request an integration](https://github.com/kloudi-tech/vscode-app/issues/new?labels=Request+An+Integration)

## Report an Issue or Give Feedback
If Kloudi has mis-identified your query intent or if certain minor features seem missing and you need them added, we can be notified about that too. You may also rate the accuracy of the data and actions suggested by Kloudi and we will ensure that the Kloudi's algorithm's are trained better to understand your workflow and intents.

Kloudi is a platform that will grow and get better with your usage and we have ensured that feature requests or feedbacks are received from within the product's design. We are young and eager to learn from our users.

- [Click here to report an issue](https://github.com/kloudi-tech/vscode-app/issues/new?labels=issue)
- [click here to give feedback](https://github.com/kloudi-tech/vscode-app/issues/new?labels=enhancement)


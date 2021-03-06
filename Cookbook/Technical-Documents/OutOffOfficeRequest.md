# Requesting and Notifying Out Of Office time

Someone who is Out Of Office means that they are not in their usual work place at their usual working hours. This can be when someone goes on holidays or when someone that usually works in the office is working from somewhere else.

OOO time has to be requested and approved by your Line Manager and your Project Manager.

There are different types of OOO and each one of them have different requirements for requesting and for being notified.

## Holidays 🌴

To promote a healthy work-life balance we should take 25 holiday days per year. You can book your holidays at your convience, you might just need to sync first with your Squad, including the iOS engineers in it, to see if every one is OK with it. 

Ideally, you should give at least 2 weeks notice before taking any holiday but there are exceptions for emergency situations. If you want to book more than 5 consecutive days you ideally should give 4 weeks notice.

### Request

1. Check with the iOS Engineers in your squad that the work is covered during you absence.
1. Ask for approval from your PM - only if approved you can proceed to the next steps.
1. Communicate it to your line manager and mention your PM approval
1. Request in Bamboo

### Notify

1. [Send an event](#steps-to-configure-the-outlook-event) to the iOS Team Calendar and to your Squad email group
1. Update the [Team Plan document](https://docs.google.com/spreadsheets/d/1kdY3edy_TeqIGH_7VnZzElxgVo_qD2z4EF-arWNShyw/edit?usp=sharing) 
1. Notify the iOS Team and your Squad via Slack on the working day before you go on holidays.
1. [Enable automatic reply message](#steps-to-configure-automatic-reply) in your Babylon Outlook account.
1. At the end of your last working day before going on holidays change your Slack status to 🌴**On holiday** and set to clear after your last holiday day. 

If there is a big impact in the iOS Team or in your Squad due to you being away, please communicate a few days before in the team specific slack channel and do a handover if needed.

#### Steps to Configure the Outlook event
1. Open Outlook 
1. Select Calendar
1. In the menu on the left select the iOS team calendar (Please make sure you have the iOS Team calendar added as a shared calendar to your Outlook)
1. Select Appointment
1. Subject: `<Your name>` Holidays 🌴
1. Duration: All-day event
1. Show as: Free
1. Reminder: None
1. Hit "Send"

#### Steps to Configure automatic reply
1. Open Outlook 
1. Select Tools
1. Select Out of Office
1. ✔️ Send automatic replies for account `<your outlook account>`
1. Reply once to each sender with: `<Define a message mentioning the period you are on holidays>`
1. ✔️ Only send replies during this time period
1. Start time: First day of your holiday 
1. End time: Last day of your holiday

### Before leaving

When we leave on holidays we should make sure we leave our work either finished or delegated to someone else. There are a couple of steps that should be performed to reduce the impact of the absence.

1. Try to finish any work in progress before you go.
1. Resolve the reviews on your opened PRs and try to get them merged. 
1. In the event of not being able to complete 1. and/or 2. please sync with another iOS Engineer, ideally someone from your squad, and do a handover. When handing over an opened PR please make sure you add the iOS Engineer as `Assignee`.
1. Make sure your JIRA tickets are up-to-date. Any pending ticket should
	1. Have a description of what is left to be done.
	1. Who to contact if necessary.
	1. If it's something urgent should be assigned to another team member and a proper handover should be done with that person.
1. [Set your status to "Busy" on GitHub](#steps-to-be-added-to-the-pullreminder-exclusion-list) to prevent yourself being added as a PR reviewer while you are away. 
1. Once you get back, you have to clear your "Busy" status. Adding a Slack reminder (`/remind me to clear my GitHub "Busy" status on <date>`) before you leave might help you not to forget.

#### Steps to set your status to "Busy" on GitHub
1. Go to [GitHub.com](https://github.com) and sign in.
1. Click your avatar in the top right.
1. Click "Set status".
1. Tick "Busy" and confirm by clicking "Set status".

## Working from Home 🏡
This section is only valid for non-remote employees.

Working from home is a benefit and should be seen as such. 
At the moment it is accepted that an engineer, once settled in the iOS Team processes, project, and squad is allowed to work from home 1-2 days per week. 
The number of days may very depending on your personal situation and your squad’s way of working. These should be discussed and agreed with your Line Manager and your PM.

When working from home you should notify your squad and the rest of the iOS team (via our Slack channel) when you are away and when are you expecting to come back.

### Request

1. Ask for approval from your PM - only if approved you can proceed to the next steps.
2. Communicate it to your line manager and mention your PM approval
3. Request in Bamboo

### Notify

1. Please notify the rest of the iOS team and your squad via Slack on the working day before you are working from home. Emergencies might happen that require you to work from home and only notify on the same day. That will be acceptable if there is a reasonable excuse for it. Furthermore, if you are planning to work from home (in a non-emergency situation) for more than 1 consecutive day please give at least 1 week notice.
2. On the day you are working from home change your Slack status to 🏡 **Working remotely**.

### Being remote

Our team is composed by people who work 100% remote and people who work a few days in the office and a few days remotely. To keep everyone up-to-date with everyone's schedule, what is happening in the project and to maintain a good level of cooperation between the engineers we need to be mindful of being active in the relevant channels (Slack, Email, Zoom).
As part of your communication with your Squad and the iOS Team you should:

- Notify in Slack when your working day starts, finishes and any time you are off during the day. This should be written in the iOS-underground and in your Squad's Slack channels
- In addition to the iOS stand-up notes, you should communicate what are you planning to do during the day in your Squad's stand-up if you have one or in your Squad's Slack channel.

For more tips on remote working please visit Babylon's [Handbook for Remote Working](https://docs.google.com/document/d/1hjKtx1pPL_pxhLEuW-46w2XwxsC-mkw3Cp5uaHB2P8c/edit)

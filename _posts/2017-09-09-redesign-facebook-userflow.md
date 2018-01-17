---
layout: post
title: Re-designing Facebook’s User Flow
author: Crystal
date: 2017-09-09
---

Task: Design a new sign up user flow for Facebook.

Platform: iOS.

Time: 24 hours.

## Table of Contents:
1. Facebook's Original User Flow
2. Questions & Potential Issues
3. Research 
4. Strategy
5. New User Flow
6. Resources

---

# Facebook's Original User Flow
## Mobile Screenshots and Flow
I tested the on-boarding user flow for New Users on Facebook's iOS app and took screen shots as I went. I placed them on in a visual flow for me to reference as I mapped out their User Flow.
![](https://static.notion-static.com/d890b6a2e61c40b18f29802ae43bbae3/Faceboom-mobile-userflow.png)

## User Flow Diagram
Using [draw.io](http://draw.io) and the visual flow (pictured above), I mapped out the user flow for New Users:
![](https://static.notion-static.com/740b782b853a41d4ad844973cfd12241/facebook-userflows-newuser-1.0.jpg)

# Questions and Potential Issues
Here are potential problem spots and questions that I came up as I tested the on-boarding process and mapped their user flow.
- Feels like there are many steps, and there is no progress bar. Would adding one be beneficial? Or is there a better way?
- It takes an extra step to tap on screen to find `CONTINUE` button.
- Does the `GO` button do the same thing as `CONTINUE` ?
- There is no `BACK` button. Would adding one be beneficial?
- Why is there no `CANCEL` button?
- Why is birthdate necessary? Would privacy option be beneficial?
- Why is gender necessary? And why are there only two options, Female & Male?
- Would privacy options be beneficial when inputting birthdate and gender?
- Cannot hide password. :(
- It takes an extra step to move between mobile and email input. Would it be more beneficial to place both on same page?
- Where are these friend suggestions coming from? Are they even useful if they don't have any information from me? Do I have to search for my friends one at a time via their names?
- On email confirmation, how useful is it to have additional options such as:
	  -- change email address
	  -- confirm by phone

# Research
In this phase, I investigated the importance of and best practices for signups, forms, and their flows. See [resources](#resources) I used at the end of the case study.

## Why do we care about details of sign-ups and forms?
Conversion and drop-off rates! 

## What can go wrong?
- Trust can be an issue. People are afraid of being spammed, or that their personal information will be manipulated.
- The form takes too long or is difficult to understand
- Users give up fatigue.
- Users don't understand why certain information is required, again leading to the issues with privacy and trust.

## The Do's and Don'ts
![](https://static.notion-static.com/99419468-c8fc-4ffe-9293-c3b12e80b13a/B046129F-58D0-4B09-A464-09E6C0756F08.png)

## Smashing UX Design on Forms
### General Notes
- Complete form in as little time as possible
- Understand how to understand questions correctly
- Provide bare minimum of information
- Trust that their personal details are in the safe hands
- Complete form in one go without have to come back later with additional information.
- Use a vertical layout
- Clear CTA
- Clear labels
- Differentiate labels from text
- Use reasonable defaults
- Show progress
- In-line validation
- Mobile forms need to be easier than desktop counterparts. Simplify them!
- Break form into smaller chunks.

### Common mistakes
- Harsh Error notifications. Be polite.
- Inflexible input data formats
- Not generating specific and helpful messaging
- No inline validation as user progresses
- Too many questions
- Too much legalese


#  Strategy
After gathering data from testing and research, I brainstormed user stories and considered business requirements.

## User Stories
![](https://static.notion-static.com/22510552-819d-48f7-a502-8ff9ab913017/777337C0-0C9F-41A5-B984-B0BD3F08A249.png)

## Business Requirements
![](https://static.notion-static.com/9da25dd5-1b12-4a76-a4dd-cdbb40f11eac/F808C9C5-7991-4AE7-BBE1-677D1AD067FC.png)

#  New User Flow
Below, you'll see the new user flow. Here is what changed:

- Name input moved to beginning of flow. It has potential to be more welcoming than being presented with Terms of Services immediately. This would need to be tested.
- Originally, Selecting between mobile and email address took an extra step. This was removed on the theory that less steps is more. This would need to be tested.
- An option to hide and show password was added for user's feeling of safety and security. This is especially important if registering in public.
- To make it a quicker process, users are given the option to complete their profile. If this project were to continue on, users would be informed of the benefits of doing so, and encouraged to finish.
- The option to find friends via contact information alleviates the huge task of adding friends. We want to do the work for the user as much as possible.
- For email/phone confirmation, I removed the option to change email address and verify by phone. Further testing would be needed here.
- *MISSING FROM USER FLOW: option to resend confirmation email/message*

![](https://static.notion-static.com/0777cd79e31f462eaadeda8b057a38d0/facebook-userflows-newuser-2.0.jpg)

# Resources
* [Designing UX Login Form and Process - UX Planet](https://uxplanet.org/designing-ux-login-form-and-process-8b17167ed5b9)
* [UX Flows: How to Craft Effective Sign-ups](https://www.dtelepathy.com/blog/design/ux-flows-sign-ups)
* [10 Ways to Present Legal Terms at Sign-up](https://www.pactsafe.com/blog/10-ways-to-present-legal-terms-at-sign-up)
* [Smashing UX Design](https://www.goodreads.com/book/show/8675550-smashing-ux-design)


 _Fin._

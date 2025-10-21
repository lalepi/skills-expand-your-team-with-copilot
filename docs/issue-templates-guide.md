# Issue Templates Guide

## Overview

To make it easier for teachers and staff to request changes without needing to know how to code, we've created a series of issue template forms. These templates guide you through providing all the information needed for the Copilot coding agent to automatically implement your requests.

## How to Use Issue Templates

1. Go to the [Issues page](https://github.com/lalepi/skills-expand-your-team-with-copilot/issues) on GitHub
2. Click the **"New Issue"** button
3. You'll see a list of template options - choose the one that best fits your needs
4. Fill out the form with as much detail as possible
5. Click **"Submit new issue"**
6. The Copilot coding agent will automatically process your request

## Available Templates

### 1. Add New Activity

**Use this template when:** You want to add a new extracurricular activity to the system.

**What you'll need to provide:**
- Activity name (e.g., "Cooking Club", "Swimming Team")
- Description of what students will do
- Days of the week the activity meets
- Start and end times
- Maximum number of students allowed

**Example use case:** "I want to add a new Photography Club that meets on Thursdays from 3:30 PM to 5:00 PM"

---

### 2. Modify Existing Activity

**Use this template when:** You need to change details of an activity that already exists.

**What you'll need to provide:**
- Name of the activity to modify
- What you want to change (schedule, description, capacity, name)
- New information for the fields you're changing
- Reason for the changes

**Example use case:** "I need to change Chess Club from Mondays and Fridays to Tuesdays and Thursdays because of room availability"

---

### 3. Manage Student Registrations

**Use this template when:** You need to add or remove students from activities.

**What you'll need to provide:**
- What action you need (add, remove, move students)
- Activity name
- Student email address(es)
- Reason for the change

**Example use case:** "Add three new students to the Soccer Team: john.smith@mergington.edu, jane.doe@mergington.edu, and alex.johnson@mergington.edu"

---

### 4. Report a Bug

**Use this template when:** Something isn't working correctly on the website.

**What you'll need to provide:**
- What went wrong
- What should happen instead
- Steps to reproduce the problem
- Where the problem occurred (which page)
- How often it happens

**Example use case:** "When I try to register a student for Chess Club, I get an error message saying 'Activity not found'"

---

### 5. UI/UX Improvement

**Use this template when:** You have ideas to make the website easier or better to use.

**What you'll need to provide:**
- What part of the website needs improvement
- What's difficult or confusing right now
- How you'd like it to work instead
- Who will benefit from the change
- Priority level

**Example use case:** "The text on the activities page is too small to read. Can we make it larger and use a darker color?"

---

### 6. Feature Request

**Use this template when:** You want to suggest a new feature or capability.

**What you'll need to provide:**
- Description of the new feature
- What problem it solves
- Who will use it
- How it should work
- Priority level

**Example use case:** "Add the ability to send email notifications to parents when their students sign up for activities"

---

## Tips for Writing Good Issue Requests

1. **Be Specific:** The more details you provide, the better the Copilot coding agent can understand what you need.

2. **Use Examples:** Give specific examples when possible (e.g., actual activity names, student emails, times).

3. **Explain Why:** Helping us understand the reason for the change ensures we implement the right solution.

4. **One Request Per Issue:** If you have multiple unrelated changes, create separate issues for each one.

5. **Check Existing Issues:** Before creating a new issue, check if someone else has already requested something similar.

## What Happens After You Submit

1. The Copilot coding agent will review your issue
2. It will plan the implementation
3. Make the necessary code changes
4. Test the changes
5. Update your issue with progress
6. Close the issue when the work is complete

You'll receive notifications on GitHub as the agent works on your request.

## Need Help?

If you're not sure which template to use, or if none of the templates fit your needs, you can:
- Use the **Feature Request** template and explain your situation
- Ask in the [Discussions](https://github.com/lalepi/skills-expand-your-team-with-copilot/discussions) section
- Contact the technical team directly

## Examples of Well-Written Issues

### Good Example - Add New Activity
```
Activity Name: Robotics Workshop
Description: Students will learn to build and program robots using LEGO Mindstorms kits
Days: Wednesdays and Fridays
Start Time: 3:30 PM
End Time: 5:00 PM
Maximum Students: 16
Additional Notes: We'll need access to the computer lab for programming
```

### Good Example - Bug Report
```
What went wrong: When I click the "Register" button for Drama Club, I see an error message "Failed to update activity"
What should happen: The student should be added to Drama Club's participant list
Steps to reproduce:
1. Go to the activities page
2. Scroll to Drama Club
3. Click "Register"
4. Enter student email: test@mergington.edu
5. Click "Register" button
6. See error message
Where: Activities list page, specifically the Drama Club registration
How often: Every time I try
```

### Good Example - UI/UX Improvement
```
Area: Activities list display
Current problem: When there are many activities, it's hard to scan through them all. The weekend activities get lost at the bottom of the list.
Suggested improvement: Add a filter button for "Weekend Only" activities, or create a separate section that shows weekend activities first.
Who benefits: Both teachers and students looking for weekend activities
Priority: Important - would make finding weekend activities much easier
```

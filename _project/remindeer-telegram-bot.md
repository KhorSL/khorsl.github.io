---
layout: project_single
title:  "Remindeer Telegram Bot"
slug: "remindeer-telegram-bot"
---

## About Remindeer
Like it or not, digital gadgets have become a key part of people's lives. We now spend a large amount of waking hours on our digital devices. Checking the phone for messages after waking up have become a daily routine for many people.  

As such, Remindeer was created to satisfy the need for a simple bot that sends scheduled notifications.

## Programming Languages

- Python

## Remindeer Features

### Remind

This is arguably the most important function in this Bot.  

The usage is straight forward; simply input the command `/remind` with the desired reminder.

#### Example Command

```text
/remind Bring umbrella
```

```text
Current reminders:

1. Bring umbrella
2. Search for paper clips
3. Dental appointment at 10:45
4. RSVP to John's party
```

___

### List

The bot will reply the user with all reminders and the time of reminder that are saved.

#### Example Command

```text
/list
```

#### Example Response

```text
1. Bring umbrella

20 Aug 2019, Tue, 09:00 AM


2. Search for paper clips

05 Aug 2019, Mon, 10:45 AM


3. Dental appointment at 10:45

07 Sep 2019, Wed, 09:50 AM


4. RSVP to John's party

05 Aug 2019, Mon, 07:30 PM
```

___

### Delete

Delete saved reminders based on the index that appeared after `/list` command.

#### Example Command

```text
/delete 1
```

#### Example Response

```text
`Bring umbrella` deleted
```

```text
1. Search for paper clips
2. Dental appointment at 10:45
3. RSVP to John's party
```

___


### Help

#### Example Command

```text
/help
```

___

## Future Development Plan
- [ ] Snooze button
- [ ] Multiple delete
- [ ] Reminder repitition

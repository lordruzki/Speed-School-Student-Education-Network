# Daily Planner

🏗️ !!REPO IS STILL UNDER PLANNING!!

## 🗒️ Project Plan

A web-based or mobile application that allows the user to catalogue agendas from push notifications on their device.
The application would notify the user to check their agenda at different points in the day.

It would be built around features that help me remember stuff and accepts writing prompts with Markdown, similar to obsidian.

## How it would work:
### Agenda Notes
Each "Task" is saved as an individual Agenda note. They are stored in files and are identified with Containers. The first line will always be the title and all consecutive lines will be body paragraphs.

### Containers
Each "Tag" declares where the note is stored. Examples include "Homework", "Home", "Personal". The "Remember" tag is used to identify important things that shouldn't be forgotten.

### Containers Menu
This menu allows the user to add and view Containers.

### Remember This
Once a day, the program will push a notification that features a specific "Remember Note". This note is as expandable as needed but cannot be duplicated in any way. There can only be one Remember Note.

### Daily View
Renders a "Daily Rundown" section in the homepage that displays the current day Agenda. Below would be the "Remember This" entry and below that would be a "Due Soon" section.

### Calendar View
Renders an either week-long or month-long calendar that contains all the Agendas for each day.

#### Weekly Calendar
Displays all the agendas for the next 7 days. It does not skip days. They are displayed side by side so the user travels the days via side to side swiping or arrow buttons on-screen.

#### Monthly Calendar
Displays a Calendar that displays Containers and their notes on that day only. Selecting a certain day opens up the Agenda for that day. This view would not support swiping for the sake of optimization.

Feature Concepts
---
- Local saving
- Cloud syncing through external Linux server
- Web application
- Native desktop application
- Native mobile application
- Homework assignment tracking
- Daily notes to remember stuff with some sort of tag based organization
- Calendar implementation
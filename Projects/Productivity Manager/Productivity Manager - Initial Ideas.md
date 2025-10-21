---
tags:
  - adhd-productivity-manager
---
---
## Idea

I have ADHD. I really struggle to keep track of my time - my daily tasks go neglected, under the radar. I also get very easily distracted when working. I need a time and task management system to enhance my workflow and reduce distractions leading to a more optimised life.

I've decided to build my own product to help with this very issue. The app should feature 3 key sections:

- A **task management dashboard**, featuring task creation with due dates and priority ranking. The dashboard should feature a tab for switching between list or Kanban views.
- A calendar with the ability to add, edit and move tasks within the calendars cells. The calendar should be responsive, collapsing into the current days tasks.
	- Not urgent but the calendar should also feature an Ai assistant that:
		- Organises your tasks and manages your day, prioritising tasks that it deems most fit for your goals.
		- Should also time block your calendar based on your daily and top priority tasks along with their estimated time of completion.
	- Calendar should also integrate with calendar apps, automatically creating time slots.
- A Pomodoro timer that can adapt to your current tasks, displaying a count down dashboard with the current task you are working on.
	- Once you complete a task - you can check it off and the next task will start. The user should be promoted if they want to have a break or continue the time.
	- Dashboard will allow the user to adjust the work and break durations, as well as number of loops before a long break. During the work session - the device should go into focus mode - limiting websites and notifications.
-  During a work session,  the device should go into focus mode - limiting websites and notifications. The app should display quotes or messages with styled backgrounds.
- The app should also feature a notification system, letting the suer know when important tasks are due, as well as general info important to the user.

I want the app to feature a minimalistic, simple style with a bold primary - The UX should be simple to use with little distractions.

I want to build the product for myself - but I want to build the product with authentication and billing systems incase I want to market it in the future.

Some additional ideas:

- User designed goals or hobbies they want to make time for.
- Gratitude journaling
- Note taking
- Time tracking
- Different Pomodoro sessions depending on the task your doing - i.e reading will display quotes from authors or books, playing an instrument - the equivalent etc.

### Tech Stack

- Next.Js
- Typescript
- Zod
- Zustand
- ShadCn
- TailwindCSS
- Supabase
	- Auth
	- Database


#### Frontend
- Next.Js
- Typescript
- ShadCn
- TailwindCss
- Zustand
- Zod

#### Backend
- Next.Js
	- API routes
	- Server actions
	- Server functions
- Zustand
- Zod
- Supabase
	- Authentication
	- Database management
		- PostgreSQL
- Resend
#### Dev Ops
- GitHub
	- CI/CD
	- Permissions
	- Version control
- Vercel
	- Hosting
- Cloudflare
	- DNS management
	- Domain management
	- Firewall management
#### Other Tools
- Pirsch
	- Analytics
- 
cfm-user-stories
================

- As a
- I want to
- And the outcome is?

- User
  - See all the talks on the schedule	
    - I see a high level tabular style data of all the talks
  -	See all the talks for a particular room
    -	I see a high level tabular style data of all the talks for a particular room
  -	Find out what a talk is about
    -	I see a view of a talk including the speaker and description
  - Attend a talk
    - User marked as attending talk, added to their timeline
  -	See what talks I'm signed up for
    -	I see a personalised list of talks
  - Be notified if talks I'm signed up for change
    - I receive a notification if the room changes, a talk is cancelled or it changes time.
		
- Speaker
  - Add my talk to the timetable
    - I pick a slot, add a title & description, and commit my talk to the timetable
  - Know where my talk is scheduled
    - I receive a notification if the room changes, a talk is cancelled or it changes time.
  - Withdraw my talk
    - I withdraw my talk and people don't turn up (are notified of cancellation)
		
- Event manager
  - Add session slots to the timetable
    - I choose what time/date & duration & add them
  -	Add Rooms to the timetable
    -	I give the room a name & capacity
  - Add a talk on behalf of another (registered) attendee
    - I create a talk and change the owner to another user
    - If the user exists, it sets them as the talk owner
    - Otherwise, they're created with a temporary password they can log in with.
  -	Relocate talks from one room to another
    -	Easy to move talks from one room

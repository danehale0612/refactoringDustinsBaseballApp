####Phase 1

-using Bootstrap - done.

-min/max team limits - in place. Season can't start without at least 4 teams, trying to add an 8th team will bring up an alert telling you league is full.

-add teams - working.

-save team info to server - working.

-show team info on hover - working.

####Phase 2

-uses pre-defined schedule; differentiates automatically depending on league size. Accounts for bye week. Working.

-capture scores by week: working. 

*	On saving scores, Schedule and save scores modal update with MANUAL page refresh. Work in progress.

-Win/Loss calculated automatically on score entry, standings update dynamically without manual refresh.

-Standings sortable by column by manually clicking table head.

##WHAT ISN'T WORKING --

*	After saving a round of scores, you __need to manually refresh page__. Everything is saved properly, but schedule table and save scores modal will not be properly updated until the next manual page refresh. 

*	If you delete a team from the middle of the teams list, score assignments will be off. Just don't delete a team from middle of field.

*	Validation not preventing form submit. 

*	Score submit form has no current validation; does not prevent ties.

Dane:

-added NO Ties for 8 teams (working still on getting something in place for less than 8 teams)

-fixed validation for entering a new team

-worked with Zach on trying to have the scores refresh automatically with out doing a page refresh

-Added Zach's code (It is commented on what his code is).  He worked on getting the scores to add to the scores table.
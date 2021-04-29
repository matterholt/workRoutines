# Workout Routines
- Matthew Atterholt
- 2021/04/13

## Statement of Goals

Goal is to build a Progressive web application that will allow users to create and save their own personal lifting routine. Reduce the complication of trying to figure out what to do next in their workout. Which would allow them to get in lift and get out. Have a visual progression of how much they have lifted of each exercise.

## Summary

The application would need to be able be accessed while offline. The purpose would be able to help users get into the rhythm of working out specifically with weight lifting. By creating personal workout routines that would be have specific exercise that would need to be completed. The application would show if the users what routine that would be need to be completed and would have a calender to show how consistent the user is.


## Detail Description

The user landing page would have the routine of the day at the top and able to tap/click to start the routine. Then would go into the listing of each exercises. If no routine is scheduled then would be considered as a rest day, or alternative exercise that could be created on the fly. At the very lest the user landing page should have show them how often the user has completed or not the routine. Also could have some other user stats and details. 

Would like the application to be able to add the desired exercise to perform. The inputs for exercise would contain name, reps, sets, starting weight, PRs and what muscles that it hits. If there is a Public API to use that to reduce complication. This page would serve as a library of exercises that the user has performed. Should be able to sort, star, and delete exercises. **find an API that has all information on lifting.  From this library a workout routine can be curated. Exercises would need to be place in order desired of perform. Multiple Routines can be created so name and exercise list and what days desired to perform the routine like, so Monday, Tuesday, etc. May need to have how many weeks the routine should last and description of the routine such as weight loss, power lift. etc

In routine that user is performing the first exercise should be at the top, below that are the rest of the exercises to be performed. The current performing exercise the user should see the info for the (sets/reps/weights). The weights could be shown as a number of plates (keep it simple) or just a number. At every set of reps scheduled to be performed would need to have a completed set and failed set button. The failure button yields a reduction in weight (2.5lb x 2 or 5lbs) and a rest timer for the next set of the exercise with the reduction of weight. **not sure if safe to continue same exercise or stop at failure then proceed to the next exercise. When successfully completed the one set of reps with the desired weight and reps then a rest timer will activate. At this time the user would be allowed to modify weights and continue the rest of the set with the adjusted desired weight. The rest timer will alert when to start then next set of the same exercise. Once successfully completing the all the sets of reps with the desired weight a successful lift. Before transitioning to the next exercise user would make a judgment on how well the lift went. Basically will ask the user if they would like to add weight.  The default would be remain the same. So could possibly have a countdown timer to whatever the user would like to be defaulted.

Once workout has been completed, then the day is marked with a positive check. Then will return to the user dash. There the workout of the day will show a completed

## User Interface –- wire-frame

## Milestones

- application landing page with user login
- adding and creating an exercise 
- create a weekly routine
- document the consistency of working out


## Database


### NOTES


- Rest days do not have an impact on a miss day
- Calendar to show how many days the user has successfully followed the routine
- How to handle the different weight and reps for the same exercise? Like weight increase and the reps decrease. ???
- Set up a desired time to rest between the lifts
- Default would be simple lift and progress to next. But Different routines should have different desired outcomes. So if want to perform a PR then that routine should be scheduled, HIT, or cross fit like failure.
- Estimated time workout will take.
- User landing page for mobile should be able to customize the order or what get rendered to page components
- Create music play list, action for Spotify or something.

User app settings, should be saved a local storage or should be sent to a database table… probably both. 
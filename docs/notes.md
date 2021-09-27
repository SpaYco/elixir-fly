## Experience

This has been a great challenge! I've never used Elixir, Phoenix, or LiveView, it's been fun learning it and making it work! knowing rails has helped, and I was able to do it much quicker, but the most challenging part for me was the LiveView, while I was able to learn how I can make a LiveView trigger with user interaction, that's where most tutorials have stopped until I found that I can recall the fetching every X amount of seconds (however, I still don't think this is the most efficient way, so please let me know if there are better ways!)
I'm super excited to work on Elixir more and discover all of its capabilities.

## what you built and what you didn't build

- I've been able to build 3 tables, the same as `fly status` give, except one extra field in the instances table (output) to give users more information on what they need!
- I've made the tables with an easy-to-read layout, so the users can see all of what they need!
- I implemented a LiveView that updates every 10 seconds by fetching the data from the API and updating the page with what changed (double checked that it doesn't re-render the whole page)

## what you'd improve or fix if you had more time

- I would spend more time on the mobile experience, while tailwind-made tables are still readable on mobile, they can be improved!
- I would update the Instances table to always show the ID on the left, and for the rest of the columns to be scrollable, because (while I haven't used fly.io much) I'm confident that's what they would use most of the time when they find what they need in the table!
- Add tests
- Edge Cases:
  - The API would stop sending the deployment status after a while from the deployment, I can improve the page instead of leaving the table empty

## how you'd determine if this feature is successful

- I would look into if the feature is accomplishing the goal it's supposed to do.
- Gathering feedback would help get more information about the feature and how to improve it.
  - Success rate - We don't want it to keep failing all the time
  - User Error rate - Does the user know how to use it?
  - Customer satisfaction - Are users happy with this feature? And what do they want to change?

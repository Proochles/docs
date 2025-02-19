# Feedback
Tickets allows your users to provide feedback on the support they received:
![Example screenshot](/img/feedback_example.webp)

## Enabling Feedback
In order for users to be asked to rate your service, you must first enable feedback on the [web dashboard](./dashboard.md). 

Select your server and open the settings page:
![Enable feedback](/img/enable_feedback.webp)

Check the `Enable User Feedback` box and press submit.
Next time a user closes a ticket, they will be asked for feedback.

## Viewing Feedback
There are several ways to view feedback:

### /stats
If you are a [premium](https://ticketsbot.net/premium) subscriber, you can view your feedback statistics with `/stats server`:
![/stats server](/img/feedback_stats.webp)

### Placeholders
You can include the following placeholders in your welcome message to display your feedback rating to users:
- %average_rating%
- %rating_count%

You can view more placeholders by clicking [here](./placeholders.md).

### Per User
If you are a [premium](https://ticketsbot.net/premium) subscriber, you can use `/stats user` to view the average rating on tickets claimed by a specific user:
![/stats user](/img/feedback_user.webp)

### Viewing Individual Ticket Ratings
You can view the ratings of individual tickets by navigating to the transcripts page on the dashboard. Next to each ticket, the rating given by the user will be shown:
![Individual ratings](/img/feedback_transcripts.webp)

### Dashboard
More dashboard options will be implemented when Discord adds forms & prompts.

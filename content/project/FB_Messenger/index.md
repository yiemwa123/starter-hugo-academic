---
title: Reconnecting with old friends on FB Messenger
summary: This is my first UX case study centered around understanding how we can help people reconnect with their old friends through Facebook Messenger
tags:
- Projects
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
### Overview
Facebook Messenger is a convenient and easy way to text other people, especially if you already have a Facebook account. However, just because you are able to contact a large number of people easily does not meant that it is easy to stay in touch with people.

For this project, I created a feature that recommends friends for users to reconnect with and incentivizes the user to reconnect by allowing them to send confetti to an old friend.

Check out the prototypes in action here:

Sender (the one sending the confetti) - https://youtu.be/KEQg_N0veK8
Receiver (the one receiving the confetti) - https://youtu.be/TCsz5BJr5j0

### User Research
I conducted interviews with students who use FB Messenger and asked them questions regarding if/how they reach out and whether they were content with how in touch they are with old friends. The insights that I got were:

* There was a lot of variation in whether people desire to stay in touch with their old friends

About half of the interviewees were content with how they were keeping in touch with old friends, while the other half wished that they could keep in touch with more people. I decided to move forward with this problem space because I still felt that there was value in pursuing this problem space, since relationships vary from person to person and even if some people were content with how things were, there were still many interviewees who wanted to keep in touch with more people.

* Users feel awkward about reaching out to their old friends

* Users are unsure of what to say when the reach out to old friends


#### So, how do we encourage users to reach out to old friends on Messenger?

### Ideation
After a brainstorming session with two other friends, we ended up with 3 possible solutions worth exploring

* A reconnect button - users can indicate that they want to reconnect with another user and that user will be notified
* A guilt-tripping time display - displaying the amount of time that has passed by since you last talked to another user
* A collaborative game - providing a challenge for the users to complete and discuss together

The idea that I ended up pursuing was the first one because:

* Reconnecting with another person would only be valuable if both users wanted to reconnect with each other.
* Knowing that another user wants to talk to you could potentially ease the awkwardness of reaching out to someone.
* The fact that both users want to reconnect with each other could be a good conversation starter

### Developing User Flows and User Testing
I developed several mid-fidelity user flows for the sender (the one reaching out) and the receiver (the old friend the sender wants to reach out to). After conducting user testing with the flows that seemed the most promising and iterating the flows based on participant feedback, these were the flows that I developed:


__Sender__
![]("../static/uploads/final1.jpg")

* App recommends someone for the user to reconnect with in the form of a pinned chat
* User sends message

__Receiver__
![]("../static/uploads/final2.jpg")

* User receives message in a separate reconnect inbox
* User responds to message

However, when I sought feedback from a teaching assistant, she noted that the feature seemed empty since it just separates messages into two inboxes. When users reconnect with someone, it should feel more meaningful since they are essentially rekindling a relationship with someone. This led to the addition of allowing the users to send confetti.

Confetti is cute, fun, and different from the other functionality that Messenger offers like stickers and gifs. I thought that confetti could make the interaction feel less awkward by incentivizing reconnecting with old friends. Since this functionality would only be available if the user is reconnecting with someone, it also makes reconnecting seem more meaningful.

After modifying the user flow to allow users to send confetti, I conducted user testing. This is the final flow after incorporating feedback from participants.

__Sender__
![](./uploads/final.jpg)

* App recommends people for the user to reconnect with in a separate reconnect inbox
* User selects user they want to reconnect with
* User types a message to send to the user
* User selects confetti to send

__Receiver__
![]("uploads/group8.jpg")

* User receives message in the separate reconnect inbox
* User receives message and confetti animation
* User responds to the message

### Reflection
Ideally, I would have liked to have done another round of user testing, but due to time constraints, I was unable to do so.  I would love to test out my final prototype again in the future! Another thing that I mentioned was figuring out how the app would recommend people for users to reconnect with. I didn’t quite figure out the details of how a recommendation system might work, but if given the chance, I would be open to discussing with engineers on the technical constraints of creating such a system and what factors should be considered when developing the system.


*Note: This is a shorter version of an article that I wrote on Medium. You can check out the full article [here](https://yiemwang.medium.com/reconnecting-people-with-their-old-friends-messenger-case-study-19985a2a3e2b)*








# IOS101 Final Project - Elizabeth Kushelevsky
## Brainstorm
1. LeetCode challenge
    - Create timed challenges with your friends to complete Leetcode problems. Compete for points and build a leaderboard.
2. On-campus book loans
    - Find people on your college campus with the course books you need. Use a map and make searchable by title. Use an in-app chat.
3. Recipes and ingredients
    - Input ingredients you have and recipes you want to make. App compares them and makes you an on-the-go grocery list
4. Upload notes
    - Scan notes from class, then upload them to send automatically

## Evaluation

### LeetCode Challenge ###
* #### How uniquely mobile is it?
    Not very; in fact, the user would likely already be on a computer browser to complete the challenges.
    Mobile advantages: real-time, push notifications
* #### Is there a compelling story?
    Yes - I was talking with my friends who are also CS majors about how to motivate ourselves to practice for technical interviews this summer. We love playing poker together, so I came up with the idea to run a LeetCoding challenge in similar fashion—complete problems with scores corresponding to difficulty levels, share a deadline, then split a pot based on accumulated points.
* #### What's the market?
    CS majors and their friends looking for motivation to sharpen their technical skills. There is a well-defined audience who would find this product very useful as a motivating tool.
* #### How habit-forming is it?
    It shouldn't be something that people feel the need to check constantly, but users will want to check their progress and standings occasionally through the leaderboard.
* #### What's the scope?
    I think the most complicated part of this project would be loading user data from an API endpoint to user data on LeetCode. I looked into it, and endpoints definitely exist, though not directly from LeetCode. However, because users have public profiles, all data is publicly available, and the app would still serve a purpose if I focused my efforts on this part and a leaderboard.
### Upload Notes ###
* #### How uniquely mobile is it?
    Very; the use of a phone camera makes uploading much more usable.
    Mobile advantages: camera, push notifications
* #### Is there a compelling story?
    Yes - My university's office of disability services coordinates students to share notes with their peers who request accommodations, and note-takers can get paid for their work. However, the filing process is often clunky, files can be too large to send over email on certain devices, and there is no good reminder system to actually send notes.
* #### What's the market?
    Note takers at my university and the office of disability services
* #### How habit-forming is it?
    It's a productivity app that will be used weekly to scan and submit notes.
* #### What's the scope?
    The purpose and product are very well defined. What I could see as the most difficult part is connecting an iPhone's camera utilities, especially since I would ideally use the "scan documents" mode. Also, we did not learn how to make POST requests in Swift, but I imagine it is not difficult to figure out.
## Final Decision
I will be making the note-taking app!

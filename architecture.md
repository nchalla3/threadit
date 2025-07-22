### Guiding Questions:

1. Who are we building this app for?
- We're building this app for start-ups, clubs, and any other organization that has thousands of new messages every day, and needs some way to keep track of it beyond tediously reading through each message to figure out what's going on
- Ex: I (Naveen) am the Outreach Lead for Formula Slug, and one thing that was commonly brought up at meetings was that "Slack is our form of documentation". While it's definitely possible to search through Slack to figure out decisoin-making rationales for certain features of the car, this process is extremely time-consuming, annoying, and can often lead to missing details. Furthermore, my co-founder (Advay) has mentioned that messages gets missed often through the sheer speed and rapid-fire forward motion he's seen in his time as the co-president of the UW Software Engineering Career Club (SWECC) and as an intern for Spice AI
2. Why are we building it?
- We are building this app first and foremost as a learning experience to get more familiar with common developer tools used in professional, industry workflows. Additionally, we've seen this problem firsthand in our extracurricular experiences and believe it can solve a real problem and help improve the quality-of-life for developers and individuals working in large-scale teams
3. What should it do?
- It should:
 1. connect and  parse through the sea of messages sent in a Teams/Slack/Discord/etc server and auto-summarize each thread, detecting the intention behind a particular decision/discussion/meeting and highlighting important conclusions in a dedicated channel
 2. Take Action: Integrate with Jira/Trello/Notion to assign tasks based off of discussions with certain keywords, tag/follow up on important decisions, and reopen issues that have gone stale
 3. Fine-grained Roles: Product Managers can see architectural decisions made by senior engineers and catch up on overwhelming amounts of messages, personalized to the needs of the team
4. How does it work?
- It uses Next.Js and Tailscale for its front-end integrations, Java Spring Boot for the back-end/auth/database, and the OpenAI API for natural language processing to rapidly read through messages and make decisions
5. How do we validate that it works?
- We know that Threadit works when real people are saving time by having a Jarvis-style dashboard of the important parts of discussions, ensuring that less time and energy is wasted in the minutiae and spent actually building
6. What is our MVP?
- Our minimum viable product is a Threadit that can simply read through a million messages in Slack and provide summarized insights using the OpenAI NLP
7. How can we build and measure success?
- We can build this using monolithic architecture, measuring success as we hit various milestones in our authentication wrapper, database configuration, successful deployment to test servers, and successful usecases in our own experiences and then to our first real users.



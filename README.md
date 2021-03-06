Welcome to our development culture document.  Here describes how we view the world and behaviors and ideals that make you successful here at Packet

### Our Mission

`Any hardware combination, any OS, any location, in our DC or yours, 100% successful provisions under 60 seconds`

### Our Company Core Values

* We are excited about leading our industry.
* We are driven, ambitious and persistent people.
* We find creative solutions to hard problems.
* We are effective at getting things done the right way.
* We are community minded and do the right thing.

### Our Team Culture

Teammates driven by [Autonomy, Mastery and Purpose](https://en.wikipedia.org/wiki/Drive:_The_Surprising_Truth_About_What_Motivates_Us) working together with [psychological saftey](https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html) is the basis for everything we do.

### Done right through Core Behaviors

 * __Care about...__ - This is the most important behavior as all other behaviors depend on this
      * Care about the craftmanship of your work.
      * Care about Packet.
      * Care about your coworkers and their success.
      * Care about standards or quality.
      * Care about learning and growing your skills.

 * __Take small purposeful steps__ - We are doing some great things, but we can only get there one commit at a time.
      * Think "why" am I working on this
      * Think "how" can I do this in incremental steps
      * Think "who" else do I need help or info from
      * Practice makes perfect

 * __Listen then collaborate__ - Listen to understand, rather than to respond
      * Listen with empathy, understand the other's point of view
      * Give your full attention
      * Give space for others to respond
     
 * __Give honest and continuous feedback__ - 
      * Be Specific and timely
      * Give compliments openly, critiques privately
      * Use the ["when you, I feel..."](https://www.erikbohlin.net/handouts/Constructive_Feedback.pdf) form of feedback

 * __Seek learning and be uncomfortable__ - Don't get complacent, find new ways to do things
      * Don't pick a path just because its easy or comfortable
      * Pick the right tool for the job
      * There's always multiple ways to do something, explore them      

If you retain anything from this article, it is the core behaviors from above.  We live by this, we hire by this, we fire by this.

### How and why we do it

Here are things we specifically do to help achieve our mission

__Code__

What   | Reasoning | Tooling
:------- | ----- | ---------
(Near) Atomic Changes | Pushing smaller changes allows us to deliver incremental value; also reduces chance of breakage | GitHub
High code coverage | CI is useless without good quality coverage, and we can't ship to production confidently without it | Drone
Refactor constantly | Reduce code debt on every issue you work on | GitHub, Rubocop

__Docs__

What   | Reasoning | Tooling
:------- | ----- | ---------
Branches and PRs | introduce small changes safely, ensure the code fits our philosophy, knowledge sharing | GitHub, Jira, Slack
Effective documentation | moving quickly means we work on a lot of different things, document for future teammates or yourself | GitHub Markdown, Jira, Confluence
Aligned Development | Make sure what we're working on brings business value | Trello, Jira

__DevOps__

What   | Reasoning | Tooling
:------- | ----- | ---------
Tight CI/CD | The way we can ship the code quickly and confidently | GithHub, Drone, Quay.io, Hashistack
Automated System/UI Testing | Once code is in production, is it really working?  Running things like Runscope against the API gives us confidence that new changes didn't mess up prod | Runscope
DevOps Culture| Everyone should know how stuff runs and keep an eye that services are working as expected | Rollbar, NewRelic, Hashistack

### Our Team

We've adapted the "Spotify" [model](https://blog.crisp.se/wp-content/uploads/2012/11/SpotifyScaling.pdf) for scaling our teams.  We have a few squads and are still experimenting with the right mix of people and skillsets.

Squad Name    | Main Focus | SLO | Squad Lead
:-------------|----------- | --- | -------------
[X-force](https://packet.atlassian.net/secure/RapidBoard.jspa?rapidView=60&useStoredSettings=true) | Customer Management and Overall Experience | [API Apdex](https://synthetics.newrelic.com/accounts/45249/monitors/ee8b6b9b-7373-411d-a801-67708572e293/sla?view=daily-sla-report) | Linda
[Suicide Squad](https://packet.atlassian.net/secure/RapidBoard.jspa?rapidView=61&useStoredSettings=true) (SuS) | Compute Products, Provisioning | [Successful Provision %](https://northstar.packet.net/d/71i_Y0Jmz/vip-provision-metrics?orgId=1) | Lucas
[Network Warriors]() | Network Products & Automation | TBD | Patrick
[Deadlift](https://packet.atlassian.net/secure/RapidBoard.jspa?rapidView=65) | Production Engineering | [API & Network Availability]() | Phil

__Proposed Future Squads__

These are teams that require more focused attention but don't have the critical mass yet for a well functioning team.

Squad Name    | Main Focus | SLO | Squad Lead
:-------------|----------- | --- | -------------
[CMR](https://packet.atlassian.net/secure/RapidBoard.jspa?rapidView=66&projectKey=SWE) | Usage & Billing | TBD | TBD
[ICP]() | Asset Management | TBD | TBD


### Resources

* Our [Interview](interview.md) process    
* Our [Onboarding](onboard.md) process    
* [Leading](leading.md) @ Packet    
* SWE [Overview & Roadmap](https://trello.com/b/A814D0t8/software-eng-roadmap) (private)    
* [How to create Pyschological Safety](https://hbr.org/2017/08/high-performing-teams-need-psychological-safety-heres-how-to-create-it)

# Open Source Software management

We keep forks of every Project, Deployment Manifests, and Infrastructure as Code (IaC) dependency repo to havefull governance over the repositories:

- __Availability:__ Because our services resilience and continuity depends on these repositories, and we want and need total control over the repository used as a dependency. NOTE: There could be few exceptions when using official source makes sense;
- __Reliability (Avoid unforeseen events):__  in the event that the original project becomes discontinued while we are still working or depending on it (the owners, generally individual maintainers of the original repository, might decide to move from github, helm, terraform, etc. or even close their repo for personal reasons);
- __Political Activism (Avoid unforeseen events):__ While there is certainly a political element to the free software movement and open source software movement, we believe that political activism outside of the scope of those movements has no place in the open source community. The number one political agenda for any free and open source project should be the promotion of free and open source software. Any other political messages could distract or divert people from our primary mission;
- __Stability:__ Our forks form modules (ansible roles / terraform / dockerfiles, etc.) are going to be locked to fixed versions so no unexpected behavior will occur;
- __Projects that don't tag versions:__ having the fork protects against breaking changes;
- __Write access:__  to every component repository ensuring at all times that we can support, update, maintain, test, customize and release a new version of this component;
- __Licence & Ownership:__ We rely on projects using MIT and Apache 2.0 license. We keep full rights to all commercial, modification, distribution, and private use of the code (No Lock-In w/ owners) through forks inside our own repos.

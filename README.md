# Leeward Habitat for Humanity 
 
Habitat for Humanity Leeward O’ahu (Leeward Habitat) is a local affiliate of a world- wide organization that builds houses with volunteer labor and sells those houses to very low-income families (those earning under 50% of the area median income). Habitat works to build homes in Leeward O’ahu which includes the areas of Kapolei, Ewa Beach, and Wai’anae. It is our mission to eliminate substandard housing and homelessness in Leeward O’ahu. With our help, families work hand in hand with volunteers to build a simple, decent home for themselves. 
 
 # Code for Hawaii x Leeward Habitat
 ## Phase 1
 ### Problem
Current website https:/leewardhabitat.org is a WordPress site that has been neglected since approx 2017. The theme and content are outdated, there's broken images and links, it just needs some TLC.
### Solution
CfH's kind volunteers are going page by page and fixing their site, adding new/updated content as it becomes available, and providing technoligical consult to the Executive Director Jo Bautista. 
### Action
Contributors can begin by adding thier site audit [here](https://github.com/CodeforHawaii/LeewardHabitatForHumanity/blob/main/notes/HFH-site-reviews.md) and/or drop a comment in the LeewardHabitat Slack channel and we can get you plugged in to a developmemnt enviroment. </br>
Our workflow currently looks like this:


 ```mermaid
graph TD;
    A[Live Site]-->B[Staging Site];
    B[Staging]-->C[Dev site x];
    B[Staging]-->D[Dev site y];
    B[Staging]-->E[Dev site z];
```

Start with a clone of the current live site. Make changes based on the site audits and input from Jo (_issues coming soon_). Changes are pushed from there to the staging site where they can be tested and reviewed. Once approved the changes are then pushed from the staging to the live production site. 

### Resources
https://leewardhabitat.org </br>
https://learm.wordpress.org </br>
https://developer.wordpress.org

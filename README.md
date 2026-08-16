# UnityProjects
<h1 align="center">Hi 👋, I'm Aaron</h1>
<h3 align="center">My goal for making this account is to be in MIT and graduate with ComputerScience and Electrical Engineering PHD</h3>
<h3 align="center">Roblox dev(sort of beginner) • Luau, Python and C# • Learning Game Systems & UI • Aspiring MIT CS & EE </h3>

- 🔭 I’m currently working on **A roblox tycoon**

- 🌱 I’m currently learning **Luau, Python and Unity**

<h3 align="left">Languages and Tools on this Repository:</h3>
<p align="left">
  <a href="https://unity.com" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/unity/unity-original.svg" alt="Unity" width="40" height="40"/>
  </a>
</p>

# August 14, 2026 

### What I worked on
- I continued on my ball platform game
- Fixed tag identication error
- added new powerup that shoots bullets to people

### What I learned
- I learned foreach
- I got a better understanding on how FindObjectByType

### Problems
- I reused the projectile from enemy which hit me at the beginning so I made a different bullet that doesnt affect player
- The FindObjectByType I was using was outdated

### Next
- I'm planning to add the gem in game and make bullets more powerful
- Also making the scripts more dynamic

# August 15, 2026 

### What I worked on
- I continued on my ball platform game
- Added push power for the player bullets
- Making the bullet shots timed every 1.5 seconds
- Added the new power up into the spawn manager
- Changed the indicator and powerup model

### What I learned
- I learned more on how coroutines work
- Difference between CompareTag and GetComponent
- Materials and how to use it correctly

### Problems
- I was using CompareTag for searching a component
- The new power up was using the same material as the old so it both had same color
- Trying to use as timer with Time.deltaTime but got lazy and used coroutines

### Next
- Adding 1 more enemy
- Adding 1 more powerup
- Also making the scripts more dynamic

# August 16, 2026 

### What I worked on
- I continued on my ball platform game
- Added boss enemy that spawn every 10 levels
- Combined shoot and push enemy ability into boss

### What I learned
- How to reuse functions in different script

### Problems
- When adding the boss battle in the Spawn Manager, I put the boss chance at the end, which made it almost never spawn
- Forgot to put rigidbody which didn't allow addForce to work
- At the beginning, I planned to make a special script to remake the SpawnManager script for spawning boss enemies, but then decided to reuse the SpawnManager's function in the special script which felt like a waste, so I put everything for the boss in the SpawnManager script instead

### Next
- Adding 1 more powerup
- Also making scripts more dynamic

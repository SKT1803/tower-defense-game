# Tower Defense (Java Game)

A classic Tower Defense game built in Java! Defend your base from waves of alien invaders by strategically placing towers along the path.

---

## Game Features

- **Custom Maps**: Create your own maps — 3 included maps to start with.
- **3 Enemy Types**: Each enemy has unique abilities and health levels.
- **3 Tower Types**: Choose from 3 different towers, each with unique attack styles and range.
- **Interstellar Soundtrack**: Background music inspired by *Interstellar* adds immersion.
- **Victory Goals**: Kill a certain number of mobs to win the game.
- **Java Based**: Built entirely with Java for learning and fun!

---

<pre>
## Project Structure
TowerDefense
├── 📁 .settings # Eclipse project settings
├── 📁 bin # Compiled class files
├── 📁 res # Game graphics
│ ├── cell.png
│ ├── coin.png
│ ├── heart.png
│ ├── mob1.png, mob2.png, mob3.png
│ ├── tileset_air.png
│ └── tileset_ground.png
├── 📁 save # Map data
│ ├── map1
│ ├── map2
│ └── map3
├── 📁 src # Source code
│ ├── Block.java
│ ├── Frame.java
│ ├── KeyHandel.java
│ ├── Mob.java / Mob2.java / Mob3.java
│ ├── Room.java
│ ├── Save.java
│ ├── Screen.java
│ ├── Store.java
│ └── Value.java
├── .classpath
├── .project
└── interstellar.wav # Background music
</pre>


---

## How to Run

   ```bash
   git clone https://github.com/yourusername/tower-defense-java.git
      cd tower-defense-java

   Compile the game:
      javac -d bin src/*.java

   javac -d bin src/*.java
      java -cp bin Frame
  ```


---
#Mobs
<br>
<img src="https://github.com/user-attachments/assets/08baf61b-a724-4ecc-bd70-073a13eda62f" width="200" height="200">
<img src="https://github.com/user-attachments/assets/128609ef-8798-4424-934a-7505c28b50bd" width="200" height="200">
<img src="https://github.com/user-attachments/assets/44733f12-3919-46ca-988f-021abf72d0de" width="200" height="200">

---
Gameplay
<br>
<table>
  <tr>
    <td><img src="screenshots/2.png" width="400"></td>
    <td><img src="screenshots/3.png" width="400"></td>
  </tr>
     <tr>
    <td><img src="screenshots/4.png" width="400"></td>
    <td><img src="screenshots/5.png" width="400"></td>
  </tr>
     <tr>
    <td><img src="screenshots/6.png" width="400"></td>
    <td><img src="screenshots/7.png" width="400"></td>
  </tr>
     <tr>
    <td><img src="screenshots/8.png" width="400"></td>
  </tr>
</table>









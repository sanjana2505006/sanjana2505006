# Hi there, I'm Sanjana 👋

I'm a passionate developer who loves coding and exploring new technologies. Welcome to my GitHub profile!

## About Me

- 🌱 I’m currently learning advanced web development and cloud computing.
- 👯 I’m looking to collaborate on open source projects.
- 💬 Ask me about web development, JavaScript, Python, and cloud services.
- 📫 How to reach me: sanjana2505006@example.com

## Skills

- **Languages:** JavaScript, Python, Java, C++
- **Web Development:** HTML, CSS, React, Node.js
- **Databases:** MongoDB, MySQL, PostgreSQL
- **Cloud Services:** AWS, Azure, Google Cloud

## Projects

### [Project Name](https://github.com/sanjana2505006/project-name)
Brief description of the project and what technologies were used.

### [Another Project](https://github.com/sanjana2505006/another-project)
Brief description of the project and what technologies were used.

## GitHub Stats

![Sanjana's GitHub stats](https://github-readme-stats.vercel.app/api?username=sanjana2505006&show_icons=true&theme=radical)

## Connect with Me

- [LinkedIn](https://www.linkedin.com/in/sanjana250506/)
- [LeetCode](https://leetcode.com/u/sanju2505/)
- [Twitter](https://twitter.com/sanjana2505006)

## Play a Game: Offline T-Rex

<details>
  <summary>Click to play the Offline T-Rex Game!</summary>
  <br>
  <div>
    <canvas id="gameCanvas" width="600" height="150"></canvas>
    <script>
      // Offline T-Rex Game JavaScript Code
      document.addEventListener('DOMContentLoaded', (event) => {
        let canvas = document.getElementById('gameCanvas');
        let context = canvas.getContext('2d');
        let dino = { x: 50, y: 100, width: 50, height: 50 };
        let cactus = { x: 600, y: 100, width: 50, height: 50 };
        let isJumping = false;
        let jumpHeight = 0;
        
        function draw() {
          context.clearRect(0, 0, canvas.width, canvas.height);
          context.fillStyle = 'green';
          context.fillRect(dino.x, dino.y - jumpHeight, dino.width, dino.height);
          context.fillStyle = 'brown';
          context.fillRect(cactus.x, cactus.y, cactus.width, cactus.height);
          if (isJumping) {
            jumpHeight += 5;
            if (jumpHeight >= 50) {
              isJumping = false;
            }
          } else if (jumpHeight > 0) {
            jumpHeight -= 5;
          }
          cactus.x -= 5;
          if (cactus.x <= -50) {
            cactus.x = 600;
          }
          requestAnimationFrame(draw);
        }
        
        document.addEventListener('keydown', (event) => {
          if (event.code === 'Space' && !isJumping) {
            isJumping = true;
          }
        });
        
        draw();
      });
    </script>
  </div>
</details>

Thanks for visiting my profile! 😊

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

- [LinkedIn](https://www.linkedin.com/in/sanjana2505006)
- [Twitter](https://twitter.com/sanjana2505006)

## Play a Game: Rock Paper Scissors

<details>
  <summary>Click to play Rock Paper Scissors!</summary>
  <br>
  <div>
    <button onclick="play('rock')">Rock</button>
    <button onclick="play('paper')">Paper</button>
    <button onclick="play('scissors')">Scissors</button>
    <p id="result"></p>
  </div>
  <script>
    function play(userChoice) {
      const choices = ['rock', 'paper', 'scissors'];
      const computerChoice = choices[Math.floor(Math.random() * 3)];
      let result = '';

      if (userChoice === computerChoice) {
        result = "It's a tie!";
      } else if ((userChoice === 'rock' && computerChoice === 'scissors') || 
                 (userChoice === 'paper' && computerChoice === 'rock') || 
                 (userChoice === 'scissors' && computerChoice === 'paper')) {
        result = 'You win!';
      } else {
        result = 'You lose!';
      }

      document.getElementById('result').innerText = `You chose ${userChoice}, computer chose ${computerChoice}. ${result}`;
    }
  </script>
</details>

Thanks for visiting my profile! 😊

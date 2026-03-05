<div align="center">

# 🖥️ Discover Computing

### *Hands-on programming education through creative computing.*

*Empowering students to build, create, and explore through project-based coding experiences.*

---

![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![p5.js](https://img.shields.io/badge/p5.js-ED225D?style=for-the-badge&logo=p5dotjs&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Teachable Machine](https://img.shields.io/badge/Teachable%20Machine-4285F4?style=for-the-badge&logo=google&logoColor=white)

</div>

---

## 📖 About Discover Computing

**Discover Computing** is a **5-day, project-based programming program** designed to introduce students to modern development tools, creative coding, and machine learning. Through hands-on projects, students move from writing their first lines of code to building interactive games and real-time machine learning applications.

### 🎯 Key Learning Outcomes

- ✅ Navigate GitHub workflows — repos, branches, commits, and Codespaces
- ✅ Build interactive visuals and animations using **p5.js**
- ✅ Understand real-time rendering at **60 frames per second**
- ✅ Design game mechanics including movement, input, and scoring systems
- ✅ Train and deploy custom **machine learning models** using a webcam
- ✅ Connect ML predictions to live program behavior
- ✅ Build a functional **paint application** from scratch

---

## 📅 Program Curriculum

The program spans **five days**, each focused on a distinct computing concept — building progressively from foundational tools to creative and intelligent applications.

---

### Day 1 — GitHub & Creative Coding

**Topics Covered:**

| Concept | Description |
|---|---|
| GitHub Account Setup | Creating and configuring a GitHub profile |
| Repositories | Understanding how code is stored and organized |
| Branches & Commits | Tracking changes and working collaboratively |
| GitHub Codespaces | Writing and running code directly in the browser |
| Markdown Documentation | Writing `.md` files to document projects |

**🐶 Project: Dog Drawing with p5.js**

Students created an animated dog illustration using **p5.js built-in shape functions**, combining circles, rectangles, and ellipses to construct a character rendered at **60 frames per second**.

```javascript
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
  // Draw dog body
  ellipse(200, 250, 150, 100); // body
  ellipse(200, 170, 90, 90);   // head
  rect(160, 290, 30, 60);      // left leg
  rect(210, 290, 30, 60);      // right leg
}
```

> Students discovered how real-time rendering works by observing how p5.js redraws the canvas every frame.

📁 [Project Repository Link Here]

---

### Day 2 — Interactive Graphics

**Topics Covered:**

- Drawing and positioning shapes using `x` and `y` coordinates
- Understanding the `setup()` and `draw()` animation loop
- Using variables to control object position and behavior
- Responding to mouse and keyboard input
- Experimenting with motion and interactivity

**✏️ Project: Interactive Sketch**

Students built interactive p5.js sketches where objects responded to cursor movement and user actions — exploring how variables and animation loops create the illusion of motion.

```javascript
let x = 200;
let y = 200;

function draw() {
  background(255);
  ellipse(mouseX, mouseY, 50, 50); // follows the cursor
}
```

📁 [Example Project Link Here]

---

### Day 3 — Game Mechanics

**Topics Covered:**

| Concept | Description |
|---|---|
| Game Loop | How `draw()` powers continuous game state updates |
| Player Movement | Moving a character across the canvas |
| Keyboard Input | Responding to WASD key presses |
| Custom Functions | Encapsulating logic into reusable blocks |
| Score System | Using variables to track collected coins |

**🎮 Project: Mario-Style 8-Bit Game Prototype**

Students built a platformer-inspired game prototype featuring a player character, keyboard controls, and a coin collection system.

**Example functions students implemented:**

```javascript
function jump() { /* launches player upward */ }
function doubleJump() { /* applies second upward force mid-air */ }
function crouch() { /* reduces player hitbox height */ }
function collectCoin() { score += 1; } // increments coin counter
```

> Students learned how **functions encapsulate game logic** — keeping code clean, readable, and reusable.

📁 [Game Demo Link Here]

---

### Day 4 — Machine Learning with Teachable Machine

**Topics Covered:**

- Training a custom image classification model using **Google Teachable Machine**
- Collecting webcam training data for gesture recognition
- Connecting ML model predictions to p5.js program logic
- Using conditionals to trigger visual responses

**🤖 Project: Gesture-Controlled Animation**

Students trained a model to recognize hand gestures via webcam, then wired the predictions into a live p5.js sketch — because both p5.js and Teachable Machine models run at **60 frames per second**, the interaction feels instant.

**Gesture → Response Mapping:**

| Gesture | Visual Effect |
|---|---|
| ✌️ Peace Sign | Screen turns **green** |
| 👍 Thumbs Up | Block turns **blue** |
| 🖐️ Open Hand | Background resets |

```javascript
// Pseudocode: connecting ML predictions to program logic
if (prediction === "peace_sign") {
  background(0, 200, 0); // green
} else if (prediction === "thumbs_up") {
  fill(0, 0, 255);        // blue block
}
```

> Students connected **machine learning predictions to program logic** — seeing how AI outputs become inputs for creative applications.

📁 [Teachable Machine Project Link Here]

---

### Day 5 — Building a Paint Program

**Topics Covered:**

- Capturing real-time mouse position with `mouseX` and `mouseY`
- Using `mouseIsPressed` to conditionally draw
- Generating persistent visuals across frames
- Building a functional creative tool from scratch

**🎨 Project: p5.js Paint Application**

Because p5.js renders at **60 frames per second**, holding the mouse button down continuously fires drawing commands — one per frame. Students leveraged this to build a working paintbrush tool.

```javascript
function draw() {
  if (mouseIsPressed) {
    fill(0);
    noStroke();
    ellipse(mouseX, mouseY, 20, 20); // draws a circle at cursor position
  }
}
```

As the cursor moves with the button held, new circles are drawn each frame — creating the appearance of a **continuous brush stroke**. Students effectively built their own drawing application from first principles.

📁 [Paint Tool Demo Link Here]

---

## 🛠️ Technologies Used

| Technology | Role in Program |
|---|---|
| ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) **GitHub** | Version control, Codespaces, and project hosting |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) **JavaScript** | Core programming language used across all projects |
| ![p5.js](https://img.shields.io/badge/p5.js-ED225D?style=flat&logo=p5dotjs&logoColor=white) **p5.js** | Creative coding library for visuals, animation, and interaction |
| ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white) **TensorFlow.js** | ML model inference running in-browser via JavaScript |
| ![Google](https://img.shields.io/badge/Teachable%20Machine-4285F4?style=flat&logo=google&logoColor=white) **Google Teachable Machine** | No-code model training using webcam image data |

---

## 🌟 Example Student Projects

| Project | Description | Link |
|---|---|---|
| 🐶 Dog Drawing | Animated character built with p5.js shapes | [Project Link Here] |
| 🎮 Interactive Game | Mario-style platformer with WASD controls and coin collecting | [Project Link Here] |
| 🤖 Gesture Animation | Webcam gesture recognition wired to real-time visuals | [Project Link Here] |
| 🎨 Paint Application | Freehand drawing tool built in p5.js | [Project Link Here] |

---

## 📁 Repository Structure

```
discover-computing/
│
├── day1-dog-project/          # p5.js dog drawing + GitHub intro
├── day2-interactive-sketch/   # Shape drawing and animation exploration
├── day3-game-project/         # Mario-style game prototype
├── day4-ml-interaction/       # Teachable Machine gesture project
├── day5-paint-app/            # Freehand paint application
│
└── README.md
```

## Discover Computing

Discover Computing gives students more than just coding skills — it gives them a new way of thinking.

Over five days, students:

- 🔧 Learn **modern development tools** used by professional engineers
- 🧠 Build genuine intuition for **programming concepts** like loops, functions, and variables
- 🎨 Experience **creative computing** — where art, design, and code intersect
- 🤖 Gain early exposure to **machine learning** through hands-on, visual projects
- 🚀 Leave with real, working projects they built themselves

> *Every program on this page was created by a student. Explore the repositories, fork a project, and keep building.*

---

<div align="center">

**Discover Computing** · Built by students, for students.

![Made with p5.js](https://img.shields.io/badge/Made%20with-p5.js-ED225D?style=flat&logo=p5dotjs&logoColor=white)
![Powered by JavaScript](https://img.shields.io/badge/Powered%20by-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![ML with Teachable Machine](https://img.shields.io/badge/ML-Teachable%20Machine-4285F4?style=flat&logo=google&logoColor=white)

</div>

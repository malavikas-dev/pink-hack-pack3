<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# [Pinkquiz] 🎯

## Basic Details

### Team Name: [Pink Hack Pack]

### Team Members
- Member 1: [Malavika] - [AISAT]
- Member 2: [Vismaya] - [AISAT]

### Hosted Project Link
[ https://malavikas-dev.github.io/pink-hack-pack3/]

### Project Description
[QuizBattle AI is a fast-paced browser-based quiz game built with HTML, CSS, and JavaScript. It features 6 categories — Science, History, Tech, Sports, Movies, and Geography — each with 3 difficulty levels. Players answer 10 questions with a 15-second timer per question, earning bonus points for speed and streaks. The game includes a live score tracker, animated feedback, and a detailed results review screen.]

### The Problem statement
[Students and casual users lack an engaging, fast-paced way to test their general knowledge across multiple topics in a fun, gamified format.]

### The Solution
[QuizBattle AI is a browser-based quiz game that challenges users with 10 timed questions across 6 categories and 3 difficulty levels, with a scoring system that rewards speed and streaks.]

---

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: [HTML, CSS, JavaScript]
- Frameworks used: [ None (Vanilla JS)]
- Libraries used: [Google Fonts (Bebas Neue, DM Sans)]
- Tools used: [VS Code, Git, GitHub]

**For Hardware:**
- Main components: [List main components]
- Specifications: [Technical specifications]
- Tools required: [List tools needed]

---

## Features

List the key features of your project:
- Feature 1: [6 Categories: Science, History, Tech, Sports, Movies, Geography.Animated UI: Particle background, smooth transitions, responsive design]
- Feature 2: [3 Difficulty Levels: Easy, Medium, Hard.15-Second Timer: Countdown timer per question with color warnings]
- Feature 3: [Dynamic Scoring: Bonus points based on speed + streak multiplier
.Streak Tracker: Visual streak dots + best streak recorded]
- Feature 4: [Instant Feedback: Toast notifications for correct/wrong answers.Results Review: Full answer breakdown after quiz ends]

---

## Implementation
git clone https://github.com/malavikas-dev/pink-hack-pack3.git
### For Software:

#### Installation
```bash
[git clone https://github.com/malavikas-dev/pink-hack-pack3.git]
```

#### Run
[open quiz-battle.html]
### Application Workflow
```
[User Opens App
      ↓
Select Category (Science / History / Tech / Sports / Movies / Geography)
      ↓
Select Difficulty (Easy / Medium / Hard)
      ↓
Click START BATTLE
      ↓
10 Questions Loaded (shuffled from question bank)
      ↓
Each Question → 15s Timer starts
      ↓
User Selects Answer → Instant Feedback Toast
      ↓
Score = 100 + (timeLeft × 10) + (streak × 20)
      ↓
After 10 Questions → Results Screen
      ↓
Review Answers / Play Again / Go Home]
```

### For Hardware:

#### Components Required
[List all components needed with specifications]

#### Circuit Setup
[Explain how to set up the circuit]

---

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)

![Screenshot1](Add screenshot 1 here with proper name)
*Add caption explaining what this shows*

![Screenshot2](Add screenshot 2 here with proper name)
*Add caption explaining what this shows*

![Screenshot3](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*

#### Diagrams

**System Architecture:**

![Architecture Diagram](docs/architecture.png)
*Explain your system architecture - components, data flow, tech stack interaction*

**Application Workflow:**

![Workflow](docs/workflow.png)
*Add caption explaining your workflow*

---

### For Hardware:

#### Schematic & Circuit

![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

#### Build Photos

![Team](Add photo of your team here)

![Components](Add photo of your components here)
*List out all components shown*

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

---

## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

**Base URL:** `https://api.yourproject.com`

##### Endpoints

**GET /api/endpoint**
- **Description:** [What it does]
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
```

[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![App Flow](docs/app-flow.png)
*Explain the user flow through your application*

#### Installation Guide

**For Android (APK):**
1. Download the APK from [Release Link]
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to Settings > Security
   - Enable "Unknown Sources"
3. Open the downloaded APK file
4. Follow the installation prompts
5. Open the app and enjoy!

**For iOS (IPA) - TestFlight:**
1. Download TestFlight from the App Store
2. Open this TestFlight link: [Your TestFlight Link]
3. Click "Install" or "Accept"
4. Wait for the app to install
5. Open the app from your home screen

**Building from Source:**
```bash
# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug
```

---

### For Hardware Projects:

#### Bill of Materials (BOM)

| Component | Quantity | Specifications | Price | Link/Source |
|-----------|----------|----------------|-------|-------------|
| Arduino Uno | 1 | ATmega328P, 16MHz | ₹450 | [Link] |
| LED | 5 | Red, 5mm, 20mA | ₹5 each | [Link] |
| Resistor | 5 | 220Ω, 1/4W | ₹1 each | [Link] |
| Breadboard | 1 | 830 points | ₹100 | [Link] |
| Jumper Wires | 20 | Male-to-Male | ₹50 | [Link] |
| [Add more...] | | | | |

**Total Estimated Cost:** ₹[Amount]

#### Assembly Instructions

**Step 1: Prepare Components**
1. Gather all components listed in the BOM
2. Check component specifications
3. Prepare your workspace
![Step 1](images/assembly-step1.jpg)
*Caption: All components laid out*

**Step 2: Build the Power Supply**
1. Connect the power rails on the breadboard
2. Connect Arduino 5V to breadboard positive rail
3. Connect Arduino GND to breadboard negative rail
![Step 2](images/assembly-step2.jpg)
*Caption: Power connections completed*

**Step 3: Add Components**
1. Place LEDs on breadboard
2. Connect resistors in series with LEDs
3. Connect LED cathodes to GND
4. Connect LED anodes to Arduino digital pins (2-6)
![Step 3](images/assembly-step3.jpg)
*Caption: LED circuit assembled*

**Step 4: [Continue for all steps...]**

**Final Assembly:**
![Final Build](images/final-build.jpg)
*Caption: Completed project ready for testing*

---

### For Scripts/CLI Tools:

#### Command Reference

**Basic Usage:**
```bash
python script.py [options] [arguments]
```

**Available Commands:**
- `command1 [args]` - Description of what command1 does
- `command2 [args]` - Description of what command2 does
- `command3 [args]` - Description of what command3 does

**Options:**
- `-h, --help` - Show help message and exit
- `-v, --verbose` - Enable verbose output
- `-o, --output FILE` - Specify output file path
- `-c, --config FILE` - Specify configuration file
- `--version` - Show version information

**Examples:**

```bash
# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
```

#### Demo Output

**Example 1: Basic Processing**

**Input:**
```
This is a sample input file
with multiple lines of text
for demonstration purposes
```

**Command:**
```bash
python script.py sample.txt
```

**Output:**
```
Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
```

**Example 2: Advanced Usage**

**Input:**
```json
{
  "name": "test",
  "value": 123
}
```

**Command:**
```bash
python script.py -v --format json data.json
```

**Output:**
```
[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
```

---

## Project Demo

### Video
[]

*Explain what the video demonstrates - key features, user flow, technical highlights*

### Additional Demos
[🔗 https://malavikas-dev.github.io/pink-hack-pack3/quiz-battle.html]

---

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** [ChatGPT]

**Purpose:** [What you used it for]
- Example: "Generated boilerplate React components"
- Example: "Debugging assistance for async functions"
- Example: "Code review and optimization suggestions"

**Key Prompts Used:**
- "Debug this async function that's causing race conditions"

**Percentage of AI-generated code:** [35%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions
- Category and difficulty selection
- Question accuracy verification
- Scoring formula design
- Game flow and navigation design
- Color theme and visual style decisions
- Timer duration and warning threshold setting
- GitHub repository setup and management
- GitHub Pages deployment
- Filename and structure organization
- Feature prioritization and scope definition
- User experience flow testing
- Performance and load time testing
- Final project review and quality check


*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

- [malavika]: [Full project — concept, development, testing, and deployment]
- [vismaya]: [helps in idea hacking and created the design appearence.]

---

## License

This project is licensed under the MIT License

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub

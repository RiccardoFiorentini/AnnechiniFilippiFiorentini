# CodeKataBattle

**CodeKataBattle (CKB)** is a platform designed to help students improve their software development skills by competing in code kata battles. Educators can challenge students by creating programming exercises where teams of students compete, enhancing their skills through practice and competition.

## How It Works

### Code Kata Battle
A code kata battle is a programming exercise in a chosen language (e.g., Java, Python) that includes:
- A brief description.
- A software project with build automation scripts.
- Test cases (without the program implementation).

Students complete the project using a test-first approach and submit their solutions. Scores are assigned based on test case success, timeliness, and code quality.

### Tournaments
Educators create tournaments and grant permissions to colleagues. Students are notified of new tournaments and can subscribe by a deadline. Each battle within a tournament follows these steps:
1. Upload the code kata.
2. Set student group sizes.
3. Set registration and submission deadlines.
4. Configure scoring options.

### Student Participation
Students form teams, join battles, and fork the provided GitHub repository. Using GitHub Actions, they automate notifications to the CKB platform upon committing code, triggering score updates based on functional tests, timeliness, and code quality.

### Scoring
Scores range from 0 to 100, with automated and optional manual evaluations:
- **Automated**: Functional test success, timeliness, and static code analysis.
- **Manual**: Educator-assigned personal scores.

### Real-time Updates
Scores are updated in real-time as students commit code, with live rankings available for both students and educators.

### End of Battle
Post-submission, educators may perform manual evaluations if required. Final ranks are then consolidated and shared with all participants.

### Tournaments and Badges
Tournaments rank students based on their cumulative battle scores. Educators can also define gamification badges with specific rules to reward achievements. These badges are visible on student profiles.

## Features
- **Real-time Score Updates**: Automated updates with each commit.
- **Flexible Scoring Configuration**: Automated and manual scoring options.
- **Gamification**: Custom badges and tournament ranks.
- **Team Collaboration**: Students form and manage teams for each battle.

## Conclusion
CodeKataBattle provides an engaging way for students to practice coding skills, with structured challenges and real-time feedback. Educators can create comprehensive coding competitions, enhancing the learning experience through collaboration and competition.

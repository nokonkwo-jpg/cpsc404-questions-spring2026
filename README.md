# CPSC 404 Senior Seminar - Question Submissions

**Spring 2026 | Trinity College**

This repository is where you submit your weekly pre-class questions using Git and GitHub workflows - putting into practice the open source collaboration principles from *Producing Open Source Software*.

## 📚 Course Information

- **Instructor:** Ken Kousen
- **Course:** CPSC 404: Senior Seminar
- **Textbooks:**
  - *Help Your Boss Help You* by Ken Kousen
  - *Producing Open Source Software* by Karl Fogel

## 🎯 Learning Objectives

By using this repository, you will:
- Practice Git workflows (fork, clone, branch, commit, push, pull request)
- Experience open source contribution patterns
- Build your GitHub portfolio
- Learn collaborative code review
- Understand distributed version control

## 📋 Weekly Workflow

### One-Time Setup (Week 1)

1. **Fork this repository** (click "Fork" button in top right)
2. **Clone your fork locally:**
   ```bash
   git clone https://github.com/YOUR-USERNAME/cpsc404-questions-spring2026.git
   cd cpsc404-questions-spring2026
   ```
3. **Add upstream remote** (to get updates):
   ```bash
   git remote add upstream https://github.com/kousen/cpsc404-questions-spring2026.git
   ```

### Each Week (Weeks 2-13)

**Due: Wednesday 11:59 PM before each Thursday class**

1. **Update your fork** with any new content:
   ```bash
   git checkout main
   git pull upstream main
   git push origin main
   ```

2. **Create a new branch** for this week's question:
   ```bash
   git checkout -b week02-lastname-question
   # Example: git checkout -b week02-kousen-question
   ```

3. **Create your question file** in the appropriate week folder:
   ```bash
   # Navigate to the week's questions folder
   cd week02-chapter01/questions

   # Create your question file (use your actual name)
   # Format: lastname-firstname.md
   touch kousen-kenneth.md
   ```

4. **Write your question** in the file (use any text editor):
   ```markdown
   # Week 2 Question - Chapter 1: Making Inevitable Conflict Productive

   **Student:** Kenneth Kousen
   **Date:** January 28, 2026

   ## Question

   [Your substantive question here - aim for insight, synthesis, or debate]

   ## Context (optional)

   [Brief context if needed to clarify your question]
   ```

5. **Commit and push** your question:
   ```bash
   git add .
   git commit -m "Add Week 2 question on inevitable conflict"
   git push origin week02-lastname-question
   ```

6. **Open a Pull Request:**
   - Go to your fork on GitHub
   - Click "Compare & pull request" (green button appears after push)
   - Title: `Week 2 Question - Your Name`
   - Description: Optional - add any notes
   - Click "Create pull request"

7. **Respond to feedback** (if I request changes):
   - Make edits to your file
   - Commit and push to the same branch
   - The PR updates automatically

## 📝 Question Quality Guidelines

Your question should demonstrate critical engagement with the reading. Refer to the syllabus for the 0-3 grading rubric:

- **3 (Excellent):** Insightful, synthesizes concepts, invites debate
- **2 (Good):** Demonstrates understanding, focuses on application
- **1 (Adequate):** Basic comprehension question
- **0 (Insufficient):** Missing or shows lack of reading

## 📁 Repository Structure

```
cpsc404-questions-spring2026/
├── README.md (this file)
├── week02-chapter01/          # HYBHY Ch 1
│   ├── README.md              # Chapter info and due date
│   └── questions/
│       └── [your-file.md]
├── week03-chapter02/          # HYBHY Ch 2
├── week04-chapter03/          # HYBHY Ch 3
├── week06-dual-reading/       # HYBHY Ch 4 + ProducingOSS Ch 8
├── week07-chapter05-async/    # HYBHY Ch 5 (async week)
├── week08-dual-reading/       # HYBHY Ch 6 + ProducingOSS Ch 6
├── week10-dual-reading/       # HYBHY Ch 7 + ProducingOSS Ch 4
├── week11-chapter08/          # HYBHY Ch 8
├── week12-chapter09/          # HYBHY Ch 9
└── week13-chapter10/          # HYBHY Ch 10
```

## 🔄 Why Pull Requests?

This workflow mirrors real open source contribution:

- **Forking** = creating your own workspace (ProducingOSS Ch 8)
- **Branches** = isolated feature development
- **Pull Requests** = requesting your contribution be merged
- **Code Review** = maintainer feedback (that's me!)
- **Merge** = accepting your contribution

You're experiencing the collaboration model discussed in *Producing Open Source Software*!

## ❓ Common Questions

**Q: What if I make a mistake in my PR?**
A: Just push new commits to the same branch - the PR updates automatically. This is normal workflow!

**Q: Can I see other students' questions?**
A: Yes! Once PRs are merged, all questions become visible. This encourages learning from peers.

**Q: What if I'm stuck on Git?**
A: Ask in class, check office hours, or see [GitHub's Git Guide](https://docs.github.com/en/get-started/using-git/about-git).

**Q: Can I submit late?**
A: PRs are timestamped. Late submissions follow the course late policy (see syllabus).

**Q: What about Week 7 (async week)?**
A: Same process! Plus you'll submit a separate written analysis via Moodle.

## 🎓 Grading

- Questions are worth 20% of your final grade
- Each week graded 0-3 (see rubric above)
- Lowest 2 scores dropped
- Due: Wednesdays at 11:59 PM
- Grading based on PR submission timestamp

## 🔗 Resources

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
- [ProducingOSS Online](https://producingoss.com/en/producingoss.html)
- [Markdown Guide](https://www.markdownguide.org/)

## 📧 Questions?

- **Office Hours:** Wednesdays 1:30-3:00 PM (MECC 175)
- **Email:** kkousen@trincoll.edu

---

**Remember:** This isn't just about submitting assignments - you're building real-world Git skills while studying open source collaboration. By the end of the semester, you'll have a portfolio of thoughtful questions demonstrating your growth!

*Last updated: January 2026*

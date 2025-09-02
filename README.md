# 🤝 G-WAC Team Collaboration Exercise

Welcome to the **Git Collaboration Bootcamp**! This exercise is designed to give you hands-on experience with real-world Git collaboration workflows. You'll practice branching, pull requests, merge conflicts, and team coordination.

## 🎯 **Exercise Objectives**

By completing this exercise, you will:

- ✅ **Master Git branching workflow** - Create and manage feature branches
- ✅ **Experience real merge conflicts** - Learn to resolve conflicts like a pro
- ✅ **Practice pull request workflow** - Submit and review code changes
- ✅ **Develop team coordination skills** - Communicate effectively through Git

---

## 👥 **Team Members**

*Everyone adds their name below. This is where the magic (and conflicts) happen!*

### **Course Team**
- **Vincent Donkoh** - Lead Learner & Git Workflow Facilitator

### **Participants**
*Add your name here using the format below:*

```
- **Mouhamadou Fadel DIOP** -  PhD Student, London School of Hygiene and Tropical Medicine - Coffee ☕ and Football addict
```

**Examples:**
- **Sarah Chen** - PhD Student, London School of Hygiene - Coffee addict ☕
- **James Mitchell** - Research Fellow, Oxford University - Weekend rock climber 🧗
- **Maria Santos** - Data Scientist, WHO Geneva - Speaks 4 languages 🌍

---

## 🚀 **Getting Started**

### **Step 1: Clone the Repository**
```bash
git clone https://github.com/VincentSD/team-collaboration-exercise.git
cd team-collaboration-exercise
```

### **Step 2: Create Your Branch**
```bash
git checkout -b add-[your-name]
# Example: git checkout -b add-sarah-chen
```

### **Step 3: Add Your Information**
1. Open `README.md` in your favorite editor
2. Find the "Participants" section above
3. Add your line using the format provided
4. Save the file

### **Step 4: Commit Your Changes**
```bash
git add README.md
git commit -m "Add [Your Name] to team directory"
# Example: git commit -m "Add Sarah Chen to team directory"
```

### **Step 5: Push Your Branch**
```bash
git push origin add-[your-name]
```

### **Step 6: Create Pull Request**
1. Go to the GitHub repository
2. Click "Compare & pull request" 
3. Add a descriptive title: "Add [Your Name] to team directory"
4. Submit the pull request

---

## ⚔️ **Handling Merge Conflicts (The Fun Part!)**

When multiple people edit the same file, conflicts are **guaranteed**! Here's how to handle them:

### **When You Get a Conflict:**

1. **Fetch the latest changes:**
   ```bash
   git fetch origin
   git merge origin/main
   ```

2. **Open README.md** - You'll see conflict markers like:
   ```
   <<<<<<< HEAD
   - **Your Name** - Your Institution - Your Fun Fact
   =======
   - **Someone Else** - Their Institution - Their Fun Fact  
   >>>>>>> origin/main
   ```

3. **Resolve the conflict** by keeping both entries:
   ```
   - **Your Name** - Your Institution - Your Fun Fact
   - **Someone Else** - Their Institution - Their Fun Fact
   ```

4. **Complete the merge:**
   ```bash
   git add README.md
   git commit -m "Resolve merge conflict - keep all team members"
   git push origin add-[your-name]
   ```

---

## 🎯 **Pro Tips for Success**

### **Communication is Key**
- 💬 **Comment on pull requests** - Give friendly feedback to teammates
- 👀 **Check existing PRs** before starting - See what others are working on
- 🤝 **Help resolve conflicts** - Collaborate to keep everyone's information

### **Git Best Practices**
- 📝 **Write clear commit messages** - Help teammates understand your changes
- 🔄 **Keep branches up to date** - Regularly sync with main branch
- ✅ **Test your changes** - Make sure the README looks good after your edits

### **Conflict Resolution**
- 🛡️ **Don't panic** - Conflicts are normal and easy to fix
- 👥 **Keep everyone's info** - Never delete someone else's contribution
- 🧹 **Clean up markers** - Remove all `<<<<<<<`, `=======`, `>>>>>>>` lines

---

## 📊 **Success Criteria**

Your team succeeds when:

- ✅ **Everyone appears in the participants list**
- ✅ **All team members created their own branch**
- ✅ **Everyone submitted a pull request**
- ✅ **Merge conflicts were resolved collaboratively**
- ✅ **Team reviewed and commented on each other's PRs**
- ✅ **Final README is clean and includes everyone**

---

## 🆘 **Need Help?**

### **Common Issues & Solutions**

**Q: I can't push my branch**
A: Someone else probably merged first. Run `git pull origin main` and resolve conflicts.

**Q: I accidentally deleted someone's name**
A: Check the Git history with `git log` and restore their information.

**Q: I don't see my branch on GitHub**
A: Make sure you pushed it: `git push origin add-[your-name]`

**Q: The conflict markers are confusing**
A: Ask a teammate for help! Collaboration means working together.

### **Ask for Help**
- 🙋 **Create an issue** if you're stuck
- 💬 **Comment on existing PRs** to ask questions
- 👥 **Work together** - this is a team exercise!

---

## 🎉 **Learning Outcomes**

After completing this exercise, you'll understand:

- **How real development teams collaborate**
- **Why merge conflicts happen and how to fix them**
- **The importance of clear communication in Git workflows**
- **How to coordinate changes across multiple contributors**

**These skills transfer directly to:**
- 🔬 **Research collaborations** - Co-authoring papers and sharing code
- 💼 **Professional development** - Working in software development teams
- 📚 **Open source contributions** - Contributing to scientific software projects

---

## 🏆 **Ready to Start?**

1. **Clone this repository**
2. **Create your branch** 
3. **Add your name** to the participants section
4. **Submit your pull request**
5. **Help teammates** resolve any conflicts
6. **Celebrate** your successful collaboration! 🎉

**Remember:** The goal isn't to avoid conflicts - it's to learn how to resolve them together as a team!

---

*Built with ❤️ for the G-WAC community*  
*Teaching the next generation of collaborative researchers*

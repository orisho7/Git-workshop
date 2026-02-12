# GDG on Campus Mustaqbal University - Git Workshop

Welcome to the **GDG Git Workshop**! 🚀

In this session, you will learn the basics of Git by contributing to this shared photo gallery project. Follow the steps below to add your favorite photo to the website.

## 🛠️ Prerequisites

- [Git](https://git-scm.com/downloads) installed on your machine.
- A GitHub account.

## 🚀 Step-by-Step Guide

### 1. Clone the repository

Open your terminal/command prompt and run:

```bash
git clone <repository-url>
cd <repository-folder>
```

### 2. Create a new branch

Always work on a separate branch to avoid conflicts:

```bash
git checkout -b student/your-name
```

### 3. Add your photo

- Find a cool photo (keep it appropriate!).
- Save it to the `images/` folder.
- Use a short, descriptive name (e.g., `ali-tech.jpg`).

### 4. Update the Gallery

- Open `index.html` in your favorite editor (VS Code recommended).
- Scroll down to the `<!-- STUDENT CARDS START HERE -->` section.
- Copy the example card block and paste it below the line.
- Update the details:
  - Change `src` to `images/your-photo-name.jpg`.
  - Change the `<h3>` to **your name**.
  - Change the `<p>` to a short description of the photo.

### 5. Commit and Push

```bash
git add .
git commit -m "Add Ali's favorite photo"
git push origin student/your-name
```

### 6. Create a Pull Request

Go to the repository on GitHub and click "Compare & pull request" to submit your changes!

---

Built with ❤️ by GDG on Campus Mustaqbal University.

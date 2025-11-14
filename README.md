# 📘 Student Spotlight – SMIT Batch 18

A simple HTML/CSS learning project where Batch 17 students create their own profiles, display achievements, and showcase projects.

This README will help you understand:

* ✔️ How the folder structure works
* ✔️ Where to add your files
* ✔️ How to add your photo & profile
* ✔️ How the website is organized

Perfect for beginners using **only HTML, CSS, and a little JavaScript**.

---

# 📁 Project Structure (Beginner-Friendly Guide)

```
student-spotlight-smit-batch17/
│
├── index.html
├── about.html
├── students.html
├── achievements.html
├── course.html
├── contact.html
│
├── /students/
│   ├── SMIT-421836/
│   │   ├── Ahmed.html
│   │   ├── Ahmed.css
│   │   ├── Ahmed.js
│   │   └── /Assets/Images/
│
├── /assets/
│   ├── /images/
│   ├── /videos/
│
├── /css/
│   ├── main.css
│   ├── layout.css
│   ├── components.css
│   ├── responsive.css
│
├── /js/
│   ├── script.js
│   └── studentData.js
│
├── /data/
│   └── students.json
│
├── /projects/
│   ├── index.html
│
└── README.md
```

Below is a **simple explanation** of everything.

---

# 🧭 Main Pages (Top-Level HTML Files)

These are the main screens of the website:

| Page                | Purpose                                       |
| ------------------- | --------------------------------------------- |
| `index.html`        | Home page – introduction, trainer, highlights |
| `about.html`        | About SMIT, trainer, course description       |
| `students.html`     | Grid/list of all students                     |
| `achievements.html` | Awards, rising stars, badges                  |
| `course.html`       | Course modules, assignments, roadmap          |
| `contact.html`      | Contact or feedback form                      |

These are shared pages of the whole class.

---

# 👨‍🎓 `/students/` Folder – Your Personal Profile Area

Inside `/students/`, each student has **their own folder** named with their **Roll Number**:

Example:

```
/students/SMIT-421836/
```

Inside your folder, you can have:

| File              | What it is                 |
| ----------------- | -------------------------- |
| `YourName.html`   | Your personal profile page |
| `YourName.css`    | Your custom styling        |
| `YourName.js`     | Optional JS for your page  |
| `/Assets/Images/` | Your photos, badges, icons |

👉 **Every student creates their own folder + HTML page.**
👉 This keeps the project organized and clean.

---

# 🎨 `/assets/` – Shared Files

This folder contains items used by *everyone*:

### `/assets/images/`

* Trainer image
* Badges (HTML, CSS, Rising Star…)
* Common icons
* Generic student placeholder images

### `/assets/videos/`

* Optional intro videos
* Class recordings
* Highlights (if any)

Students should **not** put their personal files here.
Personal images go inside their own folder:

```
/students/YourRoll/Assets/Images/
```

---

# 💅 `/css/` – Global Styles

These CSS files control the **whole website**:

| File             | Purpose                          |
| ---------------- | -------------------------------- |
| `main.css`       | Colors, fonts, global styles     |
| `layout.css`     | Structure, grid, spacing         |
| `components.css` | Cards, buttons, badges, sections |
| `responsive.css` | Mobile/tablet styles             |

Students use these **by adding classes** in their own pages.

---

# ⚙️ `/js/` – Basic JavaScript

| File             | What it does                               |
| ---------------- | ------------------------------------------ |
| `script.js`      | Menu toggle, dark mode, UI interactions    |
| `studentData.js` | (Optional) Store student data in JS format |

Not required for basic HTML/CSS work.

---

# 📊 `/data/` – Optional JSON

Contains:

```
students.json
```

A central place to store all student info (future enhancement).
Beginners do not need to edit this.

---

# 💻 `/projects/` – Project Showcase

This folder holds **student projects**.

Example structure:

```
/projects/
   ├── index.html         # All projects gallery
   ├── /SMIT-421836/
   │      └── portfolio.html
```

Students place their project pages inside **their own folder** inside `/projects/`.

---

# ✨ How to Add Your Student Profile

Follow these 4 simple steps:

---

### ✔️ Step 1 — Create Your Folder

Inside `/students/`, create a folder named with your roll number:

```
/students/SMIT-42xxxx/
```

---

### ✔️ Step 2 — Add Your Files

Inside your folder, add:

```
YourName.html
YourName.css
YourName.js  (optional)
```

and create an assets folder:

```
/Assets/Images/
```

---

### ✔️ Step 3 — Add Your Photo

Place your picture here:

```
/students/YourRoll/Assets/Images/
```

---

### ✔️ Step 4 — Link Your Page in students.html

Inside `students.html`, your card should link to your page.

Example:

```html
<a href="students/SMIT-421836/Ahmed.html" class="student-card">
    <img src="students/SMIT-421836/Assets/Images/profile.jpg" alt="Ahmed">
    <h3>Ahmed</h3>
</a>
```

---

# 🎯 Goal of This Project

This project teaches:

* ✔️ How to organize a real project
* ✔️ How to structure folders properly
* ✔️ How to build individual pages inside a shared website
* ✔️ How to use HTML & CSS professionally
* ✔️ How to collaborate as a batch

No React.
No backend.
Just clean **HTML + CSS** learning.

---

# 🙌 Final Notes

This is a learning project.
Keep your files clean, named properly, and well-organized.


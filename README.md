# Vertex Studio

A team portfolio and project tracker built by 4 classmates learning web development together.
The site introduces the team, showcases each member's work, and documents all projects.

---

## Repository Structure

```
vertex-studio/
├── index.html              # Team home page
├── members.html            # All members overview
├── projects.html           # All projects overview
├── contact.html            # Contact page
│
├── css/
│   └── global.css          # Shared styles (navbar, footer, typography, etc.)
│
├── js/                     # Shared JavaScript (when needed)
│
├── images/                 # Shared team site assets (logo, backgrounds, etc.)
│
├── members/                # Individual member profile pages
│   ├── zaid/
│   │   └── index.html      # Zaid's profile + his projects listed
│   ├── younus/
│   │   └── index.html
│   ├── omar/
│   │   └── index.html
│   └── nasim/
│       └── index.html
│
└── projects/               # All class/team projects
    └── project-javapoint/
        ├── index.html
        ├── css/
        └── images/
```

---

## Structure Rules

**Team website pages** (`index.html`, `members.html`, etc.) live at the **repo root**.

**Each project** in `projects/` follows this internal layout:
```
project-name/
├── index.html      # Project entry point (always at project root)
├── page2.html      # Additional pages also at project root
├── css/
│   ├── global.css  # Styles shared across all pages in this project
│   └── page2.css   # Page-specific styles
├── js/
└── images/
```

**Member pages** in `members/` link back to the root using `../../` paths and can link to any project via `../../projects/project-name/index.html`.

---

## Projects

| Project | Description | Folder |
|---------|-------------|--------|
| JavaTPoint Clone | A clone of the JavaTPoint tutorial website | [projects/project-javapoint](./projects/project-javapoint/) |

---

## Team

| Name | GitHub |
|------|--------|
| Mohammad Younus | https://github.com/MohammadYounusM |
| Omar Qaljaei | https://github.com/Omar-sul-khil |
| Nasim Sohail | — |
| Zaid Nayeb | https://github.com/ZaidNayeb |

---

## Contributing

1. Create a new branch for your work: `git checkout -b your-branch-name`
2. Make your changes inside your project folder
3. Push and open a Pull Request to `main`
4. Get at least one teammate to review before merging

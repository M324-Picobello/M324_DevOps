# Lernjournal Tristan Evans

**Name:** Tristan Evans
**Class:** AP23d
**Project period:** 13.11.2026 – 29.01.2027

Team Meetings files led by me: 

---

## Day 1 – 2026-11-16

| Time          | Duration | Location |
|---------------|:--------:|----------|
| 08:10 – 11:40 | 4 School Hours| School TBZ|

**Task:** P1 – Projekt Setup und Infrastruktur

### Goals

- [x] Get all described Work in the [P1 – Projekt Setup und Infrastruktur](https://gitlab.com/ch-tbz-it/Stud/m324/-/blob/main/Projekt/P1_Praxis_Infrastruktur.md) done as a team.

### Work Done

| Activity                                        | Result                                                  |
|-------------------------------------------------|---------------------------------------------------------|
| Set up the Kanban board with Tim Kunz           | Board with phases (e.g. To Do, In Progress, Review, Done) |
| Set up the Git repository with Tim Kunz         | Repository with the required structure|
| Configured Maven and starter Java structure for the project| Working `pom.xml` and build setup|
| Created the base project structure together| Folders `Theorie/`, `Dokumentation/`, `Code/` and `Readme.md` |
| Team strategy planning| First plan for how the group will proceed|

Together with Tim Kunz I helped setting up the Github repository and the Kanban board in it according to the P1 requirements. My main part was the **Maven configuration** and the **base structure** of the project. In hindisght though, the situation developed so that I spoke alot and tried connecting the teams together with technologies.
I even planned and led a Team meeting and the end of the morning, which even surprised me, since I don't do much leading in projects. I made the decisions about Maven and the other project tools together with my teammates and included their ideas.

### What I Learned

- **Maven setup:** How to configure a project with Maven so the whole team can build it the same way.
- A `.gitignore` should be created **before** the first commit, so be more careful next time.
- **Removing tracked files:** A folder that was already committed is not removed by just adding it to `.gitignore`.
- **Scope of a task:** Working only on what the current task asks for keeps the work focused.

### Problems and Solutions

| Problem                                  | Cause                                         | Solution                                                        | Status |
|------------------------------------------|-----------------------------------------------|-----------------------------------------------------------------|--------|
| The `.idea/` folder was committed to the repo | I forgot to create a `.gitignore` before the first commit | Creating a `.gitignore` | Open   |

```
# .gitignore
.idea/
*.iml
target/
```

### Reflection

> **Went well:** Setting up Maven and the other project tools went well. We coordinated our ideas as a team and found a good overall strategy for the group.
>
> **Didn't go well:** I worked too fast during the setup and forgot the `.gitignore`. Now I have to clean up the repository. As a team we also planned much too far ahead (might be a good thing though). Strategy planning is part of the tasks after P1, so we spent time on things that were not part of the current task yet.
>
> **Next time:** I will work more slowly during setup and check the basics (like `.gitignore`) before the first commit. Before planning, I will check what the current task actually asks for, so we stay within its scope.

### Next Steps

1. Create the `.gitignore` and remove `.idea/` from the repository
2. Lead the team meeting at 11:20
3. Link all documents, the time log and the Lernjournal in the `Readme.md`
4. Prepare the tool choice reasoning for the team discussion FG1 (week 2)

*Sources:* P1 – Projekt Setup und Infrastruktur

---

## Day 2

# Module 1

Module one consists of two separate **Git** and **Build tools** tasks. 
**Build tools** task focuses on Gradle usage

## Table of contents

1. [Build tools](#build-tools)
   - [Gradle questions](#gradle-questions)
2. [Git](#git)
   - [Git questions](#git-questions)

## Build tools

Task requires you to:
1. Install gradle
2. Create simple java lib
3. Create multi-module project
4. Use custom lib inside your multi-module project

### Gradle questions:

🌱 [ 0 ] Zero level

1. Definition of Build tools
2. Name any Java build tool you know
3. How to build project using gradle CLI?

---

🪴 [ 1 ] Novice level

1. Why not to just compile java project using `javac`?
2. Gradle pros
3. Gradle cons
4. How to init gradle project using CLI?
5. Latest stable Gradle version
6. What is dependency?
7. How to add dependency?

----

🌳 [ 2 ] Intermediate level

1. What is `gradlew`?
2. What is gradle task?
3. What is gradle plugin?
4. How to not repeat same value in many places inside `build.gradle`
   and move it to constant?
5. Name several basic gradle tasks
6. Describe gradle `java` plugin
7. What is Gradle Daemon?
8. Compare `api`, `implementation`, `testImplementation` and
   `runtimeOnly` configurations

---

🍁 [ 3 ] Advanced level

1. Describe how gradle resolves dependencies versions conflicts
2. Describe build steps for multi-module project
3. How can you extend an existing task?
4. How to generate `gradlew` for an existing project?
5. Where to change your project's `gradlew` version
6. Tell about gradle test reports

## Git 

Task consists of two sub-tasks:
1. Create simple local repo and get to know the branches.
2. Some advanced gir workflow including remote repositories.

### Git questions:

🌱 [ 0 ] Zero level

1. What is vcs
2. What is Git
3. Name some other vcs
4. How to create commit

---

🪴 [ 1 ] Novice level

1. Git pros
2. Tell the full flow of creating new file and committing it
3. What is git index
4. Explain branch
5. Explain commit
6. Difference between Git and GitHub?
7. Tell about `vim`

----

🌳 [ 2 ] Intermediate level

1. Why is branch considered to be *cheap* and *lightweight* comparing to other vcs?
2. Tell about CVCS
3. Tell about DVCS
4. Describe `merge` mechanic
5. Describe `rebase` mechanic
6. Git `tags`
7. Explain `cherry-pick`
8. Explain `patch`
9. Explain `reset`
10. How to edit commit that is already created?
11. Why should several developers work in separate branches, not in the one? When 
should work in one branch?
12. Describe interactive rebase options and possibilities
13. Explain git repository possible file states (unversioned, modified and so on...)

---

🍁 [ 3 ] Advanced level

1. Ways to concatenate commits
2. `merge` vs `rebase`
3. How does git store files?
4. Describe contents of .git folder
5. How to add gitignore files only for local repository only, not for a whole project's .gitignore
6. Explain Git trees
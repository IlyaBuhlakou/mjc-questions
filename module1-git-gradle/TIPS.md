# TIPS

There I will collect some common advices from discussions.

## Commits and pull-requests

### Commits

Commits should be atomic. But not too granular. Some tasks might 
consist of one commit. Other require more of them. For example: 
- Fixing 1 common bug in 10 files should be done as 
1 commit since these changes are related even they are from different files.
- Pull-request's comments should be fixed in one commit, so it will be easier for other's to see 
what's changed since last pr.
- Implementing task like "Create two utils libraries" might be done in four commits:
  1. Add Utils1
  2. Add Utils1Test
  3. Add Utils2
  4. Add Utils2Test

### Pull-requests


- It's usually should be like 5 commits each pull-request (pr) 
for a big feature and 1 for a small.
- After opening a **pr** all newly pushed commits will be automatically attached 
to **pr**

So the perfect workflow for the first module task might look like this:
1. (checkout **module1** branch) - Create initial commit (build.gradle, gradlew.jar, gradlew, gradle.properties, 
README.md and so on)
2. Several commits with changes. Don't create too many commits. Try to generify task scopes and create commits 
according to them. Example commits for module 1 gradle task: 
   1. "Init library project"
   2. "Add StringUtils"
   3. "Add StringUtilsTest"
   4. "Init multi-project project"
   5. "Add core Utils class"
   6. "Add api App class and main"
3. Open pull-request from **module1** to **master**
4. Some comments are added to pull-request
5. (**module1**) - push 1 commit with fixes
6. Some comments are added to pull-request again
7. (**module1**) - push another commit with fixes

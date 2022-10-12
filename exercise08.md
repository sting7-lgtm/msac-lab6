# Exercise 8 - Viewing changes before committing

1. Ensure your working directory is clean

2. Add text to any one of your files

3. Delete different text from another of your files

4. Look at `git status`

5. View all the changes you've made

        git diff

6. Does the following command return anything?

        git diff --staged

        "No"

7. Add one of your changed files to the index

        git commit add <changed file>

8. What do these commands show?

        git diff
        git diff --staged

"git diff shows:
diff --git a/vegetables.txt b/vegetables.txt
index e51eeba..9c164d1 100644
--- a/vegetables.txt
+++ b/vegetables.txt
@@ -2,4 +2,8 @@ tomato

 carrot

-cabbage
\ No newline at end of file
+cabbage
+
+broccoli
+
+Melamela
\ No newline at end of file"

"git diff --staged shows:
diff --git a/fruits.txt b/fruits.txt
index f1dff2d..eb21504 100644
--- a/fruits.txt
+++ b/fruits.txt
@@ -1,5 +1,3 @@
 apple
 banana
 tomato
-blueberry
-strawberry
\ No newline at end of file"

9. Add the other changed file to the index

        git commit add <other changed file>

10. What do these commands show?

        git diff
        git diff --staged

"git diff shows nothing.  

git diff --staged shows:
diff --git a/fruits.txt b/fruits.txt
index f1dff2d..eb21504 100644
--- a/fruits.txt
+++ b/fruits.txt
@@ -1,5 +1,3 @@
 apple
 banana
 tomato
-blueberry
-strawberry
\ No newline at end of file
diff --git a/vegetables.txt b/vegetables.txt
index e51eeba..9c164d1 100644
--- a/vegetables.txt
+++ b/vegetables.txt
@@ -2,4 +2,8 @@ tomato

 carrot

-cabbage
\ No newline at end of file
+cabbage
+
+broccoli
+
+Melamela"

11. Commit the changes

12. Check that your working directory is clean

13. Create a new file named `clothing.txt`

14. Does the new untracked file show up in git diff?

        git diff

        "It does not"

15. Add and commit the new file

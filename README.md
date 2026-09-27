# Java Team Git Workflow Lab

A Northeastern University team lab (Team 15) for practicing a feature-branch and pull-request workflow in Java.

## Workflow

Each of the three team members:

1. Created a branch from `main` (`feature-member1`, `feature-member2`, `feature-member3`).
2. Added their own class (`Member1`, `Member2` or `Member3`) on that branch.
3. Opened a pull request, got it reviewed and merged it into `main`.

`Main.java` then calls all three classes. The merged pull requests are listed under the [Pull requests](../../pulls?q=is%3Apr+is%3Aclosed) tab.

## Run

```bash
cd lab_6
javac -d out src/*.java
java -cp out Main
```

Expected output:

```
Hello from Member 1!
Hello from Member 2!
Hello from Member 3!
```

You can also open `lab_6/` as a NetBeans project.

## Team

[@Jason0173](https://github.com/Jason0173) · [@KKkaiiiiiii](https://github.com/KKkaiiiiiii) · [@q34tiug92](https://github.com/q34tiug92)

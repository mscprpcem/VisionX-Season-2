# Week 3 Quiz - Web Development & Git/GitHub

### Q1. A developer is preparing a registration form and wants an ID field that cannot be edited by the user. Which statements about HTML form controls are correct? Select all that apply.

A) readonly keeps the value eligible for submission  
B) disabled always submits the field value  
C) readonly prevents the user from editing the value  
D) disabled inputs are normally excluded from form submission  

**Answer:** A, C, D

**Explanation:** readonly prevents editing while the value can still be submitted. disabled controls are normally not submitted. The statement that disabled always submits the value is false.

---

### Q2. A developer wants to keep a block of HTML in the document but prevent it from rendering until JavaScript instantiates it. Which statements are correct? Select all that apply.

A) `<template>` is designed for this purpose  
B) `<section>` automatically provides the same lazy-instantiation behavior  
C) `<template>` content can later be instantiated with JavaScript  
D) `<template>` content is not rendered as normal page content immediately  

**Answer:** A, C, D

**Explanation:** The HTML `<template>` element stores inert client-side content that is not rendered immediately and can later be instantiated through JavaScript.

---

### Q3. Consider this Flexbox layout: .container { display: flex; flex-direction: row; justify-content: center; align-items: flex-start; }. The developer wants to change how items are positioned vertically without changing horizontal distribution. Which property should be modified?

A) justify-content  
B) align-items  
C) flex-direction  
D) align-content  

**Answer:** B

**Explanation:** With a row direction, the cross axis is vertical, so align-items controls alignment on that axis.

---

### Q4. A box uses ``box-sizing: border-box``. Which statements correctly describe how its declared width works? Select all that apply.

A) The declared width includes padding  
B) The declared width refers only to the content area  
C) Padding and border are accounted for inside the specified width  
D) The declared width includes the border  

**Answer:** A, C, D

**Explanation:** With border-box, the specified width includes the content, padding, and border; they are not added outside the declared width.

---

### Q5. A developer sets .box { width: 300px; padding: 20px; border: 5px solid black; `box-sizing: border-box`; }. They claim the element will be 350px wide because padding and border are added to width. What is correct?

A) Correct, because padding is always added to width  
B) Correct, because border is always added to width  
C) Incorrect, because border-box includes padding and border within the specified width  
D) Incorrect, because border-box removes both padding and border  

**Answer:** C

**Explanation:** With border-box, the declared width includes the content, padding, and border.

---

### Q6. A navigation bar uses nav { `position: sticky; top: 0;` }. At first it behaves like a normally positioned element. What happens when scrolling reaches the specified threshold?

A) It immediately becomes permanently fixed to the viewport  
B) It becomes absolutely positioned relative to the nearest grid container  
C) It remains static and never changes position  
D) It sticks at the specified threshold while scrolling  

**Answer:** D

**Explanation:** A sticky element behaves normally until the threshold is reached, then sticks relative to its scroll container.

---

### Q7. A developer runs `console.log(typeof typeof 1);` and expects number. What is actually printed?

A) "string"  
B) "undefined"  
C) "number"  
D) "object"  

**Answer:** A

**Explanation:** typeof 1 returns the string "number"; applying typeof to that string returns "string".

---

### Q8. A developer writes `console.log([] + []);` and expects an empty array because two empty arrays are being added. What is actually printed?

A) []  
B) 0  
C) undefined  
D) ""  

**Answer:** D

**Explanation:** Arrays are converted to primitive string values during +, so two empty arrays produce an empty string.

---

### Q9. A JavaScript developer wants comparisons that do not perform implicit type coercion. Which statements are correct? Select all that apply.

A) Strict equality (===) compares value and type  
B) Loose equality (==) can perform type coercion  
C) The === operator is strict equality  
D) The = operator performs assignment  

**Answer:** A, B, C

**Explanation:** The === operator checks both value and type without implicit coercion. The == operator may coerce types. The = operator is assignment.

---

### Q10. A developer receives values from user input and wants to compare both their value and data type without implicit type coercion. Which operator should be used?

A) ==  
B) =  
C) Strict equality (===)  
D) !==  

**Answer:** C

**Explanation:** The strict equality operator === compares value and type without implicit type coercion.

---

### Q11. An inner JavaScript function still accesses a variable from its outer function even after the outer function has already returned. Which mechanism explains this behavior?

A) Hoisting  
B) Event Loop  
C) Prototype Chain  
D) Closure  

**Answer:** D

**Explanation:** A closure allows an inner function to retain access to variables from its outer lexical scope.

---

### Q12. Three asynchronous operations are running: A succeeds, B fails, and C succeeds. You need a result showing the outcome of every operation even though one failed. Which method is most appropriate?

A) Promise.all()  
B) Promise.resolveAll()  
C) Promise.allSettled()  
D) Promise.first()  

**Answer:** C

**Explanation:** Promise.allSettled resolves after every input promise settles, reporting both successes and failures.

---

### Q13. A developer has completed a feature on a separate branch and wants teammates to review the changes before they are merged into the main branch. Which statements about the GitHub workflow are correct? Select all that apply.

A) A Pull Request can be used to request review and merging of code changes  
B) A Pull Request is the same as downloading a repository  
C) Reviewers can inspect the proposed changes before merging  
D) A Pull Request is commonly opened to propose changes from one branch into another  

**Answer:** A, C, D

**Explanation:** A Pull Request is used to propose code changes for review and possible merging. It is not a command for downloading a repository.

---

### Q14. You are working on a feature branch and need to move to another existing branch before continuing your work. Which Git command is designed for switching branches?

A) git switch  
B) git merge  
C) git fetch  
D) git stash  

**Answer:** A

**Explanation:** git switch is used to switch to another branch. git merge combines branch histories, git fetch downloads remote updates, and git stash temporarily saves uncommitted changes.

---

### Q15. You have uncommitted changes in your working directory, but you need to temporarily set them aside so you can work on another task without committing the unfinished changes. Which Git command is most appropriate?

A) git revert  
B) git stash  
C) git tag  
D) git clone  

**Answer:** B

**Explanation:** git stash temporarily saves uncommitted changes so you can switch tasks and return to them later.

---

### Q16. You want to download remote Git changes for inspection without automatically integrating them into your current branch. Which statements are correct? Select all that apply.

A) git fetch and git pull are always identical in effect  
B) git pull generally downloads and integrates remote changes  
C) fetch is useful when you want to inspect remote updates before integrating them  
D) git fetch downloads remote information without automatically merging it  

**Answer:** B, C, D

**Explanation:** git fetch retrieves remote updates without automatically merging them. git pull generally performs a fetch followed by integration. The two commands are not identical in effect.

---

### Q17. You modified index.html, style.css, and password.txt, but you want only the first two files included in the next commit. What is the main purpose of the staging area here?

A) It permanently stores all three files  
B) It allows you to select which changes will be included in the next commit  
C) It automatically uploads selected files to GitHub  
D) It creates a separate GitHub repository  

**Answer:** B

**Explanation:** The staging area lets you choose the changes that will be part of the next commit.

---

### Q18. Two developers modify the same part of the same file differently. When Git tries to merge their branches, it cannot determine which version should be kept. What has occurred?

A) Merge conflict  
B) Repository corruption  
C) Remote failure  
D) Branch deletion  

**Answer:** A

**Explanation:** A merge conflict occurs when Git cannot automatically reconcile competing changes.

---

### Q19. A developer has committed a feature locally and now wants the commit to appear on the configured remote Git repository. Which statements are correct? Select all that apply.

A) The local commit must already exist before it can be pushed  
B) git clone is not the command used to upload an existing local commit  
C) git fetch uploads local commits to the remote  
D) git push uploads local commits to the remote  

**Answer:** A, B, D

**Explanation:** git push uploads local commits to the remote repository. The commit must exist locally first. git fetch downloads remote information, and git clone creates a local copy rather than uploading an existing local commit.

---

### Q20. You created a branch, modified code, staged the changes, and committed them locally. The commit does not yet exist on GitHub. What should you do next to upload the commit to the remote repository?

A) git fetch  
B) git push  
C) git clone  
D) git pull  

**Answer:** B

**Explanation:** git push uploads local commits to the configured remote repository.

---

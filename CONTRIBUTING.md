# Contribution Guide

Follow these quick steps to submit your assignment:

### 1. Setup
To setup the repository in you local, follow the below commands:

 - Clone the forked repo:
 ```sh
  git clone git@github.com:{your_username}/GDG-FOSS-1.git

  or

  git clone https://github.com/{your_username}/GDG-FOSS-1.git
 ```

 - Set your repo as origin:

 ```sh
   git remote add origin git@github.com:{your_username}/GDG-FOSS-1.git

   or

   git remote add origin https://github.com/{your_username}/GDG-FOSS-1.git
 ```

  - Set the main repo as upstream:

  ```sh
    git remote add upstream git@github.com:AkshajSonar/GDG-FOSS-1.git

    or

    git remote add upstream https://github.com/AkshajSonar/GDG-FOSS-1.git
  ```

### 2. Branching (⚠️IMPORTANT)
Create a new branch using **your College Roll Number**.
```bash
git checkout -b <your-roll-number>
```

### 3. The Work
Open the repository in your editor and complete the two tasks:
* Fill out **`PROFILE.md`**

Add and commit this change:

```sh
  git add .
  git commit -m "Add information in PROFILE.md"
```

* Write your tech deep-dive in **`TECHNICAL_DOCUMENTATION.md`**

```sh
  git add .
  git commit -m "Add information in TECHNICAL_DOCUMENTATION.md"
```

*(Reminder: 100% human-written content only. AI generation = Disqualification.)*

### 4. Submit

Push your changes to origin
```bash
git push origin <your-roll-number>
```
Go to **github -> your repository -> create a PR** to the main upstream repository.

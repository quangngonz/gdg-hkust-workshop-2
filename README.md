# GDG@HKUST - Workshop 2: Git

Welcome to the final task! The goal is to use the Git skills you've learned to add your profile to this repository.

You will follow the complete "Fork & Pull Request" workflow, which is the standard way to contribute to open-source projects.

## Your Mission

Your task is to add two files to this project in a new branch and then open a Pull Request.

1.  A **JSON file** named `data.json` in the `participants/` directory to be filled with your information.
2.  A **profile picture** in the `assets/` directory.

---

### Step-by-Step Guide

#### 1. Fork This Repository

Click the **Fork** button at the top-right of this page to create your own copy of this project on your GitHub account.

#### 2. Clone Your Fork

On your computer, clone **your forked repository**.

```bash
# Replace <your-github-username> with your actual username
git clone https://github.com/<your-github-username>/gdg-hkust-workshop-2.git
cd gdg-hkust-workshop-2
```

#### 3. Create a New Branch

Always create a new branch for your changes. Name it after your username for clarity.

```bash
# Replace <your-itsc-id> with your actual ID
git checkout -b <your-itsc-id>-submission
```

#### 4. Update Your Data File

Open your existing JSON file in the `participants/` directory — it should be named `data.json`.

- **What to do**: Edit the file and update the fields with your current information.
- **Format**: Make sure it follows this structure:

```json
{
  "name": "Your Full Name",
  "email": "your-email@example.com",
  "github_username": "your-github-username",
  "itsc": "your-itsc-username"
}
```

#### 5. Add Your Profile Picture

Add a profile picture of your choice to the `assets/` directory.

- **File Name**: Name it exactly `<your-github-username>.png` (or `.jpg`, `.jpeg`).
- **Location**: Place the image file inside the `assets/` folder.

#### 6. Commit Your Changes

Stage both of your new files and commit them with a descriptive message.

#### 7. Push Your Branch to Your Fork

Push your new branch and commit to your repository on GitHub.

```bash
# Replace <your-github-username> with the name of your branch
git push origin <your-itsc-id>-submission
```

#### 8. Open a Pull Request

You're almost done!

1.  Go to your forked repository on GitHub.
2.  You should see a banner prompting you to "Compare & pull request". Click it.
3.  Add a title like "Add Jane Doe's Profile".
4.  Click the **Create pull request** button.

### Congratulations!

You have successfully completed the workshop. Once your pull request is reviewed and merged, you have officially contributed to the project!

### Congratulations!

You have successfully completed the workshop. Once your pull request is reviewed and merged, you have officially contributed to the project!

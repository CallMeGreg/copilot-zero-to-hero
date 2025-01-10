# Welcome 👋

This guide was created for people in non-developer roles who want to start using Copilot in their day to day.

## Step 1: Install, Update, and Setup Visual Studio Code

<details>
<Summary>Click to expand</Summary>
<br>

Now that GitHub Copilot is available in GitHub.com, you don't _need_ to use an Integrated Developer Environment (IDE) like Visual Studio Code (VS Code) to use Copilot. However, VS Code offers some customization and functionality that you can't get in GitHub.com today.

If you don't have VS Code, you can [download it here](https://code.visualstudio.com/download).

If you already have VS Code, make sure you update to the latest version:
- With VS Code open, click the `Code` tab at the top left
- Select `Check for Updates...`
- If an update is available, apply it, then restart VS Code when prompted

![Screenshot 2025-01-03 at 3 04 30 PM](https://github.com/user-attachments/assets/efb6bf41-b37c-4319-aea6-261591be459f)

- In VS Code, let's create a new workspace to work through all of our exercises:
  - Select `File` --> `Open Folder...`
  - If needed, create a new folder so that you're working from a clean slate

![Screenshot 2025-01-03 at 3 52 28 PM](https://github.com/user-attachments/assets/1df15209-5cbe-4681-8092-312e700e2507)


</details>

## Step 2: Install the GitHub Copilot Extension

<details>
<Summary>Click to expand</Summary>
<br>

- Select the `Extensions` button from the left hand navigation bar

![Screenshot 2025-01-03 at 2 46 57 PM](https://github.com/user-attachments/assets/2d4614a1-3f8a-482e-9971-62b91cc3dcd6)


- Search for "**Copilot**"
- Click the `Install` button next to `GitHub Copilot`

![Screenshot 2025-01-03 at 2 47 21 PM](https://github.com/user-attachments/assets/16eebc7f-725e-4ae0-88bd-654bd0f90c65)

- In the Copilot panel on the right, select `Sign in to Use Copilot`

![Screenshot 2025-01-03 at 2 47 45 PM](https://github.com/user-attachments/assets/1aba3bb2-3867-4af4-9fba-a27c6cfef1e5)


- Select `Continue` next to your primary account

![Screenshot 2025-01-03 at 2 48 11 PM](https://github.com/user-attachments/assets/cf1999ac-855a-442d-ac85-cd023fd3e1e3)

- Select `Continue` again

![Screenshot 2025-01-03 at 2 51 38 PM](https://github.com/user-attachments/assets/194af187-e0c5-4488-aad6-6eb2e603f3c8)

</details>

## Step 3: Getting familiar with Copilot

<details>
<Summary>Click to expand</Summary>
<br>

- To ensure Copilot is properly authenticated, type "Hello" in the Copilot Chat window and hit enter.

![Screenshot 2025-01-03 at 3 39 56 PM](https://github.com/user-attachments/assets/6356229f-21fe-4a3c-be05-a0f572c782a9)

- If Copilot does not respond, or if you see an error, double check that:
  - You are authenticated with a GitHub account that has a Copilot license (click the `Accounts` icon at the bottom left)
  - You have the latest version of VS Code (click `Code` --> `Check for updates...`)
  - You have the latest version of the Copilot Extension (click `Extensions` --> `GitHub Copilot` --> `Update` or `Restart Extensions`)
  - You have restarted VS Code after applying any updates (click the `Manage` gear icon at the bottom left)
 
- Copilot has some pre-defined shortcuts called _**slash commands**_. You can view all of the available slash commands by typing `/help`.

![Screenshot 2025-01-03 at 3 47 38 PM](https://github.com/user-attachments/assets/be10b5c5-95d3-424a-9812-985d03067a60)

- Two very helpful slash commands are `/new` and `/explain`.
  - `/new` is great when you need to create many files or a folder structure for a new project.
  - `/explain` is a quick way to have Copilot teach you more about what it generated, or to have Copilot summarize a large block of text/code.

</details>

## Step 4: Draft markdown content

<details>
<Summary>Click to expand</Summary>
<br>

Sometimes you know what you want to cover, but not how you want to present it. I find that it can be easier tweaking something vs. designing from scratch.

For example, maybe you want to create a new README for your team's repository. Here are some prompts that got me to a great outline:

```
Create a template markdown file to be used as the readme for my team's GitHub repository.
It should include sections for our mission, what we do, and our team's pictures and contact information.
Include examples in each section.
```

```
Update the team picture to link to CallMeGreg's github profile picture
```

```
In the team pictures section, change the pictures to a table that also includes columns for their name, handle, and email address
```

```
Adjust the size of the picture to be smaller
```

After just a few back and forths, I was left with this markdown content:

![Screenshot 2025-01-08 at 6 09 00 PM](https://github.com/user-attachments/assets/ceea0f68-9153-4d01-94d7-b846192bc2a8)

Which looked like this in GitHub:

![Screenshot 2025-01-08 at 6 09 32 PM](https://github.com/user-attachments/assets/6e0384ec-61e4-4ed9-b5c5-3962c6fbc61f)

</details>

## Step 5: Reformat into markdown

<details>
<Summary>Click to expand</Summary>
<br>

At GitHub, I find myself writing _a lot_ of markdown between README's, issues, and discussions. However I prefer to take notes in Google Docs, and copying/pasting between the two can be _really_ ugly.

This is an area where Copilot can help take the burden of reformatting off your plate.

When converting something to markdown, try the following prompt:

```
Can you convert the following notes into markdown format?
Use bulleted lists, use formatting to bold important parts, and include emojis in titles where appropriate.

<Paste in your raw notes here>
```

For example, starting with a Google Doc that looks like this:

![Screenshot 2025-01-08 at 6 14 36 PM](https://github.com/user-attachments/assets/68478d7f-32b1-4615-b53f-d3c068174e6c)

This is what a direct copy and paste into GitHub Issues looks like ☹️

![Screenshot 2025-01-08 at 6 17 02 PM](https://github.com/user-attachments/assets/1bfc51a8-80fd-4ab9-9ed5-ec2ba45bd228)


And here's what it looks like after using the simple Copilot prompt from above 🤩

![Screenshot 2025-01-08 at 6 18 28 PM](https://github.com/user-attachments/assets/540fb3b8-9f82-428d-a2f4-1a81675e0b08)

</details>

## Step 6: Copilot reviews

<details>
<Summary>Click to expand</Summary>
<br>

On top of helping you write and format content, Copilot can review content for typos, style, and clarity.

We can also customize what Copilot looks for in its reviews by specifying review instructions.

Navigate to the VS Code `Extensions` tab and search for Copilot. Then click the `Manage` gear icon next to GitHub Copilot Chat.

![Screenshot 2025-01-10 at 10 33 25 AM](https://github.com/user-attachments/assets/43be0441-1793-4ff2-b535-13456c45790c)

Scroll down to the section labeled `Github › Copilot › Chat › Review Selection: Instructions`. Be sure to find "Review Selection", and not one of the other instructions sections for other things like code generation and test generation.

Click `Edit in settings.json`.

![Screenshot 2025-01-10 at 10 34 33 AM](https://github.com/user-attachments/assets/df87efc1-e9d4-4265-b9af-4babe768efc8)

If you're offered a quick selection, choose one of the options that start with `"text"`, then modify the instructions to your liking. Or manually update the `github.copilot.chat.reviewSelection.instructions` section to look like this:

```
    "github.copilot.chat.reviewSelection.instructions": [
        {
            "text": "Look for spelling and grammar mistakes, refine for clarity, and add emojis where appropriate."
        }
    ],
```

Save the `settings.json` file and go back to a file that you would like to review.

Highlight all of the text that wou want Copilot to review, then right click and select `Copilot` --> `Review and Comment`

![Screenshot 2025-01-10 at 10 50 46 AM](https://github.com/user-attachments/assets/4d985674-6d23-4543-ba02-636959349c54)

You can quickly apply or discard suggestions with the `Apply` and `Discard` buttons, jump between suggestions with the arrows, move a comment to that Chat window, or discard all suggestions and return to edit mode.

![Screenshot 2025-01-10 at 10 53 10 AM](https://github.com/user-attachments/assets/82a81645-29fc-422e-b166-0f52e80b50db)

</details>

## Step 7: Create an issue template
<details>
<Summary>Click to expand</Summary>
<br>

Issue templates are a great way to streamline collection of GitHub Issues in a consistent fashion.

Copilot can help elevate your issue template game by providing the boilerplate code needed for [issue forms](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms), rather than using markdown / markdown comments in your templates.

Start by prompting Copilot with a rough outline of what you want to achieve, being as specific as possible about default labels, assignees, and the form fields you want to include.

```
I want to create a GitHub issue template using an issue form.
The form will be used to capture feedback about our recent team offsite.
Include the default label "Offsite Feedback" and assign the issue to CallMeGreg.
The form should have fields for an overall rating 1-10, a text box for what went well, and a text box for what could be improved next time.
Also, include a required dropdown selection for which specific team the user is a part of: Engineering, Product, or Design.
```

Remember, Copilot might not get it exactly right the first time. Ask follow up questions to fix errors, adjust styling, add ghost text, change the order of the fields...you're the pilot!

With the prompt from above, I ended up with a new issue template that looks like this:

![Screenshot 2025-01-10 at 11 08 55 AM](https://github.com/user-attachments/assets/2fea6562-141d-41ce-900f-6e42731deaa6)

</details>

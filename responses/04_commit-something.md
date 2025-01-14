# Step 5: Commit a file

![Joyful_Orpheus](https://user-images.githubusercontent.com/18013689/113243939-38647700-9271-11eb-97d7-0c579828bab8.png)

> **Orpheus:** Heyyyyyyyy... about that new branch. Pretty nice, but like there's nothing changed in it yet. Get on that. xoxoxoxo

:tada: You created a branch!

Creating a branch allows you to make modifications to your project without changing the deployed `main` branch. Now that you have a branch, it’s time to create a file and make your first commit!

<details><summary>Commits 101</summary>

## Commits 101

When you’re finished creating or making changes to a file on GitHub, scroll to the bottom of the page. Then find the "Commit new file" section.

In the first field, type a commit message. The commit message should briefly tell contributors about the changes you are introducing to the file.

### Rules to live by for commit messages:

- Don’t end your commit message with a period.
- Keep your commit messages to 50 characters or less. Add extra detail in the extended description window if necessary. This is located just below the subject line.
- Use active voice. For example, "add" instead of "added" and "merge" instead of "merged".
- Think of your commit as expressing intent to introduce a change.

<hr>
</details>

### :keyboard: Activity: Your first commit

The following steps will guide you through the process of committing a change on GitHub.

1. Create a new file on this branch called `info.html`. You can do so using [this shortcut]({{ thePayload.repository.html_url }}/new/{{ thePayload.ref }}?filename=info.html) or manually as follows:
      - Return to the "Code" tab
      - In the branch drop-down, select "{{ thePayload.ref }}"
      - Click **Create new file**
      - In the "file name" field, type `info.html`.
1. When you’re done naming the file, add the following content to your file:

      ```html
      <!DOCTYPE html>
      <html>

      <head>
        <meta charset="utf-8">
        <title>Orpheus' Amazing Science Project</title>
        <meta name="viewport" content="width=device-width, initial-scale=1">

        <style>
          main {
            background-color: yellow;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
          }

          html {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: lightcyan;
          }
        </style>
      </head>

      <body>


        <main>
          <h1>Info Page.</h1>
          <p>This site was created for the National Science Project Compeition, by Orpheus.</p>
          <p>
            [insert a joke here later when I think of one]
          </p>
          <p><a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ">Return to main page.</a></p>
        </main>

      </body>

      </html>
      ```

1. After adding the code, you can commit the change by entering a commit message in the text-entry field below the file edit view. For guidelines on commit messages, check out the **Commits 101** drop-down, just above these instructions
1. When you’ve entered a commit message, click **Commit new file**

---
<h3 align="center">I'll respond when I detect a new commit on this branch.</h3>

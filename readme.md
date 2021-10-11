# Project Setup/Configuration

To set up the project to run on your local machine, 
you will need the following:

- Python
- A GitHub.com account
- An editor: VS Code (easiest to install), PyCharm (preferred)

## GitHub

Please go to [GitHub.com](https://www.github.com/) and sign up for an account.
I will invite you to be a collaborator on our repository.

## Mac Instructions

Python comes with the Mac OS. To make sure you have it,
open the "terminal" app on your machine.

### Step 1

Type the following into the command line:

```
python3 --version
```

Here's what I got:

![](./mac_python_version.png)

This means I have Python version 3.9.7 installed.
If you don't have the same number, that's fine, as long as it's
at least 3.6 or so. 

### Step 2

Download [GitHub desktop](https://desktop.github.com/).

If you see a warning like this, click "Open".

![](mac_open_github.png)

Now log in with your GitHub.com credentials.

![](mac_sign_in_github.png)

When you sign in online, you will probably see something like this:

![](authorize_github.png)

Click Authorize desktop.

Next, back in the GitHub desktop app, make sure your email
is the same one you used to sign up. You'll probably have 
to select it in the dropdown menu.

![](mac_configure_git.png)

If you see a popups like these, just
do what they're asking you to do.

![](mac_move_to_applications.png)
![](mac_finder_github.png)
![](mac_github_make_changes.png)

We'll come back to GitHub Desktop later.

### Step 3

Download [VS Code](https://code.visualstudio.com/). Installing this 
should be pretty straightforward.

![](mac_visual_studio_code_page.png)

Now skip past the PC Instructions to [Cloning the Repository](#Cloning the Repository).

## PC Instructions

*Will add this later*

## Cloning the Repository

Back in GitHub desktop, you should see the following screen:

![](github_desktop_get_started.png)

Click the Clone button. If you accepted the invite,
you should see the `cis200` repository.

![](github_desktop_clone.png)

If you see the option to `Pull Origin`, then click that button to pull down others' changes. Otherwise, just move on to the next step.

![](github_desktop_pull_origin.png)

## Creating a New Branch

Open the Branch dropdown to begin the process of creating a new branch.

![](github_desktop_new_branch.png)

The naming pattern for branches is `lowercase-separated-by-dashes`.
Name this your `firstname-lastname` just as an example.

![](github_desktop_create_branch.png)
![](github_desktop_name_branch.png)

At this point, any changes you make will be on **your branch**, so they will not affect others.

## Making Your Changes

In your editor (VS Code or PyCharm), find the `contributors.md` file. 
Add a new bullet point with your name.
Save the file.

![](add_to_contributors_md.png)

Back in GitHub Desktop, you should see your
changes highlighted. Green means addition.
Red means subtraction.

![](github_desktop_changes.png)

Now it's time to **commit** your changes to your branch.
Type a title into the box on the bottom left. 
The convention is to write it like a "command". 
Click on the Commit button when you're done.

![](github_desktop_commit.png)

Once you've committed your change, it's time to `publish` your branch.

![](github_desktop_publish_branch.png)

Next, create a `pull request` by clicking on the blue button in the same place.

![](github_desktop_create_pr.png)

This will open a browser window. Click on the green `Create pull request` button.

![](github_open_pull_request.png)

The last step is to request a review from me, `jack-hermanson`. Click on the `Reviewers` link, type in my name, and request a review.
![](github_reviewers.png)


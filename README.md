# Epi Coder's GitHub Basics
Get started with GitHub for Washington Department of Health use!

:warning: **READ THIS FIRST:**

> If you encounter a problem with this course, please open an [Issue](https://github.com/DOH-EPI-Coders/GitHub-Basics/issues/new).\
> Suggestions, feedback, questions, or new ideas can be shared in the [Discussions](https://github.com/DOH-EPI-Coders/GitHub-Basics/discussions).\
> If you'd like to contribute towards the development of this course, please read the [Contributor Guidelines](https://github.com/DOH-EPI-Coders/GitHub-Basics/blob/main/.github/contributing.md).

<details id=0>
<summary><h2>Getting Started</h2></summary>

**Course Overview:**

- **Who is this course for?** This training is designed for ALL WADOH GitHub enterprise users – developers, non-developers, and supervisors.
- **Topics Covered:** GitHub Basics will cover the fundamentals of GitHub use, communication, and collaboration.
- **Length of Course:** This course consists of 5 modules and will take you between 2-4 hours to complete.
- **Prerequisites:** An introduction to GitHub like this [training for the Office of Immunization](https://stateofwa.sharepoint.com/:v:/s/DOH-GitUsersGroup/ER4nGr6eN_lFm3fb6yL67S0BN3xQhNnWO92N46GBRIKg9w?e=xpC2h7) is helpful, but _not required_.

**Course tips:**

* Glossary terms will be _emphasised_ and linked to their definition. 
* This course includes optional video links. Look for the :tv: emoji and follow the link to the video.

## How to start this course

1. Right-click **Start course** and open the link in a new tab.\
   <br />[![start-course](https://user-images.githubusercontent.com/1221423/218596841-0645fe1a-4aaf-4f51-9ab3-8aa2d3fdd487.svg)](https://github.com/DOH-Epi-Coders/GitHub-Basics/generate)
2. In the new tab, follow the prompts to create a new repository.
   - For owner, choose the `DOH-Epi-Coders` organization
   - Suggested name: `GitHub-Basics-DOH-ABC1234` - i.e. replace `ABC1234` with your username
   - Use the `Internal` visibility setting
   - Click the green `Create repository from template` button\
   <br>![Create a new repository](/images/create-repo-from-template.svg)

3. After your new repository is created, wait about 20 seconds, then refresh your new repository page. Follow the step-by-step instructions in the new repository's README. [GitHub Actions](https://docs.github.com/en/actions) will automatically close this `Getting Started` and open the first module `Fundamentals`.

</details>

<!--Module 1-->
<details id=1 open>
<summary><h2>Module 1: Fundamentals</h2></summary>
Please read and follow these instructions carefully.

### 1.1  What is Git and GitHub?
**Git** is software you install on your computer that enables you to track the history of changes to files – known as a version control system or VCS. This can be used individually or collaboratively and locally or remotely. Git is often accessed with command-line, but there are graphical interfaces –called _Git clients_— that make most common tasks in Git accessible with the click of a button.

:tv: [Watch this video for an introduction on version control](https://git-scm.com/video/what-is-version-control) (6 min)

**GitHub** is a web-platform that extends the functionality of Git. It can store Git repositories and provides additional tools for communication, collaboration, project management, and code development with Git as its core. GitHub is designed like a social media platform but for project collaboration and code development. GitHub is what we'll be focusing on in this training.

:tv: [What is GitHub](https://www.youtube.com/watch?v=pBy1zgt0XPc) (3 min)
:tv: [Watch this introduction on GitHub from the GitHub Team](https://www.youtube.com/watch?v=w3jLJU7DT5E) (4 min)

### 1.2  How are staff at WADOH using these platforms?
WADOH staff are encouraged to store and collaborate on their code projects using GitHub. Our goal is for all projects utilizing code to be stored on and utilized from GitHub. Here's are some examples of how teams are making use of the platform:
- As a convenient location to store, document, share, and transfer projects
- Collaborating on complex code development with GitHub's project management tools and workflows
- Capturing feedback directly from stakeholders and using it to manage tasks for current or future projects
- Integrating GitHub's version control and automation with other cloud applications in CEDAR
- Creating internal websites
- Creating Q&A discussions for documenting questions and solutions
- As a means to reduce silos, share knowledge, and establish standard best practices

### 1.3  WADOH GitHub enterprise conditions of use
Please read the conditions of use for our enterprise GitHub outlined here before continuing with this training:   
   
>**Do not store data above Category 2 – See [DOH Data Classification Matrix](https://stateofwa.sharepoint.com/sites/DOH-hts/ITSO/_layouts/15/Doc.aspx?sourcedoc=%7BC38FF650-CF32-44A1-80BE-B390B816C2B3%7D&file=_Data%20Classification%20Matrix.docx&action=default&mobileredirect=true)**\
  >  Non-sensitive, publicly available data only\
  >  Absolutely no PII, sensitive health information, etc.
   
> **Do not upload code or other files containing credentials – Such as:**\
  >  API Keys, OAuth tokens, passwords, usernames, or other credentials\
  >  Server connection files or login information
   
> **We cannot create Public repositories**\
  >  Repos should be **Internal** and **Private** visibility only; public repos are disabled by enterprise policy
   
> **All members must abide by Washington State Department of Health policies and procedures and applicable State and Federal laws.**
   
:bulb: Questions about these guidelines and how or when to apply them can and should be asked in the [Discussions](https://github.com/DOH-EPI-Coders/GitHub-Basics/discussions).
   
### 1.4  GitHub interface

</details>

<!--Module 2-->
<details id=2>
<summary><h2>Module 2: Communication</h2></summary>

GitHub allows us to preserve conversations, create documentation, and provide feedback in ways our other workplace productivity tools cannot. GitHub can and should be used for planning projects, tracking tasks, and collaborating with stakeholders during the development of a code product. This module aims to familiarize GitHub users – whether their role is to develop code or not— with the means to communicate effectively using GitHub.
   
There are a few things we'll need to know to get started on this module:

<!-- content borrowed from https://github.com/skills/introduction-to-github-->
>**What is a repository?** A [_repository_](https://docs.github.com/get-started/quickstart/github-glossary#repository) is a project containing files and folders. A repository tracks versions of files and folders. For more information, see [About repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories).  
<!--📺 [Video: NEEDS NEW VIDEO]()-->

<!-- content borrowed from https://github.com/skills/introduction-to-github-->
>**What is a branch?** A [_branch_](https://docs.github.com/en/get-started/quickstart/github-glossary#branch) is a parallel version of your repository. By default, your repository has one branch named `main` and it is considered to be the definitive branch. Creating additional branches allows you to copy the `main` branch of your repository and safely make any changes without disrupting the main project. Many people use branches to work on specific features without affecting any other parts of the project.
>  
>Branches allow you to separate your work from the `main` branch. In other words, everyone's work is safe while you contribute. For more information, see [About branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches).  
<!--📺 [Video: NEEDS NEW VIDEO]()-->

>**What is Markdown?** [_GitHub-Flavored Markdown_](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) is a lightweight syntax for communicating on GitHub. You can format text to add heading, lists, bold, italics, tables, and many other stylings. You can use Markdown most places around GitHub:
>
>- Files with the `.md` or `.markdown extension` like READMEs
>- Comments in [issues](https://docs.github.com/issues/tracking-your-work-with-issues/about-issues), [pull requests](https://docs.github.com/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests), and [discussions](https://docs.github.com/discussions/collaborating-with-your-community-using-discussions/about-discussions)
>- Sharing snippets of text in [Gists](https://docs.github.com/github/writing-on-github/editing-and-sharing-content-with-gists/creating-gists)
>- Pages in repository [wikis](https://docs.github.com/en/communities/documenting-your-project-with-wikis/about-wikis)
>  
>Take a moment to skim GitHub's [basic markdown syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) for formatting your communications on GitHub before moving on to submodule _2.1 - GitHub READMEs_.

<details id=2.1>
<summary><h3>2.1 - GitHub READMEs</h3></summary>

:book: [About READMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)  |  :book: [Writing on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
   
>**What is a README?** A README is text file containing information about the files in a repository that is typically the first file a visitor to a repository will see. A README file helps you share expectations and manage contributions to your project.

- Talk about creating them/how they are created
- Link to READMEs
   
#### What should a README include?
A specific format won't be suggested here – READMEs are flexible to whatever a repository's contributors have deemed useful! However, here are some helpful guidelines to what you should expect when creating, reviewing, or reading READMEs:
   
   - A title and description of what the project is for
   - Instructions for how to develop, use, and test the code
   - Instructions for how people can help (if this is complex, you might use a [_contributing.md_](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors))
   - List the contact information of the maintaining team and stakeholders as well as where to ask questions

:bulb: If a README gets too long, consider using Wikis or hyperlink to other markdown files

#### Using Markdown to Make a README Readable
GitHub markdown can help organize your README in a way that makes it referenceable and readable. At a minimum, you should familiarize yourself with:
   
1. [Headers](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#headings)
   
   ```
   # H1
   ## H2
   ###### H6
   ```
   
2. [Styling Text](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text)
   
   ```
   **bold**
   _italic_
   ~~strikethrough~~
   <ins>underline</ins>
   ```
   
3. [Hyperlinks](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links)
   
   ```
   [Text to be shown](URL Address)
   [GitHub Basics](https://github.com/DOH-EPI-Coders/GitHub-Basics)
   ```
   
4. [Including Images](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images) :warning: `Be mindful of PII!`
   
   ```
   
   ```   
   
5. [Code Blocks](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)
   
   ```
   ```R
   # Some comment
   some_R_function()
   ```
   ```

#### **Activity**: Create a new README file
   
<img src="https://img.icons8.com/ios-glyphs/30/1A1A1A/1.png"/> Open the `Code` tab of your repository in a new browser tab and create a new branch\
<img src="https://img.icons8.com/ios-glyphs/30/1A1A1A/2.png"/> After creating your new branch, click the `Add File` button → Click `Create File` to open a blank file editor. In the name box, type `README-2.md`.\
<img src="https://img.icons8.com/ios-glyphs/30/1A1A1A/3.png"/> Add a _header_ in the editing box called `GitHub Basics`. Any header level is fine.\
<img src="https://img.icons8.com/ios-glyphs/30/1A1A1A/4.png"/> Add some text below your header line and style it with some of the markdown you've learned.\
<img src="https://img.icons8.com/ios-glyphs/30/1A1A1A/5.png"/> Preview your document by clicking the Preview tab in the New File interface.\
<img src="https://img.icons8.com/ios-glyphs/30/1A1A1A/6.png"/> If your markdown works as intended, scroll to the bottom of your new file and add a commit message. Click `Commit` when you are ready.
<!--<img src="https://img.icons8.com/ios-glyphs/30/1A1A1A/7.png"/>-->
</details>

<details id=2.2>
<summary><h3>2.2 - GitHub Issues</h3></summary>
   
:tv: [What is GitHub Issues?](https://www.youtube.com/watch?v=6HWw7rhwvtY)  |  :book: [About Issues](https://docs.github.com/issues/tracking-your-work-with-issues/about-issues)  |  :earth_africa: [Explore GitHub Issues Features](https://github.com/features/issues)

>**What is an Issue?** Issues are suggested improvements, tasks or questions related to the repository. Issues can be created by anyone (for public repositories), and are moderated by repository collaborators. Each issue contains its own discussion thread. You can also categorize an issue with labels and assign it to someone.   

Issues is an accessible way for all participants in a project to contribute while allowing developers to organize and track these contributions alongside their code and workflows.
   
   - End-users that run into problems can document them and developers can ask for feedback directly
   - Stakeholders providing subject-matter-expertise can weigh in on developer questions
   - Supervisors can add issues to (:tv: GitHub Projects, boards, and tables)[https://www.youtube.com/watch?v=yFQ-p6wMS_Y] for tracking and following up
   - Developers can familiarize with progress on an Issue or leave notes for other developers
   
Commonly used markdown in Issues includes:
  
  1. Task lists
  2. Mentioning other users or teams
  3. Mentioning other Issues, Pull Requests, or Discussions
  4. Including Screenshots

Issues are very flexible to the unique needs of each project. Their utility makes them invaluable for collaboration. To the right of the Issue comment box, you'll find:

   `Assignees` Issues can be assigned to a GitHub user\
   `Labels` Repository owners might use a labelling system to help sort, search, or identify at a glance what Issues are for and what work needs to be done to resolve them\
   `Projects` Issues can be added to existing Projects\
   `Milestone` Milestones can be created for planning due dates or other goals for completing sets of Issues\
   `Development` is where developers can quickly create _issue branches_ for beginning work on an Issue\
   `Notifications` allow collaborators to get updates for an Issue

#### Activity: Create an Issue and use GitHub markdown
   
   
</details>

<details id=2.3>
<summary><h3>2.3 - GitHub Discussions</h3></summary>
   
:tv: [What is GitHub Discussions?](https://www.youtube.com/watch?v=bErGYN3Ljz8)  |  :book: [Discussions - Quickstart](https://docs.github.com/en/discussions/quickstart)  |  :book: [About Discussions](https://docs.github.com/discussions/collaborating-with-your-community-using-discussions/about-discussions)  |  :earth_asia: [Explore GitHub Discussions Features](https://github.com/features/discussions)

>:warning: Discussions are not enabled by default in a repository or in an organization. See [Enabling Discussions On Your Repository](https://docs.github.com/en/discussions/quickstart#enabling-github-discussions-on-your-repository)


- Why and when to use discussions in your project
For more information on best practices when using Discussions, see [Organizing Discussions](https://docs.github.com/en/discussions/quickstart#organizing-discussions)
</details>

<details id=2.4>
<summary><h3>2.4 - GitHub Pull Requests</h3></summary>
   
>**What is a Pull Request?** Pull requests are proposed changes to a repository submitted by a user and accepted or rejected by a repository's collaborators. Like issues, pull requests each have their own discussion forum.

- Pull requests introduction for non-developers
- Markdown in Pull Requests (review)
</details>

<details id=2.5>
<summary><h3>2.5 - GitHub Markdown Files</h3></summary>
- Creating markdown files
- Sharing markdown files
- Linking to markdown files in other markdown files
</details>

<!-- End of Module 2-->
</details>

<!--Module 3-->
<details id=3>
<summary><h2>Module 3: Repositories</h2></summary>

- New Repository
- READMEs + Best Practices
- .gitignore
- Configuring for collaboration
- Tags & Releases

</details>

<!--Module 4-->
<details id=4>
<summary><h2>Module 4: GitHub Flow</h2></summary>

- Branch
- Commit
- Pull Request
- Review
- Merge

</details>

<!--Module 5-->
<details id=5>
<summary><h2>Module 5: Collaboration</h2></summary>

- Assigning Issues
- Labeling
- Milestones
- GitHub Projects
  
</details>

<!--Module 6-->
<details id=6>
<summary><h2>Course Completion</h2></summary>

- Congrats!
- Summary
- Next Steps
- Give us [Feedback](https://github.com/DOH-EPI-Coders/GitHub-Basics/discussions) or [report a problem](https://github.com/DOH-EPI-Coders/GitHub-Basics/issues)
- Further reading/additional resources
  - GitHub Glossary

</details>

<a target="_blank" href="https://icons8.com/icon/">Icons by Icons8</a>

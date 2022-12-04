# SFFA SOP Repo

This is the repository for the Science Fiction Fantasy Alliance (SFFA) Standard Operating Procedures (SOPs).

## Usage

The SOPs are written in Markdown format with YAML front matter meta data. These documents may be viewed and edited through GitHub's web interface, or by cloning the repository and editing the files locally through several supported Markdown editors.
    - [vscode](https://code.visualstudio.com/)
    - [Obsidian](https://obsidian.md/)

### Editing

Editing the SOPs requires a GitHub account. If you do not have one you can create a free account [here](https://github.com/join). With an account, you can now edit the SOPs directly through GitHub's web interface by navigating to the document you wish to edit and clicking the pencil icon in the top right corner of the document. Once you have made your changes you can commit them by clicking the green "Commit changes" button at the bottom of the page including information about the change.

Editing can also be done through GitHub's web tools which can be used [here](https://github.dev/Sci-Fi-Fantasy-Alliance/Standard-Operating-Procedures/blob/main/) you can use the extensions it recommends to edit the documents but a page refresh is required after installing an extension.

### Cloning

Cloning requires the use of Git. If you do not have Git installed you can download it [here](https://git-scm.com/downloads). Once you have Git installed you can clone the repository by opening a terminal and navigating to the folder you wish to clone the repository into. Once you are in the desired folder you can clone the repository by running the following command:

    git clone https://github.com/Sci-Fi-Fantasy-Alliance/Standard-Operating-Procedures.git

With git installed you can also use vscode to clone the repository. To do this open vscode and click the "Clone Repository" button on the welcome screen. A text box will appear where you can paste the repository URL. `https://github.com/Sci-Fi-Fantasy-Alliance/Standard-Operating-Procedures.git`

Once you have pasted the URL click the "Clone" button. The repository will now be cloned to your local machine.

### Editing Locally

Opening the repository in VSCode or Obsidian can be done by opening the folder you cloned the repository into. (default: `./Standard-Operating-Procedures/`)

Editing the SOPs locally requires that every commit be pushed to the remote repository. VSCode has a built-in Git interface that can be used to commit and push changes. To use this interface click the "Source Control" button in the left sidebar. This will open a new sidebar with a list of all the files that have been changed. To commit a change click the checkmark next to the file you wish to commit. A text box will appear where you can enter a commit message. Once you have entered a message click the checkmark in the top right corner of the text box. This will commit the change to your local repository. To push the change to the remote repository click the three dots in the top right corner of the sidebar and click "Push".

You can also use the terminal to commit and push changes. To do this open a terminal and navigate to the repository folder. Once you are in the repository folder you can commit changes by running the following commands:

    git commit -m "commit message"
    git push

**NOTE**: You will need to set your username and email for git to commit changes. To do this run the following commands:

    git config --global user.name "username"
    git config --global user.email "email"

You will only have to set this once.

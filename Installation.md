# Deployment

### These steps will help you set up Mkdocs on your local machine and run its development server.

* MkDocs setup

* MkDocs requires Python and pip to be installed. To check if Python is installed on your computer, type the following command at the command prompt:

`python --version` 

* The version of Python currently installed on your computer will be displayed.

If you currently don't have Python installed on your computer, go to Python.org and download an installer appropriate for your system.

* To use mkDocs, you'll need pip. If you have pip, ensure it's updated, then install mkDocs. If you don't have pip, download get-pip.py and run the following command to install it.

`python get-pip.py`

* Installing MKDocs

To install MkDocs, simply open your command prompt and enter this command.

  `pip install mkdocs`

* Creating a new project:

Run the following command in your terminal, replacing PROJECT_NAME with the name of your project.

`mkdocs new PROJECT_NAME`
`mkdocs new PROJECT_NAME`

You should find two items: a file named mkdocs.yaml and a folder named docs. The folder contains a single markdown file called index.md.

* Running the Documentation

To access the documentation, simply open your terminal and type in the following command:

`mkdocs serve`

* To access your documentation through the browser, please navigate to the http://127.0.0.1:8000/

You will see a default MKDocs page when you access the IP address.

* Overview of the MKDocs File Structure

Before proceeding, it's crucial to review the initial project structure.

 `mkdocs.yml    # The configuration file.`
    docs/
        `index.md  # The documentation homepage.`
        ...        # Other markdown pages, images and other files.
`
Here is a breakdown of what each file means:

MY-DOCSThis is the name that was given to the project. You can decide to name it anything of your choice.

.docs/This folder is designated for storing technical documentation, written exclusively in markdown format, within the selected folder.

mkdocs.ymlThis is the configuration file for your MKDocs project. It is written in YAML and controls various aspects of your documentation, including the site name, theme, navigation, and more. You can easily customize your project by modifying this file according to your preferences.

N/B: These commands will assist you in navigating through the process of building the documentation site.

mkdocs new [dir-name] - Create a new project.
mkdocs serve - Start the live-reloading docs server.
mkdocs build - Build the documentation site.
mkdocs -h - Print help message and exit.
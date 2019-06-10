Create a publication
Automatically
The leading reference management tools enable you to export your publications to the open BibTeX format. If you are new to research we recommend managing references with Zotero, a popular open source tool.

In your reference management tool, create a list of your own publications and export it as a *.bib BibTeX file.

Python 3 is a prerequisite, so please install Python 3 if it’s not already installed. Also, you should backup your website before continuing, or ensure that it is checked into Git so that you can review the changes that will be proposed by Academic’s admin tool later on.

Open your Terminal or Command Prompt app and install Academic’s admin tool:

pip3 install -U academic
Use the cd command to navigate to your website folder in the terminal.

Then import your publications with:

academic import --bibtex <path_to_your/publications.bib>
The tool is in beta status and intended purely to help assist you, so the generated output in the publication folder should be reviewed prior to publishing your site. You can also consider enhancing the output by taking a look at the front matter parameters in the files alongside the details in the Manually section below.

To contribute to the tool or submit feature requests and bug report, please check out the Academic admin tool on GitHub.
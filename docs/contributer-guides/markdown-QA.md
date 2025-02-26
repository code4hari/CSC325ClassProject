# Markdown Quality Assurance  

To ensure only high-quality Markdown files are pushed to the default branch, contributors must check their files using `Vale` and `markdownlint-cli` before committing changes.  

## Running Vale  

Before pushing, run the following command to check for style and grammar issues:  
```sh
vale .
If Vale reports any errors or warnings, review them and make necessary edits to improve clarity, consistency, and readability.

## Running MarkDownLint  
To check for formatting issues in Markdown files, run:
markdownlint .

If issues are found, you can automatically fix common errors with:
markdownlint --fix .


Ensuring Quality
Always run vale . and markdownlint . before pushing changes.
Fix any errors or warnings they report.
If unsure about a suggestion, check the repository’s documentation guidelines or ask a maintainer.
Following these steps helps maintain clear, consistent, and properly formatted documentation.
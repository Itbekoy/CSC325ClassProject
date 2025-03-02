## Introduction
You can use Vale and Markdownlint to make sure that the markdown files you push are only high quality. It flags potential  style errors and inconsistencies, which developers should remedy before pushing their changes to the default branch.

## Environment

You should open the project root in either a VSCode DevContainer or a GitHub CodeSpace. This will install both Vale and Markdownlint, as defined in the dev container config file.

## Vale Setup

To install the necessary Vale packages, run `vale sync`. 

## Run Vale and Markdownlint

To analyze all Markdown files, run both `vale` and `markdownlint`:

```
vale .
markdownlint .
```

This will produce a list of potential style errors and inconsistencies. These must before pushing changes to default branch of the repository. 
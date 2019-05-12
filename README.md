# git-log-to-markdown

Export log commits grouped by day to markdown file (optionally filtered by author and set start/end date)

## Install instructions

Copy the `git-log-to-markdown` to the `/usr/local/bin` folder for all users to have access.

## Usage

In your project simply run git-log-to-markdown and it will output a gitlog.md file.

Optional parameters

 - -a, --author       to filter by author
 - -s, --since        to select start date
 - -u, --until        to select end date

## Example output

```bash
$ git-log-to-markdown --author="Ludvig Lundgren"

# Gitlog

## 2019-05-11
 * add README
 * add gitignore

## 2019-05-12
 * add feature
```


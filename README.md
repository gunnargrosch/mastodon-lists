# Lists of Mastodon users to import

## Description

Repository contains csv files with lists of Mastodon users ready for import to your user on your Mastodon instance.

## Available lists

- [AWS Community Builders](aws-community-builders.csv): Members of the AWS Community Builders program.
- [AWS Developer Relations](aws-devrel.csv): Folks in the AWS Developer Relations organization.
- [AWS Employees](aws-employees.csv): Folks from all over AWS (including DevRel).
- [AWS Heroes](aws-heroes.csv): Members of the AWS Heroes program.
- [AWS User Group Leaders](aws-user-group-leaders.csv): User group leaders (can include CBs and Heroes).

## How to import

A GitHub Actions workflow will create a zip file with all the `csv` files in it. This zip file also contains a concatenated, sorted, and deduplicated `aws-all.csv` file which contains all the other `csv` files.
To download this artifact go to the GitHub Actions section, click on the latest workflow run, and download the `AWS-Mastodon-Lists` artifact file from it.
Alternatively clone the repository or download individual files.

1. In Mastodon web ui, navigate to `Preferences` > `Import and export` > `Import`.
1. Select `Following list` in the `Import type` dropdown menu.
1. Choose the csv file in the `Data` section.
1. Select `Merge` to keep existing records in your following list and add new ones.
1. Click `Upload` for Mastodon to start importing users.
1. Repeat as needed for additional lists.

## Contribute

Help keep the lists up to date by creating a PR or contact Gunnar Grosch in the way you see fit. Also applies if you want to be removed from any of the lists.

## Author

**Gunnar Grosch** - [GitHub](https://github.com/gunnargrosch) | [Twitter](https://twitter.com/gunnargrosch) | [LinkedIn](https://www.linkedin.com/in/gunnargrosch/) | [Mastodon](https://hachyderm.io/@gunnargrosch)

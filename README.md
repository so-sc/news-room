# SOSC - News Room :newspaper:
Repository to handle media coverage, contents and articles related to the community.
> This repository is managed by [Gloria Borger](https://github.com/haxzie/gloria-borger)

## Table of contents :clipboard:
- [Submitting articles to Sahyadri Buzz](https://github.com/so-sc/media-room/blob/master/README.md#submitting-articles-to-sahyadri-buzz-mega)
- [Tweeting through official SOSC handle](https://github.com/so-sc/media-room/blob/master/README.md#tweeting-through-official-sosc-handle-bird)
- Post event Reports and Yearly reports

## Submitting Articles to Sahyadri Buzz :mega: 
This repository stores all the contents that's been sent to Sahyadri Buzz and other stake holders. After each event SOSC is hosting, a report should be sent to the Buzz and other related individuals. 

### How to submit?
- Open an issue in this repository with title as the subject of the Email
- Write down the body of the email in the body of the Issue.
- To add images, simple drag and drop the images from your computer to the text box.
- Request an admin to approve the issue, or if you are an admin or owner of the repo. Comment '/approve' or add the label `Approved` to the issue.
- Once the issue is approved, you can send the mails to any of the mailing list listed in the `.github/news-room.yml` by simply commenting `/mail to GROUP_NAME` eg: `/mail to buzz`.
- To test out the email before mailing anyone, we highly recomment you to mail the email to your personal email or the test emails by `/mail to test` or `/mail to youremail@example.com`
- Once the PR is merged, the Bots will take care of mailing the article with all the images to the mail ID's mentioned in the `.github/sosc-bot.yml` file.

## Tweeting through official SOSC Handle :bird:
### THIS FEATURE IS UNDER DEVELOPMENT
[SOSC's twitter handle](https://twitter.com/sahyadri-osc) is partially managed by bots. ie. Bot's will be able to pick the changes introduced to the repository's twitter dorectory and tweet it through the official SOSC twitter account.

### How to tweet?
- Create a new file inside `tweets` directory with the a short title and date of the tweet. eg `djangogirls-24-03-2018.md` and add all the contents of the tweet into the markdown file without any styling.
- Make sure the entire tweet is less than 280 characters.
- Submit a PullRequest with the tweet name and date as title. Add all the images to be tweeted inside the PullRequest body. You can do that by drag and dropping the image files from your computer to the PullRequest text field.
- Add appropriate labels and request review from on the SOSC Members.
- Once the PullRequest is merged. The bots will take care of tweeting out the contetns through the official SOSC Twitter account.

# SOSC - News Room :newspaper:
Repository to handle media coverage, contents and articles related to the community.
> This repository is managed by ProBot

## Table of contents :clipboard:
- [Submitting articles to Sahyadri Buzz](https://github.com/so-sc/media-room/blob/master/README.md#submitting-articles-to-sahyadri-buzz-mega)
- [Tweeting through official SOSC handle](https://github.com/so-sc/media-room/blob/master/README.md#tweeting-through-official-sosc-handle-bird)
- Post event Reports and Yearly reports

## Submitting Articles to Sahyadri Buzz :mega: 
This repository stores all the contents that's been sent to Sahyadri Buzz and other stake holders. After each event SOSC is hosting, a report should be sent to the Buzz and other related individuals. 

### How to submit?
- Create a markdown file inside `Sahyadri-Buzz` directory with title and all the required contents related to the event eg: `devhost18-24-03-2018.md`. Note to keep things as descriptive and short as possible. Donot forget to mention about SOSC's involvement in the article.
- Submit a `PullRequest` by adding appropriate message and include images in the PullRequest body, You can do that just by drag and dropping the images from your computer to the PullRequest comment body.
- Add appropriate labels if the article needs to be held before sending out on a different date.
- Request review from any of the members in SOSC Media team, once the review is completed and if any changes has been requested, submit the changes by editing the file in the same PullRequest.
- Once the PR is merged, the Bots will take care of mailing the article with all the images to the mail ID's mentioned in the `.github/sosc-bot.yml` file.

## Tweeting through official SOSC Handle :bird:

[SOSC's twitter handle](https://twitter.com/sahyadri-osc) is partially managed by bots. ie. Bot's will be able to pick the changes introduced to the repository's twitter dorectory and tweet it through the official SOSC twitter account.

### How to tweet?
- Create a new file inside `tweets` directory with the a short title and date of the tweet. eg `djangogirls-24-03-2018.md` and add all the contents of the tweet into the markdown file without any styling.
- Make sure the entire tweet is less than 280 characters.
- Submit a PullRequest with the tweet name and date as title. Add all the images to be tweeted inside the PullRequest body. You can do that by drag and dropping the image files from your computer to the PullRequest text field.
- Add appropriate labels and request review from on the SOSC Members.
- Once the PullRequest is merged. The bots will take care of tweeting out the contetns through the official SOSC Twitter account.

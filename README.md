# KrypticRewards
![img](https://i.postimg.cc/wjdvLBMy/Untitled-1920-1080-px.png)

KrypticRewards is a Python script that automates Microsoft Rewards tasks, saving you time and effort. With this script, you can automate tasks like daily searches, quizzes, and other reward-earning activities. 

## Getting Started

### Prerequisites

Before using KrypticRewards, you need to have the following:

* A Microsoft account with Microsoft Rewards program membership.
* A valid phone number for verification.

### Usage

To use KrypticRewards, you need to provide your Microsoft account details as secrets in your repository's settings. The script uses these secrets to sign in to your account and perform the automated tasks. 


![secrets](https://i.postimg.cc/Y9g2vK7f/2023-04-05-09-45.png)


The following secrets need to be added to your repository's settings:

* `ACTIVATION_KEY`: A paid activation key to use this script. Contact `@krypticBit` over Telegram to purchase one.
* `FIRST_ID`: The email address or username of the first Microsoft account you want to use.
* `SECONDARY_ID`: The email address or username of the second Microsoft account you want to use.
* `CHAT_ID`: Your Telegram chat ID to upload logs.
* `BOT_TOKEN`: Your Telegram bot token to upload logs.

To run the script, add the `workflow_dispatch` event or set up a cron job using the `schedule` event in the `/.github/workflows/rewards.yml` file. 

## Authors

* KrypticBit / [AKhilRaghav0](https://github.com/AKhilRaghav0)



---
sidebar_position: 1
---

# User Count Channels Guide

## Introduction

Count Channels Are A Way Of Displaying Your Server Stats In A Good Looking Manner.

## Preview

![preview of count channel](https://i.imgur.com/Pmzlto2.png)

So The Above 👆 Is A Preview Of What We Will Be Building!

## Types Of Count Channels

Yeet Currently Provides **4 Types** Of Count Channels. These Are As Follows:

- **Real Members Count Channel** - This Is The Count Of Real People In Your Discord Server
- **BOT Count Channel** - This Is The Count Of BOTs In Your Discord Server
- **Total User Count Channel** - This Is The Sum Of Bots & Real People In Your Discord Server
- **Goal Channel** - This Is a Free Channel, Which Means You Are Allowed To Type In Whatever You Want In It, But People Generally Use It For Goal Counts.

## Setup The Channels

### Members, Bots & Total

![addcountchannel command](https://i.imgur.com/ZNMWXca.png)

We Will Be Using `/addcountchannel` Command For These.

![](https://i.imgur.com/IGuZ6Ov.png)

This Command Has 2 Options, The Type Of Channel You Wanna Create & The Text.
In The First Option Choose The Type You Like.

Talking About The Second Option which is the `text`, You Can Enter Anything There. You Can Type In `$COUNT`, Which Will Be Replaced By The Actual Count.

For Example Lets Say You Enter: `Members: $COUNT`, Then The Channel Will Say: `Members: 100` Or Whatever No. Of Members You Have In Your Server.

![](https://i.imgur.com/nYK292d.png)

Here We Have Filled Up This Command Like This.

![](https://i.imgur.com/ws7G1EK.png)

On Running The Command, If Everything Is Good, You Will See This Message.

![](https://i.imgur.com/D0AU09n.png)

And As You Can See The `Member Count` Channel is Created Successfully!

### The Goal Count

Unlike The Other Count Channels, The Goal Channel Doesn't Provide Any `$COUNT` Variable. So You Are Free To Type In Anything You Want.

## Updation Of Count Channels

The Count Channels Update On The Following Events:

- Whenever A New User (including Bots), Join Your Server
- Whenever An User (including Bots), Leaves, Or Has Been Kicked
- In Case Of Any Error Resulting In Bot Restart.

To Avoid Any Inaccurate Counts, **Yeet** Also Updates The Channels Every **10 Minutes**

## Edit Count Channels

To Update Any Channel Simply Run The Command Again, With The New Options That You Want.
You Can Also Delete Any Channels And Run The Command To Create Them Again.

## Ratelimit Warning

**Discord** Allows To Change The Channel Names, Only 2 Times Every 10 Minutes.

And Hence, If You Run The `/addcountchannel` command, on an existing channel more than 2 times in 10 minutes, that process's state would be pending and would automatically be resolved after 10 minutes.

![](https://i.imgur.com/URwNmCU.png)

You May See This Message When Running The Command More Than 2 Times In 10 Minutes.

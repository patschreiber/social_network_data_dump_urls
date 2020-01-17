# Social Network Data Dump URLs
A collection of URLs that point to where one can request the data dump a given social network will generate for you. I didn't realize more social networks offered this feature, so this repo is an attempt to collate all of the ones that _do_, in addition to providing instructions on how a user can procure their available data. 

<br>

## Table of Contents
* [Table of Contents](#table-of-contents)
  * [1. Facebook](#1-facebook)
  * [2. Instagram](#2-instagram)
  * [3. Twitter (Todo)](#3-twitter)
  * [4. Tik Tok (Todo)](#4-tiktok)
  * [5. Snapchat](#5-snapchat)
  * [6. LinkedIn (Todo)](#6-linkedin)
  * [7. Twitter (Todo)](#7-twitter)
  * [8. Spotify](#8-spotify)

<br>

## 1. Facebook

The fat cat in the room. Provides a lot of options to generate a dump of one's data. Unfortunately, what you _won't_ find in the export are the the data models and projections they've constructed _from_ your data.

### 
|Quick Link (Go Here)|
|:----|
|[https://www.facebook.com/settings?tab=your_facebook_information](https://www.facebook.com/settings?tab=your_facebook_information)<br><sub>(Be sure to log in first!)</sub>|

#### Step-by-step

1. Log into the web interface at [https://www.facebook.com/login](https://www.facebook.com/login)
2. Click the **Down Arrow** all the way to the right of the blue navigation bar, then [**Settings**](https://www.facebook.com/settings)

3. Click [**Your Facebook Information**](https://www.facebook.com/settings?tab=your_facebook_information) in the lefthand menu.
4. Click **View** next to **Download Your Information**
5. Select the desired options (please see the [Data Filtering Options](#data-filtering-options) section for more info)
6. Click the blue **Create File**
7. An alert is displayed that explains the data may take some time to compile.

> An email with the download link will be sent to the email address associated with the account when the data is ready. Additionally, clicking the **Available Copies** tab will allow a user to download previously-compiled copies of the data.

#### [Data Filtering Options](#data-filtering-options)

Facebook provides options on how the data will be compiled. One can filter by the following fields:

|Option Name|Available Values|
|-----------|----------------|
|Date Range|`All of my data`, or a start and end date range|
|Format|`HTML`, `JSON`|
|Media Quality|`High`, `Medium`, `Low`|

Additionally, there are quite a few options to filter **Your Information**
<details>
  <summary>Expand to see all of the options for <strong>Your Information</strong></summary>

  |Option Name|Description|
  |-----------|-----------|
  |Posts|Posts you've shared on Facebook, posts that are hidden from your timeline, and polls you have created|
  |Photos and Videos|Photos and videos you've uploaded and shared|
  |Comments|Comments you've posted on your own posts, on other people's posts or in groups you belong to|
  |Likes and Reactions|Posts, comments and Pages you've liked or reacted to|
  |Friends|The people you are connected to on Facebook|
  |Stories|Photos and videos you've shared to your story|
  |Following and Followers|People, organizations or business you choose to see content from, and people who follow you|
  |Messages|Messages you've exchanged with other people on Messenger|
  |Groups|Groups you belong to, groups you manage and your posts and comments within the groups you belong to|
  |Events|Your responses to events and a list of the events you've created|
  |Profile Information|Your contact information, information in your profile's About section, your life events, hobbies and music.|
  |Pages|Pages you are the admin of|
  |Marketplace|Your activity on Marketplace|
  |Payment History|A history of payments you've made through Facebook|
  |Saved Items and Collections|A list of the posts you've saved, and your activity within collections|
  |Your Places|A list of places you've created|
  |Apps and Websites|Apps and websites you log into using Facebook and apps you admin|
  |Portal|Info associated with your Portal, such as favorites and photos on Superframe|
  |Other Activity|Activity associated with your account, such as Pokes given and received|

  #### Information About You
  ##### Information associated with your Facebook account, such as your logins to Facebook and what devices you use.

  |Option Name|Description|
  |-----------|-----------|
  |Ads|Ads topics that are most relevant to you, advertisers who have collected information directly from you and information you've submitted to advertisers|
  |Search History|A history of your searches on Facebook|
  |Location|Information related to your location|
  |About You|Information associated with your Facebook account|
  |Security and Login Information|A history of your logins, logouts, periods of time that you've been active on Facebook and the devices you use to access Facebook.|
</details>

#### Data Format

> TODO (Too long, didnt document)

<br>

## 2. Instagram

Instagram is a subsidiary of Facebook (the Corporation). Assume that any data contributed to Instagram will be thrown into the same pot of "data stew" Facebook (the product) has already vacuumed up.

### 
|Quick Link (Go Here)|
|:----|
|[https://www.instagram.com/download/request/](https://www.instagram.com/download/request/)<br><sub>(Be sure to log in first!)</sub>|

#### Step-by-step

1. Log into the web interface at [https://www.instagram.com/](https://www.instagram.com/)
2. Click the above link or navigate to [https://www.instagram.com/accounts/privacy_and_security/](https://www.instagram.com/accounts/privacy_and_security/) and click [Request Download](https://www.instagram.com/download/request/
)
3. An email with the download link will be sent to the email address associated with the account.

#### Data Format

> The data comes in json-formatted files, along with any posts, stories, or other DMs you may have submitted.
<details>
 <summary>Expand to see the folder structure</summary>
 
```
.
├── autofill.json
├── checkout.json
├── comments.json
├── connections.json
├── contacts.json
├── direct
│   └── [datetime]
│       └── [truncated].jpg
├── likes.json
├── media.json
├── messages.json
├── photos
│   ├── [datetime]
│   │   └── [truncated].jpg
│   └── [datetime]
│       ├── [truncated].jpg
│       └── [truncated].jpg
├── profile
│   └── [datetime]
│       └── [truncated].jpg
├── profile.json
├── saved.json
├── searches.json
├── settings.json
├── stories
│   ├── [datestamp]
│   │   └── [truncated].mp4
│   └── [datestamp]
│       ├── [truncated].jpg
│       └── [truncated].mp4
├── stories_activities.json
└── videos
    ├── [datestamp]
    │   └── [truncated].mp4
```
</details>

<br>

## 5. Snapchat

### 
|Quick Link (Go Here)|
|:----|
|[https://accounts.snapchat.com/accounts/downloadmydata](https://accounts.snapchat.com/accounts/downloadmydata)<br><sub>(Be sure to log in first!)</sub>|

#### Step-by-step

1. Log into the web interface at [https://accounts.snapchat.com/accounts/login](https://accounts.snapchat.com/accounts/login)
2. On the **Manage My Account** page, click [My Data](https://accounts.snapchat.com/accounts/downloadmydata)
3. Scroll to the bottom and click **Submit Request**

> An email with the download link will be sent to the email address associated with the account when the data is ready.

#### Data Format

> The data is provided in both HTML and JSON formats. The initial folder structure should be similar to:
<details>
  <summary>Expand to see the folder structure</summary>

```
.
├── html
│   ├── account.html
│   ├── account_history.html
│   ├── bitmoji.html
│   ├── bitmoji_kit_user.html
│   ├── cameos_metadata.html
│   ├── chat_history.html
│   ├── community_lenses.html
│   ├── connected_apps.html
│   ├── faq.html
│   ├── friends.html
│   ├── in_app_reports.html
│   ├── in_app_surveys.html
│   ├── location_history.html
│   ├── memories_history.html
│   ├── purchase_history.html
│   ├── ranking.html
│   ├── search_history.html
│   ├── shared_story.html
│   ├── shop_history.html
│   ├── snap_ads.html
│   ├── snap_games.html
│   ├── snap_history.html
│   ├── subscriptions.html
│   ├── support_note.html
│   ├── talk_history.html
│   ├── terms_history.html
│   └── user_profile.html
├── index.html
└── json
    ├── account.json
    ├── account_history.json
    ├── bitmoji.json
    ├── bitmoji_kit_user.json
    ├── cameos_metadata.json
    ├── chat_history.json
    ├── community_lenses.json
    ├── connected_apps.json
    ├── friends.json
    ├── in_app_reports.json
    ├── in_app_surveys.json
    ├── location_history.json
    ├── memories_history.json
    ├── purchase_history.json
    ├── ranking.json
    ├── search_history.json
    ├── shared_story.json
    ├── shop_history.json
    ├── snap_ads.json
    ├── snap_games.json
    ├── snap_history.json
    ├── subscriptions.json
    ├── support_note.json
    ├── talk_history.json
    ├── terms_history.json
    └── user_profile.json
```
</details>

<br>

## 8. Spotify

Spotify requires a lengthy three-step process to procure a user's data. They state the process can take up to 30 days(!) to complete.

###
|Quick Link (Go Here)|
|:----|
|[https://www.spotify.com/us/account/privacy/](https://www.spotify.com/us/account/privacy/)<br><sub>(Be sure to log in first!)</sub>|

#### Step-by-step

1. Log into the web interface at [https://accounts.spotify.com/en/login](https://accounts.spotify.com/en/login)
2. Spotify sends an email with a link to confirm your request. If the email can't be found fpr whatever reason, it can be resent from the same page.
3. After confirming the email, a notification will be sent telling the user Spotify is collating their data. **_This can take up to 30 days to complete_**. <sub>(As presumably the monkeys :monkey: with typewriters manually transcribe your data)</sub>
4. An email will be sent when the data is ready to be downloaded.

#### Data Format

> TODO: Update when received

---

## Contributing

Please submit a PR if I missed a service or there's a Better Way®. Furthermore, you can reach me via multiple avenues at [https://patschreiber.com/contact](https://patschreiber.com/contact)

## License




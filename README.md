# LightHouse

A WeChat mini-program for tracking personal content intake, derived from testing mini-program skills.

## About

LightHouse helps you systematically record, rate, and review your consumption of various media and ideas. Track what you watch, read, listen to, and think about — all in one place.

## Features

- **Multi-category tracking** — Record content across 5 categories: Podcasts, Videos, Movies, Books, and Ideas
- **Today view** — See all records created today with time-based greetings
- **History & filtering** — Browse all records chronologically, filter by category
- **Rating system** — Give 1-5 star ratings to each entry
- **Statistics** — View total records, daily counts, streak tracking, and category distribution
- **Cloud sync** — WeChat login with cloud database backup

## Tech Stack

- WeChat Mini Program (native development)
- WeChat Cloud Development (Cloud Functions + Cloud Database)
- Custom TabBar component

## Project Structure

```
├── app.js / app.json / app.wxss     # App entry and global config
├── pages/
│   ├── index/                       # Today's records
│   ├── list/                        # Record history with filters
│   ├── add-record/                  # Add / edit / delete records
│   └── profile/                     # User profile and statistics
├── components/
│   ├── nav-bar/                     # Custom navigation bar
│   └── intake-card/                 # Record display card
├── custom-tab-bar/                  # Custom bottom tab navigation
├── cloudfunctions/
│   ├── addRecord/                   # Create record
│   ├── getRecords/                  # Query records and stats
│   ├── updateRecord/               # Update record
│   ├── deleteRecord/               # Delete record
│   └── login/                      # User authentication
└── utils/                           # Date formatting and category definitions
```

## Getting Started

1. Install [WeChat DevTools](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)
2. Import this project
3. Enable Cloud Development in WeChat DevTools
4. Build and run

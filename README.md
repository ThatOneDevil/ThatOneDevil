
### 👋 Hi there im devil - aka (ThatOneDevil)

## I'm a java devloper.

- 🔭 I'm 
- 🌱 I’m currently learning everything 🤣
- 👯 I’m looking to help others!
- 🥅 2022 Goals: Learn way more java.
- ⚡ Fun fact: I love to play games!


## Github Status

![ThatOneDevil](https://github-readme-stats.vercel.app/api?username=thatonedevil&show_icons=true&theme=radical&hide_border=true)


## Top langugages


![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=thatonedevil&layout=compact&theme=radical)


## Activity
<!--START_SECTION:activity-->

name: Update README

on:
  schedule:
    - cron: '*/30 * * * *'
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: Update this repo's README with recent activity

    steps:
      - uses: actions/checkout@v2
      - uses: jamesgeorge007/github-activity-readme@master
        env:
          GITHUB_TOKEN:

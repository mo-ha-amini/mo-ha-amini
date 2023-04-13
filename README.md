### Hi there 👋

- 🌱 I’m currently learning Rust and Typescript
- 👯 I’m looking to collaborate on 
- 🤔 I’m looking for help with ...
- 💬 Ask me about Javascript
- 📫 How to reach me: mhaminii18@gmail.com

- ⚡ Fun fact: 

![](https://komarev.com/ghpvc/?username=mo-ha-amini&style=flat-square&color=blueviolet)

<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ waka_82b3cbfc-6e76-4feb-9f27-dbea666a6995 }}
          GH_TOKEN: ${{ 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 }}
<!--END_SECTION:waka-->

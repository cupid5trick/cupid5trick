# Features

- timestats from wakatime
- github activities graph

# anmol098/waka-readme-stats

- You need to update the markdown file(.md) with 2 comments. You can refer [here](https://github.com/anmol098/waka-readme-stats#update-your-readme) for updating it.
- You'll need a WakaTime API Key. You can get that from your WakaTime Account Settings
  - You can refer [here](https://github.com/anmol098/waka-readme-stats#new-to-wakatime), if you're new to WakaTime
- You'll need a GitHub API Token with `repo` and `user` scope from [here](https://github.com/settings/tokens) if you're running the action to get commit metrics
    
    > enabling the `repo` scope seems **DANGEROUS**  
    > but this GitHub Action only accesses your commit timestamp and lines of code added or deleted in repository you contributed.
    
  - You can use [this](https://github.com/anmol098/waka-readme-stats#profile-repository) example to work it out
- You need to save the WakaTime API Key and the GitHub API Token in the repository secrets. You can find that in the Settings of your repository. Be sure to save those as the following.
  - WakaTime API Key as `WAKATIME_API_KEY=<your wakatime API Key>`
  - GitHub Personal Access Token as `GH_TOKEN=<your github access token>`
- You can enable and disable feature flags based on requirements.

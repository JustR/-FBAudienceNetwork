# FBAudienceNetwork
FBAN 6.11.1 source
Used to solve the problem that pod install "Error installing FBAudienceNetwork"

Instructions：

1. cd ~/.cocoapods/repos/master/Specs
2. search and find FBAudienceNetwork 6.11.1 folder
3. edit FBAudienceNetwork.podspec.json
4. replace source and save，like this：
"source": {
    "http": "https://github.com/JustR/FBAudienceNetwork/releases/download/FBAN/FBAudienceNetwork-6.11.1.zip"
  },
5. try "pod install" again 

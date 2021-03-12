# Set-Uniswap Token List

## Custom Set Details

In order to add your own custom details for your set, please follow these steps:

1. Create a fork of the repo that you will be working off of to create a pull request against.
2. Add a new file into the `set-details` folder that is named as `[insert-your-set-address].setdetails.json` (i.e. 0x1494CA1F11D487c2bBe4543E90080AeBa4BA3C2b.setdetails.json)
3. Make sure that the JSON follows the correct schema here: https://github.com/SetProtocol/uniswap-tokenlist/blob/main/set-details.schema.json. You can verify it by pasting the schema into https://www.jsonschemavalidator.net and see if your input JSON matches properly. If you need to have multi-line JSON, you can use a HJSON converter to help with writing it and then paste in the final valid JSON spit out from it (can use https://hjson.github.io/try.html for example)
4. Also add your token details to the set.tokenlist.json if it is not in there already.
5. Create a pull request against the master branch. Follow the PR template to submit the proper signature (signed current version number [i.e. 1] via TokenSets UI)


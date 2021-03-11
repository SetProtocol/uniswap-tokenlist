# Set-Uniswap Token List

## Custom Set Details

In order to add your own custom details for your set, please follow these steps:

1. Create a branch in this repo that you will be working off of to create a pull request.
2. Add a new file into the `set-details` folder that is named as `[insert-your-set-address].setdetails.json` (i.e. 0x1494CA1F11D487c2bBe4543E90080AeBa4BA3C2b.setdetails.json)
3. Make sure that the JSON follows the correct schema here: https://github.com/SetProtocol/uniswap-tokenlist/blob/main/set-details.schema.json. You can verify it by pasting the schema into https://www.jsonschemavalidator.net and see if your input JSON matches properly.
4. Create a pull request with this new file in it. Follow the PR template to submit the proper signature (signed version number [i.e. 1.0.0] via TokenSets UI)


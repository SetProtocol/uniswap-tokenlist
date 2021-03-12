When submitting a new or existing set details change, make sure you have followed the following steps:

- []  Add a new file (or update existing file) into the `set-details` folder that is named as `[insert-your-set-address].setdetails.json` (i.e. 0x1494CA1F11D487c2bBe4543E90080AeBa4BA3C2b.setdetails.json)
- [] Make sure that the JSON follows the correct schema here: https://github.com/SetProtocol/uniswap-tokenlist/blob/main/set-details.schema.json. You can verify it by pasting the schema into https://www.jsonschemavalidator.net and see if your input JSON matches properly. If you need to have multi-line JSON, you can use a HJSON converter to help with writing it and then paste in the final valid JSON spit out from it (can use https://hjson.github.io/try.html for example)
- [] If updating existing set details, update the version number appropriately (see the JSON schema above for version numbering explanation).
- [] If adding brand new token, make sure to add it to the set.tokenlist.json as well following the correct schema from Uniswap: https://github.com/Uniswap/token-lists/blob/master/src/tokenlist.schema.json
- [] Attach the proper signature (signed current version number [i.e. 1] via TokenSets UI) here (i.e. 0x21fbf0696d5e0aa2ef41a2b4ffb623bcaf070461d61cf7251c74161f82fec3a4370854bc0a34b3ab487c1bc021cd318c734c51ae29374f2beb0e6f2dd49b4bf41c):

[ATTACH SIGNATURE HERE]


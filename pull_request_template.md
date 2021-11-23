When submitting a new or existing set details change, make sure you have followed the following steps:

### Adding New Set Details
- [ ]  Add a new file (or update existing file) into the `set-details` or `set-details-polygon` folder that is named as `[insert-your-set-address].setdetails.json` (i.e. 0x1494CA1F11D487c2bBe4543E90080AeBa4BA3C2b.setdetails.json). Make sure to provide the [checksum address](https://ethsum.netlify.app/) for your Set
- [ ] Verify the JSON follows the correct schema according to this [template](https://github.com/SetProtocol/uniswap-tokenlist/blob/main/set-details.schema.json). You can verify it by pasting the schema into this [schema validator](https://www.jsonschemavalidator.net) and checking if your input JSON matches properly. If you need to have multi-line JSON, you can use a HJSON converter to help with writing it and then paste in the final valid JSON spit out from it (see README for example)
- [ ] If adding brand new token, make sure to add it to the `set.tokenlist.json` or `set.polygon.tokenlist.json` as well following the correct schema from Uniswap: https://github.com/Uniswap/token-lists/blob/master/src/tokenlist.schema.json

### Updating Existing Set Details
- [ ] If updating existing set details, update the version number appropriately (see the JSON schema above for version numbering explanation).
- [ ] When generating a signature, make sure the version signed is for the one reflected in the version details for your entry.

### Signature (Required)

- [ ] Attach the proper signature. You can generate one by going to the page for your Set on TokenSets and signing in. Tap on your Set's name and follow the instructions provided (i.e. 0x21fbf0696d5e0aa2ef41a2b4ffb623bcaf070461d61cf7251c74161f82fec3a4370854bc0a34b3ab487c1bc021cd318c734c51ae29374f2beb0e6f2dd49b4bf41c):

[INSERT SIGNATURE HERE]

# jmeter-documentserver-performance

Reports for some performance test of `onlyoffice-documentserver`
All test performed on DigitalOcean 2GB Ram/2CPU Droplet with 4GB Swap with Docker image

Results for [5.0.4.15](https://github.com/onlyoffice-testing-robot/jmeter-documentserver-performance/blob/master/ds-5.0.4-ce68b81.zip)

Test are:
* `coauth-user-generator` - open single document via several users and add shape to it
* `convert-files-sync-via-service` - perform sync convert of docx to odt. Most performance heavy.
* `spellchecker-single-word` - check single word via Spellcheker websocket by several users

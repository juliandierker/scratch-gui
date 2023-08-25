This is a fork of https://github.com/LLK/scratch-gui

We use this at eduki interactive with a modificated asset-path to provide scratch as an element in our unit creator
The UI is adapted to our needs at www.pearup.de

## Publish

For publish-actions you need to build the entire project new localy with

`BUILD_MODE=dist npm run build`

Make sure Node is running on V 16 or V 14

if it fails you can try

`sudo BUILD_MODE=dist NODE_OPTIONS='--openssl-legacy-provider' npm run watch --openssl-legacy-provider`

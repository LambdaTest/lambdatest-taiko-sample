# Lambdatest Taiko Sample

## Pre-requisite
- Node should be installed
- Clone the repo using `git clone git@github.com:LambdaTest/lambdatest-taiko-sample.git`
- Move to taiko-gauge folder using `cd lambdatest-taiko-sample/taiko-gauge`
- Install taiko globally using `npm install -g taiko`
- Install gauge cli globally using `npm install -g @getgauge/cli`
- Install dependencies using `npm install`

## Running the tests
- Tet username and accessKey using below commands
    - For MacOS/Linux
        `export LT_USERNAME=<user_name>`
        `export LT_ACCESSKEY=<access_key>`
    - For Windows
        `set LT_USERNAME=<user_name>`
        `set LT_ACCESSKEY=<access_key>`
- To run tests use command `npm test`

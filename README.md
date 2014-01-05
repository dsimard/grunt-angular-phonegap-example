grunt-angular-phonegap-example
==============================

An example project with dsimard/grunt-angular-phonegap

## Getting started

1. Clone this project

        git clone https://github.com/dsimard/grunt-angular-phonegap-example.git && cd grunt-angular-phonegap-example/ 

2. Install npm modules

        npm install

3. Install bower dependencies

        bower install

4. Add a mobile platform

        cordova platform add android

4. Build the project

        grunt phonegap:build

5. Start an emulator

        grunt phonegap:emulate


## Commits

Here are the commits from the different steps when I started the project.

### Step 1

Create phonegap project : [0426f3b](https://github.com/dsimard/grunt-angular-phonegap-example/commit/2d14bf17f776350b0ba993e991f96ceef0426f3b)


### Step 2

User latest phonegap version : [12af00d](https://github.com/dsimard/grunt-angular-phonegap-example/commit/c66d368d06340f784a2b33d9fa79ca2fb12af00d) 


### Step 3

Initialize angular application : [58bf8bb](https://github.com/dsimard/grunt-angular-phonegap-example/commit/23ea3d50334bb7bc36948a39df440fc1058bf8bb)

You will be ask to overwrite `.gitignore`. **Do not accept**. Instead, press `d` for difference
and copy the added lines in your clipboard to paste later. Then press `n` for no.

### Step 4

Add `grunt-angular-phonegap` to the app : [c943348](https://github.com/dsimard/grunt-angular-phonegap-example/commit/350c8777a79571cc140ab5c860c86f12ec943348)

### Step 5

Load npm tasks (`grunt.loadNpmTasks("grunt-angular-phonegap");`) : [fb931bc](https://github.com/dsimard/grunt-angular-phonegap-example/commit/084309dad20b8e249a74e84bfdc0c4fb7fb931bc)

### Step 6

Add a platform : `cordova platform add [platform]` (no commit)

### Step 7

`grunt phonegap:check` (no commit)

### Step 8

`grunt phonegap:build`

### Step 9

`grunt phonegap:emulate`
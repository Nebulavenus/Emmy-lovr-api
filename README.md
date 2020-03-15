# Emmy-lovr-api

A script to generate [LÖVR](https://lovr.org/) API autocomplete files for [EmmyLua](https://github.com/EmmyLua/IntelliJ-EmmyLua).

## How to use it

1. Download or clone the [LÖVR DOCS](https://github.com/bjornbytes/lovr-docs) into a directory on your computer (if you want the API for an older version, check the "branches" of that repository).
2. Create a directory named `api` in the directory, do not put any files in there or run anything in it.
3. Download `genEmmyAPI.lua` from this repository into the same directory (either click on the filename and click "Raw" and save the file, or download or clone repository to your computer and move the file over).
4. Copy `init.lua` inside of `lovr-docs/api/` next to `genEmmyAPI.lua`
5. Run `genEmmyAPI.lua` in the directory, i.e. run `lua genEmmyAPI.lua` in the terminal. This will generate the API autocomplete files in the `api` folder.
6. Copy the `api` folder into your project's source folder, the same folder where `main.lua` is (you can rename it whatever you want, it doesn't have to be called `api`).

Once you start or refresh your IDE (might be automatic) you should have autocomplete and quick documentation for LÖVR!

## Other LÖVR versions

When you want to change the LÖVR version you use, just delete the `api` folder from your project, and redo the steps above for the appropriate version of the API.

## Credits

Original script by https://github.com/tangzx  
One tiny modification of the script, README by https://github.com/kindfulkirby  
Next tiny modification of the script and README by https://github.com/Nebulavenus
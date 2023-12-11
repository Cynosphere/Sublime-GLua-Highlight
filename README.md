# GLua syntax highlighting for Sublime Text 4
This is literally a copy paste of the default Lua syntax highlighting with GLua
syntax added. I did this because the old syntax files have some old choices that
I do not personally like with my color scheme (e.g. commas were colored red for
whatever reason).

Completion (if it still even works, I just use LSP) is also updated to latest
wiki scrape as of 2023/12/10 (`yyyy/mm/dd`)

## Installing
1. Open Sublime Text
2. Select Preferences > Browse Packages...
3. Copy the folder in which this README.txt is located, to the folder that just opened
4. Restart Sublime Text

### Disabling default Lua syntax
1. Preferences > Settings - User
2. Add a comma after the last setting
3. Make a newline under the last setting
4. Paste the following line: `"ignored_packages": ["Vintage", "Lua"]`

(Note how "Vintage" is also there. It's a package that's disabled by default.)

## Credits
- FPtje - Original maintainer
- JohnnyCrazy and djtb2924 - gmod-wiki-scraper

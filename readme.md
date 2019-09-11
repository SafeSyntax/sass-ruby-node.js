| **SASS using by Node.js**  |
| ---------------- |

## How to work SASS with Node.js
### Download Node.js from https://nodejs.org/en/
### Open CMD then your project directory (C:\Users\Rasel\Desktop\SASS>)
#### npm init (C:\Users\Rasel\Desktop\SASS\sass>npm init)
-Enter
package name: (sass) YourProjectName 
-Enter
Description: Your Description
-Enter
-Enter Continuesly..


Is this OK? (yse)
Enter

### Now command
npm install node-sass --save

### Go to package.json command
"scripts": {
    "compile:sass": "node-sass sass/style.scss(your sass file location) css/style.css(your css file location)"
  },

### Now Command
npm run compile:sass

or,

### "scripts": {
    "compile:sass": "node-sass sass/style.scss css/style.css -w"
  },
npm run compile:sass (now when save scss always changing)






----------------------------







|  **SASS using by Ruby** |
| ---------------- |
## How to work SASS with Ruby
### Download Ruby Installer from https://rubyinstaller.org/downloads/
Install rubyinstaller simple way like a software
### Open CMD 
gem install sass 

### now command
sass --watch sass\style.scss:css\style.css


And now when save sass then will change css






-------------------------------------------

## Most Useful Command
| CMD Command | Description | Command Example | Example (After Command)  |
| ------------| ----------- | --------------- | ------------------------ |
| CD\ | Running the CD\ command to change the directory to root  			| C:\Users\Rasel>cd\ | C:\Users\Rasel> to C:\> |
| CD | Running the CD command to change the directory to a specific folder 	| C:\>cd users\rasel | C:\> to C:\Users\Rasel> |
| CD.. | Running the CD.. command to go up one level in the directory tree | C:\Users\Rasel>CD .. | C:\Users\Rasel> to C:\Users> |
| Drive: | Changing the drive in Command Prompt | C:\Users\Rasel\Desktop\cmd>E: | C:\Users\Rasel\Desktop\cmd> to E:\> |
| Drive:\>cd /d Drive:\FolderName | Changing the drive and directory in Command Prompt | E:\>cd /d C:\users | E:\> to C:\Users> |
| dir | Using the DIR command to see the contents of a directory |  |  |
| mkdir newDirectoyName | create a new directory with Command Prompt | C:\Users\Rasel\Desktop\cmd>mkdir newDirectoyName | newDirectoyName (Created) |
| MKDIR drive:test | Using MKDIR to create a new directory, with a full path | C:\Users>mkdir e:\trymybest | C:\Users> to e:\trymybest |
| MKDIR Folder\Subfolder | Creating a folder with subfolders, using MKDIR in Command Prompt | mkdir hello\hi | Created Hello > Hi (Folder) |
| ren FolderOldName FolderNewName | Renaming folders with the REN command, in Command Prompt | e:\>ren hello kry |  hello to kry |
| Same Avobe | Renaming files with the REN command, in Command Prompt |  |  |
| nul > FileName | Creating a File | C:\Users\Rasel\Desktop\SASS> nul>README.md | README.md (file created) |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
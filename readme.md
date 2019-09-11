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
# Let's learn SASS 

## Install SASS 
- Install through terminal :
- `sudo gem install sass`
- Double check to make sure that it has installed:
- `sass -v`
You should see a message that tells you what version of SASS you are using. Something - like: 
- `Sass #.#.# (Version Name)`


## Run SASS 
- Download this project 
- Put the **SASS** folder to your **Desktop**
- In terminal, go to this project 
- `cd /Users/yourUserName/Desktop/SASS/get-started`
- Change directory to your stylesheet 
- `cd stylesheets`
- Tell SASS to watch your **SASS** folder and compile it to your **CSS** folder
- `sass --watch sass:css --style expanded` 
- Minify for production when you publish
- `sass --watch sass:css --style compressed` 
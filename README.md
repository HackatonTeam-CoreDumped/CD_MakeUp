# CD_MakeUp
Open styles library, proudly made by Core Dumped Hackaton Team

# Hey, listen to me
This, guys, is a node project. Once you are inside of it you need to install the dependencies, so:

`
$ cd <<PROJECT-PATH>>
$ npm install
`

Just in case, you can also install node-sass globaly (it has some issues finding its path it seems). **This step might not be needed for you**. Install it globaly with `` npm install -g node-sass``

# Last step, I promise
To run the project and execute everything do:
`$ npm run start`
This will do the following:
1. Compile the sass to the css folder
2. Start listening to the changes you do to the sass and compile it automagically
3. Start a server that serves the html

Therefore, once it is running, you just edit the sass and html, and refresh the page as you normally do, the server will handle the rest for you.
Besis.

# Progress bar

To implement the progress bar, just copy this into the html:

```html
<div class="progress">
  <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%"></div>
</div>
```

Write `progress-bar-stripped` if you want stripes on the progress bar, and ``progress-bar-animated`` if you want an animation on it.

# Switch 

To implement the switch, just copy this into the html:

```html
<div class="my-switch">
   <label class="switch">
     <input type="checkbox">
     <span class="my-slider round"></span>
   </label>
</div>
```

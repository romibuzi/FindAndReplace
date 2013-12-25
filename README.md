Find And Replace
---------------


The jar archive is located in <code>build</code> directory


<h4>What it looks like :</h4>

![screenshot](https://raw.github.com/Romibuzi/FindAndReplace/master/images/Capture.JPG "")


<h4>Works only under JDK 1.7, JavaFX 2 librairies are not available with JDK 1.6 </h4>

<h4>Why I did it :</h4>

I wanted to make a small visual app for my agency where project manager and front-end developpers often have to recup big text files (typically big SQL dump to work locally) and make a simple replace in the file.

Of course they can make it with text editors, but they often crash when the file is really large (>30MB)

They are not really attracted by the terminal and the <code>sed</code> command (they don't know what they miss, as this command is powerful). So I've decided to make it a little more fun.

<h5>Feel free to recup this project and add more options or functionnalities, at the moment the app supports only very basic operations and the UI is... basic^^</h5>

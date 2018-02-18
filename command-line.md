The command line as I experienced it, is a way to tell precise action you want to do to your computer, which feels like understanding the inside better. You can think of the storage in your coputer like a map and so using the command line is very similar to giving directions to someone to go somewhere - do imagine that you are guiding someone in a maze of rooms to go somewhere secret (you can't just mention the final direction immediately, the full path has to be unrolled precisely) you can tell her every move to do, and she can tell exactely where she is  and what are the things near her (if you are confused you can ask her every moment).
What is good about this way of using your computer is the knowledge it gives you about it. It feels cleaner, sure you have to know what you are doing, but you get less noise in what you want to be done. All your folders and documents are still stored in it in the exact same graphic way you are used to see in your desktop and else, but by accessing them using the command line you can take actions that go deeper (like seeing hidded files automatically created and not shown graphically to you). 

Let's use the image of a computer terminal being its own geographic planet to explain the next ten commands.

cd ~ : is the one you use to go (often go back) to the basis. If you imagine that you are in a maze game it will take you back to the start/home.

cd "directory" : takes you to a country(directory) if the conditions of access are respected (to use it you need to be able to see it on the direct map -see "ls")

pwd : tells you where you are. If you think of you computer as a world, your folders (directories) are settlements and files cities, typing "pwd" will print out your position in your computer world

ls : gives you a written map at a certain focal of your surroundings. If you are at a global world view you'll only see continents (main folders). If you are at the continent view, you'll see the contries but not the other continents...
ls -al : gives you a more developped view of the former map. You'll get the same map starting at the same base focal, but you'll get to go through all the hidden cities(files) and countries(directories) you may have and through all the zooms possible.

mkdir : creates a new empty folder (directory) where you are. As if you would set a new settlement (that can be then filled with further settlements anf/or cities).

touch : create a new empty file (city) where you are. As if you would implant a new town (that can be filled with info but not extended to contain other file).

less "file" : shows you the inside of your city(file). With this command you can stroll (scroll) to get a good impression of your city(file) and use the space key to see it displayed by districts (pages). Type the letter "q" to exit the city(file).

cp "file" "directory" : duplicates your city(file) in another country (directory). Be careful not to have a city(file) with the same name in your country (directory) of destination as this command will change it to the exact same you are copying.

rm : removes your file/city.
rm -rf : removes your settlement/folder even if it is filled.

exit : exit the world/terminal.

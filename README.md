Here's how you can run Card Conjurer locally on Windows!

STEP 1: If you're on Windows download WAMP here: https://wampserver.aviatechno.net/?lang=en Get the appropriate version for your PC at the top. You may also want to download the VC++ redistributable at the bottom of the page if you've never grabbed these before. I recommend getting the "VC 2015-2022" (the latest) on the list to the right.
r/magicproxies - How To: Run Cardconjurer Locally on Windows

Choose according to your operating system, most likely you have 64 Bit

STEP 2: Install and run wampserver, an icon will show up in the tray -- it should be GREEN. If its orange or red, something isn't working.
r/magicproxies - How To: Run Cardconjurer Locally on Windows

Icon should be green

STEP 3: Click the icon in the tray, then go to PHP > version > select the newest version in the list. (wampserver will now automatically restart)
r/magicproxies - How To: Run Cardconjurer Locally on Windows

STEP 4: Go grab the cardconjurer source files here: https://github.com/MrTeferi/cardconjurer Hit green "Code" button > Download ZIP

STEP 5: Navigate to the www folder in your wamp directory. For me, this directory was at C:/wamp64/www. Delete everything in this folder, then in the cardconjurer zip you downloaded, extract the contents of the "cardconjurer-master" folder to this folder. Your "www" directory should now look similar to this:
r/magicproxies - How To: Run Cardconjurer Locally on Windows

Yours might be missing a few of these folders (which I added myself)

STEP 6: Cardconjurer should now be live on localhost. In a web browser navigate to localhost/index.php (just putting localhost should work as well).

Anytime you wanna use cardconjurer WAMP has to be running. If you are on MacOS/Linux you can use XAMPP (should be about the same process following this guide), and of course if you're on linux chances are you know what to do.

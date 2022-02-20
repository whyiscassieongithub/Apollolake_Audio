Forking @EMLommers Apollolake_Audio so it works with GalliumOS3.1
Please note there will be no updates or further releases unless there is a bug or there is a new version of galliumos, thank you.

TUTORIAL for @whyiscassieongithub's method of installing audio

Make sure you are on Ubuntu 21.10 for this, doesn't matter what flavor

Adding Deb-Src URIs to the source list

Do sudo apt edit-sources
then choose option one and undo the hash before deb-src in every link, except the impish indri image one at the top

Installing Git
sudo apt install git

Cloning the repository that has the resources required
git clone https://github.com/whyiscassieongithub/Apollolake_Audio

Go to the new directory
cd Apollolake_Audio

Make the new script executable
chmod +x apollolake.sh

Run the new script
./apollolake.sh

Don't let the System sleep during this process as it can cause problems.
NOTE: In my testing, the headphone jack doesn't work but YMMV.

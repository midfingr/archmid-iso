# archmid-iso

YouTube Video: https://youtu.be/i3-Ys7th4Pw

This is the 64-bit source for the archmid iso.

How to use:
- To download use:  git clone https://github.com/midfingr/archmid-iso
- Move the customrepo folder to your home folder

Change the permission of the archmid-iso to root
i.e. sudo chown -R root:root archmid-iso

As root open ~/archmid-iso/pacman.conf and change to Server=file:///home/your_user_name/customrepo/$arch (near the botton)

Navigate to ~/customrepo/x86_64
- In a terminal type:
repo-add customrepo.db.tar.gz *.tar.xz

Be sure to edit/build as root or sudo

Feel free to edit, add/remove packages, or fork, etc. as you see fit.

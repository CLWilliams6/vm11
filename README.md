<<<<<<< HEAD
vm11
====

cm11 patched to run on VM670
=======
roomservice.xml for experimental cm-11 for thunderc

to build:

init androidarmv6 repo

directions here: https://github.com/clwilliams6/android

cd to your androidarmv6 directory, then

git clone https://github.com/clwilliams6/android_roomservice.git .repo/local_manifests/ -b vm11

then

repo sync

. build/envsetup.sh

then

lunch cm_thunderc-userdebug
mka

output zip in out/target/product/thunderc
>>>>>>> 7d41bbdfda6856a7d73bf6b100583ba6fcc70cdb

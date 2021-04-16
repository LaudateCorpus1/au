<link rel="prerender" href="https://sdrausty.github.io/au/">
# [au](https://github.com/SDRausty/au)

#### -r--r--r-- [au](https://raw.githubusercontent.com/SDRausty/au/master/au)
#### -rwxrwx--- [au](https://wae.github.io/au/au)

Tapping [`au`](https://raw.githubusercontent.com/sdrausty/au/master/au) at the command prompt 💪 in [Termux 🙂 ](https://termux.com/) will update and backup your [Termux](https://termux.com/) installation in three keystrokes! You can use [`au`](https://github.com/sdrausty/au/blob/master/au) 📲 to backup your installation files in [Termux,](https://termux.com/) i.e. `*.deb` files available for reinstallation, if the need should arise on your Android or Chrome device. 

Should you find your [Termux](https://termux.com/) operating system unstable for any reason after updating, you can use `dpkg --purge pkg_name`, and then `dpkg --install pkg_name` from `/storage/emulated/0/Android/data/com.termux/txdebs` to downgrade packages to a previous version of a package in the hope of regaining package stability in [Termux.](https://termux.com/)

You should use the script [`au`](https://github.com/sdrausty/au/blob/master/au) from your `$PATH`. To see your `$PATH`, type `$PATH` +enter/return. Then use `mv au destination_directory` to move [`au`](https://github.com/sdrausty/au/blob/master/au) to your `$PATH`. [`au`](https://github.com/sdrausty/au/blob/master/au) will update and backup your [Termux](https://termux.com/) in three keystrokes!

Every time you want to `apt update && apt upgrade` and `pkg up`, you will also be backing up your former installation debs to `/storage/emulated/0/Android/data/com.termux/txdebs` by using [`au`.](https://github.com/sdrausty/au/blob/master/au) Ideally, you should change `/storage/emulated/0/Android/data/com.termux/txdebs` to an external mirco SD card destination in lines 8 and 10 of [au](https://github.com/sdrausty/au/blob/master/au) to save space on device!

If you find your system unstable, you can use `dpkg --purge pkg_name` and then `dpkg --install pkg_name` from `/storage/emulated/0/Android/data/com.termux/txdebs` to downgrade packages to a previous version of a package in the hope of regaining package stability. Enjoy utilizing [Termux](https://termux.com/) 💪🙂 on device! [Termux](https://termux.com/) is completely amazing on a smartphone and/or a tablet in you pocket! 
<!--au index.md EOF-->

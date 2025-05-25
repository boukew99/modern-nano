# Modern Nano Configuration
Nano is a popular, pre-installed and **accessible** terminal editor. One can use it to do easy system configuration in /etc for example. It works over SSH.

## Installation
For /home usage one can place this file in your user directory.
`mv nanorc ~/.nanorc`
Though in this space one can also use more visual editors.

The real useful use case is to edit system files which require `sudo` privileges. For that install it in system configuration directory. `mv nanorc /etc/nanorc`. However, there will be a file there probably though. On Debian it is the same file, but just with more things commented out. So you need to do `sudo cp nanorc /etc/nanorc`. If you are fine with overwriting it.

Now if you use `nano` you will see the new configuration!

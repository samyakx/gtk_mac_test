# gtk_mac_test

On macOS:
Install Homebrew (if not already installed):

sh

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"


Install GTK:

sh

brew install gtk+3


Compile the Code:

sh

gcc -o hello_gtk hello_gtk.c `pkg-config --cflags --libs gtk+-3.0`


Run the Application:

sh

./hello_gtk


This will open a window with a button labeled "Hello, World!". Clicking the button will print "Hello, World!" to the console.


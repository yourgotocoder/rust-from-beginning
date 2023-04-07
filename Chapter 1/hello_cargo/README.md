## Introducing cargo

Cargo is a handy tool provided by rust that is both the package manager as well as the build tool that we will be using for most of our rust projects.
Creating project with **cargo** is really easy. We just have to use the **cargo new** command. We provide our project name at the end of that command like so: **cargo new hello_word**
This command will create a new folder called **hello_world** within the directory where we executed that command.

This new directory will have a predefined structure. We will mostly be concerned with the **src** directory, there we will find a file called **main.rs**. This is the file that cargo will be using to generate our binaries, thus we will write our logic in that file.
Once we have written our program in the main.rs file, we can build it using the **cargo build** command in our terminal. This will generate a new folder inside our project called **target** that will contain our executable in the **debug** folder.

It will be much easier to see how our executable runs by using the **cargo run** command instead. This command will both build the executable and run it after it is done compiling.



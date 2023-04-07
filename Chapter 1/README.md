## Installation
If you’re using Linux or macOS, open a terminal and enter the following command:
`curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh`

You can go this [link](https://doc.rust-lang.org/stable/book/ch01-01-installation.html) to learn more about the installation process.

## Writing and running your first rust program
All rust files end with the rs extension. i.e Your file will have to have the `.rs` for it to be recognized as a rust file.

Rust programs will have a main function that contains code that will be executed. To create an executable file we have to compile the rust file into a binary by using the **rustc** compiler.
We can compile a rust file by using the following command in our terminal `rustc filename`. For eg: `rustc hello_world.rs` will produce an executable called hello_world in our diretory.
Using **rustc** to compile our files is convenient to create a standalone executable but in real projects where we will be relying on external libraries, it is better to use cargo instead.
The basics of using cargo can be found [here](https://github.com/yourgotocoder/rust-from-beginning/tree/master/Chapter%201/hello_cargo)

# my_cli
A basic implementation of Command Line Interface (CLI) written wholly in Zig.

How you can use this CLI tool:

1. Download the source code.
2. Make sure you have Zig compiler installed on your machine.
3. Open up Command Prompt/Bash.
4. First, build the program using "$ zig build".
5. Now pull the hello menu using "$ ./zig-out/bin/mcli help".

You will be seeing:

   Usage: my-cli <command> [options]

Commands:
  hello    Greet someone
  help     Show this help message

Options for hello:
  -n, --name <value>    Name to greet

$ ./zig-out/bin/my-cli hello
Hello, World!

$ ./zig-out/bin/my-cli hello -n Misbah
Hello, Misbah!

$ ./zig-out/bin/my-cli hello --name Hasan
Hello, Hasan!

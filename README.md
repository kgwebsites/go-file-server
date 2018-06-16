# Go File Server
A simple file server program written in 20 lines of go.

## Instructions
1. Download the file for your operating system, either fs-linux, fs-mac, or fs-windows.exe.
2. On your command line or terminal run the file. `$ ./fs-mac`

By default it will create a file server at the current directory you are at on port 3000.

You can add the flag -port to change the port that your server runs at. `$ ./fs-mac -port 5000`.
You can add the flag -path to change the path that is served at. `$ ./fs-mac -path "~/User/Documents/projects/hello-world"`.
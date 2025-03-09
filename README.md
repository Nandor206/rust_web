## Simple web server in Rust
I started this project as a web app at first, now it's gonna be an Nginx copy, because I got bored doing it web app (I didn't even had any idea what to do).

Some times I use questionable commit messeges, please don't take it seriusly. TY

### Download my app:
#### Linux/Mac (Tested on Fedora 41)
- Fire up the terminal and run this:
```sh
curl -O https://github.com/Nandor206/rust_web/releases/download/v1.1.0/rust_web
curl -O https://github.com/Nandor206/rust_web/releases/download/v1.1.0/config.yaml
```
#### Windows (Not tested)
- Fire up CMD or Powershell and run this:
```sh
curl -O https://github.com/Nandor206/rust_web/releases/download/v1.1.0/rust_web.exe
curl -O https://github.com/Nandor206/rust_web/releases/download/v1.1.0/config.yaml
```

### Config.yaml (doesn't work without it)
Don't worry, if you installed the app right it should be in the same directory as the runnible. (Must be in the same directory as the runnible!)
If you don't happen to have one you can create one with this template:
```yaml
# If empty ("") default is going to be used
# File that will be served (defaults to index.html)
html: ""
# Path where the html can be found (defaults to the same directory where the launcher is found)
path: "./assets"
# If you want custom error 404 page put a 404.html file in the same directory as the other directory
```
### Directory tree:
```
├── assests
│   ├── index.html
│   ├── 404.html
│   └── style.css
├── rust_web
```


### To run the app:
- On Windows:
Run the .exe file
- On Linux/Mac:
Run the file in the terminal:
```sh
./rust-web
```

## TODO:
- Multi page support
- Custom port support
- A normal project name
- Other error support

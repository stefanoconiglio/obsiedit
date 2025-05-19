# obsiedit
A simple script to transparently edit a local file (filesystem) in Obsidian. When invoked on a local file, it will
1. copy the file over to the Obsidian vault specified in `obsiedit` (see further) in the `external_files` folder
2. open a terminal shell and open Obsidian to that file
3. when you are done, pressing RETURN in the terminal shell will copy the file out of Obisidian and back to the filesystem over its previous copy

## Installation
1) Copy `obsiedit` to where you keep your local executable files. Typically it's `/home/USERNAME/bin/` with
`USERNAME=whoami`.
2) Edit `obsiedit` and fill out `VAULT_NAME=""` and `VAULT_PATH=""`
3) Copy `obsiedit_naut` to /home/USERNAME/.local/share/nautilus/scripts/ with with
`USERNAME=whoami` and fill out `FILEPATH=""`

## Usage
1. From command line: `obsidedit myfile.md`
2. From nautilus: right click on `myfile.md`, go under Scripts and select obsieditnaut

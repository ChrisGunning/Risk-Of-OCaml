# risk_of_ocaml
This project is based on the classic board game Risk, built in OCaml. 

## Description
risk_of_ocaml: the classic strategy board game Risk, now in OCaml!

Risk is a game based on diplomacy, conflict, and conquest. Conquer the 
world by controlling armies, making alliances (or enemies!), and capturing 
territories.

The game supports 2 to 6 players, with a GUI map for players to enjoy.

## Installation and Running the Game
This project depends on the [OCaml bindings for Raylib](https://github.com/tjammer/raylib-ocaml) ([Raylib](https://www.raylib.com/)), the [OCaml bindings for Raygui](https://opam.ocaml.org/packages/raygui/raygui.0.6.0/) ([Raygui](https://github.com/raysan5/raygui)), [OUnit](https://github.com/gildor478/ounit) and [Yojson](https://github.com/ocaml-community/yojson) Use the package manager [opam](https://opam.ocaml.org/) to install these dependencies.

### Installing OPAM and initializing an OPAM switch
Follow the directions [here](https://cs3110.github.io/textbook/chapters/preface/install.html#create-an-opam-switch)

### Installing dependencies for Risk_of_OCaml
In a terminal instance, run
```bash
opam depext raylib
```
This command will install the C dependencies of Raylib. Now run
```bash
opam install -y utop odoc ounit2 qcheck bisect_ppx menhir ocaml-lsp-server ocamlformat ocamlformat-rpc raylib raygui yojson
```
to install all dependencies for this game.

## Running the game
In the source directory of the project, run
```bash
make build
```
to build the project. Then run
```bash
make play
```
to run [risk_of_ocaml](https://github.coecis.cornell.edu/jp2369/3110proj) in terminal.

## Contributors
Jimmy Phan, Chris Gunning, Ethan Lin, Nadya Lumy, 

# edgy_boards_reloaded
Decompose electronic circuits into testable, shareable and reusable basic blocks. That is, in essence, what this project is about. Drasticly reduced cost of PCB manufacturing over the last decade as well as a proper open source EDA toolchain with higherarchical sheet support ([KiCad](https://www.kicad.org/)) have led us to rethink how the electronic circuit design workflow should be organized. 
This repository contains the deign requirements which a basic block mus fulfill to be part of this project as well as organized list of repositories where basic blocks can be found. The set of defined interfaces with which blocks can be connected together can be found [here](https://github.com/skunkforce/things_on_edge).

#Contributing
## workflow
1. make a new repository from the tempolate repository XXX either in this organization (if you are a member) or in your own github.
2. make a pull request to this repo with your board name, description and link added to the README.md with status "initial"
3. develope, test and order your board. 
4. make sure you fulfill the quality checklist
5. make a release of your repository
6. make a pull request to this repository with the release version number as well as test.md description of tests.


## quality checklist
1. schemetic is organized such that only the edgy connectors and possible decoupling caps are in the toplevel sheet and everything that could be reused is in its own subsheet (potentially with more subsheets). This will help your users only include the subsheet when composing edgys for a larger design. 
2. put_on_edge is included as a submodule and referenced locally
3. All symbols, footprints and 3d models are contained and referenced in the repository
4. the kicad style follows our style guide
5. a tes.md describing what tests were carried out and their results as well as a readme.md which contains a picture and a description.
6. a 3d model is availible in .stp format
7. it is strongly recommended that the board contain an MIT licence file. If this is not possible it should be clearly noted in the list contained the the README.md of this repo.
8. optional but recommended, the board contains the open hardware logo on the silkscreen

## edgy composition workflow
1. add all edgys used in th e composition as submodules
2. add the subsheets of the respective edgies as higherarchial subsheets in the new design 
3. subsheets should be named after the edgy board from which they come.

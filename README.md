# GameCube Memory Card KiCad

KiCad footprint and symbol for the Memory Card port on a Game Cube.

**WARNING**: Untested. Ordered PCB on Feb 9th, 2024. Will be a hot minute until
I get it back from the fab.

## gc-memcard-adapter

A thanks to [gc-memcard-adapter](https://github.com/jamchamb/gc-memcard-adapter)
for motivating me on this project, as well as some of the Dolphin staff who have
helped me understand the way the data is encoded. This work is to help with
[issue 3](https://github.com/jamchamb/gc-memcard-adapter/issues/3) to allow for
users to use the scripts with a more refind approach than to solder to each
memcard they wish to read/write to.

## Work In Progress

This footprint has been sent to the fab for testing. Once I receive it back
I will post the results on whether or not it fits well enough. Desoldering a
Memory Card port is annoying enough as it is, so I might look into other options
for people who for whatever reason wish to use the gamecube memory card port in
their projects. In a separate repo, I will also be including my own scripts for
reading and parsing GCP/GCI files, including a script to copy a GCI file (either
extracted from a GCP file or exported by Dolphin) to a functional Memcard.

## The Elephant In The Room

This project exists mainly as a testament to the sheer boredum and curiousity
of hackers. Anyone who wishes to back up their saves from their gamecubes, will
have a much easier and cheaper time buying a GameCube and installing Swiss on
it to then copy over the save to a SD Gecko. Desoldering the memory port on a
GameCube is not an easy feat, with the ground plane soaking in a lot of the heat
when reworking, and pins that are really easy to mess up.

Please, do not ruin any motherboards if you want to attempt to follow, and only
buy motherboards that are already broken or are being sold for parts. No
GameCubes were harmed in the making of this project, and we shouldn't be
wasteful and have that change.

## Images

![schematic](https://github.com/DeadlySurgeon/gamecube_memcard_kicad/blob/main/images/schematic.png)

![footprint](https://github.com/DeadlySurgeon/gamecube_memcard_kicad/blob/main/images/footprint.png)

## License

```
    Copyright 2024 deadly.surgery

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use these files except in compliance with the License.
    You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
```

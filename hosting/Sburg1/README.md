# Sburg

This is Team Altgenstuck's fork of the Sburb engine, originally written by the folks at WhatPumpkin. The objective of this fork is to deliver a version of the original engine that is simpler and easier to develop multiple walkarounds for.

## Setup

1. Clone this repository.
2. Run `npm install`
3. ???
4. Profit!

## Running Sburg locally

First, build Sburg and copy `Sburb.min.js` to your project folder (`altgenbound` is used as an example). Then run `npm run start` to start a local web server.
```
$ cd Sburg
$ npm run build
$ mv Sburb.min.js ./projects/altgenbound/
# npm run start
```

## Project layout

The projects in this repo, including HTML, assets, SburbML and other "deployables", should be in a self-contained folder within `./projects`. This differs from the original WP repository which split its levels and resources in the repository root. Each project should be immediately deployable, the only requirement being to drop a copy of `Sburb.min.js` in the project folder root, which can be made at any time by running `npm run build`.

Projects also include a `config.js` file in the project root, which contains settings for things normally hardcoded into the Sburb engine (e.g. chooser colours).

## Copyright notice

Copyright (c) 2012, Alexis Beingessner
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

All artistic and musical assets used in this project are the property of their 
respective creators. They are used in the development of this project with their 
permission. If you fork or otherwise copy this project, you must obtain 
permission from them to use their works. 

For more information, please visit https://github.com/WhatPumpkin/Sburb/wiki

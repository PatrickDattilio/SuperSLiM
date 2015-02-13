[SuperSLiM](http://tonicartos.github.io/SuperSLiM/)
=========
![Maven central version](https://img.shields.io/maven-central/v/com.tonicartos/superslim.svg?style=flat-square)

SuperSLiM is a configurable layout manager for the RecyclerView. It provides a vertical scrolling list of sections. Each section may have a header, and can have its own unique layout. The section layouts can be one of the provided layouts, or can be of your own creation.

SuperSLiM also has a maintained [wiki](https://github.com/TonicArtos/SuperSLiM/wiki) with guides and documentation to help you out.

## Feature Overview
**Section Headers**  
- Sticky headers
- Headers in content margins - *like Google Calendar with Material Design*
- Header overlays

**Section Layouts**  
- Linear
- Grid
- Staggered Grid - *not yet implemented*
- or create your own
 
**Support for RTL languages**  

See the [Roadmap](https://github.com/TonicArtos/SuperSLiM/wiki/Roadmap) for more details and future development.

## Getting Started
### Including in your project
Add the following to your build.gradle file.
```
dependencies {
    compile 'com.tonicartos:superslim:+'
}
```
You can replace the '+' with the exact version if you do not want to always sync to the latest version.

For more detail please refer to the [Getting Started](https://github.com/TonicArtos/SuperSLiM/wiki/Getting%20Started) and [User Guide](https://github.com/TonicArtos/SuperSLiM/wiki/User's%20Guide) wiki pages.

## Support
- [Wiki](https://github.com/TonicArtos/SuperSLiM/wiki)
- [Google+ Community](https://plus.google.com/communities/104097089134643994744)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/superslim) *(Please tag questions with superslim)*.
 
## Samples
Included in the repository.

[![Example App](https://raw.githubusercontent.com/TonicArtos/SuperSLiM/pretty_screencap/example/screencaps/SuperSLiM-demo-small.gif)](https://github.com/TonicArtos/SuperSLiM/tree/master/example)

## Acknowledgements
Thanks to Dave Smith for his introduction to writing a RecyclerView LayoutManager over at [Wires are Obsolete](http://wiresareobsolete.com/), and to Lucas Rocha for his [TwoWayView Library](http://github.com/lucasr/twoway-view/) which is worth checking out too.

## License
```
Copyright (C) 2014 Tonic Artos

SuperSLiM is largely original with some pieces from from Lucas Rocha's TwoWayView Library and the AOSP.

Copyright (C) 2014 Lucas Rocha

Copyright (C) 2014 The Android Open Source Project

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

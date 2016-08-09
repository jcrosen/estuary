<!--
    README.md

    Copyright 2016 Jeremy Crosen

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
-->

# Estuary

## Purpose
A work-in-process project to meet the following needs:

* Deepen my knowledge of clojure and building a system of coordinated services
* Provide a free and open source streaming service solution for educational and personal use
* Have fun

The primary purpose of Estuary as a whole is to enable large-scale stream broadcasting through a combination of small and flexible libraries and applications.  The ideal outcome is a suite of tools that may be useful independently or as parts of a larger whole.  If allowed to fantasize other contributors might choose to innovate further and extend the ecosystem.  But for now it's just a hobby project, so continue at your own peril...



## Organization
_wip_

This repository describes the project as a whole and provides an introduction to the broader public.  It will also function as a collection point for any global project documentation or discussions.

### Overview

* `estuary-streams` - library that implements an interface and reference stream protocols
* `estuary-streamhub` - service that wraps `estuary-streams` and implements an api for managing streams
* `estuary-web` - web service that consumes `estuary-streamer` and provides a user-interface with authentication and serves streams over websockets
* `estuary-play` - browser utilities for consuming streams and presenting the content to users
* `estuary-codecs` - interfaces and implementations for stream content codecs

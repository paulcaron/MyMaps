# My Maps 

## *Your name here*

**My Maps** displays a list of maps, each of which show user-defined markers with a title, description, and location. The user can also create a new map. 

Time spent: **10** hours spent in total

## Functionality 

The following **required** functionality is completed:

* [x] The list of map titles is displayed.
* [x] After tapping on a map title, the associated markers in the map are shown.
* [x] The user is able to create a new map.

The following **extensions** are implemented:

* [x] Change the primary color to red.
* [x] Add the possibility to remove any map by sliding to the right. To this extent, I followed [this tutorial](https://medium.com/@zackcosborn/step-by-step-recyclerview-swipe-to-delete-and-undo-7bbae1fce27e).

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/paulcaron/MyMaps/blob/master/mymaps_walkthrough.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

To add the possibility to remove any map by sliding to the right, I had to create a new class. This class inherits from ItemTouchHelper.SimpleCallback which handles the flag callbacks when dragging and swiping. However, my implementation of maps removal is not persistent.

## License

    Copyright 2020 Paul Caron

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

# DDMathParser

## Documentation

Please see [the DDMathParser wiki](https://github.com/davedelong/DDMathParser/wiki) for up-to-date documentation.

*Note, the linked wiki only supports the Swift version of DDMathParser, and the instructions there WILL NOT work with this version.*

## License

Copyright (c) 2010-2011 Dave DeLong

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


## Note from Sn0wCh1ld

This is absolutely not my project. This is a product of Dave DeLong. It was said by him [here](https://twitter.com/davedelong/status/659818621548400640) that this commit was most likely the final one using only Objective-C. I forked his repo and forced it to update to that commit in order to have a pure ObjC version of DDMathParser.

## How to install
This is partially based on [this](http://stackoverflow.com/questions/6975796/adding-a-simple-library-to-an-xcode-4-project) StackOverflow question.

1. Open Terminal
2. Type ```cd [insert root directory of your project here]``` (for example, cd /Users/Sn0wCh1ld/Desktop/Development/ObjC/Apps/MyApp/), then press enter.
3. Type ```git submodule add https://github.com/sn0wch1ld/DDMathParser-ObjC.git External/DDMathParser```, then press enter.
4. Wait for it to clone and stuff.
5. Once you see ```Mac-Name:YourApp UserName$```, open Xcode.
6. Open your project.
7. Open Finder, go to the project's root directory (same one as before).
8. You should see a folder called "External". Open it.
9. You should see a single folder called "DDMathParser". Open it.
10. You should see a bunch of folders, of which one should be called "DDMathParser". Don't open it.
11. Drag it over into Xcode, right beneath the project file's name (it has a blue Xcode project icon, and is the highest level file in that directory).
12. Check "copy items if necessary", and under the "Added folders" option, select "Create groups". Under the targets menu, check everything.
13. Press finish.
14. In your .m files (for example, ViewController.m), with the other #import lines, or if there are none, beneath the comments at the top, or if there are none of those either, at the very top of the file, add the line ```#import "DDMathParser.h"```.
15. There you go, you should be ready to go!

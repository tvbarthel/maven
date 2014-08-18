Maven
=====

Maven repository for our open-source projects on github.

Usage
=======

To use our libraries, just add our repo as a new maven repository in the top-level build.gradle of your project :

```javascript
allprojects {
    repositories {
        mavenCentral()
        maven {
            url 'https://github.com/tvbarthel/maven/tree/master/'
        }
        ...
    }
}
```

After that, you will be able to add dependency on any project listed bellow.

BlurDialogFragment
=======

A library used to display dialog fragment with a blur effect behind.

Add the following lines to the build.gradle of your module : 

```javascript
dependencies {
    ...
    compile 'fr.tvbarthel.lib.blurdialogfragment:lib:0.0.4@aar'
    compile 'com.android.support:appcompat-v7:19.+'
    ...
}
```

More information : [BlurDialogFragment on GitHub](https://github.com/tvbarthel/BlurDialogFragment)

Credits
========
Credits go to Thomas Barthélémy [https://github.com/tbarthel-fr](https://github.com/tbarthel-fr) and Vincent Barthélémy [https://github.com/vbarthel-fr](https://github.com/vbarthel-fr).

License
=====================
Copyright (C) 2014 tvbarthel

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Material Ripple Layout pre 14
===============

Fork of https://github.com/balysv/material-ripple version 1.0.2 supporting pre 14 devices using
nineoldandroids (http://nineoldandroids.com) library.

Usage
--------------------

Compile and include the release AAR file into your libs folder, then, modify build.gradle to import
the new library as shown (asuming you renamed the file library-release.aar to material-ripple-1.0.2-pre14.aar and placed it into libs folder:

    repositories {
        mavenCentral()
        flatDir{
            dirs 'libs'
        }
    }

    dependencies {
        compile(name:'material-ripple-1.0.2-pre14', ext:'aar')
    }

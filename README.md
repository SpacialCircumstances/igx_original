# IGX

Slightly fixed version of Intergalactics (IGX) source code

Taken from: https://sourceforge.net/projects/igx/
All rights belong to the owners of the original project.
According to sourceforge, the code is GPL 2 licensed, but no license file can be found in the distribution.
I own nothing and take no responsibility.

Original website: [playigx.com (Web archive from 2011)](https://web.archive.org/web/20140510095418/http://playigx.com/)

## Changes

- Removed unused imports that were not available on JDK 8
- Fixed name of bot class
- Added gradle build script

## Building and running

1. Build project with `gradle installDist`
2. Start server with `.\build\install\igx_original\bin\server.bat ./ 50` (PS) or `build/install/igx_original/bin/server ./ 50` (unix)
3. Start client with `.\build\install\igx_original\bin\client.bat localhost` (PS) or `build/install/igx_original/bin/client localhost` (unix)
4. Enjoy

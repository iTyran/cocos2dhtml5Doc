In the tutorial, I will show you how to setup a new cocos2d-html5 project from scratch. Before that, I want to
give you a brief description of cocos2d-html5's directory structures.

# Overview of cocos2d-html5 directory structures
Here is the cocos2d-html5 directory structure:

![directory](directorystructure.png)

##Understanding the directory structure

- The /root/template/  directory is for creating new Cocos2d-html5 projects. All of your games resources, such as images, sounds, background music, config files should go in the /root/template/res. Your own game source code files should go into /root/template/src.

- The /root/Cocos2d/ directory hosts all core engine files, /root/CocosDenshione/ hosts audio engine files, and  /root/extension/ hosts some useful modules, such as EditBox, CocosBuilder Reader and CocoStudio Reader, etc. All these three directories are expanded files, while /root/lib/ have a minified file of these three part together. 

- The /root/box2d/ and /root/chipmunk/ hosts physics engine.

- The /root/HelloHTML5World/ contains a simple hello world.

- The /root/license/ includes all the license files in this project, as we mentioned before, the license of Cocos2d-html5 is MIT, it is the freest license of all open source license.

- The Samples directory, you can find all classes usage in Tests. It also includes sample games. All the tests and games can be run in JSB. This is where you should start from.

- The /root/tools/ directory includes JS Doc tool and closure compiler. The /root/template/build.xml is the config file for closure compiler, you can package your game into single file in advance mode via ANT. What you need to do just add your game js files and then type ant in the console in the directory of /root/template/.



# Taking a look at the built-in examples

There are 2 types of full game samples built-in with Cocos2d-html5. All of the source code are completely free and open to you. Here is a short introduction about these sample games.

## Taking a Look at the Tests
In Figure 5, you open the link named “Test cases”. It will show you the entire tests built-in with Cocos2d-html5. Here is the screenshot:

## Taking a Look at the Sample Games

There are 2 types of full game samples built-in with Cocos2d-html5. All of the source code are completely free and open to you. Here is a short introduction about these sample games


# Setting up your first "Hello World" Project



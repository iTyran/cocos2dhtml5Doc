In the tutorial, I will show you how to setup a new cocos2d-html5 project from scratch. Before that, I want to
give you a brief description of cocos2d-html5's directory structures.

# Overview of cocos2d-html5 directory structures
Here is the cocos2d-html5 directory structure:

![directory](directorystructure.png)

##Understanding the directory structures

The directory structures can be separated into four parts:

### Part1: engine related folders

- The **cocos2d** directory holds all the core engine files. The main components of cocos2d-html5 are implemented in these js files.

- The **CocosDenshion** directory holds all the audio engine related files.

- The **extension** directory holds some useful extension modules, such as EditBox, CocosBuilder Reader and CocoStudio Reader, etc. 

- The folder **box2d** and **chipmunk** are third party physics engine.

### Part2: tests,sample games and template

- The folder **HelloHTML5World** contains a simple **Hello World** sample. When you are new to cocos2d-htlm5, you may want to give it a try. It is the minimax skeleton of a full cocos2d-html5 app.

- The **template** is more or less the same as **HelloHTML5World** except for that **template** is more clean. **Template**  folder is where you should start from. At the end of part of this tutorial, we will create a new project based on this folder.

- The **samples** directory, it contains all the **tests** of cocos2d-html5. It also includes some playable sample games. All the tests and games can be run in iOS and android with javascript binding. 

### Part3: miscellaneous

- The **license** directory includes all the license files in this project, as we mentioned before, the license of Cocos2d-html5 is MIT,you can refer to the folder to get more details about the licenses of cocos2d-html5.

- The **tools** directory includes JS Doc tool and closure compiler. The **template** folder contains a build.xml which is a config file for closure compiler, you can package your game into single file via Ant. 



# Taking a look at the built-in examples

There are 2 types of full game samples built-in with Cocos2d-html5. All of the source code are completely free and open to you. Here is a short introduction about these sample games.

## Taking a Look at the Tests
In Figure 5, you open the link named “Test cases”. It will show you the entire tests built-in with Cocos2d-html5. Here is the screenshot:

## Taking a Look at the Sample Games

There are 2 types of full game samples built-in with Cocos2d-html5. All of the source code are completely free and open to you. Here is a short introduction about these sample games


# Setting up your first "Hello World" Project



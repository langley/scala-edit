# Introduction #

ScalaEdit is an easy to use text editor with built-in Scala and sbt terminals. The sbt (simple build tool) terminal turns ScalaEdit into a powerful development environment for Scala projects. This guide describes how to get started with an sbt project in ScalaEdit. There are a lot of configuration options for sbt that are not covered here. Please see [sbt hompage](https://github.com/harrah/xsbt/wiki) for more info.

# Step by Step #

If you have not done that already you need to download and start ScalaEdit to follow this guide. See description on the [front page](http://code.google.com/p/scala-edit).

  1. Select an empty directory where you want to store your project files with the menu item "Project->Change Root..."
  1. If it is not already done you can make the file list to the left autorefresh by selecting "Project->Auto Refresh"
  1. Start an sbt terminal with "Terminal->SBT Terminal->Version 0.11"
  1. Sbt will now initialize a project folder in the folder you have selected. The target directory will contain the compiled classes.
  1. Use "File->New" to start editing the first file.
  1. Save the file (by pressing the save button or Control-s) as "HelloWorld.scala" in the project directory. Note that it is good practice to put all Scala code in a directory called src/main/scala under your project directory.
  1. Paste in the following content to the file:
> > ```scala

object HelloWorld{
def main(args:Array[String]){
println("Hello World")
}
}```
  1. Save the file
  1. Run the HelloWorld program by pressing the run button in the sbt terminal. If it works you will see Hello World printed out to the terminal.
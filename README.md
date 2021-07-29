# sample_c_app README

**Create a C++ console app project**

Prerequisites

Have Visual Studio with the Desktop development with C++ workload installed and running on your computer. If it's not installed yet, see Install C++ support in Visual Studio. https://docs.microsoft.com/en-us/cpp/build/vscpp-step-0-installation?view=msvc-160

1.	In Visual Studio, open the File menu and choose New > Project to open the Create a new Project dialog. Select the Console App template that has C++, Windows, and Console tags, and then choose Next

![Alt text](https://docs.microsoft.com/en-us/cpp/build/media/vs2019-choose-console-app.png?view=msvc-160)

2.	In the Configure your new project dialog, enter HelloWorld in the Project name edit box. Choose Create to create the project.

![Alt text](https://docs.microsoft.com/en-us/cpp/build/media/vs2019-configure-new-project-hello-world.png?view=msvc-160)

Visual Studio creates a new project. It's ready for you to add and edit your source code. By default, the Console App template fills in your source code with a "Hello World" app:

![Alt text](https://docs.microsoft.com/en-us/cpp/build/media/vs2019-hello-world-code.png?view=msvc-160)

When the code looks like this in the editor, you're ready to go on to the next step and build your app.

**Build and run a C++ console app project**

You've created a C++ console app project and entered your code. Now you can build and run it within Visual Studio. Then, run it as a stand-alone app from the command line.


**Build and run your code in Visual Studio**

1.	To build your project, choose Build Solution from the Build menu. The Output window shows the results of the build process.

![Alt text](https://docs.microsoft.com/en-us/cpp/build/media/vscpp-build-solution.gif?view=msvc-160)

2.	To run the code, on the menu bar, choose Debug, Start without debugging.

![Alt text](https://docs.microsoft.com/en-us/cpp/build/media/vscpp-start-without-debugging.gif?view=msvc-160)

**Run your code in a command window**

1.	In Solution Explorer, select the HelloWorld solution (not the HelloWorld project) and right-click to open the context menu. Choose Open Folder in File Explorer to open a File Explorer window in the HelloWorld solution folder.

2.	In the File Explorer window, open the Debug folder. This folder contains your app, HelloWorld.exe, and a couple of other debugging files. Hold down the Shift key and right-click on HelloWorld.exe to open the context menu. Choose Copy as path to copy the path to your app to the clipboard.

3.	To open a command prompt window, press Windows+R to open the Run dialog. Enter cmd.exe in the Open textbox, then choose OK to run a command prompt window.

4.	In the command prompt window, right-click to paste the path to your app into the command prompt. Press Enter to run your app.

![Alt text](https://docs.microsoft.com/en-us/cpp/build/media/vscpp-run-in-cmd.gif?view=msvc-160)

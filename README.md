# Installing Python with Miniconda and Visual Studio Code

<a href="https://www.youtube.com/watch?v=qMhMeB9dg-g" target="_blank">
  <img src="https://img.youtube.com/vi/qMhMeB9dg-g/0.jpg" alt="Your Video Title" width="560" height="315" border="10"/>
</a>


In this tutorial, we'll be walking through the steps to install Python on your computer using Miniconda and Visual Studio Code. We'll also create a Python environment and run a simple "Hello World" program to make sure everything is working as expected.

## Step 1: Download and Install Miniconda

1. Start by visiting the Miniconda website at [miniconda.org](https://docs.conda.io/en/latest/miniconda.html).
2. Choose the appropriate version for your operating system, either Windows, Mac, or Linux. 
3. Download the installer and run it on your computer. 
4. Follow the instructions to complete the installation process. Make sure to add Miniconda to your system PATH. 

## Step 2: Install Visual Studio Code

1. Visit the Visual Studio Code website at [code.visualstudio.com](https://code.visualstudio.com/).
2. Download the appropriate version for your operating system.
3. Install Visual Studio Code and launch it.

## Step 3: Create a Python Environment

1. Open the Command Prompt or Terminal (depending on your operating system).
2. Type the following command and hit enter:
```conda create --name myfirstenv python=3.7```
3. Wait for the environment to be created. 
4. Once it's done, activate the environment by typing the following command and hitting enter:
```conda activate myfirstenv```
5. To verify that the environment was created and activated successfully, type the following command and hit enter:
```conda info --envs```

## Step 4: Create and Run a "Hello World" Program

1. Click on the File menu, then select New File. 
2. Type in the following code: 
```print("Hello World")```
3. Save the file with a .py extension (e.g., helloworld.py). 
4. In the terminal, type the following command and hit enter:
```python helloworld.py```
5. You should see "Hello World" printed in the terminal.

And that's it! You have successfully installed Python on your computer using Miniconda and Visual Studio Code. If you run into any issues or have any questions, feel free to leave a comment below.

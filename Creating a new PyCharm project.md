
# Getting Started With PyCharm

## Creating a New PyCharm Project

1. When you first open PyCharm, you see three blue rectangular buttons at the center of the screen: `New Project`, `Open`, and `Get from VCS`. To get started, click on the New Project button. If you don't see these rectangular buttons you can choose `File > New Project` from the top of the screen menu.

2. You will get to a new screen called `New Project`. Here on top, you can set a location for your project. I want to store all of my projects for this class in a folder called `idsc3001_projects`. I also want each subject to have a separate project, so I put a `/`  after the `Idsc3001Projects` and then append `fundamentals_project` to the end. This way, I will be storing all class projects in the folder called `Idsc3001Projects`, and in it, each section will have a separate project folder; for example, the `fundamentals_project` folder will contain the code that we are going to write today.

	Now something very critical here. If you pay attention, I don’t use “space”s in the names I give. **Avoiding spaces** is intentional. Because how the space character is used in English to separate words **is not allowed** in programming. To make what you write readable without using the space character, you simply replace the spaces with the “_” character.

3. Under the `New environment using` bullet point, you can choose the project’s “Base interpreter.” Remember that we talked about interpreters in class and learned that they are translators from the Python programming language to the machine language. Here make sure that Python 3. x (x means another number) is selected. If it is not selected, click on the drop-down menu and choose the option that starts with “python 3”. Now,  ff you don’t see such an option, you either do not have Python 3 installed, or PyCharm fails to find the location that it is installed in. If you are sure you have installed Python3 and you know its location, you can set it in the “Location” tab right above the “Base interpret” tab.
4. Last, be sure that you uncheck the “create a main.py welcome script” check box.
5. Once you have done the above steps, click on the create button on the left-bottom corner to create your first project. 
Wait for the project to get created. 
6. Once it is finished, if the Tip of the Day window pops up, check the “Don’t show tips” in the bottom right corner” of the window, so it won’t bother you each time you create or open a project.
 
## Know Your Way Around PyCharm
What you see in front of you may seem complicated and scary, but don’t worry. We will use only one of these tools. Before you start, if you have accidentally changed something, or what you see on the screen does not look like where I begin, from the top menu, select `Window > Restart` Default Layout. For now we will only work with the `Project` tab.

- Project tab: Project is located on the left side, and it shows you what you have in your project’s folder. You can open or close it by clicking on the Project button. 

## Write Your First Python Program
To write your first python program, under the Project tab, right-click on the project’s root (most top) folder. If you have chosen names as I did, it should be called `fundamentals_project`. 

From the opened menu, select `New > Python File`. A `New Python File` window will appear on the screen. Here type a name for your file; you can do it as me and choose the name `hello_word`. Hit enter to create the file. Now, if you look into the Project tab, you should see your `hello_word.py` file. 

**Here are a few points to consider**: As you can see in the Project tab, folders and files are identified by icons to make it easier to distinguish them. This brownish folder icon shows folders, and the python logo indicates python files.

Now is the time to code. Double-Click on the file that you have just build in the Project tab. This will open your file in the big right area of PyCharm, where you can write code. Now write

```python
print("hello world")
```
This is the shortest program that you can possibly write; it is just one line of code. The tradition is that this is the first program in a new programming language.  

## Run Your First Python Program
To run your program for the frist time, right-click on the name of the file in the `Project` tab and select `Run <NAME OF THE FILE>`. It has a green traiangle icon next to it, for example in my case it is `Run 'hello_world'`. Once you click `Run 'hello word'` it runs the program, and adds a new `Run` tab in the bottom bar, and opens up the `Run` window, in which you can show the result of running your program. If what you see in it is something like:

> hello world


> Process finished with exit code 0 

it means that you have successfully run your first program. 

Now that you have run your file, you can see that its name appears in a drop-down menu on the top-right corner, on the left side of the green triagnle that looks like a play button. This green traiangle is called the `Run Button` and it runs the file shown on its left side (the drop down menue). So next time that you want to run your file, check if the name of your file exists in this drop-down menue, if it is there select it it is not already selected, and then click the green `Run Button` to run it. 




 


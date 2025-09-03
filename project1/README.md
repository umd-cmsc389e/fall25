# CMSC389E Project 1 - Tutorial Island

Due: **Friday, September 19th, 2025 at 11:59PM**

Prior to starting **Project 1**, ensure you have went through the entirety of the [Setup README](https://github.com/umd-cmsc389e/fall25/tree/main/setup). 

## Importing Projects
To import the project, you need to download `project1.zip`, extract it, and move it into the `saves` folder of your Fabric installation folder. The easiest way of doing this is the following:

1. Download `project1.zip` from this directory
2. Locate your `./Downloads` folder and extract the contents of `project1.zip` into `project1`
3. Use `Ctrl + X` on the `project1` folder to cut it, saving it into your clipboard
4. Go to your Minecraft Launcher and locate the **Installation Folder** for `fabric-loader-1.20.1`, similar to what you did during setup. Click on "Open installations folder"
![image](https://hackmd.io/_uploads/B1PLvzvwJl.png)
5. Navigate to the `saves` folder, and use `Ctrl + V` to paste `project1`
6. Finally, run Minecraft, go to "Singleplayer", and you should see **Project 0** has been successfully imported!


## Submitting Projects
Projects will be submitted and autograded via **Gradescope**. If you are not already in the **Gradescope**, the join code can be found in the syllabus. To submit the project, you will need to locate your `project1` world file, zip it into `project1.zip`, and submit it into the relevant Gradescope assignment. Here's a step-by-step:

1. Go to your Minecraft Launcher and locate the **Installation Folder** for `fabric-loader-1.20.1`, similar to what you did during setup. Click on "Open installations folder"
![image](https://hackmd.io/_uploads/B1PLvzvwJl.png)
2. Go to the `saves` folder, right click on `project1`, and compress it to **ZIP File**. 
3. Go to the Gradescope assignment and upload the relevant **ZIP File**.

## Notes

* For any of the tasks, **DO NOT** destroy or move the input/output lamps. We hardcode the input/output locations for the autograder to test your builds. 
* You may build outside of the **Gold Blocks**, but we always provide you with enough space to complete your build inside. 
* To receive directions for each of the tasks, **Middle Click** on the **Book and Quill** inside of the **Item Frame**. If you accidentally destroy them, don't worry - we put the instructions here as well.


## Redstone Basics

1. **Produce Signal**
   Connect the input and output with redstone dust to produce an output signal.

2. **Extending Signal Strength**  
   Connect the input and output by extending the redstone signal with a repeater.

3. **Vertical Signal Transmission**  
   Connect the input and output by transmitting the redstone signal up a glass tower.

4. **NOT Gate**  
   Wire the circuit as follows:  
   - When the input is **ON**, the redstone torch is **OFF**, and the output is **OFF**.  
   - When the input is **OFF**, the redstone torch is **ON**, and the output is **ON**.  
   Notice, this is a **NOT gate**!

5.  **Comparator Signal Difference**  
   Use a comparator to output the difference between the signal strength of the blue and green inputs.
   *Hint: Use another comparator!*


## WorldEdit Basics
*For these tasks, utilize the WorldEdit mod. Refer to the [Setup README](https://github.com/umd-cmsc389e/fall25/tree/main/setup) for commands!*

6. **Elevate the Crafting Area**  
   Move this little crafting area 10 blocks upwards into the air.

7. **Multiply Your Wealth**  
   Stack this cube of diamond ore 10 times forward.

8. **Apartment Demolition**  
   Destroy this apartment by setting the entire region to be empty! (lol)

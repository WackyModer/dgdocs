# How to have easier debugging

What this does is it changes the DIR your mod compiles to, then runs the desktop goose executable for easy debugging and testing!

## How to do it

Open your mod SLN file. Then navigate to the solution explorer. Right click the "**DefaultMod**" project file thing and select "**properties**" from the dropdown.

Navigate to "**Debug**" on the right side of the screen and in the "**Start Action**" section of the screen that you see, select "**Start external program**", then select browse. From the window that it opens up, navigate to the desktop goose executable, select that, then click open on the bottom right then save the modifications to the debug options.

After that you must navigate to the "**Build**" tab on the left side of the screen. Then at the bottom it theres a section that says "**Output**". On the item that says "**Output Path**", select browse, and navigate to your "**DefaultMod**" folder in "**Assets/Mods**" then save your debug

Once you do that you can navigate to the "**Solution explorer**", right click "**DefaultMod**", then hover over debug and select start "**New instance**", or "**Start without debugging**", it doesn't matter. 

That's it! Now you can compile your code and have it exported to your mod folder, and have it start running on desktop goose!
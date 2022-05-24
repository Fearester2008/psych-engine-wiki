*On this Example, i will be adding a new difficulty called "Crazy", all charts for this difficulty should end with "-crazy".*

***For adding a new Difficulty in Source you should either:***

# Method 1 (Both Lua and Source code)
## Open the Master Editor Menu
Press 7 on the Main Menu and select the Week Editor.

![](https://i.imgur.com/LLFVnhn.png)

Go to the "Other" tab and write your difficulties names under "Difficulties".

![](https://i.imgur.com/ppvOPJj.png)

# Method 2 (Source code-only)
## Adding to the list

This is probably the easiest part.
Our difficulty will be called `Crazy`, and the chart suffix will be `-crazy`

Open CoolUtil.hx inside `source/`, right at the start, you will see this array:

![](https://i.imgur.com/qjzt2vG.png)

So... add your new difficulty to it, like this.

![](https://i.imgur.com/bgHCHYF.png)

## Files needed

You will need the difficulty image for the Story mode menu, and you're also gonna have to do the Crazy difficulty chart to all songs.
Here's my Crazy difficulty image for an example:

![](https://i.imgur.com/mvaseyY.png)

Put this image inside `assets/preload/images/menudifficulties/` with it being named `crazy.png` and we're ready to go!
If you've done everything alright, it should be in and working properly!

![](https://i.imgur.com/MDzP1PF.png)
![](https://i.imgur.com/qHY7beU.png)

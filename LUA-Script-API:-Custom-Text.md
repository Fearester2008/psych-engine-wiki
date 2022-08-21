# Creating/Adding/Removing a Lua Text
### makeLuaText(tag:String, text:String, width:Int, x:Float, y:Float)
creates a Lua Text object on position `x`, `y` and a width with 'width'

### addLuaText(tag:String)
Spawns a Lua Text on the stage

### removeLuaText(tag:String, destroy:Bool = true)
removes a Lua Text off the stage
* `tag` - The Lua Sprite's tag
* `destroy` - Specifies if you don't want to use the sprite anymore. Default value is `true` (Set to `false` if you want to re-add it later)


### setTextString(tag:String, text:String)
Sets text string at the specified tag


### setTextSize(tag:String, size:Int)
Sets text size at the specified tag

### setTextWidth(tag:String, width:Float)
Sets text width at the specified tag

### setTextBorder(tag:String, size:Int, color:Int)
Sets text border at the specified tag

### setTextColor(tag:String, color:String)
Sets text color at the specified tag

### setTextFont(tag:String, font:String)
Sets text font at the specified tag

### setTextItalic(tag:String, italic:Bool)
Sets text as italic or not based on the ``italic`` parameter

### setTextAlignment(tag:String, alignment:String = 'left')
Sets text alignment at the specified tag
``'left'``,``'right'``, or ``'center'``

### getTextString(tag:String)
Gets text object's text at the specified tag

### getTextSize(tag:String)
Gets text object's size at the specified tag

### getTextFont(tag:String)
Gets text object's font at the specified tag

### getTextWidth(tag:String)
Gets text object's width at the specified tag

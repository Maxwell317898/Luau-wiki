# Methods

**Table of contents** <br>

* **syntax**

* **MORE**

# syntax

```lua
local part = script.parent
part:Destroy()
```
ok look the part is the script's parent 

what we do is the function Destroy (Destroy is a default function) witch will destroy the part and also the script :(

ALSO the function when you are invoking it on a part (eg: ``script.parent``) you must separate the part and the function with a : eg: ``part:Destroy()``

you do not need to do the ``local part = path.to.part.or.reference`` you can also just have a ``game.workspace.part``

# MORE
ok if you want more then ok here is a list it is just that i recommend you play around with this first 
```lua
:Destroy()
:Clone()
:MoveTo(pos) -- modals only i think
:move(pos) -- depracticated
:ScaleTo(perams)
:PivotTo(perams-needed)
:GetChidren(perams-needed)
:GetPropertyChangedSignal()
:ClearAllChildren()
:FindFirstChild()
-- these are only small portion of all the Methods
```
U NEED TO PLAY WITH THESE FIRST IN RBX STUDIO to understand

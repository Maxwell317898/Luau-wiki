# Methods

**Table of contents** <br>

* **syntax**

* **MORE**

# syntax

```lua
local part = script.parent
part:Destroy()
```
the part is a object in the workspace witch we have defined with the local

what we are doing is deleting the parent (the thing the script is in).
but a thing to remeber is that this is only happening in your server,
basicly this will not delete this from studio

this will also delete the childeren of the part or instance you are deleting. so in this instance it would also remove the script

when we use ``:Destroy()`` we are calling the method onto the part or instance before it eg: ``part`` this can also be something like this ``game.workspace.part`` it will still have the same result

## Remote events
when you get better at coding you might want to use a remote event to communicate between the server & client these use the method also as a function like this
```lua
local event = game.replicatedstorage.event
event:FireServer(data, strings)
```
if you are confused about this part just remember this for later
# MORE
ok if you want more then ok here is a list it is just that i reccomend you play around with this first 
```lua
:Destroy()
:Clone()
:MoveTo(pos) -- models only i think
:move(pos) -- deprecated
:ScaleTo(params)
:PivotTo(params-needed)
:GetChidren(params-needed)
:GetPropertyChangedSignal()
:ClearAllChildren()
:FindFirstChild()
-- this is only small portion of all the Methods
```


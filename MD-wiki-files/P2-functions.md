 **Content**

* **Structure of Functions** <br>
* **Calling Functions** <br>
* **Why use functions?** <br>
* **Kinda complicated stuff** <br>



## Structure of functions
In this article we will be using this little key system. Take a Look!
```lua
--[[ Our key
vvv The identifier]]
function hello() --<< the call name
    [insert code here] -- main code
end -- end statement
```
Ok as we see here are some basic rules <br>

The identifier Must Be "function" this shows Roblox that this is a function <br>

The call name can be anything just make sure it ends with ``()`` we will get on to some more thing you do with the ``()`` later  <br>

The end statement Must be ``end`` this just tells Roblox to stop <br>

## **Calling functions**
```lua
function hello()
    print("hello")
end
hello()
```
Ok when we call a function the function must be above (or Defined) the calling being ``hello()`` 

as we see ``hello()`` is defined and is it told to run ``print("hello")``.  functions run the code thay were told to do you call also call a function more then 1 time 

the name of the thing you are calling must be the same as one of the things you have defined or else you will get an error

## **Why use functions?**
We use functions to make our code shorter and not have to re-write all the code instead we use a function

**Here is an example**
```lua
-- my function
function sayhi()
    print("hi")
    if math.random(1, 2) == 1 then
        print("wow i said some text")
    end
end
while true do
    wait(1)
    sayhi()
end
```
> [!IMPORTANT]
> be careful when using ``while true do`` because it can couse lag when running continuously

## **Kinda complicated stuff**
Ok as I said in a function you can have something like this "say(What)" for the call name (bit next to "function") Here is the code (this will make this more understandable)
```lua
function say(What)
    print(What)
end
say("Look here is some cool text")
```
If we were to run this script in the console it would say   ``Look here is some cool text``    If you understand this already you can skip the rest of this section now just look at this code too
```lua
function say(what, type)
    if type == "w" then
        warn(what)
    else
        print(what)
    end
end
say("cool text", "W")
```
When you call or set a call name with double parameters you seperate them with a " , " 

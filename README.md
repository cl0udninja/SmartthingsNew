# Smartthings New

I'm planning to place all the code based on the new Smartthings platform that I'm using from the old Groovy version.

## Whole house fan

The SpringBoot based backend can be found [here](https://github.com/cl0udninja/rPi.QuietCool)

To enable the custom capabitility it is using:
```
X:\dev\SmartthingsNew>smartthings capabilities:create
? Capability Name: Wholehouse Fan Speed
? Select an action... Add an attribute
? Attribute Name:  speed
? Select an attribute type: string
? Maximum length (default: no max length):
? Add a setter command for this attribute? Yes
? If you want to add a basic command, enter a command name now (or hit enter for none):
(Basic commands are simple commands that set the attribute to a specific value.) setHigh
? Command Value:  HIGH
? If you want to add a basic command, enter a command name now (or hit enter for none): setLow
? Command Value:  LOW
? If you want to add a basic command, enter a command name now (or hit enter for none):
? Select an action... Finish & Create
```

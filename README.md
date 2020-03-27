## Welcome to my website!

I love coding and sometimes can't stop!

Here is some of my favorite scripts!

You can use the [editor on GitHub](https://github.com/skeletalz/SkeletalScripts/edit/master/README.md)
### Jailbreak Car TP!
One of my favorite scripts I've made is a jailbreak tp system!
Just replace car with "Camaro" or the name of the car you want
And replace (place) with the CFrame / vector3 you want to be at!
```LUA

local VehicleName = car
   if  workspace.Vehicles[VehicleName].Seat.Player ~= true then
   workspace.Vehicles[VehicleName].PrimaryPart = workspace.Vehicles[VehicleName].Seat
   workspace.Vehicles[VehicleName]:SetPrimaryPartCFrame(workspace[game:GetService("Players").LocalPlayer.Name].HumanoidRootPart.CFrame + Vector3.new(0,5,0))
   
   wait(2)
   -- if you want a car to Teleport then keep the script below
   workspace.Vehicles[VehicleName].PrimaryPart = workspace.Vehicles[VehicleName].Seat
   workspace.Vehicles[VehicleName]:SetPrimaryPartCFrame(place)
```
### Baconator V2 | Piggy Script!!!
Another one of my favorite scripts is Baconator! It is a great Piggy script that is constantly being updated!

```LUA
loadstring(game:HttpGet("https://luawhitelistcheck.000webhostapp.com/BaconatorV2.lua"))()
```

My [Youtube Channel](https://www.youtube.com/channel/UCRfSrYi47Y7kRdoq2G1UHFA?view_as=subscriber) is a place where you can find some of my latest scripts and can become a beta tester!

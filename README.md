# Ex.No:1  Implementing various effects in Unreal Engine
#### Name: Nithishkumar P
#### Register number: 212221230070

## Aim:
To implement various effects in a material such as emissive, roughness and metallic properties in Unreal Engine.
## Algorithm:
### Step 1:
Create new project in unreal engine.
### Step 2:
1. Click Content Drawer -> Content -> Create new folder(Materials) -> Open -> Create new Material -> Rename to material type
### Step 3:
1. For emissive material,
2. Open the blueprint of the created material
3. right click -> Multiply
4. right click -> Constant4Vector -> Select the preferred colour -> Connect the RGB to A Multiply
5. right click -> Constant -> Select the preferred value -> Connect to B Node in Multiply
6. Connect the Result Node of Multiply to Emissive Color
### Step 4:
1. For roughness material,
2. Open the blueprint of the created material
3. right click -> Constant4Vector -> Select the preferred colour -> Connect the RGB to Base Colour Node
4. right click -> Constant -> Select the preferred value -> Connect to Roughness Node
### Step 5:
1. For metallic material,
2. Open the blueprint of the created material
3. right click -> Constant4Vector -> Select the preferred colour -> Connect the RGB to Base Colour Node
4. right click -> Constant -> Select the preferred value -> Connect to Metallic Node
### Step 6:
1. Add new shape in the game world and apply the materials to get various effects.


## Output:
### Emissive material:
![emis](https://user-images.githubusercontent.com/93427017/229302721-a79ece55-aa86-4341-8c09-273ec84fbeca.png)
### Emissive Blueprint:
![emis_blue](https://user-images.githubusercontent.com/93427017/229302847-cb47582e-e37a-48c8-a70c-0a1bfa98b492.png)
### Roughness material:
![rough](https://user-images.githubusercontent.com/93427017/229303303-dc745c6e-45e4-439f-94c5-5564f754e9b3.png)
### Roughness Blueprint:
![rough_blue](https://user-images.githubusercontent.com/93427017/229303363-ca5c4da2-07ae-484d-9bbe-7217f13e0b06.png)
### Metallic material:
![metal](https://user-images.githubusercontent.com/93427017/229303468-92409f64-793c-4e2c-ad64-89ce0537378a.png)
### Metallic Blueprint:
![metal_blue](https://user-images.githubusercontent.com/93427017/229303525-206143fe-f305-4938-968e-5107741ce5ca.png)

## Result:
Thus various effects in a material such as emissive, roughness and metallic properties has been successfully implemented in Unreal Engine.

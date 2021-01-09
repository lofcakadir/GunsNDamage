# GunsNDamage v1.1
*Guns N Damage* is a UE4 plugin that contains gun functionalities and health/damage implementations. This is a very basic add-on for your game to get you started. 

v1.1 Features:
- Gun component with variaous variables you can tweak to create different types of guns. Variables are as follows; damage, distance damage falloff, bullet range, rate of fire, ammo capacity, automatic/semi, pellets per shell, shotgun spread amount, and damage type.

- An event that is called every time gun is triggered. You can add blueprint code to this event to spawn your own visual or audio effects.

- An example bullet trace.

- A health component that keeps track of the health of an actor. Decreases health amount when damage is taken.

- A death event that get's called when health drops down below zero.

---

**For guides and tutorials visit:**
**https://kadirlofca.wixsite.com/kadirlofca/games**

---
```
Plugin Installation:
- Extract plugin file to your project "Plugins" folder. Create one if missing.

- Right click on your project file and "Generate Visual Studio Project Files". Note that you may need to create an empty C++ file via editor before generating project files.

- From the generated Visual Studio file, build your project.

- Launch your project!

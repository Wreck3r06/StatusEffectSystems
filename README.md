# **StatusEffectSystems**
Unreal Engine 5 Plugin for status effects

## What is Status Effect Systems
It is an easy way to introduce status effects. Included with this plugin is 5 premade effects, an actor and an actor component.
The Actor is where the functionality for the effect goes and the actor component is for the instigator of the effect.

---

### How to Create an effect:
1. Create a child of the BP_statusEffects actor
2. Add the events Start Status effect and End status effects
3. Include the S_StatusEffects Structure
4. Create functionality for the effect

---

### How to Apply the Effect
1. Place the AC_StatusEffects Actor component onto the instigator
2. Create a Spawn actor with the status effect actor
3. get the status effect added function from the actor component

---

### Included Effects
1. Paralysis - This effect Stops player movement for a set amount of time
2. Slowing - This effect reduces the players movement speed
3. Speed Boost - This effect increases the players move speed
4. Vision - This disturbs the players vision
5. Poison - Reduces the players health


Note: If you have issues with invalid parent class then just re do the code.
# Creature Battle Project (OOP + Git Branching Practice)
This project is designed to help me learn **object-oriented programming** in Python — especially **inheritance** — while also practicing key **Git concepts** like branching, merging, conflict resolution, and version history.

I will begin with a base class (`Creature`) and create additional subclasses on separate Git branches to simulate a real development workflow.

---
## Learning Objectives

### Python / OOP
- Understand and implement **classes**
- Use **inheritance** to extend behaviors
- Override and extend methods (e.g., `attack()`)
- Practice writing simple test code in `main`

### Git / Version Control
- Create and switch branches
- Merge branches into `main`
- Resolve merge conflicts
- View commit history (`git log --graph --all`)


---
## Project Structure
oop_creature_code/\
├── creature_simulation.py # Base class + subclasses\
└── README.md

## Project Structure
Class Creature (Parent Class)\
├── FlyingCreature (Child Class)\
├── SwimmingCreature (Child Class)\
└── FireCreature (Child Class)

* Monster = SubClass of Creature (FlyingCreature, etc)

Creature is a parent class which have attribute such as (name, hp, attack_power)
and method attack(), is_alive()
All this attribute and method is inheritance by Monster which will have additional method for itself and Override the attack method() to reflect each Monster attack type.

## Test & run program
```
python creature_simulation.py
```

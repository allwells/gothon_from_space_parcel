# Python Text Game
### Title
Gothons from Planet Percal

### Category
Space Adventure


### Game Plot
Aliens have invaded a space ship and our hero has to go through a maze of rooms defeating them so he can escape into an escape pod to the planet below. The game will be more like a Zork or Adventure type game with text outputs and funny ways to die. The game will involve an engine that runs a map full of rooms or scenes. Each room will print its own description when the player enters it and then tell the engine what room to run next out of the map.


## Scenes

#### Death
This is when the player dies and should be something funny.

#### Central Corridor
This is the starting point and has a gothon already standing there that the players will have to defeat with a joke before continuing.

#### Laser Weapon Armory
This is where the hero gets a neutron bomb to blow up the ship before getting to the escape pod. It has a keypad the hero has to guess the number for.

#### The Bridge
This is another battle scene with a Gothon where the hero places the bomb.

#### Escape Pod
This is where the hero escapes but only after guessing the right escape pod.


### Key Concepts
| `Alien` | `Player` | `Ship` | `Maze` | `Room` | `Scene` | `Gothon` | `Escape Pod` | `Planet` | `Map` | `Engine` | `Death` | `Central Corridor` | `Laser Weapon Armory` | `The Bridge` |

### Class Hierarchy
* Map
	_`next_scene`_
	_`opening_scene`_
* Engine
	_`play`_
* Scene
    _`enter`_
* Death
* Central Corridor
* Laser Weapon Armory
* The Bridge
* Escape Pod

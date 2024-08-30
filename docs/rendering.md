
# rendering

## immediate mode debug rendering

Sometimes, you want to do something akin to drawing a line between two points (to visually show a raycast for the purpose of debugging).
To achieve this in yoyoengine, you can call one of the few functions:

### C API

```c
void ye_debug_line(int x1, int y1, int x2, int y2, SDL_Color color);

void ye_debug_rect(int x, int y, int w, int h, SDL_Color color);
```

### Lua API

```lua
-- WIP
```

## additional rendering outside of ECS entities

For many games, you might also want the ability to render things that are outside of the scope of ECS entities. For example, you might want to render a custom HUD or a menu that arent defined by entities in the scene.

To do this, check out the [C scripting docs](Scripting/C%20Scripting/c_scripting.md), specifically the section on callbacks.

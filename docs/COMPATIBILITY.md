# Compatibility

The standalone carries forward the visual engine previously tested by the project owner. That report does not guarantee compatibility with all clients, runtime versions or devices.

The script uses client-side APIs. The optional loader additionally requires loadstring and game:HttpGet from the runtime.

Limitations:
- Visual changes are local.
- FPS is estimated from Heartbeat, not measured by a profiler.
- No fixed FPS, RAM reduction, ping reduction or server-performance improvement is promised.
- Asset memory use may not fall when textures are hidden.
- Local collision changes do not override authoritative server behavior.
- Environment classification is heuristic and may need per-experience adjustments.

This Basic release contains no key system and no Premium Server Finder.

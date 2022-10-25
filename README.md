# LuaBridge

- Call Lua methods directly from Kotlin
- Converts argument and response types
- Lua Callback functions allow you to pass callbacks from Lua to Kotlin and call them.
- Expose a set of @JVMStatic methods to Lua that you define.

## Security

I haven't fully checked to ensure you can't call the API incorrectly and cause a crash yet, but in normal execution everything works well.

## Setup

You just need to unpack `lua-5.4.4` as `./lua-bridge/lua-5.4.4`.

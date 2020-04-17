# Examples from the [vulkan library](https://hackage.haskell.org/package/vulkan/)

... pulled into a standalone package

# Files

- `./src/ExSDL.hs` is a modified version of `./examples/sdl-triangle/Main.hs`
- `./src/Info.hs` is a modified version of `./examples/info/Main.hs`

# Issues

Currently, the `Info` example works, but the `ExSDL` example doesn't.
`ExSDL` gives this error:

    VulkanException {vulkanExceptionResult = ERROR_INITIALIZATION_FAILED}

Which seems to occur when creating the device (line 452).

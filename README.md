# Kimi-Voxel

My personal project — a voxel game engine written in Rust with GPU rendering.

## Current State

The latest version may lag due to the subvoxel system. If you want stable performance, you can disable or remove subvoxels in the code.

## Features

- Procedural terrain generation with biomes
- GPU voxel rendering via WGPU
- Cascaded shadow maps (CSM)
- Subvoxel system (experimental, causes performance issues)
- Audio: footsteps, jumps, block placement sounds
- World save/load system
- Inventory and hotbar

## Want to Help?

Any help is welcome! If you want to contribute:

- Fork the repository
- Make your changes
- Submit a Pull Request

Areas where help is especially needed:
- Subvoxel optimization
- World generation improvements
- Bug fixes

## Building

```bash
cargo build --release
```

## Running

```bash
cargo run --release
```

## Controls

- WASD — movement
- Space — jump
- Mouse — look around
- LMB — break block
- RMB — place block

## Requirements

- Rust 1.70+
- GPU with Vulkan/Metal/DX12 support

## License

MIT — do whatever you want with the code

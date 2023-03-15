```rust
pub struct Willothy {
    interests: Vec<&'static str>,
    projects: Vec<Project>
}

impl Default for Willothy {
    fn default() -> Self {
        Willothy {
            interests: vec![
                "Compilers",
                "OS Dev & Systems Programming",
                "Neovim",
                "Rust"
            ],
            projects: vec![
                Project::NeovimPlugin("flatten.nvim", Lang::Lua),
                Project::NeovimPlugin("moveline.nvim", Lang::Rust),
                Project::Library("nvim-utils", Lang::Rust),
                Project::Compiler("sharp", Lang::Rust),
            ]
        }
    }
}
```

![Stats](https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=willothy&layout=compact&theme=dracula)

[![Neovim](https://img.shields.io/badge/NeoVim-%2357A143.svg?&style=for-the-badge&logo=neovim&logoColor=white)](https://github.com/willothy?tab=repositories&q=nvim&type=public&language=&sort=stargazers)
[![Rust](https://img.shields.io/badge/Rust-black?style=for-the-badge&logo=rust&logoColor=#E57324")](https://github.com/willothy?tab=repositories&q=&type=public&language=rust&sort=stargazers)
[![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white")](https://github.com/willothy?tab=repositories&q=&type=public&language=lua&sort=stargazers)
[![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)](https://github.com/willothy?tab=repositories&q=&type=&language=c&sort=stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/willothy?tab=repositories&q=&type=&language=typescript&sort=stargazers)


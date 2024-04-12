# Nix flakes to initialize dev environments

```shell
# Initialize in the current project
nix flake init --template github:the-nix-way/dev-templates#rust

# Create a new project
nix flake new --template github:the-nix-way/dev-templates#rust ${NEW_PROJECT_DIRECTORY}
```

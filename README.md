# Nix flakes to initialize dev environments

```shell
# Initialize in the current project
nix flake init --template github:throttle2k/dev-templates#rust

# Create a new project
nix flake new --template github:throttle2k/dev-templates#rust ${NEW_PROJECT_DIRECTORY}
```

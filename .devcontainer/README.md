# Development Container Configuration

This directory contains the configuration for the GitHub Codespaces development container.

## What's Included

This development container provides a complete environment for working with the AI Readiness Primer Quarto website:

- **Base Image**: R development environment (rocker-org/devcontainer/r-ver:4)
- **Quarto CLI**: Latest version installed via dev container features
- **VS Code Extensions**:
  - `quarto.quarto` - Official Quarto extension for VS Code
  - `ms-vscode.live-server` - Live server for quick previews
- **Port Forwarding**: Automatic forwarding of port 4848 (Quarto preview server)
- **Post-Create Check**: Runs `quarto check` to verify installation

## Using the Dev Container

### With GitHub Codespaces

1. Navigate to the repository on GitHub
2. Click the "Code" button
3. Select the "Codespaces" tab
4. Click "Create codespace on main"

The container will automatically set up, and you'll be ready to work within a few minutes.

### With VS Code Locally

If you have Docker installed and the "Dev Containers" extension for VS Code:

1. Open the repository folder in VS Code
2. Press `F1` and select "Dev Containers: Reopen in Container"
3. Wait for the container to build and start

## Working with Quarto

Once your dev container is running, you can use standard Quarto commands:

```bash
# Preview the site (accessible on forwarded port 4848)
quarto preview

# Render the site
quarto render

# Check Quarto installation
quarto check
```

The preview server will be automatically accessible through the forwarded port.

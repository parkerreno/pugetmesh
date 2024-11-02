# PugetMesh
This is the docfx repo used to power the PugetMesh website.  Want to update or add something?  Open a PR and we'll review it.

## Getting Started
Once you have the repo cloned, here are the steps to get it up and running!

1. Install .NET - as of writing 8 is the latest release and LTS, 6 or higher is required.  Download it from [dot.net](https://dot.net/download) or use one of the commands below:
    <details>
    <summary>WinGet (Windows)</summary>
    ```
    winget install Microsoft.DotNet.SDK.8
    ```
    </details>

    <details>
    <summary>Homebrew (macOS)</summary>
    ```
    brew install --cask dotnet-sdk
    ```
    </details>

    <details>
    <summary>APT (Debian/Ubuntu)</summary>
    ```
    sudo apt-get update && \
    sudo apt-get install -y dotnet-sdk-8.0
    ```
    </details>
2. Install docfx
    ```
    dotnet tool install -g docfx
    ```
3. Run docfx (kill & rerun after making changes)
    ```
    docfx --serve
    ```

For more information on docfx, see https://dotnet.github.io/docfx/
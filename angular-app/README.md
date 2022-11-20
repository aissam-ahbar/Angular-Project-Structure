# Project Structure

## .editorconfig

Configuration for code editors. See EditorConfig.

## .gitignore

Specifies intentionally untracked files that Git should ignore.

## README.md

Introductory documentation for the root application.

## angular.json

CLI configuration defaults for all projects in the workspace, including configuration options for build, serve, and test tools that the CLI uses, such as Karma, and Protractor. For details, see Angular Workspace Configuration.

## package.json

Configures npm package dependencies that are available to all projects in the workspace. See npm documentation for the specific format and contents of this file.

## package-lock.json

Provides version information for all packages installed into node_modules by the npm client. See npm documentation for details. If you use the yarn client, this file will be yarn.lock instead.

## node_modules/

Provides npm packages to the entire workspace. Workspace-wide node_modules dependencies are visible to all projects.

## tsconfig.json

The base TypeScript configuration for projects in the workspace. All other configuration files inherit from this base file. For more information, see the Configuration inheritance with extends section of the TypeScript documentation.

## src/

Source files for the root-level application project.


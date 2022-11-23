# Angular Project Structure

## src/

Source files for the root-level application project.

- File Structure Overview :

![Alt text](https://github.com/aissam-ahbar/Angular-Project-Structure/blob/main/src/assets/image.png?raw=true 'Angular Project Overview')

- File Tree (Entry point main.ts | index.html) :

![Alt text](https://github.com/aissam-ahbar/Angular-Project-Structure/blob/7166fa5181bd24288a6db512708f4fe9ad515667/src/assets/overview.png?raw=true 'Files Tree')

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

## tsconfig.spec.json

TypeScript configuration for the application tests. See TypeScript Configuration.

## tsconfig.app.json

Application-specific TypeScript configuration, including TypeScript and Angular template compiler options. See TypeScript Configuration and Angular Compiler Options.

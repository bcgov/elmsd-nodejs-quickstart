# {{ cookiecutter.name }}


## Usage

Open the `{{ cookiecutter.name }}.code-workspace` in Visual Studio Code.  This contains all extensions you will need for automatic linting and managing the project.

Add your projects to the `packages` folder.  If the `packages` folder does not already exist, create it.  See below for the expected project structure.

```
📦 {{ cookiecutter.name }}
 ┣ ...
 ┣ 📂 packages
 ┃ ┣ 📂 project-a
 ┃ ┗ 📂 project-b
 ┗ ...
```
This monorepo uses npm workspaces.  See [here](https://docs.npmjs.com/cli/v7/using-npm/workspaces) for more information on how to interact with workspaces.

## Setting up `changeset-bot`
Configure the `changeset-bot` on your GitHub repository.  See [here](https://github.com/apps/changeset-bot) for more information.
## License

```
Copyright 2022 Province of British Columbia

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

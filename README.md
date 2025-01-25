<img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white">

# ng-angular-structure-cli

Folder structure generator for Angular projects, automatically organizing components, services, guards, and other elements into a modular and maintainable architecture.

## Quick Usage
If you don't want to install the script, just copy and run this command in your Angular project:

```bash
mkdir -p src/app/{core/{guards,interceptors,interfaces,services},features/{navbar,header,footer},pages/{admin,home,login,"not-found"},shared/{components,directives,pipes}}
```

## Installation

```bash
git clone https://github.com/FlorianBx/ng-angular-structure-cli.git
```

### MacOS Setup
<details open>
<summary>BASH & ZSH</summary>

1. Add alias to your shell config (~/.zshrc or ~/.bashrc):
```bash
mkdir -p ~/bin
cp ng-struct.sh ~/bin/ng-struct.sh
chmod +x ~/bin/ng-struct.sh
echo 'alias ng-struct="~/path/to/ng-angular-structure-cli/create-structure.sh"' >> ~/.zshrc
```
2. Reload your shell config:
```bash
source ~/.zshrc
```
</details>

<details>
<summary>FISH</summary>
1. Add alias to your shell config (config.fish):
```bash
mkdir -p ~/bin
cp ng-struct.sh ~/bin/ng-struct.sh
chmod +x ~/bin/ng-struct.sh
echo 'alias ng-struct="~/bin/ng-struct.sh"' >> ~/.config/fish/config.fish
```

2. Reload your shell config:
```bash
source ~/.zshrc
```

</details>

### Windows Setup
*Open to contributions!*
<details>
<summary>BASH & ZSH</summary>

1. Add alias to your shell config (~/.zshrc or ~/.bashrc):
```bash
mkdir -p ~/bin
cp ng-struct.sh ~/bin/ng-struct.sh
chmod +x ~/bin/ng-struct.sh
echo 'alias ng-struct="~/path/to/ng-angular-structure-cli/create-structure.sh"' >> ~/.zshrc
```
2. Reload your shell config:
```bash
source ~/.zshrc
```
</details>

## Usage

In your Angular project root directory:

```bash 
ng-struct
```

## Generated Structure

```
src/
└── app/
    ├── core/
    │   ├── guards/
    │   ├── interceptors/
    │   ├── interfaces/
    │   └── services/
    ├── features/
    │   ├── navbar/
    │   ├── header/
    │   └── footer/
    ├── pages/
    │   ├── admin/
    │   ├── home/
    │   ├── login/
    │   └── not-found/
    └── shared/
        ├── components/
        ├── directives/
        └── pipes/
```

## License
MIT

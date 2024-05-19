# MTRGen Template Highlighting

Syntax highlighting for MTRGen including HTML, Markdown, YAML and more...

![IDE](https://raw.githubusercontent.com/matronator/mtrgen-vscode/main/screenshot.png)

## Languages:

Introduces syntax highlighting into vscode for the following languages:

### MTRGen Raw

Raw MTRGen templates: system name `mtrgen`.

no file default associations.

### MTRGen HTML

MTRGen HTML templates: system name `mtrgen-html`.

Default file associations: `.html.mtr`.

### MTRGen XML

MTRGen HTML templates: system name `mtrgen-xml`.

Default file associations: `.xml.mtr`.

### MTRGen CSS

MTRGen HTML templates: system name `mtrgen-css`.

Default file associations: `.css.mtr`.

### MTRGen JSON

MTRGen JSON templates: system name `mtrgen-json`.

Default file associations: `.json.mtr`.

### MTRGen Markdown

MTRGen markdown templates: system name `mtrgen-md`.

Default file associations: `.md.mtr`.

### MTRGen YAML

MTRGen YAML (sls) templates: system name `mtrgen-yaml`.

Default file associations: `.yaml.mtr`, `.yml.mtr`, and `.sls.mtr`.

### MTRGen TOML

MTRGen TOML templates: system name `mtrgen-toml`.

Default file associations: `.toml.mtr`.

### MTRGen LaTeX

MTRGen latex templates: system name `mtrgen-latex`.

Default file associations: `.latex.mtr` and `.tex.mtr`.

### MTRGen Lua

MTRGen Lua templates: system name `mtrgen-lua`.

Default file associations: `.lua.mtr`.

### MTRGen Properties

aka config / cfg / ini file: system name `mtrgen-properties`.

Default file associations: `.properties.mtr`, `.cfg.mtr`, `.conf.mtr`, `.desktop.mtr`, `.directory.mtr` and `.ini.mtr`.

### MTRGen Shell Scripts

MTRGen shell/bash/zsh templates: system name `mtrgen-shell`.

Default file associations (same as for the `shell` language with `.mtr` appended):
`.sh.mtr`, `.bash.mtr`, `.bashrc.mtr`, `.bash_aliases.mtr`, `.bash_profile.mtr`,
`.bash_login.mtr`, `.ebuild.mtr`, `.install.mtr`, `.profile.mtr`, `.bash_logout.mtr`, `.zsh.mtr`, `.zshrc.mtr`,
`.zprofile.mtr`, `.zlogin.mtr`, `.zlogout.mtr`, `.zshenv.mtr`, `.zsh-theme.mtr` and `.ksh.mtr`.

### Dockerfiles

Dockerfile templates: system name `mtrgen-dockerfile`.

Default file associations: `.dockerfile.mtr`.

Unfortunately associating `mtrgen-dockerfile` with file names like `Dockerfile.mtr` doesn't seem to work.

### MTRGen SQL

MTRGen SQL templates: system name `mtrgen-sql`.

Default file associations: `.sql.mtr`.

### MTRGen Python

MTRGen python templates: system name `mtrgen-py`.

Default file associations: `.py.mtr` and `.pyi.mtr`.

### MTRGen Cython

MTRGen cython templates: system name `mtrgen-cy`.

Default file associations: `.pyx.mtr`, `.pxd.mtr` and `.pxi.mtr`.

### MTRGen Terraform / HashiCorp configuration language

MTRGen Terraform templates: system name `mtrgen-terraform`.

Default file associations: `.tf.mtr`, `.tfvars.mtr` and `.hcl.mtr`.

### MTRGen Nginx

MTRGen Nginx Conf templates: system name `mtrgen-nginx`.

Default file associations: `.conf.mtr`.

### MTRGen Groovy

MTRGen Groovy templates: system name `mtrgen-groovy`.

Default file associations: `.groovy.mtr`.

### MTRGen Systemd Unit Files

MTRGen Systemd Unit File templates: system name `mtrgen-systemd`.

Default file associations: `.link.mtr`, `.netdev.mtr`, `.network.mtr`, `.service.mtr`, `.socket.mtr`, `.device.mtr`, `.mount.mtr`, `.automount.mtr`, `.swap.mtr`, `.target.mtr`, `.path.mtr`, `.timer.mtr`, `.snapshot.mtr`, `.slice.mtr` and `.scope.mtr`.

### MTRGen C++

MTRGen C++ templates: system name `mtrgen-cpp`.

Default file associations: `.c.mtr`, `.cpp.mtr` and `.h.mtr`.

### MTRGen Java

MTRGen Java templates: system name `mtrgen-java`.

Default file associations: `.java.mtr`.

### MTRGen JavaScript

MTRGen JavaScript templates: system name `mtrgen-js`.

Default file associations: `.js.mtr`.

### MTRGen TypeScript

MTRGen TypeScript templates: system name `mtrgen-ts`.

Default file associations: `.ts.mtr`.

### MTRGen PHP

MTRGen PHP templates: system name `mtrgen-php`.

Default file associations: `.php.mtr`.

### MTRGen Cisco IOS

Cisco IOS configuration templates: system name `mtrgen-cisco`.

Default file associations: `.ios.mtr`, `.cisco.mtr`

### MTRGen Rust

MTRGen Rust templates: system name `mtrgen-rust`.

Default file associations: `.rs.mtr`

## Extra File Associations

You can add more file associations, for example to associate `.html` files with `mtrgen-html`;
in your user or workspace settings add:

```json
"files.associations": {
  "*.html": "mtrgen-html"
},
```

## Breakpoints Support

Allows to set breakpoints in template file.
In order to correctly debug template add `"mtrgen": true` option to your configuration in `launch.json` file.

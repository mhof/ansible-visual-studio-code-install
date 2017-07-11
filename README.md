# ansible-visual-studio-code-install

Install Visual Studio Code on Fedora

## Requirements

N/A

## Role Variables

- visual_studio_code_package: Package to install using dnf
- vs_code_extensions: List of extensions to install
- vs_code_font: Set font size in VSCode
- vs_code_gpm_base_project_folders: Add default folders for Git Project Manager

## Dependencies

N/A

## Example Playbook

    - hosts: localhost
      roles:
         - { role: ansible-visual-studio-code-install }

## License

MIT

## Author Information

https://github.com/mhof

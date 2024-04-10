[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/nfa-vfxim/tk-nuke-writenode?include_prereleases)](https://github.com/nfa-vfxim/tk-nuke-writenode) 
[![GitHub issues](https://img.shields.io/github/issues/nfa-vfxim/tk-nuke-writenode)](https://github.com/nfa-vfxim/tk-nuke-writenode/issues) 


# ShotGrid Nuke Write Node <img src="icon_256.png" alt="Icon" height="24"/>

Support for the ShotGrid Write Node in Nuke.

> Supported engines: tk-nuke

## Requirements

| ShotGrid version | Core version | Engine version |
|------------------|--------------|----------------|
| -                | v0.14.28     | -              |

## Configuration

### Lists

| Name         | Description                                | Default value |
|--------------|--------------------------------------------|---------------|
| `categories` | A list of all the categories configurered. |               |


### Templates

| Name                   | Description                                      | Default value | Fields                      |
|------------------------|--------------------------------------------------|---------------|-----------------------------|
| `template_script_work` | Template for the Nuke script to get fields from. |               | context, version, [name], * |


### Strings

| Name                 | Description                                                  | Default value |
|----------------------|--------------------------------------------------------------|---------------|
| `default_category`   | Default category to select in the write node creation panel. | prerender     |
| `main_category_name` | Main category to use for output of the Nuke script           | main          |
| `main_write_name`    | Name to use for the output of the Nuke script                | main          |



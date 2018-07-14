Irrigation Package for Home Assistant

This package is used to water an 8 zone garden. The valves are powered with a relay board controled by a NodeMcu running Tasmota.

Create a folder named “packages” in your Home Assistant configuration directory.
In the packages directory you can store any number of packages in a YAML file.

To use packages in Home Assistant add the following to your configuration.yaml

homeassistant:
  packages: !include_dir_named packages/

Add the files from this packages/ to your folder.
Also to keep things all nice add the lines from the groups.yaml to your groups.yaml.


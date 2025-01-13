Repo to translate the work done by superduper1669 in the Tweakers forum (https://gathering.tweakers.net/forum/list_messages/2282240) to a single file package.yaml file.
To use this in your Home Assistant setup add this block to your main configuration.yaml file:
```

homeassistant:
  packages: !include_dir_named packages
```

create a subfolder called packages and copy the "marstek_venus_battery_control.yaml" file from this repo to the folder => 
/config/packages/marstek_venus_battery_control.yaml

Restart your Home Assistant 

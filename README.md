# Godot Game Jam Starter

## How to use
1. Do a global replace for <game-name> to the name of your game (impacts [deploy_metadata.yaml](deploy_metadata.yaml), [export_presets.cfg](export_presets.cfg), [project.godot](project.godot))
2. Do a global replace for <game-url> using https://vanny96.itch.io/<game-url> (impacts [deploy_metadata.yaml](deploy_metadata.yaml))
3. Setup the `BUTLER_API_KEY` secret. You can get it from https://itch.io/user/settings/api-keys
4. Now open your project in Godot!

## What does it include?

* Pipeline to publish on itch.io when pushing a tag `release-*`
* Debugger utility to reload scenes and display useful information 
* Main menu template
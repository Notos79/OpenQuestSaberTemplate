# OpenQuestSaberTemplate
Unity project template to make custom saber model bundles for OpenQuestSaberVR.

## Usage
-Copy the "Sabers" prefab from DefaultSabers into a separate directory (must keep the same name).\
-Open prefab.\
-Add model to the appropriate child (Left or Right).\
Use the existing blades to get models to the correct scale and position (blade length must match), then remove the old models.\
-Change asset bundle to what you want.\
-Add 2d texture called "Icon" (256x256), with the same asset bundle.\
-Build from the menu "Assets/Build AssetBundles".\
-Place the asset bundle and .manifest from "Assets/AssetBundles" to the folder on the Quest "sdcard/Android/data/com.coldstan.openquestsaber/files/sabers".

### Optional
Collider components can be added to Left and Right so that the sabers can collide with each other (default colliders used otherwise).

## Generating Icons
Icons can be generated using the IconScene.\
-Add saber prefab to the scene, move them how you want.\
-Select "Assets/IconRenderTexture", click the gear in the inspector and then "Export".

## Links
  [OpenQuestSaberVR](https://github.com/ColdStan/OpenQuestSaberVR)

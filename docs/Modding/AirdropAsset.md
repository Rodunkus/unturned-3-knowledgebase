# Airdrop Asset

!!! note "This is an [Asset v2](Asset%20Types/AssetsV2.md) class."

Overrides the care package model seen falling from the dropship, as well as the barricade spawned when it lands on the ground. Referenced by the [Level Asset](mapmaking/LevelAsset.md).

`Landed_Barricade` [Asset Pointer](AssetPtr.md): barricade item storage asset. Pivot point of the spawned barricade matches the pivot point of the care package as it hit the ground.

`Carepackage_Prefab` [Master Bundle Pointer](MasterBundlePtr.md): model to spawn falling.



Signatures:
[NEW] GWorld: 48 89 05 ? ? ? ? 44 38 3D ? ? ? ?
FreeFN: 48 89 D1 48 FF 25 ? ? ? ? C3
BoneMatrix: E8 ? ? ? ? 0F 10 40 68
ProjectWorldToScreen: 40 53 55 56 57 41 56 48 81 EC ? ? ? ? 48 8B 05 ? ? ? ? 48 33 C4 48 89 84 24 ? ? ? ? 33 DB 49
GObjects: 48 8B 05 ? ? ? ? 48 8B 0C C8 48 8B 04 D1
[NEW] GetNameByIndex: 48 89 5C 24 ? 48 89 6C 24 ? 48 89 74 24 ? 57 48 81 EC ? ? ? ? 48 8B 05 ? ? ? ? 48 33 C4 48 89 84 24 ? ? ? ? 33 ED 48 8B FA 48 89 2A 48 89 6A 08 8B
LineOfSightTo: 48 8B C4 48 89 58 20 55 56 57 41 54 41 56 48 8D 68
StaticFindObject: 48 89 74 24 ?? 48 89 7C 24 ?? 55 41 54 41 55 41 56 41 57 48 8B EC 48 83 EC ?? 4C 8B E9 48 8D 4D E8


VTables:
[NEW] DrawTransition: 0x70 [112]
[NEW] ViewportClient: 0x71 [113]
[NEW] PostRender: 0x6F [111]
[NEW] ProcessEvent: 0x4C [76]
GetPlayerViewPoint: 0x7F0
SetControlRotation: 0x760
GetCameraLocation: 0x808
GetCameraRotation: 0x800
GetFOVAngle: 0x7C0
LineOfSightTo: 0x770
[NEW] AddPitchInput: 0xCF0
[NEW] ClientSetCameraMode: 0xA08
[NEW] AddYawInput: 0xCF8

Offsets: [ALL NEW]
UWorld: 0x1123AF78
FreeFn: 0xC566C28
GetBoneMatrix: 0x149B864
ProjectWorldToScreen: 0x35BD6A8
GObjects: 0x11213D40
GetNameByIndex: 0x1004854
LineOfSightTo: 0x65403D0
StaticFindObject: 0x3EDBF1C

Other New Offsets:
RelativeLocation: 0x120
RelativeRotation: 0x138
OwningGameInstance: 0x1D0
WeaponData: 0x4A8
ComponentVelocity: 0x168
SeasonLevelUIDisplay: 0x10F8
CurrentWeapon: 0xA20
CurrentVehicle: 0x2840
CachedFuelComponent: 0x1250
CustomTimeDilation: 0x68
BIgnoreTryToFireSlotCooldownRestriction: 0x1359
GlobalAnimRateScale: 0xA68

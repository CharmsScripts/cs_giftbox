# CS Gift Box

A clean two-box starter gift system for ox_inventory.

## Female Gift Box

- $10,000 cash
- 1 Pistol
- 30 Pistol Ammo
- 1 Vehicle Voucher

## Male Gift Box

- $10,000 cash
- 1 Pistol
- 30 Pistol Ammo
- 1 Wheel Spin

Every reward is guaranteed.

## Supported Frameworks

- QBox
- QBCore
- ESX
- Standalone fallback

## Installation

1. Place `cs_giftbox_clean` in your resources folder.
2. Copy the entries from `install/items.lua` into:
   `ox_inventory/data/items.lua`
3. Add the item images to:
   `ox_inventory/web/images/`
4. Add this to server.cfg after your framework and ox_inventory:

```cfg
ensure ox_lib
ensure ox_inventory
ensure cs_giftbox_clean
```

5. Restart the server.

## Item Names

The default names are:

```lua
WEAPON_PISTOL
ammo-9
vehicle_voucher
wheelspin
```

Change them in `config.lua` if your server uses different names.

## Gender Restriction

Female characters can only open `giftbox_female`.

Male characters can only open `giftbox_male`.

To disable this restriction:

```lua
Config.EnforceGender = false
```

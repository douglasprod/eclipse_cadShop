# eclipse_carShop

## Attention
This script work only for buying car, it not have cardealer job

## Requirements
- [es_extended](https://github.com/esx-framework/es_extended/tree/v1-final)

## Installation:
Put `eclipse_carShop` in your resources folder.
Ensure `eclipse_carShop` in your server cfg.

Make sure you have a `vehicles` table in your database with prices for vehicles and their model spawn

[sql.txt](https://github.com/douglasprod/eclipse_carShop/files/6840069/sql.txt)


Do not forget to configure the config in order to add your personal car dealerships and cars (categories only) that you want

![image](https://user-images.githubusercontent.com/36680471/126147048-b9c417d7-6451-4b2a-8610-f239f11bab1b.png)


For fix bugs, when player died - make next changes in `esx_ambulancejob`

1. Go to `esx_ambulancejob/client/job.lua`
2. Find `esx_ambulancejob:setDeadPlayers`
3. Add `TriggerEvent("ECLIPSE:StopTestDrive")`

![image](https://user-images.githubusercontent.com/36680471/126147302-5f3432fc-3ec3-40c1-8115-0a16398d9ae4.png)


https://discord.gg/8nXR6rfB2C

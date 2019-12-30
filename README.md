# diy-prusa-i3-mk3-bear
My attempt to build an improved Prusa i3 MK3 3D printer clone with Full Bear frame from scratch

* This is a fork attempt to build it with China's parts, and cost down to ￥1000 CNY (< $200 USD)
* 这个分支将尝试使用中国制的元件来构建，将成本控制在1000人民币以下

![MK3 Bear Clone with Reverse Bowden](images/MK3_Bear_Clone_with_Reverse_Bowden.jpg)

## Building Instructions【构建步骤】

### Procuring Parts and Materials

* Purchase the parts and the materials according to the [Bill of Materials](#bill-of-materials) section below
* Print required 3D printed tools and parts as listed below
  * Note the print priority:
    * Priority 1 parts are required for assembling the printer
    * Priority 2 parts are useful for continious printer operation
    * Priority 3 parts are not essential, mostly decorative parts
  * It is possible to print priority 2 and priority 3 parts once the printer is assembled, using the printer itself

### Building Steps

1. Follow the [Prusa i3 Bear Full Upgrade MK3 Assembly Instruction](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/manual/assembly_instructions.md) steps 1 - 9 to assemble the v-slot frame, mount Y rods and Y motor
   * Note: The feet and the power supply lower mount can be installed later
   * Note: Use thread locker for metal thread to metal thread (not metal thread to plastic)
2. Follow the [Original Prusa i3 MK3S kit assembly guide - Y-axis assembly](https://manual.prusa3d.com/Guide/2.+Y-axis+assembly/1046?lang=en) steps 24 - 27 to assemble the Y carriage
   * Note: Lubricate linear bearings before installation
3. Follow the [Prusa i3 Bear Full Upgrade MK3 Assembly Instruction](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/manual/assembly_instructions.md) step 10, bullets 1 - 5 to mount the Y carriage on the Y rods (330 mm)
   * Note: Do not follow the Y belt installation instructions - bullets 6 - 9
4. Follow the [Original Prusa i3 MK3S kit assembly guide - Y-axis assembly](https://manual.prusa3d.com/Guide/2.+Y-axis+assembly/1046?lang=en) steps 33 - 42 to assemble and tension the Y belt, and consume 15% of gummy bears
   * Note: All3D Makers MK3 Y carriage does not have threaded M3 holes for Y belt holder and tensioner. I had to use longer M3x14 mm screws and nylock nuts to secure these parts. Prusa MK3 uses M3x10mm screws instead.
5. Follow the [Bear Extruder And X Axis Assembly - X axis](https://guides.bear-lab.com/Guide/2.+X+axis/3) to build the X axis.
   * Note: Lubricate linear bearings before installation
6. Follow the [Prusa i3 Bear Full Upgrade MK3 Assembly Instruction](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/manual/assembly_instructions.md) steps 11 - 13 to install Z motors and Z rods (320 mm), mount the X axis, and Z tops
7. Follow the [Bondtech for Prusa i3 - Assembly and Installation Manual](https://github.com/BondtechAB/Bondtech_Prusa_i3/blob/master/Doc/Assembly%20manual%20Bondtech_Prusa_i3_V1.1.pdf) to build the extruder and mount it on the X axis. Refer to [Bear X axis and Extruder - Bondtech Prusa Upgrade Extruder Assembly Guide](https://github.com/gregsaun/bear_extruder_and_x_axis/tree/master/optional_parts/bondtech_x_carriage) for X carriage mounting instructions and drawings. Install the X belt, and tighen it using two M3x18mm screws on X idler
8. Follow the [Original Prusa i3 MK3S kit assembly guide - Heatbed and PSU assembly](https://manual.prusa3d.com/Guide/7.+Heatbed++&+PSU+assembly+(Silver+PSU)/1051?lang=en) steps 1 - 17 to assemble the heatbed
9. (If priority 2 parts are available) Follow the [Prusa i3 Bear Full Upgrade MK3 Assembly Instruction](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/manual/assembly_instructions.md) steps 14 and 15 to mount the LCD and the power supply unit.
   * Note: The LCD module I've got has a slightly bigger than standard PCB, and I had to file it to make it fit.
10. (If priority 2 parts are available) Follow the [Universal Zaribo Einsy Box](https://www.thingiverse.com/thing:3239428) instructions to install the Einsy Enclosure
    * Note: The Bear Einsy enclosure is slightly wider than it should be to fit properly. I had to file a corner to make it fit.
11. (If priority 3 parts are available) install end caps according to the [Prusa i3 Bear Full Upgrade MK3 Assembly Instruction](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/manual/assembly_instructions.md) steps 14 and 19
12. Follow the [Original Prusa i3 MK3S kit assembly guide - Electronics assembly](https://manual.prusa3d.com/Guide/8.+Electronics+assembly/1052?lang=en) to wire the motors, the headbed, and the extruder to Einsy Rambo module.
13. (If priority 3 parts are available) route and secure the cables according to the [Prusa i3 Bear Full Upgrade MK3 Assembly Instruction](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/manual/assembly_instructions.md) step 18
14. Perform the pre-flight check according to the [Original Prusa i3 MK3S kit assembly guide - Preflight check](https://manual.prusa3d.com/Guide/9.+Preflight+check/1053?lang=en)
15. Calibrate the printer according to the [Prusa i3 Bear Full Upgrade MK3 Assembly Instruction](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/manual/assembly_instructions.md) steps 20 and 21.
16. (If priority 2 parts were not initially printed) Print priority 2 parts, and follow the steps 8 and 9 above to mount the LCD module, the power supply unit, and the Einsy enclosure.
17. (If priority 3 parts were not initially printed) Print priority 3 parts, and follow the steps 10 and 12 above to install end caps and route the wires

### MK3S Sensor Add-on

To be completed

### Reverse Bowden Add-on

To be completed

## Bill of Materials
Assembly/Component Type     | Description                       | Quantity | Price | Possible sources and notes
--------------------------- | --------------------------------- | -------- | ----- | -------------------------- 
Aluminum Frame and Hardware | Full Bear MK3 Upgrade Kit - [Detailed BOM](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/manual/bom.md) | 1 | $124.99 |ALL3D Makers [MK3 Bear Upgrade](https://all3dmakers.com/collections/bear-upgrade-kit/products/mk3-bear-upgrade)
3D Printed Tool             | Full Bear MK3 - [build_helper_106mm](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/build_helper_106mm.stl) | 1 | Filament | Print (priority 1)
3D Printed Tool             | [Linear Bearing Greasing cap](https://www.thingiverse.com/thing:1128781) - [Linear_Bearing_Greaser_-_LM8UU](https://www.thingiverse.com/download:1772343) | 1 | Filament | Print (priority 1) 
3D Printed Tool             | Bondtech Extruder [PTFE Cutter 6.3 mm](https://github.com/BondtechAB/Bondtech_Prusa_i3/blob/master/CAD-Files/PTFE-CUTTER_1.0.STL) | 1 | Filament | Print (priority 1)
3D Printed Part             | Full Bear MK3 - [rod_holder](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rod_holder.stl) | 4 | Filament | Print (priority 1)
3D Printed Part             | Full Bear MK3 - [y_idler_23](https://www.thingiverse.com/thing:3309424) | 1 | Filament | Print (priority 1). Note: 5 mm bore version for E3D 2GT 20T idler
3D Printed Part             | Full Bear MK3 - [y_motor_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/y_motor_mount.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Full Bear MK3 - [z_motor_mounts](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/z_motor_mounts.stl) | 1 (total of 2 parts) | Filament | Print (priority 1)
3D Printed Part             | Full Bear MK3 - [z_motor_mount_front](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/z_motor_mount_front.stl) | 2        | Filament | Print (priority 1)
3D Printed Part             | Full Bear MK3 - [z_tops](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/z_tops.stl) | 1 (total of 2 parts) | Filament | Print (priority 1)
3D Printed Part             | Full Bear MK3 - [foot](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/foot.stl) | 4 | Filament | Print (priority 2)
3D Printed Part             | Full Bear MK3 - [psu_lower_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/psu_lower_mount.stl) | 1 | Filament | Print (priority 2)
3D Printed Part             | Full Bear MK3 - [psu_upper_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/psu_upper_mount.stl) | 2 | Filament | Print (priority 2)
3D Printed Part             | Full Bear MK3 - [lcd_support_a](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/lcd_support_a.stl) | 1 | Filament | Print (priority 2)
3D Printed Part             | Full Bear MK3 - [lcd_support_b](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/lcd_support_b.stl) | 1 | Filament | Print (priority 2)
3D Printed Part             | Full Bear MK3 - [cable_clip_lcd](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/cable_clip_lcd.stl) | 6 | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [cable_clip_round](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/cable_clip_round.stl) | 5 | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [cable_clip_ziptie](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/cable_clip_ziptie.stl) | 3 | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [end_caps](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/end_caps.stl) | 2 (total of 4 parts) | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [end_cap_z_axis](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/end_cap_z_axis.stl) | 2 | Filament | Print (priority 3)
3D Printed Part             | Bear Extruder and X Axis MK3 - [x_carriage](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/mk3/x_carriage.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Bear Extruder and X Axis MK3 - [x_end_motor](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/mk3/x_end_motor.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Bear Extruder and X Axis MK3 - [x_end_idler](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/common_to_all_versions/x_end_idler.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Bear Extruder and X Axis MK3 - [x_end_idler_idler_mount](https://www.thingiverse.com/thing:3308226/files) | 1 | Filament | Print (priority 1). Note: 5 mm bore version for E3D 2GT 20T idler
3D Printed Part             | Bear Extruder and X Axis MK3 - [cable_guide_back_a](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/common_to_all_versions/cable_guide_back_a.stl) | 1 | Filament | Print (Priority 1).
3D Printed Part             | Bear Extruder and X Axis MK3 - [cable_guide_back_b](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/common_to_all_versions/cable_guide_back_b.stl) | 1 | Filament | Print (Priority 1).
3D Printed Part             | Bear Extruder and X Axis MK3 - [bondtech_x_carriage_mk3](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/optional_parts/bondtech_x_carriage/printed_parts/bondtech_x_carriage_mk3.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Bear Extruder and X Axis MK3 - [x_carriage_back](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/printed_parts/stl/mk3/x_carriage_back.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Bondtech Extruder [MK3S Sensor Add-on](https://github.com/BondtechAB/Bondtech_Prusa_i3/tree/master/CAD-Files/MK3s%20Sensor%20Add-On) | 1 | Filament | Print (priority 3)
3D Printed Part             | Original Prusa i3 MK3S - [y-belt-holder](https://github.com/prusa3d/Original-Prusa-i3/blob/MK3S/Printed-Parts/STL/y-belt-holder.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Original Prusa i3 MK3S - [y-belt-tensioner](https://github.com/prusa3d/Original-Prusa-i3/blob/MK3S/Printed-Parts/STL/y-belt-tensioner.stl) | 1 | Filament | Print (priority 1)
3D Printed Part             | Original Prusa i3 MK3S - [z-screw-cover](https://github.com/prusa3d/Original-Prusa-i3/blob/MK3S/Printed-Parts/STL/z-screw-cover.stl) | 2 | Filament | Print (priority 1)
3D Printed Part             | Original Prusa i3 MK3S - [plug-aligner](https://github.com/prusa3d/Original-Prusa-i3/blob/MK3S/Printed-Parts/STL/plug-aligner.stl) | 1 | Filament | Print (priority 3)
3D Printed Part             | [Universal Zaribo Einsy Box](https://www.thingiverse.com/thing:3239428) - [021._MK3_Bear_Einsy_Body_NO_RASP_v5.stl](https://www.thingiverse.com/download:6151820) | 1 | Filament | Print (priority 2)
3D Printed Part             | [Universal Zaribo Einsy Box](https://www.thingiverse.com/thing:3239428) - [020._MK3_Bear_Einsy_Cover_NO_RASP_v5.stl](https://www.thingiverse.com/download:6049099) | 1 | Filament | Print (priority 2)
3D Printed Part             | [Universal Zaribo Einsy Box](https://www.thingiverse.com/thing:3239428) - [EinsyBox-CableCover1-2x.stl](https://www.thingiverse.com/download:5659498) | 2 | Filament | Print (priority 2)
3D Printed Part             | [Universal Zaribo Einsy Box](https://www.thingiverse.com/thing:3239428) - [EinsyBox-CableCover2-1x.stl](https://www.thingiverse.com/download:5659499) | 1 | Filament | Print (priority 2)
3D Printed Part             | [LCD Cover for Prusa Bear Upgrade](https://www.thingiverse.com/thing:3385560) | 1 | Filament | Print (priority 2). Alternatives: Original Prusa i3 MK3S - [LCD cover; LCD knob](https://github.com/prusa3d/Original-Prusa-i3/tree/MK3S/Printed-Parts/STL), or [Prusa Bear LCD cover](https://www.thingiverse.com/thing:2941711)
3D Printed Part             | Original Prusa i3 MK3S - [Heatbed cable cover](https://github.com/prusa3d/Original-Prusa-i3/blob/MK3S/Printed-Parts/STL/heatbed-cable-cover.stl) | 1 | Filament | Print (priority 1)
Bearing                     | LMU8 Linear Bearing               | 10 | $55.50| Misumi [LMU8](https://us.misumi-ec.com/vona2/detail/110300026540/?ProductCode=LMU8)
Metal Rod                   | Z-Axis Rod - 8 mm diameter, 320 mm length  | 2 | $24 | Misumi [PSFJ8-320](https://us.misumi-ec.com/vona2/detail/110302634310/?ProductCode=PSFJ8-320)
Metal Rod                   | Y-Axis Rod - 8 mm diameter, 330 mm length  | 2 | $24 | Misumi [PSFJ8-330](https://us.misumi-ec.com/vona2/detail/110302634310/?ProductCode=PSFJ8-330)
Metal Rod                   | Z-Axis Rod - 8 mm diameter, 370 mm length  | 2 | $24 | Misumi [PSFJ8-370](https://us.misumi-ec.com/vona2/detail/110302634310/?ProductCode=PSFJ8-370)
Belt                        | 2GT Belt                          | 2 | $14.54 | Misumi [GBN8522GT-60](https://us.misumi-ec.com/vona2/detail/110302652060/?ProductCode=GBN8522GT-60)
Idler                       | 2GT 20 Tooth Idler, 6 mm width, 5 mm bore     | 2 | £10.40 | E3D [M-IDLER-T-GT2-P20-6-A-P5-H100](https://e3d-online.com/gates-powergripr-toothed-idler-6mm)
Pulley                      | 2GT 16 Tooth Pulley, 6 mm width, 5 mm bore    | 2 | £7.00 | E3D [M-PULLEY-GT2-16T-6-P5-C-H155](https://e3d-online.com/gates-powergrip-pulley-16-tooth-6mm)
Dowel Pin                   | Dowel Pin 15.8 mm length, 5mm diameter | 2 | $1.69 | All3D Makers [Bear X Axis Dowel Pin for E3D Gates 5mm bore idler](https://all3dmakers.com/collections/hardware/products/bear-x-axis-dowel-pin-for-e3d-gates-5mm-bore-idler)
Electronics Assembly        | Einsy Rambo 1.1                   | 1 | $120.00 | UltiMachine [EINSY RAMBo 1.1](https://ultimachine.com/collections/electronics/products/einsy-rambo-1-1), All3D Makers [MK3 EINSY RAMBo](https://all3dmakers.com/collections/electronics/products/mk3-einsy-rambo)
Electronics Assembly        | 2004 LCD Display - [RepRapDiscount Smart Controller](https://reprap.org/wiki/RepRapDiscount_Smart_Controller) | 1 | $18.49 | All3D Makers [MK3/MK2.5/MK2 LCD Display](https://all3dmakers.com/collections/electronics/products/2004-reprap-lcd-display)
Fan                         | Print cooling fan | 1 | $8.69 | All3D Makers [MK3 Part Cooling Fan](https://all3dmakers.com/collections/electronics/products/mk3-part-cooling-fan)
Fan                         | Hotend fan | 1 | $13.69 | All3D Makers [Sunon MF40100V1-1000U-G99 Hotend Cooling Fan](https://all3dmakers.com/collections/electronics/products/sunon-mf40100v1-1000u-g99-hotend-cooling-fan)
Electronics Assembly        | PINDA 2 sensor | 1 | $15.99 | All3D Makers [P.I.N.D.A 2 Inductive Sensor](https://all3dmakers.com/collections/electronics/products/p-i-n-d-a-2-inductive-sensor)
Electronics Assembly        | Filament sensor | 1 | $11.69 | All3D Makers [MK3S IR Sensor Kit for New Bear Extruder](https://all3dmakers.com/collections/electronics/products/mk3s-ir-sensor-kit-for-new-bear-extruder)
Heatbed                     | MK52 headbed | 1 | $68 | 3DPrintronics [MK52 Heat bed for Prusa MK3](https://www.3dprintronics.com/Prusa-i3-Mk52-Heated-Bed-p101073046). Note: Order 24V version with mounting hardware and thermistor. Optionally order MK3 Y carriage ($24), PINDA 2 sensor ($11), and Spring Steel Sheet ($45). 
Electronics Assembly        | MK3 24V Power Supply | 1 | $69.99 | All3D Makers [24V MK3 Power Supply Assembly with Power Panic](https://all3dmakers.com/collections/electronics/products/24v-250-watts-switching-power-supply)
Motors kit                  | Stepper motors kit | 1 | $124.99 | All3D Makers [Motor Kit for Bear Upgrade, MK2/3, Haribo and Zaribo Mod](https://all3dmakers.com/collections/electronics/products/motor-kit-for-bear-upgrade-mk2-3-and-haribo-mod)
Aluminum Y carriage         | Prusa i3 MK3 Aluminum Y carriage | 1 | $38.99 | All3D Makers [Prusa i3 MK3 Aluminum Y carriage](https://all3dmakers.com/collections/hardware/products/original-prusa-i3-mk3-3d-printer-aluminum-y-carriage?variant=14666953883763)
Spring Steel Sheet          | MK3 Spring Steel Sheet | 1 | $25.75 | BuildTak [FlexPlate MK3 - 9.5"x10"](https://www.buildtak.com/product/flexplate-surface/)
Print Surface               | Print Surface | 1 | $14.25 | BuiltTak [Original 3D Printing Surface - 9"X10"](https://www.buildtak.com/product/buildtak-3d-printing-surface/)
Miscellanous Hardware       | U-Bolts for LMU8U Bearings and nyloc nuts | 1 set | $7.69 | All3D Makers [U-Bolts for LMU8U Bearings](https://all3dmakers.com/collections/hardware/products/u-bolts-to-hold-the-lm8uu-bearings-to-the-y-carriage-on-the-mk2s)
Miscellanous Hardware       | Textile sleeves for headbed and extruder cables | 1 set | $5.69 | All3D Makers [MK3/MK2.5 Heatbed and Extruder Textile Sleeve](https://all3dmakers.com/collections/hardware/products/mk3-mk2-5-heatbed-and-extruder-textile-sleeve)
Miscellanous Hardware       | 3 mm x 50 cm Nylon Filament | 1 | $0.69 | All3D Makers [MK3/MK2.5/MK2S Extruder Nylon Guide](https://all3dmakers.com/collections/hardware/products/mk3-mk2-5-mk2s-extruder-nylon-guide)
Extruder                    | [Bondtech MK2/MK2S/MK3 upgrade kit with Bondtech gears](https://www.bondtech.se/en/product/prusa-i3-mk2-mk2s-extruder-upgrade/) | 1 | $115 | All3D makers [Prusa i3 MK2/MK2S Extruder Upgrade](https://all3dmakers.com/collections/electronics/products/prusa-i3-mk2-mk2s-extruder-upgrade)
Hotend                      | E3D V6, 1.75 mm nozzle, 24V | 1 | £43.00, $79.99| E3D [V6-175-24V](https://e3d-online.com/v6-all-metal-hotend), All3D Makers [MK3 E3DV6 Assembled Hotend](https://all3dmakers.com/collections/electronics/products/mk3-e3dv6-assembled-hotend)
Screw                        | M4 x 10mm button socket screw | 2 | $0.42 | Fastenal [MB2530010A20000](https://www.fastenal.com/products/details/MB2530010A20000)<br>2 - power supply upper mount
Screw                        | M3 x 8mm socket cap screw    | 6 | $1.06 | Fastenal [MS2510008A20000](https://www.fastenal.com/products/details/MS2510008A20000)<br>6 - Einsy enclosure
Screw                        | M3 x 10mm socket cap screw    | 32 | $5.91 | Fastenal [MS2510010A20000](https://www.fastenal.com/products/details/MS2510010A20000)<br>3 - Y motor mount<br>2 - Y belt holder and tensioner<br>2 - headbed cable assembly<br>3 - headbed cable cover<br>6 - X end motor and idler<br>6 - X carriage<br>8 - Einsy enclosure<br>2 - LCD enclosure
Screw                        | M3 x 12mm socket cap screw    | 8 | $1.67 | Fastenal [MS2510012A20000](https://www.fastenal.com/products/details/MS2510012A20000)<br>8 - Z motor mounts
Screw                        | M3 x 14mm socket cap screw    | 2 | $0.18 | Fastenal [MS2510014A20000](https://www.fastenal.com/products/details/MS2510014A20000)<br>2 - Y belt holder and tensioner
Screw                        | M3 x 18mm socket cap screw    | 13 | $5.89 | Fastenal [MS2510018A20000](https://www.fastenal.com/products/details/MS2510018A20000)<br>9 - X end motor and idler<br>3 - X carriage<br>1 - power supply lower mount
Screw                        | M3 x 30mm socket cap screw    | 1 | $0.32 | Fastenal [MS2510030A20000](https://www.fastenal.com/products/details/MS2510030A20000)<br>1 - Y belt holder and tensioner
Screw                        | M3 x 40mm socket cap screw    | 4 | $1.45 | Fastenal [MS2510040A20000](https://www.fastenal.com/products/details/MS2510040A20000)<br>4 - X carriage
Nut                          | M3 hex nut                    | 27 | $1.98 | Fastenal [MN2510000A20000](https://www.fastenal.com/products/details/MN2510000A20000)<br>2 - Y belt holder and tensioner<br>3 - headbed cable cover<br>3 - X carriage<br>8 - X end motor and idler<br>10 - Einsy enclosure<br>1 - power supply lower mount
Nut                          | M3 nyloc nut                  | 7 | $1.12| Fastenal [1L2510000A20000](https://www.fastenal.com/products/details/1L2510000A20000)<br>3 - Y belt holder and tensioner<br>2 - headbed cable assembly<br>2 - X end idler mount
Nut                          | M3 square nut                 | 8 | $1.60 | Fastenal [0161907](https://www.fastenal.com/products/details/0161907)<br>4 - X carriage<br>4 - Einsy Enclosure
Washer                       | M3 x 7 mm washer              | 10 | $0.32 | Fastenal [MW6330000A20000](https://www.fastenal.com/products/details/MW6330000A20000)<br>8 - Z motor mounts<br>2 - headbed cable assembly
Filament                     | 1 kg PETG                     | 1 | $24.99 | Amazon [eSUN 3D 1.75mm PETG Orange Filament 1kg](https://www.amazon.com/eSUN-1-75mm-Filament-Printer-Semi-Transparent/dp/B010Y25QZ2)
Lubricant                    | Super Lube 21030 Synthetic Grease | 1 | $4.69 | Amazon [Super Lube 21030 Synthetic Grease (NLGI 2), 3 oz Tube](https://www.amazon.com/Super-Lube-21030-Synthetic-Grease/dp/B000XBH9HI)
Thread Locker                | Medium Strength (Blue) Thread Locker | 1 | $5.57 | Amazon [Vibra-TITE 121 Medium Strength Removable Anaerobic Threadlocker, 10ml Bottle, Blue](https://www.amazon.com/gp/product/B0025PSNKM)

### Reverse Bowden Add-on
Assembly/Component Type     | Description                       | Quantity | Price | Possible sources and notes
--------------------------- | --------------------------------- | -------- | ----- | --------------------------
3D Printed Part             | [Bondtech extruder add-on](https://www.thingiverse.com/thing:3463618) - [Sensor_Body_Bowden.stl](https://www.thingiverse.com/download:6144709) | 1 | Filament | Print
3D Printed Part             | [Bondtech-Prusa_i3_MK3S-Reverse_Bowden-Sensor_Cover.stl](printed_parts/Bondtech-Prusa_i3_MK3S-Reverse_Bowden-Sensor_Cover.stl) | 1 | Filament | Print
3D Printed Part             | [Lever.STL](https://github.com/BondtechAB/Bondtech_Prusa_i3/blob/master/CAD-Files/MK3s%20Sensor%20Add-On/Lever.STL) | 1 | Filament | Print
3D Printed Part             | Bear Extruder and X Axis MK3 [vslot_mount_pc4-m10](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/optional_parts/reverse_bowden/printed_parts/vslot_mount_pc4-m10.stl) | 1 | Filament | Print
3D Printed Part             | [Spool Holder for 20mm V-Slot](https://www.thingiverse.com/thing:1625705) | 1 | Filament | Print
Hardware                    | PTFE Tubing - 1.75 mm x 1 meter<br>PC4-M10*0.9 Straight-Thru Fittings x2 | 1 set       | $15.99 | Capricorn Premium Bowden Tubing [SKU 2001](https://www.captubes.com/shop/#!/1-Meter-TL-Translucent-1-75mm-Bowden-Tubing/p/82190771/category=23214268)<br>Note: When at tubing page, add fittings from the drop down list on the right.
Screw                        | M3 x 16mm socket cap screw       | 1        | $0.11 | Fastenal [MS2510016A20000](https://www.fastenal.com/products/details/MS2510016A20000)

### Alternative: Original Prusa i3 MK3S Einsy Enclosure
Assembly/Component Type     | Description                       | Quantity | Price | Possible sources and notes
--------------------------- | --------------------------------- | -------- | ----- | -------------------------- 
3D Printed Part             | Full Bear MK3 - [rambo_base_lower_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rambo_base_lower_mount.stl) | 1 | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [rambo_base_upper_mount](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rambo_base_upper_mount.stl) | 1 | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [rambo_lid_lower_hinge](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rambo_lid_lower_hinge.stl) | 1 | Filament | Print (priority 3)
3D Printed Part             | Full Bear MK3 - [rambo_lid_upper_hinge](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/full_upgrade/for_mk3/printed_parts/stl/rambo_lid_upper_hinge.stl) | 1 |  Filament |Print (priority 3)
3D Printed Part             | Original Prusa i3 MK3S - [Einsy-base](https://github.com/prusa3d/Original-Prusa-i3/blob/MK3S/Printed-Parts/STL/Einsy-base.stl) | 1 | Filament | Print (priority 3)
3D Printed Part             | Original Prusa i3 MK3S - [Einsy-doors](https://github.com/prusa3d/Original-Prusa-i3/blob/MK3S/Printed-Parts/STL/Einsy-doors.stl) | 1 | Filament | Print (priority 3)
3D Printed Part             | Original Prusa i3 MK3S - [Extruder-cable-clip](https://github.com/prusa3d/Original-Prusa-i3/blob/MK3S/Printed-Parts/STL/Extruder-cable-clip.stl) | 1 | Filament | Print (priority 3)
3D Printed Part             | Original Prusa i3 MK3S - [Heatbed-cable-clip](https://github.com/prusa3d/Original-Prusa-i3/blob/MK3S/Printed-Parts/STL/Heatbed-cable-clip.stl) | 1 | Filament | Print (priority 3)

## Documentation

* [Prusa i3 Bear Full Upgrade MK3](https://github.com/gregsaun/prusa_i3_bear_upgrade/tree/master/full_upgrade/for_mk3/manual)
* [Original Prusa i3 MK3S Kit Assembly Manual](https://manual.prusa3d.com/c/Original_Prusa_i3_MK3S_kit_assembly)
* [Bondtech Prusa i3 Assembly Manual](https://github.com/BondtechAB/Bondtech_Prusa_i3/blob/master/Doc/Assembly%20manual%20Bondtech_Prusa_i3_V1.1.pdf)
* [Bondtech Prusa i3 - MK3S Sensor Add-On](https://github.com/BondtechAB/Bondtech_Prusa_i3/blob/master/Doc/Sensor%20Add-On%20V1.0.pdf)
* [Bear X Axis and Bondtech Extruder](https://github.com/gregsaun/bear_extruder_and_x_axis/tree/master/optional_parts/bondtech_x_carriage)
* [Optional part for Prusa i3 Bear Upgrade](https://github.com/gregsaun/prusa_i3_bear_upgrade/blob/master/optional_parts.md)
* [Regular extruder temperature drops with firmwares 3.5.0 and 3.5.1](https://github.com/prusa3d/Prusa-Firmware/issues/1405)

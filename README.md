Project Vumsy Patch Ver. 3.0.3
____________________________________
Brief overview:

This is a PvP patch meant for modded online play that adjusts underperforming parts, weapons, systems and mechanics to be more competitively viable. The goal was to not make anything weaker and not fully revert official nerfs, and if anything got weaker it has gotten well compensated.

Nothing has been nerfed, one number might've gone slightly down to bring other numbers drastically up.
Everything that were not strong in terms of parts, weapons, mechanics, etc, has been buffed.
Everything that was already good has been left alone as much as possible.
Melee specialization deals less damage, but increases melee uptime significantly.
Shields no longer hard counter melee and status, multiple shields has been buffed.
Projectiles speeds up over a set distance and almost always deal at least 1 damage within active range.
Light weights are tankier, Heavy weights are faster.
Various quality of life changes.


If you have any feedback, here's my discord server: https://discord.gg/kdVAfbRDTE and if you wanna tune in to my content, here's my twitch link: https://www.twitch.tv/vumsy

Detailed patch notes comparing vanilla can be found below.
____________________________________
Installation guide:

Either copy and paste the contents inside this folder into your Open Server/Mod Engine 2 "mod" folder or rename the folder into "mod" or whatever folder you've adjusted Open Server/Mod Engine 2 to read mods from.

Launch by using launchmod_armoredcore6.bat to play modded and through steam to play vanilla. The game will launch without anti cheat, and save files and mods will be separate from your vanilla files.

If you want to use your vanilla save file, locate and copy your AC60000.sl2 save file, and rename the copy's extension to AC60000.pvp and leave it in your save folder. (WARNING: Do not revert a .pvp file back to .sl2, you will risk a ban.)

To uninstall, remove all contents except altsaves.toml, either through deleting the old contents of the "mod" folder or renaming the folder.

If you are updating from a previous version, simply delete the old "mod" folder content and replace it with the content in this one.
____________________________________
Vanilla comparison patch notes:

System changes:

Melee:
Melee specialization damage modifier lowered from 0.5% per point to 0.01% per point, increases reload speed and reduces charge time by 1%.
Melee tracking improved, some melee weapons lunge further.
Melee attacks below 1000 combo points will all trigger the same stagger animation during combos.
When exceeding the 1000 points combo limit with melee attacks during combos, you will get a stagger extension ending the combo.
Melee Pulse Shield interference removed, now has Pulse Shield Impact Cut Rate based on listed PA Interference. Meaning Pulse blade with 147 PA interference will deal 47% of its impact through pulse shields regardless of impact reduction. (Only applies to Melee weapons with PA interference, ET, Punch and Kicks not included, does not apply to Coral Shield.)
Melee charge attacks will stagger extend and overheat shields if landed on opponent while still being vulnerable to direct hit damage (Impact bar flashes red, but is no longer stunned and can move). Trading shield damage mitigation for overheating it.
Various movement values have made melee boost track better, retain momentum and be more responsive.
Melee will no longer cancel missile barrages.
Melee boosting will accelerate up to the same maximum velocity of 900 and initial EN cost removed.
Melee boost weight penalty lowered from 0.85, 0.75 and 0.65 to 0.9, 0.8 and 0.7 at 75,000, 80,000 and 120,000 weight.

Projectiles and FCS:
Projectiles traveling past 250 meters accelerate by 1500 until reaching 1500 velocity and stanced shots grow to 6 meters in size.
Projectiles gradually lose damage and impact over distance from full to minimum 1 damage.
Ricochet damage increased from 5% to 50% and scales more aggressively until maxed at 1400 defense.
FCS predictive firing increased from 390 to 450 meters.
Targeting distance increased from 450 to 500 meters.
Targeting offset reduced from 80 to 50.
Camera positioning has been adjusted in softlock to behave more similar to hardlock for easier manual aiming.
Multi locking missiles hold time lowered from 0.5 to 0.25 seconds.

Statuses and System recovery:
System recovery reworked, base status resist lowered from 400 to 100, system recovery is now a flat value instead of modifier (Meaning 150 system recovery used to be 400 * 1.5 (600) and is now 100 + 150 (250) status resist). Status build up has been adjusted accordingly.
Status build up fall off increased from 5 points per second to 10 points per second.
20 System recovery added to every head except VE-44B.
Shields no longer block status completely from certain weapons.
Electricity damage changed from 1200 to 9% max AP damage.
Burn additionally lowers defenses by 5%.

Quick Boost:
Quick boost will fire fully automatic weapons much sooner and allow non-stance weapons to be fired during the brief initial wind up.
Long quick boost wind ups have been compensated for and will let actions be performed at a standardized timing.
All boosters QB Thrust increased.
Quick boost initial speed is the same at all weight ranges.

Assault Boost:
Impact reduction during assault boost reduced from 30% to 20%, impact bonus during assault boost increased from 20% to 25%.
Fully automatic weapons and weapon swap has been made available as soon as other actions after kicks.
Assault boost shuffle will fire fully automatic weapons much sooner.
Assault boost wind up allow fully automatic and melee weapons to be used sooner.
Assault boost aim speed increased while in Assault Boost, while AB shuffling and Kicking.
Weight penalty on assault boost lowered from 0.65, 0.7 and 0.5, 0.55 to 0.75, 0.8 and 0.65, 0.7 at 100,000 and 150,000 weight.

Energy:
Energy recovery per second while airborne increased from 5 and 10 while boosting/not boosting to 10 and 20.
Removed EN recovery delay when landing.
Stagger no longer resets redline or delay energy recovery, now applies massively penalized regeneration speed.

Firearm Specialization and Recoil:
High firearm specialization yields more target tracking.
Recoil blur accumulation breakpoint increased from 235 to 255.
Recoil blur recovery at 100 recoil increased from 80 to 110.
Recoil blur recovery breakpoint increased from 235 to 255, recovery speed increased from 200 to 265.
Recoil blur delay before recovery reduced from 0.05 to 0 at 255 recoil control.

Durability, Impact and Stagger:
Negative defense parts has been increased to 0 defense, low defense parts adjusted to match.
Every core with less AP than Basho has received +100 AP, every core below Mind Alpha has received +400 AP.
Legs with less AP then VE-42B increased by 1000, Legs with less AP than EL-TL-11 FORTALEZA increased by 1500 AP.
100 stability added to all heads.
Accumulated impact recovery start time reduced from 5 to 3 seconds.
Fixed an issue where stagger extension window varied, making combos inconsistent.
Window to use expansions during stagger is now always 3 frames after initial stun.
Direct hit vulnerability state duration increased from 1.5 seconds post stun recovery to 2 seconds post stun recovery.

Misc:
Stance fire momentum falloff has been made more erratic in the horizontal and upwards direction on bipeds and RJ's, where it retains full momentum for a duration then rapidly halts to zero in order to throw off enemy FCS better.
Shoulder cannons only lowers rotation speed upon firing on bipeds and RJ's.
Weapon bay reload penalty lowered from 50% to 25%.
Weapon swapping can be performed under any non-committal animation. (Can swap during quick boosts, assault boost shuffling, while firing, etc. and not during kick, melee attacks, stance shots, etc.)
Delay before being able to attack after swapping has been made faster.
Back to back swap timing slightly delayed to prevent accidental double swaps.
Backpedaling multiplier increased from 0.92 to 0.93.
Quick turning has been made faster and easier to input on controller.
Network synchronization and damage registration flags adjusted on multiple attacks.

____________________________________
Weapon changes:

Fists
Hit stop has been added to make it more readable for the opponent when they get hit in neutral.
Will now knock opponents back horizontally to make lining up combos easier.

PILE BUNKER - PB-033M ASHMEAD
Charged attack damage is now only on the main attack, and removed from the initial flinch, meaning damage is unchanged except slightly increased on direct hit.
Charged attack no longer resets redline.

EXPLOSIVE THROWER - DF-ET-09 TAI-YANG-SHOU
Vertical throw improved tracking.
No longer resets redline.
Will now knock opponents back horizontally to make lining up combos easier.

CHAINSAW - WB-0010 DOUBLE TROUBLE
PA Interference increased from 119 to 120.
Normal attacks:
Damage increased from 1025 to 1050.
Impact increased from 750 to 900.
Accumulative impact increased from 375 to 600.
Stagger extension total points on both attacks lowered from 1250 to 480.
Normal attack hitbox size increased from 4 to 6.
Attack instances increased from 5 to 10 (Total output unchanged).
A flinch has been added at the end of the first attack and the beginning of the second one.
Recovery improved.

Hold attack:
Impact increased from 60 to 150.
Accumulative impact increased from 30 to 75.
Heat buildup per second increased from 33 to 333.
Shield size increased, start up faster, impact reduction increased from 30 to 60.
Hitbox radius increased from 2 to 6, stagger extension points increased from 50 to 100, stagger extends.

Charged attack:
Stagger extension points on the final swing lowered from 250 to 240.

STUN BATON - VP-67EB
Stagger extension total points on 6 hits lowered from 1150 to 1000.
Improved issue were charged attack sticky doesn't stick on bad connections. (Not 100% fixed.)
System recovery reworked.

LASER DAGGER - VP-67LD
Charged attack perfect slingshot timing eased, energy cost increased during wind up and lowered during the slash. Total cost unchanged.

LASER SLICER - Vvc-774LS
Stagger extension total points on both attacks lowered from 1000 to 960.
Shield size increased, start up faster, damage mitigation increased from 40 to 50, impact mitigation increased from 30 to 50.
Charged attack recovery improved.

LASER LANCE - VE-67LLA
Normal attack stagger extension points lowered from 800 to 500.
Normal attack flinches.
Normal attack improved recovery.
Charged attack final thrust stagger extension points lowered from 800 to 500.
Charged attack slingshot timing introduced, goes on cooldown.

PLASMA THROWER - 44-143 HMMR
Normal attack:
Alleviated issue where the second hit misses at long range.

Hold attack:
Heat build up per second changed from 25 to 250.
Shield size increased, start up faster, damage reduction increased from 40 to 60, impact reduction increased from 30 to 40.
Stagger extends.
Can be lowered and canceled into normal attack faster.

Charged attack:
Plasma deals damage over time, individual explosions no longer stack.
Damage from 265 damage from 6 explosions (1590) to 138 damage over 10 ticks (1380).
Impact from 33 damage from 6 explosions (198) to 80 damage over 10 ticks (800).
Accumulative Impact from 22 damage from 6 explosions (132) to 60 damage over 10 ticks (600).
Both swings matches explosion damage and impact.
Charged attack improved tracking, improved hitboxes, improved recovery.
Attack hitboxes increased to 30~40 meters.
Charged attack whip flinches and links into itself.
No longer resets redline.

LIGHT WAVE BLADE - IA-C01W2: MOONLIGHT
PA Interference increased from 112 to 117.
Distance increased from 280 to 300.
Normal attack fire angle increased from 10 to 15.
No longer resets redline.
Improved issue where first attack doesn't render for opponent on bad connections. (Not 100% fixed.)

CORAL OSCILLATOR - IA-C01W7: ML-REDSHIFT
Distance increased from 280 to 300.
Normal attack fire angle increased from 10 to 15.
No longer resets redline.
Improved issue where first attack doesn't render for opponent on bad connections. (Not 100% fixed.)

CORAL OSCILLATOR - IB-C03W2: WLT 101
Charged attack no longer resets redline.

BURST RIFLE - MA-J-200 RANSETSU-RF
Projectile velocity increased from 530 to 550.
Burst fire interval on charged shot lowered from 0.06 to 0.03.
Firing angle on charged attack increased from 15 to 20.

LINEAR RIFLE - LR-036 CURTIS
Normal shot damage increased from 142 to 152.
Charged shot accumulated impact increased from 260 to 310.

ASSAULT RIFLE - RF-024 TURNER
Direct hit modifier increased from 185 to 210.
Rapid fire increased from 3.4 to 3.8.
Recoil lowered from 13 to 11.
Projectile speed increased 550 to 570.

ASSAULT RIFLE - RF-025 SCUDDER
Damage increased from 135 to 137.
Impact increased from 82 to 83.
Direct hit modifier increased from 185 to 210.
Rapid fire increased from 2.9 to 3.4.
Recoil lowered from 15 to 12.
Magazine rounds increased from 15 to 16.
Ammo capacity increased from 540 to 580.
Projectile speed increased from 550 to 580.

BURST ASSAULT RIFLE - MA-J-201 RANSETSU-AR
Damage increased from 77x3 to 88x3.
Direct hit modifier increased from 185 to 220.
Rapid fire increased from 3.2 to 3.6 seconds.
Recoil lowered from 7 to 6.
Magazine rounds increased from 18 to 24.
Ammo capacity increased from 450 to 600.
Projectile speed increased from 550 to 600.

MACHINE GUN - MG-014 LUDLOW
Projectile speed increased from 530 to 560.

MACHINE GUN - DF-MG-02 CHANG-CHEN
Projectile speed increased from 520 to 550.

HEAVY MACHINE GUN - WR-0555 ATTACHE
Damage increased from 62 to 67.
Impact increased from 62 to 67.
Accumulative impact increased from 25 to 26.
Direct hit modifier increased from 195 to 200.

GATLING GUN - DF-GA-08 HU-BEN
Recoil reduced from 5 to 3.
Firing angle increased from 15 to 25.
Wind up before firing lowered by 1 frame.

SHOTGUN - WR-0777 SWEET SIXTEEN
Projectile speed increased 550 to 570.
Bullet spread focal distance tightened from 75 to 80.

HANDGUN - HG-003 COQUILLETT
Projectile speed increased from 470 to 500.
Ideal range increased from 85 to 90.
Max recoil angle lowered from 12 to 10.

HANDGUN - HG-004 DUCKETT
Projectile speed increased from 470 to 500.
Max recoil angle lowered from 12 to 10.

BURST HANDGUN - MA-E-211 SAMPU
Ideal range increased from 80 to 90.
Max recoil angle lowered from 12 to 10.

NEEDLE GUN - EL-PW-00 VIENTO
Projectile speed increased from 500 to 530.
Ideal range increased from 105 to 115.
Minimum recoil angle lowered from 0.5 to 0.1.
Max recoil angle lowered from 12 to 10.
Magazine size increased from 5 to 6.
Ammunition increased from 160 to 192.

STUN GUN - VP-66EG
Status applies on the initial bullet.
Status buildup changed from 25 + 25 (50) to 9 + 9 + 9 (27).
System recovery reworked.

BAZOOKA - DF-BA-06 XUAN-GE
Projectile speed increased from 320 to 330.

BAZOOKA - LITTLE GEM
Proximity detonation increased from 7 to 8.

DETONATING BAZOOKA - 44-141 JVLN ALPHA
Stagger extends.

GRENADE LAUNCHER - DF-GR-07 GOU-CHEN
Reload reduced from 5.9 to 4.9.
Blast radius increased from 70 to 80, initial radius increased from 15 to 40.
Projectile speed increased from 360 to 420.
Hitbox increased from 0.7 to 10 within 50 meters.
Firing angle increased from 15 to 20.
Trajectory affected by gravity.
Recovery improved.

GRENADE LAUNCHER - DIZZY
Initial blast radius increased from 20 to 45.
Projectile speed increased from 340 to 400.
Expiration range increased from 265 to 300.
Firing angle increased from 15 to 20.
Hitbox increased from 0.7 to 10 within 50 meters.
Recovery improved.

GRENADE LAUNCHER - IRIDIUM
Reload reduced from 3.8 to 3.4.
Projectile speed increased from 420 to 450.
Expiration range decreased from 245 to 235.
Firing angle increased from 15 to 20.
Radius increased from 60 to 70, initial radius increased from 5 to 35.
Hitbox increased from 0.7 to 10 within 50 meters.
Recovery on biped and RJ improved.

NAPALM BOMB LAUNCHER - MA-T-222 KYORAI
Burn status build up on hit decreased from 100 + 100 + 100 (300) to 58 + 58 + 58 (174).
Burn status build up from burn decreased from 50 to 27.
Projectile speed increased from 250 to 300.
Firing angle increased from 15 and 25 to 30.
Hitbox size increased from 1 to 5.
Knockback on stagger reduced from 120 to 85.
Stagger extends.
System recovery reworked.

JAMMING BOMB LAUNCHER - MA-T-223 KYORIKU
Weight reduced from 2500 to 950.
Stagger extends.

STUN BOMB LAUNCHER - WS-1200 THERAPIST
Status build up increased from 18 + 18 + 18 (54) to 21 + 21 + 21 (63).
Stagger extends.
System recovery reworked.

FLAMETHROWER - WB-0000 BAD COOK
Impact increased from 3 to 4.
Accumulated impact increased from 1 to 2.
Pulse shield interference increased from 0 to 2.
Projectile speed increased from 230 to 245.
Recoil reduced from 10 to 3.
Status build up decreased from 30 to 11.
System recovery reworked.

LASER SHOTGUN - WUERGER/66E
Charge shot fall off is instant.

LASER SHOTGUN - VP-66LS
Impact increased on normal shot from 304 to 376.
Accumulated impact increased from 88 to 128.

LASER HANDGUN - VP-66LH
Burst fire interval on charged shot lowered from 0.06 to 0.03.
Firing angle on charged attack increased from 15 to 20.
Charge shot fall off is instant.

PLASMA RIFLE - Vvc-760PR
Damage interval on normal fire lowered in seconds from 0.1 to 0.05.

PLASMA RIFLE - IA-C01W1: NEBULA
Damage interval on normal fire lowered in seconds from 0.1 to 0.05.

CORAL RIFLE - IA-C01W6: NB-REDSHIFT
Damage interval on normal fire lowered in seconds from 0.1 to 0.05.

CORAL RIFLE - IB-C03W1: WLT 011
Damage interval on normal fire lowered in seconds from 0.2 to 0.1.
Full charge aim speed slightly increased.

MULTI ENERGY RIFLE - 44-142 KRSV
Damage interval on normal fire lowered in seconds from 0.1 to 0.05.

PULSE GUN - HI-16: GU-Q1
Distance increased from 250 to 300.
Recoil reduced from 5 to 3.

PULSE GUN - HI-18: GU-A2
Distance increased from 310 to 350.
Recoil reduced from 5 to 3.

SIEGE MISSILE LAUNCHER - WS-5000 APERITIF
Initial velocity increased from 30 to 50.
Will detonate on enemy contact while lingering in the air.
Knockback on staggered opponents reduced.

PULSE SHIELD - SI-24: SU-Q5
Initial Guard duration increased from 1 second to 1.2 seconds.
Initial Guard damage reduction increased from 65 to 66.
Energy Load lowered from 220 to 200.
Cooldown delay lowered from 2.3 to 1.7.

PULSE SHIELD - SI-27: SU-R8
Guard impact reduction increased from 48 to 58.

PULSE SCUTUM - VE-61PSA
Can lower shield for 1.550 seconds and still keep the Empowered Guard.

CORAL SHIELD - IB-C03W4: NGI 028
Guard impact reduction increased from 42 to 48.
Cooldown delay lowered from 2.1 to 1.3.
(Still unaffected by melee impact cut rate).

GATLING CANNON - DF-GA-09 SHAO-WEI
Heat build up lowered from 37 to 34.
Rapid fire increased from 14.3 to 15.
Total rounds increased from 800 to 900.

SPREAD BAZOOKA - SB-033M MORLEY
Proximity detonation increased from 5 to 7.
Firing delay lowered by 1 frame.

GRENADE CANNON - SONGBIRDS
Projectile speed increased from 360 to 420.
Initial blast radius increased from 5 to 20.
Firing angle increased from 20 to 25.
Firing delay lowered by 2 frames.

STUN NEEDLE LAUNCHER - VE-60SNA
Ideal range increased from 280 to 350.
Stun needle status build up changed from 200 to 36 + 36 + 36 + 36 (144).
Applies status on initial bullet.
Blast detonation attack frequency increased from 1 to 3.
Blast detonation time lowered from 0.5 to 0.25.
Blast detonation radius increased from 30 to 40, max blast radius is immediate.
Blast knockback against staggered opponents lowered from 120 to 20.
Blast is attacker sided and detonates even on ricochet.
Firing delay lowered by 1 frame.
System recovery reworked.

LASER CANNON - VE-60LCA
Ammunition increased from 24 to 36.
Charged attack ammo consumption increased from 6 to 9 (This keeps it at 4 charged shots).

PLASMA CANNON - FASAN/60E
Rapid Fire increased from 0.5 to 0.8.
Damage interval on normal fire lowered in seconds from 0.1 to 0.05.

PULSE CANNON - KRANICH/60Z
Recoil reduced from 5 to 3.

PULSE SHIELD LAUNCHER - EULE/60D
Deployment speed increased from 0.8 to instant deployment.
Explosion initial radius increased from 3 to 7.

LIGHT WAVE CANNON - IA-C01W3: AURORA
Missile homing lock time lowered from 3.3 to 2.5 seconds.

MISSILE LAUNCHER - BML-G1/P20MLT-04
Burst fire interval increased from 0.05 to 0.08.

MISSILE LAUNCHER - BML-G2/P03MLT-06
Burst fire interval increased from 0.08 to 1.

SPLIT MISSILE LAUNCHER - BML-G2/P17SPL-16
Missile lock on time lowered from 1.4 to 1.2 seconds.
Reload lowered from 7.7 to 7.5.

DUAL MISSILE LAUNCHER - BML-G2/P08DUO-03
Burst fire interval lowered from 0.2 to 0.18.
Reload lowered from 5.4 to 5.2.

VERTICAL MISSILE LAUNCHER - BML-G1/P01VTC-04/BML-G1/P03VTC-08 / BML-G1/P07VTC-12
Improved speed.
Damage increased from 124 to 150 per missile.
Accumulated impact increased from 55 to 65 per missile.
Direct hit modifier increased from 150 to 155.

CONTAINER MISSILE LAUNCHER - BML-G1/P29CNT
Initial missile velocity increased from 10 to 20.

CLUSTER MISSILE LAUNCHER - WR-0999 DELIVERY BOY
Improved tracking, cruise height and payload speed.
Radius increased from 24 to 28, initial radius increased from 12 to 14.
Firing delay lowered by 3 frames.

SCATTER MISSILE LAUNCHER - WS-5001 SOUP
Initial angle and tracking improved in close range for 0.5 seconds.
Knockback on staggered opponents reduced.

NEEDLE MISSILE LAUNCHER - EL-PW-01 TRUENO
Ideal range increased from 310 to 360.
Effective range increased from 410 to 460.
Missile lock on time lowered from 4.2 to 3.7 seconds.

PLASMA MISSILE LAUNCHER - Vvc-706PM
Increased spread to cover more area.

CORAL MISSILE LAUNCHER - IB-C03W3: NGI 006
Uncharged acceleration delay removed.

BULLET ORBIT - BO-044 HUXLEY
Accumulative impact increased from 15x8 to 16x8.
Heat build up per second lowered from 100 to 90.
Cooling increased from 95 to 120.
Projectile speed increased from 500 to 520.
Total rounds increased from 240 to 336.

LASER TURRET - VP-60LT
Idle duration increased from 20 seconds to 60 seconds.
Active duration increased from 10 seconds to 15 seconds.
Shots fired increased from 10 to 15.
Firing angle increased from 7 to 15.

_________________________________________________________________________

Parts changes:

Heads:
All heads have +100 stability.
All heads except VE-44B has +20 System recovery.

HEAD - HC-3000 WRECKER
Scan effect duration increased from 3 to 5 seconds.
Scan standby time lowered from 12 to 6 seconds.

HEAD - DF-HD-08 TIAN-QIANG
Kinetic defense increased from 142 to 151.
Energy defense increased from 140 to 150.
Scan standby time lowered from 11.4 to 7.5 seconds.
Attitude stability increased by an additional 100, so from 267 to 467.

HEAD - VP-44D
Kinetic defense increased from 150 to 154.

HEAD - NACHTREIHER/44E
Kinetic defense increased from 142 to 155.
Energy defense increased from 155 to 156.
Explosive defense increased from 152 to 157.

HEAD - KASUAR/44Z
Kinetic defense increased from 149 to 153.
Explosive defense increased from 151 to 156.

HEAD - LAMMERGEIER/40F
Kinetic defense increased from 130 to 150.
Energy defense increased from 153 to 154.
Explosive defense increased from 130 to 150.
Scan standby time lowered from 8 to 5.9 seconds.
Attitude stability increased by an additional 100, so from 305 to 505.

HEAD - HC-2000 FINDER EYE
Energy defense increased from 142 to 152.
Explosive defense increased from 153 to 158.

HEAD - EL-TH-10 FIRMEZA
Explosive defense increased from 154 to 159.

HEAD - 20-082 MIND BETA
Explosive defense increased from 150 to 155.

Cores:
Every core with less AP than Basho has received +100 AP, every core below Mind Alpha has received +400 AP.

CORE - DF-BD-08 TIAN-QIANG
Generator output adjustment increased from 114 to 116.
Energy load lowered from 388 to 300.

CORE - NACHTREIHER/40E
Kinetic defense increased from 349 to 361.
Explosive defense increased from 331 to 350.
Booster Efficiency increased from 126 to 128.

CORE - LAMMERGEIER/40F
AP increased by an additional 100, so 500 AP from 2470 to 2970.
Kinetic defense increased from 330 to 350.
Explosive defense increased from 337 to 353.
Attitude stability increased from 354 to 364.

CORE - CC-2000 ORBITER
Kinetic defense increased from 393 to 394.
Energy defense increased from 356 to 373.
Explosive defense increased from 374 to 376.
Attitude stability increased from 407 to 427.

CORE - CC-3000 WRECKER
Attitude stability increased from 532 to 567.

CORE - EL-TC-10 FIRMEZA
Kinetic defense increased from 384 to 385.
Energy defense increased from 360 to 365.
Explosive defense increased from 375 to 377.
Booster efficiency adjustment increased from 111 to 121.
Generator output adjustment increased from 109 to 110.
EN load lowered from 351 to 326.

CORE - EL-PC-00 ALBA
Kinetic defense increased from 370 to 375.
Energy defense increased from 370 to 375.
Explosive defense increased from 370 to 375.
Booster efficiency adjustment increased from 115 to 123.

CORE - IA-C01C: EPHEMERA
Kinetic defense increased from 335 to 355.
Explosive defense increased from 350 to 360.
Generator Output Efficiency increased from 126 to 128.
Generator Supply Efficiency increased from 96 to 115.

Arms:
Melee specialization damage modifier lowered from 0.5% per point to 0.01% per point, increases reload speed and reduces charge time by 1%.
Firearm specialization yields more target tracking.
Recoil control is more effective at handling high fire rate past 150.

ARMS - AA-J-123 BASHO
Energy defense increased from 191 to 202.
Melee specialization lowered from 158 to 150.

ARMS - AA-J-123/RC JAILBREAK
Kinetic defense increased from 180 to 200.
Energy defense increased from 190 to 200.

ARMS - DF-AR-09 TIAN-LAO
Recoil control increased from 145 to 200.
Load limit increased from 17200 to 20200.

ARMS - VP-46D
Kinetic defense increased from 196 to 204.
Explosive defense increased from 190 to 203.

ARMS - NACHTREIHER/46E
Kinetic defense increased from 204 to 205.
Explosive defense increased from 195 to 205.

ARMS - LAMMERGEIER/46F
Kinetic defense increased from 189 to 211.
Explosive defense increased from 180 to 200.

ARMS - VE-46A
Firearm specialization increased from 80 to 115.

ARMS - AC-2000 TOOL ARM
Energy defense increased from 204 to 205.
Energy load lowered from 216 to 208.

ARMS - AC-3000 WRECKER
Energy defense increased from 170 to 201.
Recoil control increased from 232 to 250.

ARMS - AS-5000 SALAD
Melee specialization increased from 131 to 136.

ARMS - EL-TA-10 FIRMEZA
Explosive defense increased from 187 to 201.

ARMS - EL-PA-00 ALBA
Kinetic defense increased from 205 to 206.
Energy defense increased from 205 to 206.
Explosive defense increased from 205 to 206.

Legs:
Legs with less AP then VE-42B increased by 1000, Legs with less AP than EL-TL-11 FORTALEZA increased by 1500 AP.
Reverse Joint legs quick boost lower to the ground and gain a short burst of momentum based on thrust when jumping.

LEGS - AL-J-121 BASHO
Weight reduced from 19720 to 18720.
Load limit increased from 62600 to 63600.

LEGS - NACHTREIHER/42E
Kinetic defense increased from 295 to 305.
Explosive defense increased from 298 to 302.

LEGS - 2C-2000 CRAWLER
Energy load lowered from 280 to 262.

LEGS - 2C-3000 WRECKER
Energy defense increased from 312 to 314.

LEGS - EL-TL-10 FIRMEZA
Energy defense increased from 266 to 300.
Explosive defense increased from 270 to 300.
Load limit increased from 52100 to 54100.

LEGS - EL-PL-00 ALBA
Kinetic defense increased from 316 to 318.
Energy defense increased from 316 to 318.
Explosive defense increased from 316 to 318.

LEGS - IA-C01L: EPHEMERA
Kinetic defense increased from 297 to 310.
Attitude stability increased from 805 to 815.

LEGS - KASUAR/42Z
Kinetic defense increased from 293 to 303.
Energy defense increased from 290 to 310.
Reverse Joint legs quick boost lower to the ground and gain a short burst of momentum based on thrust when jumping.

LEGS - LAMMERGEIER/42F
Kinetic defense increased from 285 to 300.
Explosive defense increased from 295 to 305.

LEGS - LG-022T BORNEMISSZA
Quick Boost Energy Consumption lowered from 810 to 560.
Quick Boost Reload Time lowered from 0.8 to 0.75.
Assault Boost Continuous Thrust Energy Consumption lowered 360 to 300.
Assault Boost Dodge Energy Consumption lowered from 648 to 448.
Melee boost increased from 510 to 710.
All boosters have 900 continuous melee thrust.

LEGS - VE-42B
Thrust increased from 5984 to 6668 (This is airborne speed).
Melee boost increased from 620 to 820.
All boosters have 900 continuous melee thrust.

EL-TL-11 FORTALEZA
Energy defense increased from 311 to 313.
Explosive defense increased from 314 to 316.
Drift speed doubled and has been made easier to engage.
Melee boost increased from 567 to 767.
All boosters have 900 continuous melee thrust.

_________________________________________________________________________
Boosters:

All boosters have 900 continuous melee thrust.
All boosters have increased QB thrust.

BC-0400 MULE
Quick Boost Energy Consumption lowered from 670 to 500.
Quick Boost Ideal Weight increased from 80000 to 98000.
Assault Boost Energy Consumption lowered from 381 to 333.
Assault Boost Dodge Energy Consumption lowered from 536 to 400.
Assault Boost Dodge initial thrust increased from 426 to 446.
Assault Boost Dodge continuous thrust increased from 387 to 405.
Melee boost increased from 442 to 492.

IA-C01B: GILLS
Quick boost thrust increased from 377 to 407.
Melee boost increased from 390 to 450.


_________________________________________________________________________
FCS:

Targeting distance increased from 450 to 500 meters.
FCS predictive firing increased from 390 to 450 meters.
Multi locking missiles hold time lowered from 0.5 to 0.25 seconds.
Targeting offset reduced from 80 to 50.

FCS-G1/P01
Multi lock correction increased from 40 to 72.
EN load lowered from 198 to 98.

FCS-G2/P05
Multi lock correction increased from 60 to 112.

FCS-G2/P12SML
Multi lock correction increased from 120 to 150.

VE-21A
Multi lock correction increased from 79 to 88.

IB-C03F: WLT 001
Close range assist increased from 58 to 60.
Long range assist increased from 54 to 58.

_________________________________________________________________________
Generators:

AG-J-098 JOSO
Weight lowered from 3420 to 3000.

DF-GN-02 LING-TAI
Supply Recovery increased from 833 to 1000.
Energy Output increased from 2340 to 2550.

DF-GN-08 SAN-TAI
Energy Output increased from 3210 to 3360.

VE-20A
Post-Recovery EN Supply increased from 600 to 720.

VE-20C
Supply Recovery increased from 377 to 384.
Post-Recovery EN Supply increased from 720 to 820.

IA-C01G: AORTA
Supply Recovery increased from 333 to 377.
Post-Recovery EN Supply increased from 2000 to 2050.
Energy Firearm Specialization increased from 105 to 110.
Energy Output increased from 3500 to 3750.

IB-C03G: NGI 000
Supply Recovery increased from 312 to 322.

________________________________________________________________________
Expansions:

EXPANSION - ASSAULT ARMOR
Damage increased from 1500 to 1600, only added to the large radius pulse.
Impact increased from 2000 to 2400.
Accumulative impact increased from 1380 to 1500.
PA delete radius increased from 60 to 100.
PA interference increased from 7500 to 9000.
Will stun and overheat shields if landed on opponent while still being vulnerable to direct hit damage (Impact bar flashes red, but is no longer stunned and can move).
Will no longer end combos prematurely.
Adjusted to clear direct hit vulnerability upon being able to move rather than upon firing.
Generally more consistent.


EXPANSION - PULSE ARMOR
Health increased from 3300 to 3500.
Immune to damage while shielded.


EXPANSION - PULSE PROTECTION
Barrier Health increased from 7000 to 7500.
Barrier Duration increased from 25 seconds to 60 seconds.
Instantly removes direct hit vulnerability.
Lowers impact taken by 30% and multiplies impact recovery by 10 during animation.


EXPANSION - TERMINAL ARMOR
Duration increased from 5 to 6 seconds.
Stun recovery time improved.
Refunds EN.

_______________________________________________________________________
Bonus:
Result screen shortened from 60 to 30 seconds.
Projectile velocities listed in menus.
System abnormality build up listed in menus.
Melee guard values listed in menus.
NPC Enemies can have their stagger state reset by melee charge attacks if hit during their direct hit vulnerable state post stun.
NPC Enemy direct hit vulnerability state post stun lowered from 2 to 0.5 seconds.
Arena mission COAM reward multiplied by 10.

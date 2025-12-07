[b][u]Project Vumsy Patch Ver. 3.0.8[/u][/b]
____________________________________
[b][u]Brief overview:[/u][/b]

This is a PvP patch meant for modded online play that adjusts underperforming parts, weapons, systems and mechanics to be more competitively viable. The goal was to not make anything weaker and not fully revert official nerfs, and if anything got weaker it has gotten well compensated.

[list]
[*]Nothing has been nerfed, one number might've gone slightly down to bring other numbers drastically up.
[*]Everything not strong in terms of parts, weapons, mechanics, etc, has been buffed.
[*]Everything that was already good has been left alone as much as possible.
[*]Melee specialization deals less damage, but increases melee uptime significantly.
[*]Shields no longer hard counter melee and status, multiple shields has been buffed.
[*]Projectiles speeds up over a set distance and almost always deal at least 1 damage within active range.
[*]Light weights are tankier, Heavy weights are faster.
[*]Various quality of life changes.
[/list]

If you have any feedback, here's my discord server: https://discord.gg/kdVAfbRDTE and if you wanna tune in to my content, here's my twitch link: https://www.twitch.tv/vumsy

Detailed patch notes comparing vanilla can be found below.
____________________________________
[b][u]Installation guide:[/u][/b]

Either copy and paste the contents inside this folder into your Open Server "mod" folder or rename the folder into "mod" or whatever folder you've adjusted Open Server to read mods from.

Launch by using launchmod_armoredcore6.bat to play modded and through Steam to play vanilla. The game will launch without anti cheat, and save files and mods will be separate from your vanilla files.

If you want to use your vanilla save file, locate and copy your AC60000.sl2 save file, and rename the copy's extension to AC60000.pvp and leave it in your save folder. (WARNING: Do not revert a .pvp file back to .sl2, you will risk a ban.)

To uninstall, remove all contents except altsaves.toml to keep reading your .pvp save, either through deleting the old contents of the "mod" folder or renaming the folder.

If you are updating from a previous version, simply delete the old "mod" folder content and replace it with the content in this one.
____________________________________
[b][u]Changes since Ver. 3.0.7 patch notes[/u][/b]

With more people playing, more data has been acquired to further adjust overall power-level, a select few things are being brought down a smidge, while other things are being pushed to match. More players also call for increased transparency.
Summarized, WLT and Ludlow were already strong, and further benefitted from system adjustments. Will implement systematic nerfs and introducing weapon competitors.
Heavy weight mobility is a little out of line, but rush down is not particularly strong, do going to help assault boost in general and bring down assault boost speed at the heaviest.
Kites are overall in a very strong spot with mobility/soft-lock QoL, easing the backpedal penalty isn't necessary anymore. If proven out of line in the future, that's part kites playing well with better netcode, and competitors being undertuned, don't think they need more future adjustments in the foreseeable future.
Assault boost rush-down has fallen behind melee boosting's faster and direct approach, as well as the game in general being more slippery. So assault boost hard-lock tracking is slightly better just to keep up and soft-lock is much, much stronger.
While Yue Yu doing well is very fun, Iridium doing this well makes it scary to think of what a Lammergeier, Wheelchair or similar could do with it. Its issue with it's increased reliability is uptime, so reverting the reload.
Melee seems strong, but doesn't completely dominate. There are however a few over-tuned and lackluster melee attacks on a case by case basis. There's also new-found frustration when playing against high uptime melee, but playing against strong strategies are frustrating inherently, so needs more time for player-base to adapt before drastic system changes. For now, a few outliers will be addressed, temporarily if needed.
Electric discharge being more applicable now also calls for a slight nerf in damage.
The rest are buffs and QoL and bugfixes, enjoy!

[b]Nerfs (Not nerfed from vanilla, only relative to earlier mod patches)[/b]

[list]
[*]Weight modifier on assault boost decreased from [b]0.75[/b] terminal and initial speed at [b]150,000[/b] weight to [b]0.65[/b]. (Heavies are just zooming too fast)

[*]Projectile size expansion after 250m lowered from [b]6[/b] to [b]5[/b]. (WLT sniping is a little much)

[*]Backpedal penalty reverted to vanilla, so [b]93%[/b] to [b]92%[/b]. (Due to soft-lock kiting being more viable now)

[*]Initial quick boost thrust duration on tetrapod lowered, from [b]0.2[/b] to vanilla [b]0.1[/b]. Other leg types untouched. (Performs too well with such strong mobility, stability and aerial versatility)

[*]Electric discharge damage lowered from [b]9%[/b] to [b]8.5%[/b] AP. (Reliable application means a tone down.)

[*]Select problematic melee attacks have been adjusted and are now easier to dodge. The attacks are Pulse Blade charged, Laser Slicer charged and Laser Dagger charged. (Might get buffed again in the future if general playerbase improves at dealing with melee, right now they're steamrolling a little too much with new found uptime and target access)

[*][b]LASER SLICER - Vvc-774LS[/b] Laser slicer charged momentum slightly lowered. Shield damage reduction and impact reduction reduced from [b]50[/b] to [b]45[/b]. (Slightly overperforming with cooldown melee spec)

[*][b]MACHINE GUN - MG-014 LUDLOW[/b] Projectile speed reverted from [b]560[/b] to vanilla [b]530[/b]. (LW killer)

[*][b]GRENADE LAUNCHER - IRIDIUM[/b] Reload reverted from [b]3.4[/b] to vanilla [b]3.8[/b]. (It's uptime is just too high with it's newfound reliable output)

[*][b]CORAL RIFLE - IB-C03W1: WLT 011[/b] Aim speed lowered from [b]85[/b] to [b]80[/b] on full charge, ([b]75[/b] in vanilla.) (The full charge isn't that good, but the rest of WLT is, so meeting in the middle.)
[/list]

[b]Buffs[/b]

[list]
[*]Assault boost aim speed increased while soft-locked in Assault Boost, while AB shuffling and Kicking. (A lot better, fast enough to be used in CQC even)

[*]Assault boost tracking increased while hard-locked in Assault Boost and while AB shuffling. (Just a little, 5 to 10 degrees in turn speed, doesn't affect kick tracking)

[*]Assault boost shuffle retains speed throughout thrust. (To keep up with other mobility buffs)

[*]Melee boost weight curve is now identical to assault boost. [b]40,000, 62,500, 75,000, 100,000, 150,000[/b] (Somewhat worse for ultra heavy melee, better just above and below 75k, so more weight leeway and easier to work with)

[*][b]BURST ASSAULT RIFLE - MA-J-201 RANSETSU-AR[/b] Burst fire interval lowered from [b]0.09[/b] to [b]0.075[/b]. (Still not competitive with LR/MG)

[*][b]MACHINE GUN - DF-MG-02 CHANG-CHEN[/b] Projectile speed reverted from [b]550[/b] to vanilla [b]520[/b]. Fire rate increased from [b]10[/b] to [b]11[/b]. (Ludlow competition)

[*][b]BAZOOKA - LITTLE GEM[/b] Projectile speed increased from [b]345[/b] to [b]350[/b]. Will now knock opponents back horizontally to make lining up combos easier. (Underperforming, 350 is the sweet spot for FCS targeting)

[*][b]BAZOOKA - MAJESTIC[/b] Projectile speed increased from [b]345[/b] to [b]350[/b]. Will now knock opponents back horizontally to make lining up combos easier. (WLT competitor)

[*][b]BAZOOKA - DF-BA-06 XUAN-GE[/b] Will now knock opponents back horizontally to make lining up combos easier. (QoL)

[*][b]DETONATING BAZOOKA - 44-141 JVLN ALPHA[/b] Will now knock opponents back horizontally to make lining up combos easier. (QoL)

[*][b]MULTI ENERGY RIFLE - 44-142 KRSV[/b] Projectile speed increased from [b]500[/b] to [b]600[/b] on normal fire. [*]Impact increased from [b]486[/b] to [b]499[/b] on charged fire. Accumulated impact increased from [b]169[/b] to [b]174[/b] on charged fire. Fixed a bug where full charge fire dealt inconsistent damage. (WLT competitor)

[*][b]SPREAD BAZOOKA - SB-033M MORLEY[/b] Projectile speed increased from [b]280[/b] to [b]300[/b]. Will now knock opponents back horizontally to make lining up combos easier. (Underperforming and Qol)

[*][b]LASER CANNON - VE-60LCB[/b] Charged fire projectile speed increased from [b]550[/b] to [b]730[/b]. (Fasan/LCA/SNA competitor)

[*][b]PLASMA CANNON - FASAN/60E[/b] Charge fire damage interval lowered from 0.1 per second to 0.9 per second. (Damage is the same, duration lowered from 1.2 to 1.08 seconds, a PA immunity compensation)

[*][b]PULSE SHIELD LAUNCHER - EULE/60D[/b] Initial blast range is 7 again. (It's a reasonable weapon now, so can get some power back from previous versions.)

[*][b]VERTICAL MISSILE LAUNCHER - BML-G1/P01VTC-04[/b] Will redirect after 1 second if target is high up. Direct hit modifier increased from [b]155[/b] to [b]165[/b]. Reload time lowered from [b]4.8[/b] to [b]3.5[/b]. (Trying to get Verts in a playable spot.)

[*][b]VERTICAL MISSILE LAUNCHER - BML-G1/P03VTC-08[/b] Will redirect after 1 second if target is high up. Direct hit modifier increased from [b]155[/b] to [b]165[/b]. Reload time lowered from [b]6[/b] to [b]3.9[/b] (But these things can't cost EN to dodge.)

[*][b]VERTICAL MISSILE LAUNCHER - BML-G1/P07VTC-12[/b] Will redirect after 1 second if target is high up. Direct hit modifier increased from [b]155[/b] to [b]165[/b]. Reload time lowered from [b]7.5[/b] to [b]5.8[/b](Or they become the best missile in the game.)

[*][b]CONTAINER MISSILE LAUNCHER - BML-G1/P29CNT[/b] Initial velocity reverted to vanilla. Missiles acceleration increased from [b]60[/b] to [b]75[/b]. Now aims [b]45[/b] degree aim upwards when locked on to opponent. (Qol, will possibly try to make it offset aim upwards through animations in the future)

[*][b]CLUSTER MISSILE LAUNCHER - WR-0999 DELIVERY BOY[/b] Further improved payload speed. Barrages a larger area. (Underperforming and unpopular)

[*][b]LASER TURRET - VP-60LT[/b] Direct hit adjustment increased from [b]35[/b] to [b]40[/b]. Effective range increased from [b]304[/b] to [b]370[/b] meters. (LT punish buff, can be farther away before ricochet)

[*][b]VE-20A[/b] EN capacity increased from [b]2570[/b] to [b]2600[/b]. EN recharge increased from [b]787[/b] to [b]800[/b]. (VE-20B competitor as low weight alt)

[*][b]VE-20C[/b] EN capacity increased from [b]3690[/b] to [b]3700[/b]. EN recharge increased from [b]555[/b] to [b]588[/b]. (VE-20B competitor as high EN output alt)
[/list]

[b]QoL/Bugfixes:[/b]

[list]
[*]Last patch had an emergency fix to Therapists unintended shock build up, it is included in this patch.

[*]Fixed an introduced issue where melee precancel couldn't ascend vertically.

[*]Pile bunker charge attack uses EN, so it halts EN recovery again.

[*]Adjusted charge lance and normal lance to slow down when extremely close to enemy to prevent slipping and missing.

[*]Charged lance slingshot timing eased.

[*]Landing animations have been adjusted to be actionable earlier.
[/list]
____________________________________
[b][u]Vanilla comparison patch notes:[/u][/b]

[b]System changes:[/b]

[b]Melee:[/b]
[list]
[*]Melee specialization damage modifier lowered from [b]0.5%[/b] per point to [b]0.01%[/b] per point, increases reload speed and reduces charge time by [b]1%[/b].
[*]Melee tracking improved, some melee weapons lunge further.
[*]Melee attacks below 1000 combo points will all trigger the same stagger animation during combos.
[*]When exceeding the 1000 points combo limit with melee attacks during combos, you will get a stagger extension ending the combo.
[*]Melee Pulse Shield interference removed, now has Pulse Shield Impact Cut Rate based on listed PA Interference. Meaning Pulse blade with 147 PA interference will deal 47% of its impact through pulse shields regardless of impact reduction. (Only applies to Melee weapons with PA interference, ET, Punch and Kicks not included, does not apply to Coral Shield.)
[*]Melee charge attacks will stagger extend and overheat shields if landed on opponent while still being vulnerable to direct hit damage (Impact bar flashes red, but is no longer stunned and can move). Trading shield damage mitigation for overheating it.
[*]Various movement values have made melee boost track better, retain momentum and be more responsive.
[*]Melee will no longer cancel missile barrages.
[*]Melee boosting will accelerate up to the same maximum velocity of [b]900[/b] and initial EN cost removed.
[*]Melee boost weight penalty weight thresholds changed from [b]40,000, 62,500, 75,000, 80,000, 120,000[/b] to [b]40,000, 62,500, 75,000, 100,000, 150,000[/b]. (The modifiers are [b]1, 0,95, 0,85, 0,75, 0,65[/b]).
[/list]
[b]Projectiles and FCS:[/b]
[list]
[*]Projectiles traveling past [b]250[/b] meters accelerate by [b]1500[/b] until reaching [b]1500[/b] velocity and stanced shots grow to 5 meters in size.
[*]Projectiles gradually lose damage and impact over distance from full to minimum [b]1[/b] damage.
[*]Ricochet damage increased from [b]5%[/b] to [b]50%[/b] and scales more aggressively until maxed at 1400 defense.
[*]FCS predictive firing increased from [b]390[/b] to [b]450[/b] meters.
[*]Targeting distance increased from [b]450[/b] to [b]500[/b] meters.
[*]Targeting offset reduced from [b]80[/b] to [b]50[/b].
[*]Camera positioning has been adjusted in softlock to behave more similar to hardlock for easier manual aiming.
[*]Multi locking missiles hold time lowered from [b]0.5[/b] to [b]0.25[/b] seconds.
[/list]
[b]Statuses and System recovery:[/b]
[list]
[*]System recovery reworked, base status resist lowered from [b]400[/b] to [b]100[/b], system recovery is now a flat value instead of modifier (Meaning 150 system recovery used to be 400 * 1.5 ([b]600[/b]) and is now 100 + 150 ([b]250[/b]) status resist). Status build up has been adjusted accordingly.
[*]Status build up fall off increased from [b]5[/b] points per second to [b]10[/b] points per second.
[*][b]20[/b] System recovery added to every head except VE-44B.
[*]Shields no longer block status completely from certain weapons.
[*]Electricity damage changed from [b]1200[/b] to [b]9% max AP damage[/b]. 
[*]Burn additionally lowers defenses by [b]5%[/b].
[/list]
[b]Quick Boost:[/b]
[list]
[*]Quick boost will fire fully automatic weapons much sooner and allow non-stance weapons to be fired during the brief initial wind up.
[*]Long quick boost wind ups have been compensated for and will let actions be performed at a standardized timing.
[*]Quick boost retains speed throughout thrust.
[*]Quick boost initial speed is the same at all weight ranges.
[/list]
[b]Assault Boost:[/b]
[list]
[*]Impact reduction during assault boost reduced from [b]30%[/b] to [b]20%[/b], impact bonus during assault boost increased from [b]20%[/b] to [b]25%[/b].
[*]Fully automatic weapons and weapon swap has been made available as soon as other actions after kicks.
[*]Assault boost shuffle will fire fully automatic weapons much sooner.
[*]Assault boost wind up allow fully automatic and melee weapons to be used sooner.
[*]Assault boost aim speed increased while soft-locked in Assault Boost, while AB shuffling and Kicking.
[*]Assault boost tracking increased while hard-locked in Assault Boost and while AB shuffling.
[*]Assault boost shuffle retains speed throughout thrust.
[*]Weight modifier on assault boost increased from [b]0.95, 0.9, 0.7, 0.55[/b] terminal speed and [b]0.9, 0.85, 0.65, 0.5[/b] initial speed to [b]0.95, 0.9, 0.8, 0.65[/b] terminal and initial speed at [b]50,000, 75,000, 100,000, 150,000[/b] weight.
[/list]
[b]Energy:[/b]
[list]
[*]Energy recovery per second while airborne increased from [b]5[/b] and [b]10[/b] while boosting/not boosting to [b]10[/b] and [b]20[/b].
[*]Removed EN recovery delay when landing.
[*]Stagger no longer resets redline or delay energy recovery, now applies penalized regeneration speed.
[/list]
[b]Firearm Specialization and Recoil:[/b]
[list]
[*]High firearm specialization yields more target tracking.
[*]Recoil blur accumulation breakpoint increased from [b]235[/b] to [b]255[/b].
[*]Recoil blur recovery at [b]100[/b] recoil increased from [b]80[/b] to [b]110[/b].
[*]Recoil blur recovery breakpoint increased from [b]235[/b] to [b]255[/b], recovery speed increased from [b]200[/b] to [b]265[/b].
[*]Recoil blur delay before recovery reduced from [b]0.05[/b] to [b]0[/b] at [b]255[/b] recoil control.
[/list]
[b]Durability, Impact and Stagger:[/b]
[list]
[*]Negative defense parts has been increased to 0 defense, low defense parts adjusted to match.
[*]Every core with less AP than Basho has received [b]+100 AP[/b], every core below Mind Alpha has received [b]+400 AP[/b].
[*]Legs with less AP then VE-42B increased by [b]1000[/b], Legs with less AP than EL-TL-11 FORTALEZA increased by [b]1500[/b] AP.
[*][b]100 stability[/b] added to all heads.
[*]Accumulated impact recovery start time reduced from [b]5[/b] to [b]3[/b] seconds.
[*]Fixed an issue where stagger extension window varied, making combos inconsistent.
[*]Window to use expansions during stagger is now always [b]3[/b] frames after initial stun.
[*]Direct hit vulnerability state duration increased from [b]1.5[/b] seconds post stun recovery to [b]2[/b] seconds post stun recovery.
[/list]
[b]Misc:[/b]
[list]
[*]Hitstop animation playback speed increased from 60% to 90% to reduce animation slowdown from multiple rapid damage instances.
[*]Aimpunch, damage instances deviating the model and throwing off aim, has been removed from the moment you raise your weapon until the moment you attack on all weapons.
[*]Pivoting while softlocked has become stricter on input relative to AC orientation.
[*]Quickly turning to perform actions have been significantly sped up.
[*]Turning during boost has been made sharper.
[*]Pivot animations have been adjusted to be actionable earlier.
[*]Landing animations have been adjusted to be actionable earlier.
[*]Bipeds now have unlocked camera during kicks like other leg types.
[*]Stance fire momentum falloff has been made more erratic in the horizontal and upwards direction on bipeds and RJ's, where it retains full momentum for a duration then rapidly halts to zero in order to throw off enemy FCS better.
[*]Shoulder cannons only lowers rotation speed upon firing on bipeds and RJ's.
[*]Weapon bay reload penalty lowered from [b]50%[/b] to [b]25%[/b].
[*]Weapon swapping can be performed under any non-committal animation. (Can swap during quick boosts, assault boost shuffling, while firing, etc. and not during kick, melee attacks, stance shots, etc.)
[*]Delay before being able to attack after swapping has been made faster.
[*]Back to back swap timing slightly delayed to prevent accidental double swaps.
[*]Backpedaling multiplier increased from [b]0.92[/b] to [b]0.93[/b].
[*]Quick turning has been made faster and easier to input on controller.
[*]Network synchronization and damage registration flags adjusted on multiple attacks.
[/list]
____________________________________
[b][u]Weapon changes:[/u][/b]

[b]Fists[/b]
[list]
[*]Hit stop has been added to make it more readable for the opponent when they get hit in neutral.
[*]Will now knock opponents back horizontally to make lining up combos easier.
[/list]
[b]PILE BUNKER - PB-033M ASHMEAD[/b]
[list]
[*]Charged attack damage is now only on the main attack, and removed from the initial flinch, meaning damage is unchanged except slightly increased on direct hit.
[/list]
[b]EXPLOSIVE THROWER - DF-ET-09 TAI-YANG-SHOU[/b]
[list]
[*]Vertical throw improved tracking.
[*]No longer resets redline.
[*]Will now knock opponents back horizontally to make lining up combos easier.
[/list]
[b]CHAINSAW - WB-0010 DOUBLE TROUBLE[/b]
[list]
[*]PA Interference increased from [b]119[/b] to [b]120[/b].
[/list]Normal attacks:
[list]
[*]Damage increased from [b]1025[/b] to [b]1050[/b].
[*]Impact increased from [b]750[/b] to [b]900[/b].
[*]Accumulative impact increased from [b]375[/b] to [b]600[/b].
[*]Stagger extension total points on both attacks lowered from [b]1250[/b] to [b]480[/b].
[*]Normal attack hitbox size increased from [b]4[/b] to [b]6[/b].
[*]Attack instances increased from [b]5[/b] to [b]10[/b] (Total output unchanged).
[*]A flinch has been added at the end of the first attack and the beginning of the second one.
[*]Recovery improved.
[/list]
Hold attack:
[list]
[*]Impact increased from [b]60[/b] to [b]150[/b].
[*]Accumulative impact increased from [b]30[/b] to [b]75[/b].
[*]Heat buildup per second increased from [b]33[/b] to [b]333[/b].
[*]Shield size increased, start up faster, impact reduction increased from [b]30[/b] to [b]60[/b].
[*]Hitbox radius increased from [b]2[/b] to [b]6[/b], stagger extension points increased from [b]50[/b] to [b]100[/b], stagger extends.
[/list]
Charged attack:
[list]
[*]Stagger extension points on the final swing lowered from [b]250[/b] to [b]240[/b].
[/list]
[b]STUN BATON - VP-67EB[/b]
[list]
[*]Stagger extension total points on 6 hits lowered from [b]1150[/b] to [b]1000[/b].
[*]Improved issue were charged attack sticky doesn't stick on bad connections. (Not 100% fixed.)
[*]System recovery reworked.
[/list]
[b]LASER DAGGER - VP-67LD[/b]
[list]
[*]Charged attack perfect slingshot timing eased, energy cost increased during wind up and lowered during the slash. Total cost unchanged.
[/list]
[b]LASER SLICER - Vvc-774LS[/b]
[list]
[*]Stagger extension total points on both attacks lowered from [b]1000[/b] to [b]960[/b].
[*]Shield size increased, start up faster, damage mitigation increased from [b]40[/b] to [b]45[/b], impact mitigation increased from [b]30[/b] to [b]45[/b].
[*]Charged attack recovery improved.
[/list]
[b]LASER LANCE - VE-67LLA[/b]
[list]
[*]Normal attack stagger extension points lowered from [b]800[/b] to [b]500[/b].
[*]Normal attack flinches.
[*]Normal attack improved recovery.
[*]Charged attack final thrust stagger extension points lowered from [b]800[/b] to [b]500[/b].
[*]Charged attack slingshot timing introduced, goes on cooldown.
[/list]
[b]PLASMA THROWER - 44-143 HMMR[/b]
Normal attack:
[list]
[*]Alleviated issue where the second hit misses at long range.
[/list]
Hold attack:
[list]
[*]Heat build up per second changed from [b]25[/b] to [b]250[/b].
[*]Shield size increased, start up faster, damage reduction increased from [b]40[/b] to [b]60[/b], impact reduction increased from [b]30[/b] to [b]40[/b].
[*]Stagger extends.
[*]Can be lowered and canceled into normal attack faster.
[/list]
Charged attack:
[list]
[*]Plasma deals damage over time, individual explosions no longer stack.
[*]Damage from [b]265[/b] damage from [b]6[/b] explosions [b](1590)[/b] to [b]138[/b] damage over [b]10[/b] ticks [b](1380)[/b].
[*]Impact from [b]33[/b] damage from [b]6[/b] explosions [b](198)[/b] to [b]80[/b] damage over [b]10[/b] ticks [b](800)[/b].
[*]Accumulative Impact from [b]22[/b] damage from [b]6[/b] explosions [b](132)[/b] to [b]60[/b] damage over [b]10[/b] ticks [b](600)[/b].
[*]Both swings matches explosion damage and impact.
[*]Charged attack improved tracking, improved hitboxes, improved recovery.
[*]Attack hitboxes increased to [b]30[/b]~[b]40[/b] meters.
[*]Charged attack whip flinches and links into itself.
[*]No longer resets redline.
[/list]
[b]LIGHT WAVE BLADE - IA-C01W2: MOONLIGHT[/b]
[list]
[*]PA Interference increased from 112 to 117.
[*]Distance increased from [b]280[/b] to [b]300[/b].
[*]Normal attack fire angle increased from [b]10[/b] to [b]15[/b].
[*]No longer resets redline.
[*]Improved issue where first attack doesn't render for opponent on bad connections. (Not 100% fixed.)
[/list]
[b]CORAL OSCILLATOR - IA-C01W7: ML-REDSHIFT[/b]
[list]
[*]Distance increased from [b]280[/b] to [b]300[/b].
[*]Normal attack fire angle increased from [b]10[/b] to [b]15[/b].
[*]No longer resets redline.
[*]Improved issue where first attack doesn't render for opponent on bad connections. (Not 100% fixed.)
[/list]
[b]CORAL OSCILLATOR - IB-C03W2: WLT 101[/b]
[list]
[*]Charged attack no longer resets redline.
[/list]
[b]BURST RIFLE - MA-J-200 RANSETSU-RF[/b]
[list]
[*]Projectile velocity increased from [b]530[/b] to [b]550[/b].
[*]Burst fire interval on charged shot lowered from [b]0.06[/b] to [b]0.03[/b].
[*]Firing angle on charged attack increased from [b]15[/b] to [b]20[/b].
[/list]
[b]LINEAR RIFLE - LR-036 CURTIS[/b]
[list]
[*]Normal shot damage increased from [b]142[/b] to [b]152[/b].
[*]Charged shot accumulated impact increased from [b]260[/b] to [b]310[/b].
[/list]
[b]ASSAULT RIFLE - RF-024 TURNER[/b]
[list]
[*]Direct hit modifier increased from [b]185[/b] to [b]210[/b].
[*]Rapid fire increased from [b]3.4[/b] to [b]3.8[/b].
[*]Recoil lowered from [b]13[/b] to [b]11[/b].
[*]Projectile speed increased [b]550[/b] to [b]570[/b].
[/list]
[b]ASSAULT RIFLE - RF-025 SCUDDER[/b]
[list]
[*]Damage increased from [b]135[/b] to [b]137[/b].
[*]Impact increased from [b]82[/b] to [b]83[/b].
[*]Direct hit modifier increased from [b]185[/b] to [b]210[/b].
[*]Rapid fire increased from [b]2.9[/b] to [b]3.4[/b].
[*]Recoil lowered from [b]15[/b] to [b]12[/b].
[*]Magazine rounds increased from [b]15[/b] to [b]16[/b].
[*]Ammo capacity increased from [b]540[/b] to [b]580[/b].
[*]Projectile speed increased from [b]550[/b] to [b]580[/b].
[/list]
[b]BURST ASSAULT RIFLE - MA-J-201 RANSETSU-AR[/b]
[list]
[*]Damage increased from [b]77x3[/b] to [b]88x3[/b].
[*]Direct hit modifier increased from [b]185[/b] to [b]220[/b].
[*]Rapid fire increased from [b]3.2[/b] to [b]3.6[/b] seconds.
[*]Burst fire interval lowered from [b]0.09[/b] to [b]0.075[/b].
[*]Recoil lowered from [b]7[/b] to [b]6[/b].
[*]Magazine rounds increased from [b]18[/b] to [b]24[/b].
[*]Ammo capacity increased from [b]450[/b] to [b]600[/b].
[*]Projectile speed increased from [b]550[/b] to [b]600[/b].
[/list]
[b]MACHINE GUN - DF-MG-02 CHANG-CHEN[/b]
[list]
[*]Fire rate increased from [b]10[/b] to [b]11[/b].
[*]Reload speed lowered from [b]2.2[/b] to [b]1.8[/b] seconds.
[/list]
[b]HEAVY MACHINE GUN - WR-0555 ATTACHE[/b]
[list]
[*]Damage increased from [b]62[/b] to [b]67[/b].
[*]Impact increased from [b]62[/b] to [b]67[/b].
[*]Accumulative impact increased from [b]25[/b] to [b]26[/b].
[*]Direct hit modifier increased from [b]195[/b] to [b]200[/b].
[/list]
[b]GATLING GUN - DF-GA-08 HU-BEN[/b]
[list]
[*]Recoil reduced from [b]5[/b] to [b]3[/b].
[*]Firing angle increased from [b]15[/b] to [b]25[/b].
[*]Wind up before firing lowered by [b]1[/b] frame.
[/list]
[b]SHOTGUN - SG-026 HALDEMAN[/b]
[list]
[*]Damage increased from [b]576[/b] to [b]584[/b]
[*]Impact increased from [b]360[/b] to [b]376[/b].
[*]Accumulative impact increased from [b]280[/b] to [b]288[/b].
[/list]
[b]SHOTGUN - WR-0777 SWEET SIXTEEN[/b]
[list]
[*]Projectile speed increased [b]550[/b] to [b]570[/b].
[*]Bullet spread focal distance tightened from [b]75[/b] to [b]80[/b].
[/list]
[b]HANDGUN - HG-003 COQUILLETT[/b]
[list]
[*]Projectile speed increased from [b]470[/b] to [b]500[/b].
[*]Ideal range increased from [b]85[/b] to [b]90[/b].
[*]Max recoil angle lowered from [b]12[/b] to [b]10[/b].
[/list]
[b]HANDGUN - HG-004 DUCKETT[/b]
[list]
[*]Projectile speed increased from [b]470[/b] to [b]500[/b].
[*]Max recoil angle lowered from [b]12[/b] to [b]10[/b].
[/list]
[b]BURST HANDGUN - MA-E-211 SAMPU[/b]
[list]
[*]Ideal range increased from [b]80[/b] to [b]90[/b].
[*]Max recoil angle lowered from [b]12[/b] to [b]10[/b].
[/list]
[b]NEEDLE GUN - EL-PW-00 VIENTO[/b]
[list]
[*]Projectile speed increased from [b]500 to 530[/b].
[*]Ideal range increased from [b]105 to 115[/b].
[*]Minimum recoil angle lowered from [b]0.5 to 0.1[/b].
[*]Max recoil angle lowered from [b]12 to 10[/b].
[*]Magazine size increased from [b]5 to 6[/b].
[*]Ammunition increased from [b]160 to 192[/b].
[/list]
[b]STUN GUN - VP-66EG[/b]
[list]
[*]Status applies on the initial bullet.
[*]Status buildup changed from [b]25 + 25 (50)[/b] to [b]9 + 9 + 9 (27)[/b].
[*]System recovery reworked.
[/list]
[b]BAZOOKA - DF-BA-06 XUAN-GE[/b]
[list]
[*]Projectile speed increased from [b]320[/b] to [b]330[/b].
[/list]
[b]BAZOOKA - MAJESTIC[/b]
[list]
[*]Projectile speed increased from [b]345[/b] to [b]350[/b].
[*]Will now knock opponents back horizontally to make lining up combos easier.
[/list]
[b]BAZOOKA - LITTLE GEM[/b]
[list]
[*]Projectile speed increased from [b]345[/b] to [b]350[/b].
[*]Will now knock opponents back horizontally to make lining up combos easier.
[*]Proximity detonation increased from [b]7[/b] to [b]8[/b].
[/list]
[b]DETONATING BAZOOKA - 44-141 JVLN ALPHA[/b]
[list]
[*]Stagger extends.
[*]Will now knock opponents back horizontally to make lining up combos easier.
[/list]
[b]GRENADE LAUNCHER - DF-GR-07 GOU-CHEN[/b]
[list]
[*]Reload reduced from [b]5.9[/b] to [b]4.9[/b].
[*]Blast radius increased from [b]70[/b] to [b]80[/b], initial radius increased from [b]15[/b] to [b]40[/b].
[*]Projectile speed increased from [b]360[/b] to [b]420[/b].
[*]Hitbox increased from [b]0.7[/b] to [b]10[/b] within [b]50[/b] meters.
[*]Firing angle increased from [b]15[/b] to [b]20[/b].
[*]Trajectory affected by gravity.
[*]Recovery improved.
[/list]
[b]GRENADE LAUNCHER - DIZZY[/b]
[list]
[*]Initial blast radius increased from [b]20[/b] to [b]45[/b].
[*]Projectile speed increased from [b]340[/b] to [b]400[/b].
[*]Expiration range increased from [b]265[/b] to [b]300[/b].
[*]Firing angle increased from [b]15[/b] to [b]20[/b].
[*]Hitbox increased from [b]0.7[/b] to [b]10[/b] within [b]50[/b] meters.
[*]Recovery improved.
[/list]
[b]GRENADE LAUNCHER - IRIDIUM[/b]
[list]
[*]Projectile speed increased from [b]420[/b] to [b]450[/b].
[*]Expiration range decreased from [b]245[/b] to [b]235[/b].
[*]Firing angle increased from [b]15[/b] to [b]20[/b].
[*]Radius increased from [b]60[/b] to [b]70[/b], initial radius increased from [b]5[/b] to [b]35[/b].
[*]Hitbox increased from [b]0.7[/b] to [b]10[/b] within [b]50[/b] meters.
[*]Recovery on biped and RJ improved.
[/list]
[b]NAPALM BOMB LAUNCHER - MA-T-222 KYORAI[/b]
[list]
[*]Burn status build up on hit decreased from [b]100 + 100 + 100 (300)[/b] to [b]58 + 58 + 58 (174)[/b].
[*]Burn status build up from burn decreased from [b]50[/b] to [b]27[/b].
[*]Projectile speed increased from [b]250[/b] to [b]300[/b].
[*]Firing angle increased from [b]15[/b] and [b]25[/b] to [b]30[/b].
[*]Hitbox size increased from [b]1[/b] to [b]5[/b].
[*]Knockback on stagger reduced from [b]120[/b] to [b]85[/b].
[*]Fires all shots simultaneously and stagger extends.
[*]System recovery reworked.
[/list]
[b]JAMMING BOMB LAUNCHER - MA-T-223 KYORIKU[/b]
[list]
[*]Weight reduced from [b]2500[/b] to [b]950[/b].
[*]Stagger extends.
[/list]
[b]STUN BOMB LAUNCHER - WS-1200 THERAPIST[/b]
[list]
[*]Status build up increased from [b]18 + 18 + 18 (54)[/b] to [b]21 + 21 + 21 (63)[/b].
[*]Deals full damage when one blast lands and stagger extends.
[*]System recovery reworked.
[/list]
[b]FLAMETHROWER - WB-0000 BAD COOK[/b]
[list]
[*]Impact increased from [b]3[/b] to [b]4[/b].
[*]Accumulated impact increased from [b]1[/b] to [b]2[/b].
[*]Pulse shield interference increased from [b]0[/b] to [b]2[/b].
[*]Projectile speed increased from [b]230[/b] to [b]245[/b].
[*]Recoil reduced from [b]10[/b] to [b]3[/b].
[*]Status build up decreased from [b]30[/b] to [b]11[/b].
[*]System recovery reworked.
[/list]
[b]LASER SHOTGUN - WUERGER/66E[/b]
[list]
[*]Charge shot fall off is instant.
[/list]
[b]LASER SHOTGUN - VP-66LS[/b]
[list]
[*]Impact increased on normal shot from [b]304[/b] to [b]376[/b].
[*]Accumulated impact increased from [b]88[/b] to [b]128[/b].
[/list]
[b]LASER HANDGUN - VP-66LH[/b]
[list]
[*]Burst fire interval on charged shot lowered from [b]0.06[/b] to [b]0.03[/b].
[*]Firing angle on charged attack increased from [b]15[/b] to [b]20[/b].
[*]Charge shot fall off is instant.
[/list]
[b]PLASMA RIFLE - Vvc-760PR[/b]
[list]
[*]Damage interval on normal fire lowered in seconds from [b]0.1[/b] to [b]0.05[/b].
[*]Charge shot hit count increased from [b]8[/b] to [b]10[/b].
[/list]
[b]PLASMA RIFLE - IA-C01W1: NEBULA[/b]
[list]
[*]Damage interval on normal fire lowered in seconds from [b]0.1[/b] to [b]0.05[/b].
[/list]
[b]CORAL RIFLE - IA-C01W6: NB-REDSHIFT[/b]
[list]
[*]Damage interval on normal fire lowered in seconds from [b]0.1[/b] to [b]0.05[/b].
[/list]
[b]CORAL RIFLE - IB-C03W1: WLT 011[/b]
[list]
[*]Damage interval on normal fire lowered in seconds from [b]0.2[/b] to [b]0.1[/b].
[*]Full charge aim speed slightly increased from [b]75[/b] to [b]80[/b].
[/list]
[b]MULTI ENERGY RIFLE - 44-142 KRSV[/b]
[list]
[*]Projectile speed increased from [b]500[/b] to [b]600[/b] on normal fire.
[*]Damage interval on normal fire lowered in seconds from [b]0.1[/b] to [b]0.05[/b].
[*]Impact increased from [b]486[/b] to [b]499[/b] on charged fire.
[*]Accumulated impact increased from [b]169[/b] to [b]174[/b] on charged fire.
[*]Charge attack ammo consumption lowered from [b]8[/b] to [b]5[/b].
[*]Fixed a bug where full charge fire would deal inconsistent damage.
[/list]
[b]PULSE GUN - HI-16: GU-Q1[/b]
[list]
[*]Distance increased from [b]250[/b] to [b]300[/b].
[*]Recoil reduced from [b]5[/b] to [b]3[/b].
[/list]
[b]PULSE GUN - HI-18: GU-A2[/b]
[list]
[*]Distance increased from [b]310[/b] to [b]350[/b].
[*]Recoil reduced from [b]5[/b] to [b]3[/b].
[/list]
[b]SIEGE MISSILE LAUNCHER - WS-5000 APERITIF[/b]
[list]
[*]Initial velocity increased from [b]30[/b] to [b]50[/b].
[*]Will detonate on enemy contact while lingering in the air.
[*]Knockback on staggered opponents reduced.
[/list]
[b]PULSE SHIELD - SI-24: SU-Q5[/b]
[list]
[*]Initial Guard duration increased from [b]1[/b] second to [b]1.2[/b] seconds.
[*]Initial Guard damage reduction increased from [b]65[/b] to [b]66[/b].
[*]Energy Load lowered from [b]220[/b] to [b]200[/b].
[*]Cooling increased from 88 to 98.
[/list]
[b]PULSE SHIELD - SI-27: SU-R8[/b]
[list]
[*]Guard impact reduction increased from [b]48[/b] to [b]58[/b].
[/list]
[b]PULSE SCUTUM - VE-61PSA[/b]
[list]
[*]Can lower shield for [b]1.550[/b] seconds and still keep the Empowered Guard.
[/list]
[b]CORAL SHIELD - IB-C03W4: NGI 028[/b]
[list]
[*]Guard impact reduction increased from [b]42[/b] to [b]48[/b].
[*]Cooldown delay lowered from [b]2.1[/b] to [b]1.3[/b].
[*](Still unaffected by melee impact cut rate).
[/list]
[b]GATLING CANNON - DF-GA-09 SHAO-WEI[/b]
[list]
[*]Heat build up lowered from [b]37[/b] to [b]34[/b].
[*]Rapid fire increased from [b]14.3[/b] to [b]15[/b].
[*]Total rounds increased from [b]800[/b] to [b]900[/b].
[/list]
[b]SPREAD BAZOOKA - SB-033M MORLEY[/b]
[list]
[*]Projectile speed increased from [b]280[/b] to [b]300[/b].
[*]Proximity detonation increased from [b]5[/b] to [b]7[/b].
[*]Firing delay lowered by [b]1[/b] frame.
[*]Will now knock opponents back horizontally to make lining up combos easier.
[/list]
[b]GRENADE CANNON - SONGBIRDS[/b]
[list]
[*]Projectile speed increased from [b]360[/b] to [b]420[/b].
[*]Initial blast radius increased from [b]5[/b] to [b]20[/b].
[*]Firing angle increased from [b]20[/b] to [b]25[/b].
[*]Firing delay lowered by [b]2[/b] frames.
[/list]
[b]STUN NEEDLE LAUNCHER - VE-60SNA[/b]
[list]
[*]Ideal range increased from [b]280[/b] to [b]350[/b].
[*]Stun needle status build up changed from [b]200[/b] to [b]36 + 36 + 36 + 36 (144)[/b].
[*]Applies status on initial bullet.
[*]Blast detonation attack frequency increased from [b]1[/b] to [b]3[/b].
[*]Blast detonation time lowered from[b] 0.5[/b] to [b]0.25[/b].
[*]Blast detonation radius increased from [b]30[/b] to [b]40[/b], max blast radius is immediate.
[*]Blast knockback against staggered opponents lowered from [b]120[/b] to [b]20[/b].
[*]Blast is attacker sided and detonates even on ricochet.
[*]Firing delay lowered by [b]1[/b] frame.
[*]System recovery reworked.
[/list]
[b]LASER CANNON - VE-60LCA[/b]
[list]
[*]Ammunition increased from [b]24[/b] to [b]36[/b].
[*]Charged attack ammo consumption increased from [b]6[/b] to [b]9[/b] (This keeps it at 4 charged shots).
[/list]
[b]LASER CANNON - VE-60LCB[/b]
[list]
[*]Charged fire projectile speed increased from [b]550[/b] to [b]750[/b].
[/list]
[b]DIFFUSE LASER CANNON - VP-60LCD[/b]
[list]
[*]Fixed a bug where normal fire had inverted recoil knockback in air and on ground compared to other cannons.
[/list]
[b]PLASMA CANNON - FASAN/60E[/b]
[list]
[*]Rapid Fire increased from [b]0.5[/b] to [b]0.8[/b].
[*]Damage interval on normal fire lowered in seconds from [b]0.1[/b] to [b]0.05[/b].
[*]Charge fire damage interval lowered from 0.1 per second to 0.75 per second.
[/list]
[b]PULSE CANNON - KRANICH/60Z[/b]
[list]
[*]Recoil reduced from [b]5[/b] to [b]3[/b].
[/list]
[b]PULSE SHIELD LAUNCHER - EULE/60D[/b]
[list]
[*]Deployment speed increased from [b]0.8[/b] to instant deployment, proximity radius and main damage blast activates after [b]0.8[/b] seconds, direct shots deal reduced damage like vanilla again.
[*]Blast initial radius increased from [b]3[/b] to [b]7[/b].
[*]Contact damage no longer instantly destroys friendly EULE shields. This was done because in vanilla high speed assault boost could leave them behind with delayed deployment and instant deployment removed this strategy.
[/list]
[b]LIGHT WAVE CANNON - IA-C01W3: AURORA[/b]
[list]
[*]Missile homing lock time lowered from [b]3.3[/b] to[b] 2.5[/b] seconds.
[/list]
[b]MISSILE LAUNCHER - BML-G1/P20MLT-04[/b]
[list]
[*]Burst fire interval increased from [b]0.05[/b] to [b]0.08[/b].
[/list]
[b]MISSILE LAUNCHER - BML-G2/P03MLT-06[/b]
[list]
[*]Burst fire interval increased from [b]0.08[/b] to [b]1[/b].
[/list]
[b]SPLIT MISSILE LAUNCHER - BML-G2/P17SPL-16[/b]
[list]
[*]Missile lock on time lowered from [b]1.4[/b] to [b]1.2[/b] seconds.
[*]Reload lowered from [b]7.7[/b] to [b]7.5[/b].
[/list]
[b]DUAL MISSILE LAUNCHER - BML-G2/P08DUO-03[/b]
[list]
[*]Burst fire interval lowered from [b]0.2[/b] to [b]0.18[/b].
[*]Reload lowered from [b]5.4[/b] to [b]5.2[/b].
[/list]
[b]VERTICAL MISSILE LAUNCHER - BML-G1/P01VTC-04[/b]
[list]
[*]Improved speed, will redirect after [b]1[/b] second if target is high up.
[*]Damage increased from [b]124[/b] to [b]150[/b] per missile.
[*]Accumulated impact increased from [b]55[/b] to [b]65[/b] per missile.
[*]Direct hit modifier increased from [b]150[/b] to [b]165[/b].
[*]Reload time lowered from [b]4.8[/b] to [b]3.5[/b].
[/list]
[b]VERTICAL MISSILE LAUNCHER - BML-G1/P03VTC-08[/b]
[list]
[*]Improved speed, will redirect after [b]1[/b] second if target is high up.
[*]Damage increased from [b]124[/b] to [b]150[/b] per missile.
[*]Accumulated impact increased from [b]55[/b] to [b]65[/b] per missile.
[*]Direct hit modifier increased from [b]150[/b] to [b]165[/b].
[*]Reload time lowered from [b]6[/b] to [b]3.9[/b].
[/list]
[b]VERTICAL MISSILE LAUNCHER - BML-G1/P07VTC-12[/b]
[list]
[*]Improved speed, will redirect after [b]1[/b] second if target is high up.
[*]Damage increased from [b]124[/b] to [b]150[/b] per missile.
[*]Accumulated impact increased from [b]55[/b] to [b]65[/b] per missile.
[*]Direct hit modifier increased from [b]150[/b] to [b]165[/b].
[*]Reload time lowered from [b]7.5[/b] to [b]5.8[/b].
[/list]
[b]ACTIVE HOMING MISSILE LAUNCHER - BML-G3/P04ACT-01[/b]
[list]
[*]Missile lock on time lowered from [b]1.7[/b] to [b]1.5[/b] seconds.
[/list]
[b]ACTIVE HOMING MISSILE LAUNCHER - BML-G3/P05ACT-02[/b]
[list]
[*]Missile lock on time lowered from [b]2.8[/b] to [b]2.5[/b] seconds.
[/list]
[b]CONTAINER MISSILE LAUNCHER - BML-G1/P29CNT[/b]
[list]
[*]Missiles acceleration increased from [b]60[/b] to [b]75[/b].
[*]Now aims [b]45[/b] degree aim upwards when locked on to opponent.
[/list]
[b]CLUSTER MISSILE LAUNCHER - WR-0999 DELIVERY BOY[/b]
[list]
[*]Improved tracking, cruise height and payload speed.
[*]Radius increased from [b]24[/b] to [b]28[/b], initial radius increased from [b]12[/b] to [b]14[/b].
[*]Barrages a larger area.
[*]Firing delay lowered by [b]3[/b] frames.
[/list]
[b]SCATTER MISSILE LAUNCHER - WS-5001 SOUP[/b]
[list]
[*]Initial angle and tracking improved in close range for [b]0.5[/b] seconds.
[*]Knockback on staggered opponents reduced.
[/list]
[b]NEEDLE MISSILE LAUNCHER - EL-PW-01 TRUENO[/b]
[list]
[*]Ideal range increased from [b]310[/b] to [b]360[/b].
[*]Effective range increased from [b]410[/b] to [b]460[/b].
[*]Missile lock on time lowered from [b]4.2[/b] to [b]3.7[/b] seconds.
[/list]
[b]PLASMA MISSILE LAUNCHER - Vvc-706PM[/b]
[list]
[*]Increased spread to cover more area.
[/list]
[b]CORAL MISSILE LAUNCHER - IB-C03W3: NGI 006[/b]
[list]
[*]Uncharged acceleration delay removed.
[/list]
[b]BULLET ORBIT - BO-044 HUXLEY[/b]
[list]
[*]Accumulative impact increased from [b]15x8[/b] to [b]16x8[/b].
[*]Heat build up per second lowered from [b]100[/b] to [b]90[/b].
[*]Cooling increased from [b]95[/b] to [b]120[/b].
[*]Projectile speed increased from [b]500[/b] to [b]520[/b].
[*]Total rounds increased from [b]240[/b] to [b]336[/b].
[/list]
[b]LASER TURRET - VP-60LT[/b]
[list]
[*]Direct hit adjustment increased from [b]35[/b] to [b]40[/b].
[*]Effective range increased from [b]304[/b] to [b]370[/b] meters.
[*]Idle duration increased from [b]20[/b] seconds to [b]60[/b] seconds.
[*]Active duration increased from [b]10[/b] seconds to [b]15[/b] seconds.
[*]Shots fired increased from [b]10[/b] to [b]15[/b].
[*]Firing angle increased from [b]7[/b] to [b]15[/b].
[/list]
[b]LASER DRONE - Vvc-700LD[/b]
[list]
[*]Normal fire tracking improved.
[/list]
_________________________________________________________________________

[b][u]Parts changes:[/u][/b]

[b]Heads:[/b]
[list]
[*]All heads have [b]+100[/b] stability.
[*]All heads except VE-44B has [b]+20[/b] System recovery.
[/list]
[b]HEAD - AH-J-124 BASHO[/b]
[list]
[*]AP increased from [b]1250[/b] to [b]1300[/b].
[*]Attitude stability increased by an additional [b]6[/b], so from [b]394[/b] to [b]500[/b].
[/list]
[b]HEAD - DF-HD-08 TIAN-QIANG[/b]
[list]
[*]Kinetic defense increased from [b]142[/b] to [b]151[/b].
[*]Energy defense increased from [b]140[/b] to [b]150[/b].
[*]Scan standby time lowered from [b]11.4[/b] to [b]7.5[/b] seconds.
[*]Attitude stability increased by an additional [b]100[/b], so from [b]267[/b] to [b]467[/b].
[/list]
[b]HEAD - VP-44D[/b]
[list]
[*]Kinetic defense increased from [b]150[/b] to [b]154[/b].
[/list]
[b]HEAD - NACHTREIHER/44E[/b]
[list]
[*]Kinetic defense increased from [b]142[/b] to [b]155[/b].
[*]Energy defense increased from [b]155[/b] to [b]156[/b].
[*]Explosive defense increased from [b]152[/b] to [b]157[/b].
[/list]
[b]HEAD - KASUAR/44Z[/b]
[list]
[*]Kinetic defense increased from [b]149[/b] to [b]153[/b].
[*]Explosive defense increased from [b]151[/b] to [b]156[/b].
[/list]
[b]HEAD - LAMMERGEIER/40F[/b]
[list]
[*]Kinetic defense increased from [b]130[/b] to [b]150[/b].
[*]Energy defense increased from [b]153[/b] to [b]154[/b].
[*]Explosive defense increased from [b]130[/b] to [b]150[/b].
[*]Scan standby time lowered from [b]8[/b] to [b]5.9[/b] seconds.
[*]Attitude stability increased by an additional [b]100[/b], so from [b]305[/b] to [b]505[/b].
[/list]
[b]HEAD - HC-2000 FINDER EYE[/b]
[list]
[*]Energy defense increased from [b]142[/b] to [b]152[/b].
[*]Explosive defense increased from [b]153[/b] to [b]158[/b].
[/list]
[b]HEAD - HC-3000 WRECKER[/b]
[list]
[*]Scan effect duration increased from [b]3[/b] to [b]5[/b] seconds.
[*]Scan standby time lowered from [b]12[/b] to [b]6[/b] seconds.
[/list]
[b]HEAD - EL-TH-10 FIRMEZA[/b]
[list]
[*]Explosive defense increased from [b]154[/b] to [b]159[/b].
[/list]
[b]HEAD - 20-082 MIND BETA[/b]
[list]
[*]Explosive defense increased from [b]150[/b] to [b]155[/b].
[/list]
[b]Cores:[/b]
[list]
[*]Every core with less AP than Basho has received [b]+100 AP[/b], every core below Mind Alpha has received [b]+400 AP[/b].
[/list]
[b]CORE - DF-BD-08 TIAN-QIANG[/b]
[list]
[*]Generator output adjustment increased from [b]114[/b] to [b]116[/b].
[*]Energy load lowered from [b]388[/b] to [b]300[/b].
[/list]
[b]CORE - NACHTREIHER/40E[/b]
[list]
[*]Kinetic defense increased from [b]349[/b] to [b]361[/b].
[*]Explosive defense increased from [b]331[/b] to [b]350[/b].
[*]Booster Efficiency increased from [b]126[/b] to [b]128[/b].
[/list]
[b]CORE - LAMMERGEIER/40F[/b]
[list]
[*]AP increased by an additional [b]100[/b], so [b]500[/b] AP from [b]2470[/b] to [b]2970[/b].
[*]Kinetic defense increased from [b]330[/b] to [b]350[/b].
[*]Explosive defense increased from [b]337[/b] to [b]353[/b].
[*]Attitude stability increased from [b]354[/b] to [b]364[/b].
[/list]
[b]CORE - CC-2000 ORBITER[/b]
[list]
[*]Kinetic defense increased from [b]393[/b] to [b]394[/b].
[*]Energy defense increased from [b]356[/b] to [b]373[/b].
[*]Explosive defense increased from [b]374[/b] to [b]376[/b].
[*]Attitude stability increased from [b]407[/b] to [b]427[/b].
[/list]
[b]CORE - CC-3000 WRECKER[/b]
[list]
[*]Attitude stability increased from [b]532[/b] to [b]567[/b].
[/list]
[b]CORE - EL-TC-10 FIRMEZA[/b]
[list]
[*]Kinetic defense increased from [b]384[/b] to [b]385[/b].
[*]Energy defense increased from [b]360[/b] to [b]365[/b].
[*]Explosive defense increased from [b]375[/b] to [b]377[/b].
[*]Booster efficiency adjustment increased from [b]111[/b] to [b]121[/b].
[*]Generator output adjustment increased from [b]109[/b] to [b]110[/b].
[*]EN load lowered from [b]351[/b] to [b]326[/b].
[/list]
[b]CORE - EL-PC-00 ALBA[/b]
[list]
[*]Kinetic defense increased from [b]370[/b] to [b]375[/b].
[*]Energy defense increased from [b]370[/b] to [b]375[/b].
[*]Explosive defense increased from [b]370[/b] to [b]375[/b].
[*]Booster efficiency adjustment increased from [b]115[/b] to [b]123[/b].
[/list]
[b]CORE - IA-C01C: EPHEMERA[/b]
[list]
[*]Kinetic defense increased from [b]335[/b] to [b]355[/b].
[*]Explosive defense increased from [b]350[/b] to [b]360[/b].
[*]Generator Output Efficiency increased from [b]126[/b] to [b]128[/b].
[*]Generator Supply Efficiency increased from [b]96[/b] to [b]115[/b].
[/list]
[b]Arms:[/b]
[list]
[*]Melee specialization damage modifier lowered from [b]0.5%[/b] per point to [b]0.01%[/b] per point, increases reload speed and reduces charge time by [b]1%[/b].
[*]Firearm specialization yields more target tracking.
[*]Recoil control is more effective at handling high fire rate past [b]150[/b].
[/list]
[b]ARMS - AA-J-123 BASHO[/b]
[list]
[*]Energy defense increased from [b]191[/b] to [b]202[/b].
[*]Melee specialization lowered from [b]158[/b] to [b]150[/b].
[/list]
[b]ARMS - AA-J-123/RC JAILBREAK[/b]
[list]
[*]Kinetic defense increased from [b]180[/b] to [b]200[/b].
[*]Energy defense increased from [b]190[/b] to [b]200[/b].
[/list]
[b]ARMS - DF-AR-09 TIAN-LAO[/b]
[list]
[*]Recoil control increased from [b]145[/b] to [b]200[/b].
[*]Load limit increased from [b]17200[/b] to [b]20200[/b].
[/list]
[b]ARMS - VP-46D[/b]
[list]
[*]Kinetic defense increased from [b]196[/b] to [b]204[/b].
[*]Explosive defense increased from [b]190[/b] to [b]203[/b].
[/list]
[b]ARMS - NACHTREIHER/46E[/b]
[list]
[*]Kinetic defense increased from [b]204[/b] to [b]205[/b].
[*]Explosive defense increased from [b]195[/b] to [b]205[/b].
[/list]
[b]ARMS - LAMMERGEIER/46F[/b]
[list]
[*]Kinetic defense increased from [b]189[/b] to [b]211[/b].
[*]Explosive defense increased from [b]180[/b] to [b]200[/b].
[/list]
[b]ARMS - VE-46A[/b]
[list]
[*]Firearm specialization increased from [b]80[/b] to [b]115[/b].
[/list]
[b]ARMS - AC-2000 TOOL ARM[/b]
[list]
[*]Energy defense increased from [b]204[/b] to [b]205[/b].
[*]Energy load lowered from[b] 216[/b] to [b]208[/b].
[/list]
[b]ARMS - AC-3000 WRECKER[/b]
[list]
[*]Energy defense increased from [b]170[/b] to [b]201[/b].
[*]Recoil control increased from [b]232[/b] to [b]250[/b].
[/list]
[b]ARMS - AS-5000 SALAD[/b]
[list]
[*]Melee specialization increased from [b]131[/b] to [b]136[/b].
[/list]
[b]ARMS - EL-TA-10 FIRMEZA[/b]
[list]
[*]Explosive defense increased from [b]187[/b] to [b]201[/b].
[/list]
[b]ARMS - EL-PA-00 ALBA[/b]
[list]
[*]Kinetic defense increased from [b]205[/b] to [b]206[/b].
[*]Energy defense increased from [b]205[/b] to [b]206[/b].
[*]Explosive defense increased from [b]205[/b] to [b]206[/b].
[/list]
[b]Legs:[/b]
[list]
[*]Legs with less AP then VE-42B increased by [b]1000[/b], Legs with less AP than EL-TL-11 FORTALEZA increased by [b]1500[/b] AP.
[*]Reverse Joint legs quick boost lower to the ground and gain a short burst of momentum based on thrust when jumping.
[/list]
[b]LEGS - AL-J-121 BASHO[/b]
[list]
[*]Weight reduced from [b]19720[/b] to [b]18720[/b].
[*]Load limit increased from [b]62600[/b] to [b]63600[/b].
[/list]
[b]LEGS - NACHTREIHER/42E[/b]
[list]
[*]Kinetic defense increased from [b]295[/b] to [b]305[/b].
[*]Explosive defense increased from [b]298[/b] to [b]302[/b].
[/list]
[b]LEGS - 2C-2000 CRAWLER[/b]
[list]
[*]Energy load lowered from [b]280[/b] to [b]262[/b].
[/list]
[b]LEGS - 2C-3000 WRECKER[/b]
[list]
[*]Energy defense increased from [b]312[/b] to [b]314[/b].
[/list]
[b]LEGS - EL-TL-10 FIRMEZA[/b]
[list]
[*]Energy defense increased from [b]266[/b] to [b]300[/b].
[*]Explosive defense increased from [b]270[/b] to [b]300[/b].
[*]Load limit increased from [b]52100[/b] to [b]54100[/b].
[/list]
[b]LEGS - EL-PL-00 ALBA[/b]
[list]
[*]Kinetic defense increased from [b]316[/b] to [b]318[/b].
[*]Energy defense increased from [b]316[/b] to [b]318[/b].
[*]Explosive defense increased from [b]316[/b] to [b]318[/b].
[/list]
[b]LEGS - IA-C01L: EPHEMERA[/b]
[list]
[*]Kinetic defense increased from [b]297[/b] to [b]310[/b].
[*]Attitude stability increased from [b]805[/b] to [b]815[/b].
[/list]
[b]LEGS - KASUAR/42Z[/b]
[list]
[*]Kinetic defense increased from [b]293[/b] to [b]303[/b].
[*]Energy defense increased from [b]290[/b] to [b]310[/b].
[*]Reverse Joint legs quick boost lower to the ground and gain a short burst of momentum based on thrust when jumping.
[/list]
[b]LEGS - LAMMERGEIER/42F[/b]
[list]
[*]Kinetic defense increased from [b]285[/b] to [b]300[/b].
[*]Explosive defense increased from [b]295[/b] to [b]305[/b].
[*]Fixed an issue where Explosive Thrower and other weapons failed to track opponents when quick boosting on all tetrapods during varying boost duration timings.
[/list]
[b]LEGS - LG-022T BORNEMISSZA[/b]
[list]
[*]Quick Boost Energy Consumption lowered from [b]810[/b] to [b]560[/b].
[*]Quick Boost Reload Time lowered from [b]0.8[/b] to [b]0.75[/b].
[*]Assault Boost Continuous Thrust Energy Consumption lowered [b]360[/b] to [b]300[/b].
[*]Assault Boost Dodge Energy Consumption lowered from [b]648[/b] to [b]448[/b].
[*]Melee boost increased from [b]510[/b] to [b]710[/b].
[*]All boosters have [b]900[/b] continuous melee thrust.
[*]Tanks are actionable slightly sooner after kicking.
[/list]
[b]LEGS - VE-42B[/b]
[list]
[*]Thrust increased from [b]5984[/b] to [b]6668[/b] (This is airborne speed).
[*]Melee boost increased from [b]620[/b] to [b]820[/b].
[*]All boosters have [b]900[/b] continuous melee thrust.
[*]Tanks are actionable slightly sooner after kicking.
[/list]
[b]EL-TL-11 FORTALEZA[/b]
[list]
[*]Energy defense increased from [b]311[/b] to [b]313[/b].
[*]Explosive defense increased from [b]314[/b] to [b]316[/b].
[*]Drift speed doubled and has been made easier to engage.
[*]Melee boost increased from [b]567[/b] to [b]767[/b].
[*]All boosters have [b]900[/b] continuous melee thrust.
[*]Tanks are actionable slightly sooner after kicking.
[*]Fixed an issue after vanilla wheelchair nerfs where aerial quick boosts outperformed grounded ones, they now roughly match favoring grounded quick boosts slightly.
[/list]
_________________________________________________________________________
[b][u]Boosters:[/u][/b]

[list]
[*]All boosters have [b]900[/b] continuous melee thrust.
[*]All boosters have increased QB thrust.
[/list]
[b]BC-0400 MULE[/b]
[list]
[*]Quick Boost Energy Consumption lowered from [b]670[/b] to [b]500[/b].
[*]Quick Boost Ideal Weight increased from [b]80000[/b] to [b]98000[/b].
[*]Assault Boost Energy Consumption lowered from [b]381[/b] to [b]333[/b].
[*]Assault Boost Dodge Energy Consumption lowered from [b]536[/b] to [b]400[/b].
[*]Assault Boost Dodge initial thrust increased from [b]426[/b] to [b]446[/b].
[*]Assault Boost Dodge continuous thrust increased from [b]387[/b] to [b]405[/b].
[*]Melee boost increased from [b]442[/b] to [b]492[/b].
[/list]
[b]IA-C01B: GILLS[/b]
[list]
[*]Quick boost thrust increased from [b]377[/b] to [b]407[/b].
[*]Melee boost increased from [b]390[/b] to [b]450[/b].
[/list]

_________________________________________________________________________
[b][u]FCS:[/u][/b]

[list]
[*]Targeting distance increased from [b]450[/b] to [b]500[/b] meters.
[*]FCS predictive firing increased from [b]390[/b] to [b]450[/b] meters.
[*]Multi locking missiles hold time lowered from [b]0.5[/b] to [b]0.25[/b] seconds.
[*]Targeting offset reduced from [b]80[/b] to [b]50[/b].
[/list]
[b]FCS-G1/P01[/b]
[list]
[*]Multi lock correction increased from [b]40[/b] to [b]72[/b].
[*]EN load lowered from [b]198[/b] to [b]98[/b].
[/list]
[b]FCS-G2/P05[/b]
[list]
[*]Multi lock correction increased from [b]60[/b] to [b]112[/b].
[/list]
[b]FCS-G2/P12SML[/b]
[list]
[*]Multi lock correction increased from [b]120[/b] to [b]150[/b].
[/list]
[b]VE-21A[/b]
[list]
[*]Multi lock correction increased from [b]79[/b] to [b]88[/b].
[/list]
[b]IB-C03F: WLT 001[/b]
[list]
[*]Close range assist increased from [b]58[/b] to [b]60[/b].
[*]Long range assist increased from [b]54[/b] to [b]58[/b].
[/list]
_________________________________________________________________________
[b][u]Generators:[/u][/b]

[b]AG-J-098 JOSO[/b]
[list]
[*]Weight lowered from [b]3420[/b] to [b]3000[/b].
[/list]
[b]AG-T-005 HOKUSHI[/b]
[list]
[*]EN Recharge increased from [b]1052[/b] to [b]1388[/b].
[/list]
[b]DF-GN-02 LING-TAI[/b]
[list]
[*]Supply Recovery increased from [b]833[/b] to [b]1000[/b].
[*]Energy Output increased from [b]2340[/b] to [b]2550[/b].
[/list]
[b]DF-GN-08 SAN-TAI[/b]
[list]
[*]Energy Output increased from [b]3210[/b] to [b]3360[/b].
[/list]
[b]VE-20A[/b]
[list]
[*]EN capacity increased from [b]2570[/b] to [b]2600[/b].
[*]EN recharge increased from [b]787[/b] to [b]800[/b].
[*]Post-Recovery EN Supply increased from [b]600[/b] to [b]720[/b].
[/list]
[b]VE-20C[/b]
[list]
[*]EN capacity increased from [b]3690[/b] to [b]3700[/b].
[*]EN recharge increased from [b]555[/b] to [b]588[/b].
[*]Supply Recovery increased from [b]377[/b] to [b]384[/b].
[*]Post-Recovery EN Supply increased from [b]720[/b] to [b]820[/b].
[/list]
[b]IA-C01G: AORTA[/b]
[list]
[*]Supply Recovery increased from [b]333[/b] to [b]377[/b].
[*]Post-Recovery EN Supply increased from [b]2000[/b] to [b]2050[/b].
[*]Energy Firearm Specialization increased from [b]105[/b] to [b]110[/b].
[*]Energy Output increased from [b]3500[/b] to [b]3750[/b].
[/list]
[b]IB-C03G: NGI 000[/b]
[list]
[*]Supply Recovery increased from [b]312[/b] to [b]322[/b].
[/list]
________________________________________________________________________
[b]Expansions:[/b]

[b]EXPANSION - ASSAULT ARMOR[/b]
[list]
[*]Damage increased from [b]1500[/b] to [b]1600[/b], only added to the large radius pulse.
[*]Impact increased from [b]2000[/b] to [b]2400[/b].
[*]Accumulative impact increased from [b]1380[/b] to [b]1500[/b].
[*]PA delete radius increased from [b]60[/b] to [b]100[/b].
[*]PA interference increased from [b]7500[/b] to [b]9000[/b].
[*]Will stun and overheat shields if landed on opponent while still being vulnerable to direct hit damage (Impact bar flashes red, but is no longer stunned and can move).
[*]Will no longer end combos prematurely.
[*]Adjusted to clear direct hit vulnerability upon being able to move rather than upon firing.
[*]Generally more consistent.
[/list]
[b]EXPANSION - PULSE ARMOR[/b]
[list]
[*]Health increased from [b]3300[/b] to [b]3500[/b].
[*]Immune to damage while shielded.
[/list]
[b]EXPANSION - PULSE PROTECTION[/b]
[list]
[*]Barrier Health increased from [b]7000[/b] to [b]7500[/b].
[*]Barrier Duration increased from [b]25[/b] seconds to [b]60[/b] seconds.
[*]Instantly removes direct hit vulnerability.
[*]Lowers impact taken by [b]30%[/b] and multiplies impact recovery by [b]10[/b] during animation.
[*]Fixed an issue where Explosive Thrower and Delivery Boy would one shot Pulse Protection by adjusting damage dealt down by half.
[/list]
[b]EXPANSION - TERMINAL ARMOR[/b]
[list]
[*]Duration increased from [b]5[/b] to [b]6[/b] seconds.
[*]Stun recovery time improved.
[*]Refunds EN.
[/list]
_______________________________________________________________________
Bonus:
[list]
[*]Result screen shortened from [b]60[/b] to [b]30[/b] seconds.
[*]Projectile velocities listed in menus.
[*]System abnormality build up listed in menus.
[*]Melee guard values listed in menus.
[*]NPC Enemies can have their stagger state reset by melee charge attacks if hit during their direct hit vulnerable state post stun.
[*]NPC Enemy direct hit vulnerability state post stun lowered from [b]2[/b] to [b]0.5[/b] seconds.
[/list]
Requirements 
--------------------------------------------------------------------------
Visual C++ Redistributable for Visual Studio 2012 
http://go.microsoft.com/fwlink/?LinkId=255955

Installation
--------------------------------------------------------------------------
<<Wizardry 6>>
1. Copy or install Wizardry 6 to "<DosBox>\Wiz6\"
2. Run playwiz6.bat

<<Wizardry 7>>
1. Copy or install Wizardry 7(supported only v.1.20(English/Russian)) to "<DosBox>\Wiz7\"
2. Run playwiz7.bat


Configuration
--------------------------------------------------------------------------
[Automap Mod]
It's required to set "output=opengl" and "fullscreen=false" in [sdl] section of config file.

Options in [AutoMap] section of config file:
"enable" - Enable automap feature for Wizardry 6 & Wizardry 7.
"show_tooltips" - Enable tooltips feature for Wizardry 6 & Wizardry 7.
"hide_in_dark_zones" - Hides automap in dark zones(Wizardry 6 & Wizardry 7).
"wiz7_sns_mode" - Enable "Skill & Spell" Mode (Wizardry 7).
"width" - Width of automap window.
"height" - Height of automap window.

[Wizardry 6 / 7 - Audio Popping] 
The new setting wizpopfix was developed specifically for Wizardry 6 and 7 and reduces popping from the pc speaker sounds in those games. To enable it add the 	line wizpopfix=6 or wizpopfix=7 respectively, below pcspeaker=true in the config file.

Wizardry 7 Automap Modes
----------------------------------------------------------------------------------------------------
<< "Skill & Spell" Mode >>
Level of detail is based on Mapping skill.
The result of "Locate Object" & "Wizard's Eye" spells is accumulated on automap.

<< Standard Mode >>
Always displays chests (hidden things is still invisible).
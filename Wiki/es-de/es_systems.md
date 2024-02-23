Simply add the commands to your `es_systems.cfg` file. You can edit the default [es_systems.cfg](https://gitlab.com/es-de/emulationstation-de/-/blob/master/resources/systems/android/es_systems.xml?ref_type=heads).

# Dolphin MMJR2

```
        <command label="Dolphin MMJR 2 (Standalone)">%EMULATOR_DOLPHIN-MMJR2% %ACTION%=android.intent.action.VIEW %EXTRA_AutoStartFile%=%ROMSAF%</command>
```

# Moonlight

```
    <system>
        <name>moonlight</name>
        <fullname>Moonlight Game Streaming</fullname>
        <path>%ROMPATH%/moonlight</path>
        <extension>.moonlight</extension>
        <command label="Moonlight">%EMULATOR_Moonlight% %EXTRA_UUID%=%INJECT%=Moonlight.uuid %EXTRA_AppId%=%INJECT%=%BASENAME%.moonlight</command>
        <platform>moonlight</platform>
        <theme>moonlight</theme>
    </system>
```

# Skyline

```
        <command label="Skyline (Standalone)">%EMULATOR_Skyline% %ACTION%=android.intent.action.VIEW %DATA%=%ROMSAF%</command>
```

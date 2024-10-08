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

# Nintendo Virtual Boy

```
    <system>
        <name>virtualboy</name>
        <fullname>Nintendo Virtual Boy</fullname>
        <path>%ROMPATH%/virtualboy</path>
        <extension>.bin .BIN .vb .VB .vboy .VBOY .7z .7Z .zip .ZIP</extension>
        <command label="Virtual Virtual Boy">%EMULATOR_Virtual Virtual Boy% %ACTION%=android.intent.action.VIEW %DATA%=%ROMPROVIDER%</command>
        <command label="Beetle VB">%EMULATOR_RETROARCH% %EXTRA_CONFIGFILE%=/storage/emulated/0/Android/data/%ANDROIDPACKAGE%/files/retroarch.cfg %EXTRA_LIBRETRO%=mednafen_vb_libretro_android.so %EXTRA_ROM%=%ROM%</command>
        <platform>virtualboy</platform>
        <theme>virtualboy</theme>
    </system>
```

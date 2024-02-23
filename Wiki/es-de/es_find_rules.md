Simply add these commands to your `es_find_rules.xml` file. You can edit the default [es_find_rules.cfg](https://gitlab.com/es-de/emulationstation-de/-/blob/master/resources/systems/android/es_find_rules.xml?ref_type=heads).

# Dolphin MMJR2

```
    <emulator name="DOLPHIN-MMJR2">
        <rule type="androidpackage">
            <entry>org.dolphinemu.mmjr/org.dolphinemu.dolphinemu.ui.main.MainActivity</entry>
        </rule>
    </emulator>
```

# Moonlight

```
    <emulator name="Moonlight">
        <rule type="androidpackage">
            <entry>com.limelight/com.limelight.ShortcutTrampoline</entry>
        </rule>
    </emulator>
```

# Skyline

```
    <emulator name="Skyline">
        <rule type="androidpackage">
            <entry>skyline.emu/emu.skyline.EmulationActivity</entry>
        </rule>
    </emulator>
```

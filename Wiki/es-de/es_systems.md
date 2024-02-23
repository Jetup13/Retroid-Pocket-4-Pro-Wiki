```
<systemList>
    <system>
        <name>gc</name>
        <fullname>Nintendo GameCube</fullname>
        <path>%ROMPATH%/gc</path>
        <extension>.ciso .CISO .dff .DFF .dol .DOL .elf .ELF .gcm .GCM .gcz .GCZ .iso .ISO .json .JSON .m3u .M3U .rvz .RVZ .tgc .TGC .wad .WAD .wbfs .WBFS .wia .WIA .7z .7Z .zip .ZIP</extension>
        <command label="Dolphin MMJR 2 (Standalone)">%EMULATOR_DOLPHIN-MMJR 2% %ACTION%=android.intent.action.VIEW %EXTRA_AutoStartFile%=%ROMSAF%</command>
        <platform>gc</platform>
        <theme>gc</theme>
    </system>
    <system>
        <name>wii</name>
        <fullname>Nintendo Wii</fullname>
        <path>%ROMPATH%/wii</path>
        <extension>.ciso .CISO .dff .DFF .dol .DOL .elf .ELF .gcm .GCM .gcz .GCZ .iso .ISO .json .JSON .m3u .M3U .rvz .RVZ .tgc .TGC .wad .WAD .wbfs .WBFS .wia .WIA .7z .7Z .zip .ZIP</extension>
        <command label="Dolphin MMJR 2 (Standalone)">%EMULATOR_DOLPHIN-MMJR 2% %ACTION%=android.intent.action.VIEW %EXTRA_AutoStartFile%=%ROMSAF%</command>
        <platform>wii</platform>
        <theme>wii</theme>
    </system>
    <system>
        <name>switch</name>
        <fullname>Nintendo Switch</fullname>
        <path>%ROMPATH%/switch</path>
        <extension>.nca .NCA .nro .NRO .nso .NSO .nsp .NSP .xci .XCI</extension>
        <command label="Skyline (Standalone)">%EMULATOR_Skyline% %ACTION%=android.intent.action.VIEW %DATA%=%ROMSAF%</command>
        <platform>switch</platform>
        <theme>switch</theme>
    </system>
    <system>
        <name>moonlight</name>
        <fullname>Moonlight Game Streaming</fullname>
        <path>%ROMPATH%/moonlight</path>
        <extension>.moonlight</extension>
        <command label="Moonlight">%EMULATOR_Moonlight% %EXTRA_UUID%=%INJECT%=Moonlight.uuid %EXTRA_AppId%=%INJECT%=%BASENAME%.moonlight</command>
        <platform>moonlight</platform>
        <theme>moonlight</theme>
    </system>
</systemList>
```
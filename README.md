# e6530

E6530 - Hackintosh - OPENCORE Bootloader

NOTE
+ BIOS version A13. IF you have A21 or A22 try downgrade to A13 to fix GlitchScreen when SHUTDOWN.
If you have other version without glitch screen when shutdown please TELLME!

+ Work only Catalina 10.15.5 if you have other version must be disable _xcpm_bootstrap on Kernel>Patch and AppleXCPMExtraMSR
+ BIOS need mod to full xcpm. If you don't want mod bios and want high score geekbench please disable _xcpm_bootstrap on Kernel>Patch and AppleXCPMExtraMSR (Not recommend)
  
SPEC:
  Dell Latitude E6530 I5 3230M + HD4000 + 120GB Vaseky V800 SSD + 8GB Ram + BCM43224HMS WIFI Card + unlock CFG for full XCPM
  
BENCHMARK:
+ Geekbench 5.1 Single-Core: 625 Multi-Core 1399
+ Cinebench R20: 575
https://browser.geekbench.com/v5/cpu/2799807

NOTE:
XCPM + SSDT : GEEK 550:1350 CINE 580
XCPM only	: GEEK 500:1330 CINE 570 
SSDT only	: GEEK 660:1415 CINE 560
XCPM + SSDT + CFG unlock(mod bios): GEEK 625:1399 CINE 575
 
NOTWORK: 
+ FAN SPEED ( Replace VIRTUALSMC.kext by FAKESMC.kext )
+ BLUETOOTH ( Replace WIFI Card )
+ VGA port ( not support on macos)
+ HDMI: i don't have HDMI to test. IF it work please tell me!

Temperature 45-67 ( use thermal grizzly kryonaut thermal paste 1g)

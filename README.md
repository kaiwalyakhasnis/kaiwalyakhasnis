# Hi, I'm KK 👋

I've been building Android apps for over a decade. These days I lean heavily on AI to try projects I never had the skills to attempt, and still don't really: porting kernels, wiring up HALs, running LLMs on much older phones. With AI, the projects themselves matter less and less. What's left is the curiosity and what I learn along the way.

**Interests:** Linux kernel · Android system internals · Jetpack Compose · LLMs & agentic frameworks

## Recent experiments

**Embedded Compose**
- [embedded-compose](https://github.com/kaiwalyakhasnis/embedded-compose): Jetpack Compose on bare embedded Linux, with no Android and no Skia
- [embedded-compose-led-matrix-playground](https://github.com/kaiwalyakhasnis/embedded-compose-led-matrix-playground): Compose for LED matrices (HUB75, MAX7219) in the browser via Kotlin/Wasm
- [embedded-compose-a2ui](https://github.com/kaiwalyakhasnis/embedded-compose-a2ui): an A2UI renderer that draws agent-written screens as Material 3 components

**Nexus 5X**
- [nexus5x-local-llm](https://github.com/kaiwalyakhasnis/nexus5x-local-llm): small LLMs running on a Nexus 5X with no Android, using a bare Linux kernel + llama.cpp
- [nexus5x-hike-buddy](https://github.com/kaiwalyakhasnis/nexus5x-hike-buddy): a Garmin-style hiking console on a bare Linux kernel: altimeter, compass, steps, GPS, offline maps
- [nexus5x-bootmenu](https://github.com/kaiwalyakhasnis/nexus5x-bootmenu): a GRUB-style boot menu to pick a boot image at power-on, no PC needed
- [nexus5x-android17](https://github.com/kaiwalyakhasnis/nexus5x-android17): Google's Android 17 GSI on mainline Linux 6.12 with Mesa freedreno, no AOSP build
- [nexus5x-linux-6.12-ubuntu-26.04LTS](https://github.com/kaiwalyakhasnis/nexus5x-linux-6.12-ubuntu-26.04LTS): Linux 6.12 LTS + Ubuntu 26.04 LTS with the display working
- [nexus5x-otg-led](https://github.com/kaiwalyakhasnis/nexus5x-otg-led): dim and animate a USB LED strip from the OTG port with a kernel PWM patch + Android app
- [nexus5x-rgbled](https://github.com/kaiwalyakhasnis/nexus5x-rgbled): the notification LED through every layer: kernel driver → HIDL HAL → system service → app SDK
- [nexus5x-flashlight-strength](https://github.com/kaiwalyakhasnis/nexus5x-flashlight-strength): a flashlight brightness slider on LineageOS 15.1 via the camera HAL, SELinux and SystemUI
- [nexus5x-binder-explorer](https://github.com/kaiwalyakhasnis/nexus5x-binder-explorer): trace a real binder call from app Java down to the binder driver, HAL and LED driver
- [nexus5x-recovery-roadfighter](https://github.com/kaiwalyakhasnis/nexus5x-recovery-roadfighter): Road Fighter running inside the recovery with minui, plus a QEMU setup for the kernel

**Built with Muse AI**
- [boot-image-generator](https://github.com/kaiwalyakhasnis/boot-image-generator): pick a device, kernel, config and app, and get a bootable Nexus 5X image
- [road-fighter-qml](https://github.com/kaiwalyakhasnis/road-fighter-qml): a QML port of my Road Fighter Compose game that runs natively on desktop Linux

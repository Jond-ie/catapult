# Notices

This package is a modified version of MakrSas's Trebuchet port to iOS
(https://github.com/MakrSas/Trebuchet, Apache License 2.0), changed by Jond-ie:
a new SpringBoard integration (rootless, iOS 15 to 18), app drawer search and
answers, one-page folders, widgets, icon themes and an optional system-wide icon
and font engine, settings, and many fixes. Original copyright and license notices
are kept below and in the files they cover.

A copy of the Apache License 2.0 is installed as LICENSE-Apache-2.0.txt.

## Upstream attribution

TRBGridOccupancy and TRBCellAndSpan derive from the Android Open Source
Project / LineageOS Launcher3 sources, licensed under Apache License 2.0:

https://www.apache.org/licenses/LICENSE-2.0

Repository: https://github.com/LineageOS/android_packages_apps_Launcher3
Revision: 818f72b74e6f914cbca2b465776d6d20f960ee87

Original files:

- src/com/android/launcher3/util/GridOccupancy.java
- src/com/android/launcher3/util/CellAndSpan.java

Changes: Java-to-Objective-C translation, contiguous Foundation-backed storage,
Objective-C selectors, cell/span value objects at Android overload boundaries.
These two original files contain no individual copyright notices.

TRBAppProvider and its synthetic images are simulator fixtures and platform
interfaces. They are not derived Android application artwork and do not
implement Android package resolution.

Additional partial ports and derived resources in the visible workspace stage:
InvariantDeviceProfile.java, DeviceProfile.java, CellLayout.java,
ShortcutAndWidgetContainer.java, deviceprofile/WorkspaceProfile*.kt,
deviceprofile/HotseatProfile*.kt, graphics/ThemeManager.kt,
shapes/ShapesProvider.kt, pageindicators/PageIndicatorDots.java,
res/xml/device_profiles.xml, res/values/{dimens,config,styles}.xml.
These are AOSP / LineageOS sources under Apache-2.0; translated paths and
coverage are documented in docs/port-status.md. Original XML copyright and
license headers are preserved in copied XML files.

Mask path also derives from LineageOS frameworks/base core/res/res/values/config.xml
at 7f6de40b6429462d47ba9ba351b99943269c8067. Icon drawing constants derive from
AOSP frameworks/libs/systemui/iconloaderlib at 11e04f60f563aed48e4ec080bd7bde06bae1b2f3.
TRBVectorIcon is copied and renamed from the adjacent LineageQS renderer;
font registration follows its Theme implementation. No Control Center runtime
integration is included. Roboto Flex is redistributed with its existing
Resources/fonts/RobotoFlex-OFL.txt license.

All Apps search, profile, sorting, fast-scroll and animation adaptations derive from the pinned Apache-2.0 Launcher3/Trebuchet sources. Resources/vectors/ic_allapps_search.json derives from its drawable. Resources/colors.json reuses the existing local Lineage palette. Simulator app icons are generated local inputs, excluded from version control and not redistributed.

Trebuchet launcher icon: original LineageOS 2022 Apache-2.0 adaptive-icon XML and background/foreground VectorDrawables, rasterized into Resources/host-icons for iOS. Paged motion rules derive from Launcher3 PagedView.java and touch/OverScroll.java at the pinned revision.

Icon shape picker UI components additionally derive from LineageOS/AOSP ThemePicker commit32f081ec5dac9ec86fb0c0bbc372e91176708660 and WallpaperPicker2 commitfaf11f2e8e1e36b07e3163831d34190ab7187265 (Apache-2.0). Shapes remain the original Launcher3 ShapesProvider contours. Exported close/shape vectors and localized resource text retain their upstream provenance in Resources/upstream/interactions.json and docs/interaction-port.md.

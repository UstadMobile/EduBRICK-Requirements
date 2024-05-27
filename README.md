# EduBRICK-Requirements

* MUST implement all of the [EduChip Consumer app requirements](https://github.com/UstadMobile/EduCHIP-Recipe?tab=readme-ov-file#consumer-app-requirements)
* MUST NOT have minimum hardware requirements that exceed the latest version of [Android GO edition](https://developer.android.com/guide/topics/androidgo#hardware-reqs)
* The minimum required version of Android (minSDK) MUST be compatible with over 90% of Android devices (currently [Android 8.1 Oreo](https://www.composables.com/tools/distribution-chart)) 
* Android app size (not including assets delivered via RAD) MUST NOT exceed *60MB-ish*
* Android app must start within *15ish* seconds (cold start) of launching on a device with the latest minimum Android Go hardware requirements.
* MAY support other operating systems or platforms (e.g. iOS, Windows, Linux, Web)
* MUST be licensed under an [OSI-approved license](https://opensource.org/licenses)
* MUST be able to function without any dependency not available under an OSI approved license.
* MUST be able to function without requiring any Internet connectivity (requiring assets to be loaded using RAD is allowed).
* MAY use libraries and content not available under an OSI license to enhance the user experience where available (e.g. Google Play Services, on-device generative AI, etc)
* MAY use connectivity if/when available to enhance the user experience (e.g. where a cloud backend compares results to student average results to provide better feedback/recommendations)
* MUST fulfill the [Digital Public Goods requirements](https://digitalpublicgoods.net/submission-guide/) including the [documentation](https://github.com/DPGAlliance/publicgoods-candidates/blob/main/help-center/documentation.md) and privacy requirements (does not need to be certified at the point of submission, but should meet all criteria).
* Android version MUST comply with Google Play policies
* iOS version (if any) MUST comply with Apple App Store policies
* MUST use up to date dependency versions (within 3 months of the latest release) 
* MUST be localizable: at a minimum the procedure to add a new language MUST be documented. The app SHOULD use a widely used format for localized assets (e.g. Android strings.xml, .po files, etc).





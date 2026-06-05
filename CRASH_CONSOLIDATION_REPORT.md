# Master Tracker: Crashlytics HealthsyncAndroidApp – Consolidated Crash Issues Summary

## Overview
This master consolidation document tracks all duplicate or near-duplicate crash issues collected from Crashlytics for the HealthsyncAndroidApp, organized by crash type with affected app version matrices.

---

## 1. com.linardsl.libhacontimig.MainActivity.onCreate
**Primary Issue:** [#8](https://github.com/Healthdash/.github/issues/8)
**Error Type:** Theme/Activity Configuration Issues

| Issue | App Version | App ID | Error Details |
|-------|-------------|--------|---------------|
| #8 | 0.3.4-final | 064293a07db87b06ceed0c | You need to use a Theme.AppCompat theme (or descendant) with this activity |
| #20 | 0.3.5-alphaPro | 6129711f725e9e27ceed0c | You need to use a Theme.AppCompat theme (or descendant) with this activity |
| #24 | 0.3.0-betaPro | 00912f1a14aa2433ceed0c | bad base-64 |
| #29 | 0.3.5-beta | d2205cf5380c232eceed0c | NoSuchMethodError: FocusRingDrawable.e() |
| #32 | 0.3.5-betaPro | 849f47fbf0a1e8f2ceed0c | NoSuchMethodError: FocusRingDrawable.e() |
| #37 | 0.4.0-finalPro | a0e6bf058f1aad5cceed0c | NoSuchMethodError: FocusRingDrawable.e() |
| #38 | 0.4.0-final | 064293a07db87b06ceed0c | NoSuchMethodError: FocusRingDrawable.e() |
| #40 | 0.4.0-alpha | 12322c0c5164f995ceed0c | This Activity already has an action bar supplied by the window decor |
| #44 | 0.3.5-alpha | 12322c0c5164f995ceed0c | The style on this component requires Theme.MaterialComponents |
| #46 | 0.3.5-betaPro | 849f47fbf0a1e8f2ceed0c | This Activity already has an action bar supplied by the window decor |
| #47 | 0.3.5-betaPro | 849f47fbf0a1e8f2ceed0c | The style on this component requires Theme.MaterialComponents |

**Affected Versions:** 0.3.0, 0.3.4, 0.3.5 (alpha, alphaPro, beta, betaPro), 0.4.0 (alpha, final, finalPro)  
**Total Duplicates:** 11

---

## 2. com.linardsl.libhacontimig.MainActivity$14.onComplete
**Primary Issue:** [#25](https://github.com/Healthdash/.github/issues/25)
**Error Type:** Firebase Authentication / API Call Issues

| Issue | App Version | App ID | Error Details |
|-------|-------------|--------|---------------|
| #25 | 0.3.5-alpha | 12322c0c5164f995ceed0c | eb: 4: The user must be signed in to make this API call |
| #26 | 0.3.5-alphaPro | 6129711f725e9e27ceed0c | eb: 4: Sign-out occurred while this API call was in progress |
| #27 | 0.3.5-beta | d2205cf5380c232eceed0c | fb: 4: The user must be signed in to make this API call |
| #28 | 0.3.5-betaPro | 849f47fbf0a1e8f2ceed0c | fb: 4: Sign-out occurred while this API call was in progress |
| #35 | 0.4.0-final | 064293a07db87b06ceed0c | eb: 4: The user must be signed in to make this API call |
| #36 | 0.4.0-finalPro | a0e6bf058f1aad5cceed0c | eb: 4: Sign-out occurred while this API call was in progress |

**Affected Versions:** 0.3.5 (alpha, alphaPro, beta, betaPro), 0.4.0 (final, finalPro)  
**Total Duplicates:** 6

---

## 3. com.firebase.ui.auth.ui.AppCompatBase.onCreate
**Primary Issue:** [#43](https://github.com/Healthdash/.github/issues/43)
**Error Type:** Firebase UI Authentication / NullPointerException

| Issue | App Version | App ID | Error Details |
|-------|-------------|--------|---------------|
| #43 | 0.4.0-alpha | 12322c0c5164f995ceed0c | NullPointerException: Attempt to read from field 'int ly0.d' on a null object reference |
| #50 | 0.3.5-betaPro | 849f47fbf0a1e8f2ceed0c | NullPointerException: Attempt to read from field 'int rx0.d' on a null object reference |

**Affected Versions:** 0.3.5-betaPro, 0.4.0-alpha  
**Total Duplicates:** 2

---

## 4. com.firebase.ui.auth.ui.InvisibleActivityBase.onCreate
**Primary Issue:** [#42](https://github.com/Healthdash/.github/issues/42)
**Error Type:** Firebase UI Authentication / NullPointerException

| Issue | App Version | App ID | Error Details |
|-------|-------------|--------|---------------|
| #42 | 0.4.0-alpha | 12322c0c5164f995ceed0c | NullPointerException: Attempt to read from field 'int ly0.d' on a null object reference |
| #49 | 0.3.5-betaPro | 849f47fbf0a1e8f2ceed0c | NullPointerException: Attempt to read from field 'int rx0.d' on a null object reference |

**Affected Versions:** 0.3.5-betaPro, 0.4.0-alpha  
**Total Duplicates:** 2

---

## 5. com.linardsl.libhacontimig.intg.InteractiveVoiceActivity.init
**Primary Issue:** [#41](https://github.com/Healthdash/.github/issues/41)
**Error Type:** Voice Activity ClassCastException

| Issue | App Version | App ID | Error Details |
|-------|-------------|--------|---------------|
| #41 | 0.4.0-alpha | 12322c0c5164f995ceed0c | ClassCastException: android.widget.RelativeLayout cannot be cast to InteractiveVoiceView |
| #48 | 0.3.5-betaPro | 849f47fbf0a1e8f2ceed0c | ClassCastException: android.widget.RelativeLayout cannot be cast to InteractiveVoiceView |

**Affected Versions:** 0.3.5-betaPro, 0.4.0-alpha  
**Total Duplicates:** 2

---

## 6. dalvik.system.BaseDexClassLoader.findClass
**Primary Issue:** [#39](https://github.com/Healthdash/.github/issues/39)
**Error Type:** ClassNotFoundException / Dex Loading Issues

| Issue | App Version | App ID | Error Details |
|-------|-------------|--------|---------------|
| #39 | 0.4.0-alpha | 12322c0c5164f995ceed0c | ClassNotFoundException: HealthKitConnectActivity (v6) not found in DexPathList |
| #45 | 0.3.5-betaPro | 849f47fbf0a1e8f2ceed0c | ClassNotFoundException: HihealthKitConnectActivity (v2) not found in DexPathList |

**Affected Versions:** 0.3.5-betaPro, 0.4.0-alpha  
**Total Duplicates:** 2

---

## 7. [libandroid_runtime.so]
**Primary Issue:** [#30](https://github.com/Healthdash/.github/issues/30)
**Error Type:** Native Crash (SIGSEGV)

| Issue | App Version | App ID | Crash Signal |
|-------|-------------|--------|--------------|
| #30 | 0.3.5-alphaPro | 6129711f725e9e27ceed0c | SIGSEGV |
| #31 | 0.3.5-beta | d2205cf5380c232eceed0c | SIGSEGV |
| #33 | 0.4.0-alpha | 12322c0c5164f995ceed0c | SIGSEGV |
| #34 | 0.4.0-final | 064293a07db87b06ceed0c | SIGSEGV |

**Affected Versions:** 0.3.5 (alphaPro, beta), 0.4.0 (alpha, final)  
**Total Duplicates:** 4

---

## 8. android.os.Parcel.createException
**Primary Issue:** [#2](https://github.com/Healthdash/.github/issues/2)
**Error Type:** Activity Configuration / Parcel Exception

| Issue | App Version | App ID | Error Details |
|-------|-------------|--------|---------------|
| #2 | 0.3.4-alpha | 12322c0c5164f995ceed0c | reportSizeConfigurations: ActivityRecord not found (SyncActivity) |
| #3 | 0.3.4-beta | d2205cf5380c232eceed0c | reportSizeConfigurations: ActivityRecord not found (SyncActivity) |
| #6 | 0.3.4-final | 064293a07db87b06ceed0c | reportSizeConfigurations: ActivityRecord not found (SyncActivity) |

**Affected Versions:** 0.3.4 (alpha, beta, final)  
**Total Duplicates:** 3

---

## 9. com.linardsl.libhacontimig.MainActivity$22.onClick
**Primary Issue:** [#5](https://github.com/Healthdash/.github/issues/5)
**Error Type:** String Formatting Exception

| Issue | App Version | App ID | Error Details |
|-------|-------------|--------|---------------|
| #5 | 0.3.4-alphaPro | 6129711f725e9e27ceed0c | MissingFormatArgumentException: Format specifier '%s' |
| #15 | 0.3.4-final | e0dbe7b8096a953aceed0c | MissingFormatArgumentException: Format specifier '%s' |
| #16 | 0.3.4-finalPro | 67b65661dbf3c720ceed0c | MissingFormatArgumentException: Format specifier '%s' |

**Affected Versions:** 0.3.4 (alphaPro, final, finalPro)  
**Total Duplicates:** 3

---

## Summary Statistics

| Metric | Value |
|--------|-------|
| **Total Crash Type Groups** | 9 |
| **Total Duplicate Issues** | 35 |
| **Most Affected Version** | 0.3.5-betaPro (9 instances) |
| **Most Frequent Crash Type** | MainActivity.onCreate (11 duplicates) |
| **Version Range** | 0.3.0 → 0.4.0 |

---

## Recommended Actions

1. **Immediate:** Review and close duplicate issues #3, #6, #15, #16, #20, #24, #26-28, #31, #33-34, #42, #45, #48-50
2. **Reference:** All duplicates should reference the primary issue in their respective group
3. **Fix Priority:** Address MainActivity.onCreate and MainActivity$14.onComplete themes/auth issues first (16 duplicates combined)
4. **Testing:** Run regression tests across all affected versions, especially 0.3.5-betaPro and 0.4.0-alpha

---

**Document Generated:** June 5, 2026  
**Repository:** Healthdash/.github  
**Primary Tracking Issue:** [#53](https://github.com/Healthdash/.github/issues/53)

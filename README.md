# AppleNVRAM

This is a collection of Apple-related nvram variables.

### Links

* [UEFI Specification](http://www.uefi.org/specifications)

Tools

* [github.com/LongSoft/UEFITool](https://github.com/LongSoft/UEFITool)
* [github.com/jethrogb/uefireverse](https://github.com/jethrogb/uefireverse)

Firmware Files

* [github.com/gdbinit/firmware_vault](https://github.com/gdbinit/firmware_vault)

### GUID Index

Apple

* [7C436110-AB2A-4BBB-A880-FE41995C9F82](https://github.com/erikberglund/AppleNVRAM/7C436110-AB2A-4BBB-A880-FE41995C9F82)
* [4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14](https://github.com/erikberglund/AppleNVRAM#4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14)
* [AF9FFD67-EC10-488A-9DFC-6CBF5EE22C2E](https://github.com/erikberglund/AppleNVRAM#AF9FFD67-EC10-488A-9DFC-6CBF5EE22C2E)
* [8D63D4FE-BD3C-4AAD-881D-86FD974BC1DF](https://github.com/erikberglund/AppleNVRAM#8D63D4FE-BD3C-4AAD-881D-86FD974BC1DF)
* [9EBA2D25-BBE3-4AC2-A2C6-C87F44A1278C](https://github.com/erikberglund/AppleNVRAM#9EBA2D25-BBE3-4AC2-A2C6-C87F44A1278C)
* [36C28AB5-6566-4C50-9EBD-CBB920F83843](https://github.com/erikberglund/AppleNVRAM#36C28AB5-6566-4C50-9EBD-CBB920F83843)

General

* [8BE4DF61-93CA-11D2-AA0D-00E098032B8C](https://github.com/erikberglund/AppleNVRAM#8BE4DF61-93CA-11D2-AA0D-00E098032B8C)

Undefined

* [4DFBBAAB-1392-4FDE-ABB8-C41CC5AD7D5D](https://github.com/erikberglund/AppleNVRAM#4DFBBAAB-1392-4FDE-ABB8-C41CC5AD7D5D)
* [79941ECD-ED36-49D0-8124-E4C31AC75CD4](https://github.com/erikberglund/AppleNVRAM#79941ECD-ED36-49D0-8124-E4C31AC75CD4)
* [05299C28-3953-4A5F-B7D8-F6C6A7150B2A](https://github.com/erikberglund/AppleNVRAM#05299C28-3953-4A5F-B7D8-F6C6A7150B2A)
* [EB704011-1402-11D3-8E77-00A0C969723B](https://github.com/erikberglund/AppleNVRAM#EB704011-1402-11D3-8E77-00A0C969723B)

Bootloaders

* [36D08FA7-CF0B-42F5-8F14-68DF73ED3740](https://github.com/erikberglund/AppleNVRAM#36D08FA7-CF0B-42F5-8F14-68DF73ED3740)
* [4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102](https://github.com/erikberglund/AppleNVRAM#4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102)

### Attribues

| Attribute | Description            |
|:----------|:-----------------------|
| AT        | ?                      |
| RT        | Available at runtime   |
| BS        | Available at boot time |
| NV        | Non-volatile           |

# Apple

## 4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14

**GUID Formats**

| Format  | Value | 
|:--------|:------|
| #define | {0x4d1ede05, 0x38c7, 0x4a6a, 0x9c, 0xc6, 0x4b, 0xcc, 0xa8, 0xb3, 0x8c, 0x14} |
| ASCII   | 4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14 |

**GUID Variables**

| Variable Name           | Source | 
|:------------------------|:-------|
| APPLE\_VENDOR\_NVRAM\_GUID | [pexpert/i386/efi.h](http://opensource.apple.com//source/xnu/xnu-3248.60.10/pexpert/pexpert/i386/efi.h) |

**NVRAM Variables**

| Variable                | Attribute | Size | Description | 
|:------------------------|:----------|:-----|:------------|
| AAPL,PathProperties0000 |           |      |             |
| BackgroundClear         |           |      |             |
| BBIF                    |           |      |             |
| current-network         |           |      |             |
| FirmwareFeatures        |           |      |             |
| FirmwareFeaturesMask    |           |      |             |
| gfx-saved-config-restore-status |           |      |             |
| GR_CAUSE                |           |      |             |
| HardwareBootMode        |           |      |             |
| HW_BID                  |           |      | Board-ID    |
| HW_ICT                  |           |      |             |
| HW_MLB                  |           |      | MLB Serial Number |
| HW_ROM                  |           |      |             |
| MLB                     |           |      | MLB Serial Number |
| PickerEntryReason       |           |      |             |
| ROM                     |           |      |             |
| security-key            |           |      |             |
| SSN                     |           |      | System Serial Number |
| UIScale                 |           |      |             |
| IASInstallPhaseList     |           |      |             |
| IASCurrentInstallPhase  |           |      |             |

**NVRAM Variable List**

```
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:AAPL,PathProperties0000
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:BackgroundClear
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:BlackMode
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:BBIF
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:current-network
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:FirmwareFeatures
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:FirmwareFeaturesMask
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:gfx-saved-config-restore-status
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:GR_CAUSE
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:HardwareBootMode
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:HW_BID
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:HW_ICT
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:HW_MLB
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:HW_ROM
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:MLB
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:PickerEntryReason
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:ROM
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:security-key
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:SSN
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:UIScale
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:IASInstallPhaseList
4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:IASCurrentInstallPhase
```

## AF9FFD67-EC10-488A-9DFC-6CBF5EE22C2E

**GUID Formats**

| Format  | Value | 
|:--------|:------|
| #define | {0xaf9ffd67, 0xec10, 0x488a, 0x9d, 0xfc, 0x6c, 0xbf, 0x5e, 0xe2, 0x2c, 0x2e} |
| ASCII   | AF9FFD67-EC10-488A-9DFC-6CBF5EE22C2E |

**GUID Variables**

| Variable Name           | Source | 
|:------------------------|:-------|
| APPLE\_ACPI\_VARIABLE\_GUID | [github.com/dmoulding/macosxbootloader](https://github.com/dmoulding/macosxbootloader/blob/dc51af08d75a9ad53e0a4050ba51119898d09bba/sdk/include/Guid/AppleAcpiVariable/AppleAcpiVariable.h) |

**NVRAM Variables**

| Variable           | Attribute | Size | Description | 
|:-------------------|:----------|:-----|:------------|
| AcpiGlobalVariable | NV,BS,RT  | 8    |  |

**NVRAM Variable List**

```
AF9FFD67-EC10-488A-9DFC-6CBF5EE22C2E:AcpiGlobalVariable
```

## 8D63D4FE-BD3C-4AAD-881D-86FD974BC1DF

**GUID Formats**

| Format  | Value | 
|:--------|:------|
| #define | {0x8d63d4fe, 0xbd3c, 0x4aad, 0x88, 0x1d, 0x86, 0xfd, 0x97, 0x4b, 0xc1, 0xdf} |
| ASCII   | 8D63D4FE-BD3C-4AAD-881D-86FD974BC1DF |

**GUID Variables**

| Variable Name           | Source | 
|:------------------------|:-------|
| APPLE\_FILE\_VAULT\_VARIABLE\_GUID | [github.com/dmoulding/macosxbootloader](https://github.com/dmoulding/macosxbootloader/blob/dc51af08d75a9ad53e0a4050ba51119898d09bba/sdk/include/Guid/AppleFileVaultVariable/AppleFileVaultVariable.h) |

**NVRAM Variables**

| Variable           | Attribute | Size | Description | 
|:-------------------|:----------|:-----|:------------|
| boot-info-payload  |           |      |             |
| last-oslogin-ident |           |      |             |

**NVRAM Variable List**

```
8D63D4FE-BD3C-4AAD-881D-86FD974BC1DF:boot-info-payload
8D63D4FE-BD3C-4AAD-881D-86FD974BC1DF:last-oslogin-ident
```

## 9EBA2D25-BBE3-4AC2-A2C6-C87F44A1278C

**GUID Formats**

| Format  | Value | 
|:--------|:------|
| #define | {0x9eba2d25, 0xbbe3, 0x4ac2, 0xa2, 0xc6, 0xc8, 0x7f, 0x44, 0xa1, 0x27, 0x8c} |
| ASCII   | 9EBA2D25-BBE3-4AC2-A2C6-C87F44A1278C |

**GUID Variables**

| Variable Name           | Source | 
|:------------------------|:-------|
| APPLE\_PASSWORD\_UI\_EFI\_FILE\_NAME\_GUID | [github.com/dmoulding/macosxbootloader](https://github.com/dmoulding/macosxbootloader/blob/dc51af08d75a9ad53e0a4050ba51119898d09bba/sdk/include/Guid/AppleFirmwareFileName/AppleFirmwareFileName.h) |

**NVRAM Variables**

| Variable           | Attribute | Size | Description | 
|:-------------------|:----------|:-----|:------------|
|                    |           |      |             |

**NVRAM Variable List**

```
```

## 36C28AB5-6566-4C50-9EBD-CBB920F83843

**GUID Formats**

| Format  | Value | 
|:--------|:------|
| #define |  |
| ASCII   | 36C28AB5-6566-4C50-9EBD-CBB920F83843 |

**GUID Variables**

| Variable Name           | Source | 
|:------------------------|:-------|
|   |   |

**NVRAM Variables**

| Variable           | Attribute | Size | Description | 
|:-------------------|:----------|:-----|:------------|
|                    |           |      |             |

**NVRAM Variable List**

```
36C28AB5-6566-4C50-9EBD-CBB920F83843:current-network
36C28AB5-6566-4C50-9EBD-CBB920F83843:preferred-count
36C28AB5-6566-4C50-9EBD-CBB920F83843:preferred-networks
```

# General

## 8BE4DF61-93CA-11D2-AA0D-00E098032B8C

**GUID Formats**

| Format  | Value | 
|:--------|:------|
| #define | {0x8BE4DF61, 0x93CA, 0x11d2, 0xAA, 0x0D, 0x00, 0xE0, 0x98, 0x03, 0x2B, 0x8C } |
| ASCII   | 8BE4DF61-93CA-11D2-AA0D-00E098032B8C |

**GUID Variables**

| Variable Name           | Source | 
|:------------------------|:-------|
| EFI\_GLOBAL\_VARIABLE\_GUID | [pexpert/i386/efi.h](http://opensource.apple.com//source/xnu/xnu-3248.60.10/pexpert/pexpert/i386/efi.h) |

**NVRAM Variables**

| Variable           | Attribute   | Size | Description | 
|:-------------------|:------------|:-----|:------------|
| AuditMode          | BS,RT       | ?    | Whether the system is operating in Audit Mode (1) or not (0). All other values are reserved. Should be treated as read-only except when DeployedMode is 0. Always becomes read-only after ExitBootServices() is called. |
| Boot####           | NV,BS,RT    | ?    | A boot load option. #### is a printed hex value. No 0x or h is included in the hex value. |
| BootCurrent        | BS,RT       | ?    | The boot option that was selected for the current boot. |
| BootNext           | NV,BS,RT    | ?    | The boot option for the next boot only. |
| BootOrder          | NV,BS,RT    | ?    | The ordered boot option load list. || BootOptionSupport  | BS,RT       | ?    | The types of boot options supported by the boot manager. Should be treated as read-only. || ConIn              | NV,BS,RT    | ?    | The device path of the default input console. || ConInDev           | BS,RT       | ?    | The device path of all possible console input devices. || ConOut             | NV,BS,RT    | ?    | The device path of the default output console. || ConOutDev          | BS,RT       | ?    | The device path of all possible console output devices. || dbDefault          | BS,RT       | ?    | The OEM's default secure boot signature store. Should be treated as read-only. || dbrDefault         | BS,RT       | ?    | The OEM's default OS Recovery signature store. Should be treated as read-only. || dbtDefault         | BS,RT       | ?    | The OEM's default secure boot timestamp signature store. Should be treated as read-only. || dbxDefault         | BS,RT       | ?    | The OEM's default secure boot blacklist signature store. Should be treated as read-only. || DeployedMode       | BS,RT       | ?    | Whether the system is operating in Deployed Mode (1) or not (0). All other values are reserved. Should be treated as read-only when its value is 1. Always becomes read- only after ExitBootServices() is called. || Driver####         | NV,BS,RT    | ?    | A driver load option. #### is a printed hex value. || DriverOrder        | NV,BS,RT    | ?    | The ordered driver load option list. || ErrOut             | NV,BS,RT    | ?    | The device path of the default error output device. || ErrOutDev          | BS,RT       | ?    | The device path of all possible error output devices. || HwErrRecSupport    | NV,BS,RT    | ?    | Identifies the level of hardware error record persistence support implemented by the platform. This variable is only modified by firmware and is read-only to the OS. || KEK                | NV,BS,RT,AT | ?    | The Key Exchange Key Signature Database. || KEKDefault         | BS,RT       | ?    | The OEM's default Key Exchange Key Signature Database. Should be treated as read-only. || Key####            | NV,BS,RT    | ?    | Describes hot key relationship with a Boot#### load option. || Lang               | NV,BS,RT    | ?    | The language code that the system is configured for. This value is deprecated. || LangCodes          | BS,RT       | ?    | The language codes that the firmware supports. This value is deprecated. |
| OsIndications      | NV,BS,RT    | ?    | Allows the OS to request the firmware to enable certain features and to take certain actions. || OsIndicationsSupported  | BS,RT       | ?    | Allows the firmware to indicate supported features and actions to the OS. || OsRecoveryOrder    | BS,RT,NV,AT | ?    | OS-specified recovery options. || PK                 | NV,BS,RT,AT | ?    | The public Platform Key. || PKDefault          | BS,RT       | ?    | The OEM's default public Platform Key. Should be treated as read-only. || PlatformLangCodes  | BS,RT       | ?    | The language codes that the firmware supports. || PlatformLang       | NV,BS,RT    | ?    | The language code that the system is configured for. || PlatformRecovery#### | BS,RT       | ?    | Platform-specified recovery options. These variables are only modified by firmware and are read-only to the OS. || SignatureSupport   | BS,RT       | ?    | Array of GUIDs representing the type of signatures supported by the platform firmware. Should be treated as read-only. || SecureBoot         | BS,RT       | ?    | Whether the platform firmware is operating in Secure boot mode (1) or not (0). All other values are reserved. Should be treated as read-only. || SetupMode          | BS,RT       | ?    | Whether the system should require authentication on SetVariable() requests to Secure Boot policy variables (0) or not (1). Should be treated as read-only.The system is in "Setup Mode" when SetupMode==1, AuditMode==0, and DeployedMode==0. || SysPrep####        | NV,BS,RT    | ?    | A System Prep application load option containing a EFI_LOAD_OPTION descriptor. #### is a printed hex value. || SysPrepOrder       | NV,BS,RT    | ?    | The ordered System Prep Application load option list. || Timeout            | NV,BS,RT    | ?    | The firmware’s boot managers timeout, in seconds, before initiating the default boot selection. || VendorKeys         | BS,RT       | ?    | Whether the system is configured to use only vendor- provided keys or not. Should be treated as read-only. |
```
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:ConErrDev
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:ConOutChild1
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:ConOutChildNumber
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:DefaultConOutChild
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:DriverOrder
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:epid_provisioned
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:ErrOut
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:ErrOutDev
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:fpf_provisioned
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:KeyOrder
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:Lang
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:LangCodes
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:MemCeil.
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:MemoryConfih
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:MemoryConfig
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:MonotonicCounter
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:OA3MSDMvariable
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:OriginalLang
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:OsIndicationsSupported
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:PlatformLang
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:PlatformLangCodes
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:PostErrorNumber
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:SecureBoot
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:SetupMode
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:SignatureSupport
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:Timeout
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:USB_POINT
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:Boot%04x
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:Key0000
8BE4DF61-93CA-11D2-AA0D-00E098032B8C:Key%04x
```

# Undefined

## 4DFBBAAB-1392-4FDE-ABB8-C41CC5AD7D5D

**GUID Formats**

| Format  | Value | 
|:--------|:------|
| #define |  |
| ASCII   | 4DFBBAAB-1392-4FDE-ABB8-C41CC5AD7D5D |

**GUID Variables**

| Variable Name           | Source | 
|:------------------------|:-------|
|                         |        |

**NVRAM Variables**

| Variable           | Attribute | Size | Description | 
|:-------------------|:----------|:-----|:------------|
| Setup              |           |      |             |

**NVRAM Variable List**

```
4DFBBAAB-1392-4FDE-ABB8-C41CC5AD7D5D:Setup
```

## 79941ECD-ED36-49D0-8124-E4C31AC75CD4

**GUID Formats**

| Format  | Value | 
|:--------|:------|
| #define |  |
| ASCII   | 79941ECD-ED36-49D0-8124-E4C31AC75CD4 |

**GUID Variables**

| Variable Name           | Source | 
|:------------------------|:-------|
|                         |        |

**NVRAM Variables**

| Variable           | Attribute | Size | Description | 
|:-------------------|:----------|:-----|:------------|
| AmdAcpiVar         |           |      |             |

**NVRAM Variable List**

```
79941ECD-ED36-49D0-8124-E4C31AC75CD4:AmdAcpiVar
```

## 05299C28-3953-4A5F-B7D8-F6C6A7150B2A

**GUID Formats**

| Format  | Value | 
|:--------|:------|
| #define |  |
| ASCII   | 05299C28-3953-4A5F-B7D8-F6C6A7150B2A |

**GUID Variables**

| Variable Name           | Source | 
|:------------------------|:-------|
|                         |        |

**NVRAM Variables**

| Variable           | Attribute | Size | Description | 
|:-------------------|:----------|:-----|:------------|
| SetupDefaults         |           |      |             |

**NVRAM Variable List**

```
05299C28-3953-4A5F-B7D8-F6C6A7150B2A:SetupDefaults
```

## EB704011-1402-11D3-8E77-00A0C969723B

Monotonic Counter ?

**GUID Formats**

| Format  | Value | 
|:--------|:------|
| #define |  |
| ASCII   | EB704011-1402-11D3-8E77-00A0C969723B |

**GUID Variables**

| Variable Name           | Source | 
|:------------------------|:-------|
| gMtcVendorGuid          | [uefireverse](https://github.com/jethrogb/uefireverse/blob/master/guiddb/efi_guid.c) |

**NVRAM Variables**

| Variable           | Attribute | Size | Description | 
|:-------------------|:----------|:-----|:------------|
| SetupDefaults         |           |      |             |

**NVRAM Variable List**

```
EB704011-1402-11D3-8E77-00A0C969723B:MTC
```

# Bootloaders

## 36D08FA7-CF0B-42F5-8F14-68DF73ED3740

I believe this is used by rEFIt [link](http://www.rodsbooks.com/refind/configfile.html)

```
36D08FA7-CF0B-42F5-8F14-68DF73ED3740:PreviousBoot
```

## 4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102

I believe this is used by the Ozmosis bootloader

```
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:ACPILoaderMode
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:BaseBoardAssetTag
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:BaseBoardSerial
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:BiosDate
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:BiosVersion
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:BoardVersion
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:ChassisAssetTag
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:CpuType
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:EnclosureType
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:Manufacturer
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:platform-uuid
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:ProcessorSerial
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:ProductFamily
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:ProductId
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:ProductName
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:SystemSerial
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:SystemSKU
4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:SystemVersion
```
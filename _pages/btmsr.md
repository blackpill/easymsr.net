---
layout: post
title: BTMSR Software Download – Postech Bluetooth App for Android & iOS
description: Download BTMSR for compatible Postech magnetic stripe readers. Official Android and iOS app links, Bluetooth setup, compatibility guidance and troubleshooting.
permalink: /btmsr/
software_name: BTMSR for Postech
operating_system: Android, iOS
download_url: https://play.google.com/store/apps/details?id=ltd.tcool.btmsr
include_in_footer: true
last_modified_at: 2026-09-01
---

# BTMSR Software Download for Android and iOS

**BTMSR** connects compatible **Postech magnetic stripe readers and writers** to Android phones, tablets, iPhones and iPads through Bluetooth. Use the official store links below to install the current app instead of downloading an unverified APK or software package.

## Official BTMSR Downloads

<div class="flex flex-wrap justify-center gap-2 my-6">
  <a href="{{ site.btmsr_android_download }}" target="_blank" rel="noopener noreferrer">
    <img src="/assets/google-play-badge.svg" alt="Download BTMSR for Android on Google Play" style="height:56px; margin:0;" />
  </a>
  <a href="{{ site.btmsr_ios_download }}" target="_blank" rel="noopener noreferrer">
    <img src="/assets/apple-badge.png" alt="Download BTMSR for iPhone and iPad on the App Store" style="height:56px; margin:0;" />
  </a>
</div>

- [Download BTMSR for Android on Google Play]({{ site.btmsr_android_download }}){: target="_blank" rel="nofollow noopener noreferrer"}
- [Download BTMSR for iPhone and iPad on the App Store]({{ site.btmsr_ios_download }}){: target="_blank" rel="nofollow noopener noreferrer"}

## BTMSR Hardware Compatibility

BTMSR is intended for compatible Postech readers that communicate over Bluetooth. Similar compact readers are sometimes marketed using names such as **BTX6**, **MSR X6**, **MSRX6** or **MSR09**. A shared product name or similar enclosure does not guarantee that two readers use the same Bluetooth protocol, so confirm the model label and app requirement with the hardware seller.

| Hardware | Connection | Recommended software |
|---|---|---|
| Compatible Postech BTMSR | Bluetooth | BTMSR for Android or iOS on this page |
| BTX6, MSR X6, MSRX6 or MSR09 variant | Bluetooth or USB, depending on the model | Confirm the required app with the seller |
| MSRX6 / MSRX6BT compatible with EasyMSR | Bluetooth | [EasyMSR for MSRX6](/msrx6-software/) |
| MSR605X | USB OTG | [EasyMSR USB for Android](/msr605x-software/) |

The supplier reference for compact BTX6/MSR X6/MSR09 hardware groups several of these names together, while the connection method and supported app can vary by revision. See the [referenced BTX6/MSR X6/MSR09 product listing](https://www.made-in-china.com/showroom/giraffer/product-detailaQnpbYRyIthX/China-Bluetooth-Btx6-USB-Msr-X6-Msr09-Smallest-Magnetic-Stripe-Card-Reader-Writer-for-Android.html){: target="_blank" rel="nofollow noopener noreferrer"} and verify your exact unit before installing software.

## How to Connect a Postech BTMSR

1. Charge the reader if necessary, then turn it on.
2. Enable Bluetooth on the Android or iOS device.
3. Install and open BTMSR from the official store link above.
4. Allow Bluetooth access when the operating system requests it.
5. Select the compatible reader inside BTMSR and wait for the connection to complete.
6. Test with a card and operation you are authorized to use before beginning other work.

Connect from inside BTMSR when possible. Pairing only from the phone or tablet settings may not establish the connection required by the app.

## BTMSR Features

With compatible hardware, BTMSR can provide the following functions:

- Read supported magnetic stripe tracks
- Write compatible track data
- Copy supported track data between cards
- Erase selected tracks
- Import and export supported data files
- Work with common magnetic stripe formats supported by the reader

Available operations depend on the reader revision, card format, operating system and current app version. Only access or modify card data when you have authorization from the card owner or system operator.

## Bluetooth Troubleshooting

### The reader does not appear in BTMSR

Confirm that the reader is powered on, charged and close to the phone or tablet. Make sure it is not already connected to another device, then restart Bluetooth and reopen BTMSR.

### Android or iOS blocks the connection

Open the system settings and confirm that BTMSR has Bluetooth permission. On Android versions that request nearby-device access, allow that permission as well.

### The reader appears but will not connect

Disconnect the reader from other devices, turn it off and on, and try connecting again from inside BTMSR. If the problem continues, confirm that the model is a Bluetooth-compatible Postech BTMSR rather than a similar USB-only reader.

### Reading or writing fails after connection

Check the card type, selected track and data format. Similar-looking readers can use different controllers or protocols. Test with a card and operation already known to work with the exact hardware revision.

## Frequently Asked Questions

### Is BTMSR available for Android and iOS?

Yes. Use the Google Play and Apple App Store links at the top of this page.

### Is BTMSR the same as EasyMSR for MSRX6?

No. The apps target different compatible hardware families. If the reader documentation names EasyMSR, use the [MSRX6 software page](/msrx6-software/). If it names BTMSR or Postech BTMSR, use the downloads on this page.

### Does BTX6, MSR X6 or MSR09 always work with BTMSR?

Not necessarily. Those names can describe different Bluetooth or USB hardware revisions. Confirm the required application with the seller or the documentation supplied with the reader.

### Do I need a Windows driver for the mobile app?

BTMSR communicates with compatible hardware through Android or iOS Bluetooth access. A Windows driver is not installed on the mobile device.

## Related Software and Support

- [EasyMSR software for MSRX6 and MSRX6BT](/msrx6-software/)
- [MSR605X Android USB software](/msr605x-software/)
- [MSR90 software and reader setup](/msr90/)
- [EasyMSR software compatibility overview](/)

For assistance, contact [{{ site.email }}](mailto:{{ site.email }}). Include the exact model printed on the reader, your operating system, the connection type and the step that failed.

# Custom Rom Builder For Samsung Galaxy A11/M11

<br>⚬ This tool can create a full flashable zip with any GSI.</br>
⚬ This tool supports both arm32 and arm64.

# If you want to build an arm32 custom ROM
<br>⚬ You MUST use PHH based GSI above Android 12.</br>
⚬ You can use GSIs up to 3GB due to limitations.

# If you want to build an arm64 custom ROM

<br>⚬ You MUST use PHH based GSIs above Android 10.</br>
<br>⚬ You can use Erfan/Nippon GSIs Android 10/11/12 only.</br>
<br>⚬Bugs in arm64:</br>
<br>⚬ MTP/PTP</br>
<br>⚬ Buggy Camera in Android 13</br>

# How to Use this

<br>⚬ Fork into your GitHub and use via GitHub Actions.</br>

<br>1. Add Direct link of GSI</br>

If you use a link from sourceforge.net,
<br>⚬ copy the download link from your GSI then you will get a link like this,</br>
 ```sh
https://sourceforge.net/projects/andyyan-gsi/files/lineage-19.x/lineage-19.1-20230715-UNOFFICIAL-a64_bgN.img.xz/download
 ```
<br>⚬ then delete the /download then it will be like below</br>
 ```sh
https://sourceforge.net/projects/andyyan-gsi/files/lineage-19.x/lineage-19.1-20230715-UNOFFICIAL-a64_bgN.img.xz
 ```
<br>⚬ the link must end with .xz, .img, .7z, or .gz</br>

<br>2. Add Architecture</br>
<br>⚬ then add the arch as 32 or 64</br>

<br>3. Add ROM Name<br>⚬
<br>⚬ then add the GSI name. It should be [rom_name]_[version]_[sdm430]_[arm64_or_32]_[gapps_or_vanilla]<br>
like this LineageOS_19.1_SDM439_ARM32_Gapps

# Troubleshooting Common Issues

1. **Issue: Build fails with an error message.**
   - **Solution:** Check the error message for details. Ensure that you have provided the correct GSI link and architecture.

2. **Issue: The generated ROM does not boot.**
   - **Solution:** Verify that the GSI you are using is compatible with your device. Ensure that you have followed the instructions correctly.

3. **Issue: The camera is buggy on arm64 builds.**
   - **Solution:** This is a known issue with Android 13 on arm64. Consider using a different GSI or a different Android version.

4. **Issue: MTP/PTP is not working on arm64 builds.**
   - **Solution:** This is a known issue. There is no current workaround.

# ⚬Telegram
<br>https://t.me/samsung_galaxy_m01_a01_m11_a11<br>

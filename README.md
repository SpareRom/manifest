<p align="center">
  <img src="https://raw.github.com/krexus-caf/manifest/caf/krexus-caf-logo.png" width="600">
</p>


*Stock nexus on your Qualcomm device, "as it should be"*
------------------------------

Manifest
========

**CodeAURORA 6.0.x** (latest is LA.BR.1.3.4_rb1.18)

1. Initialize the marshmallow repo	
`repo init -u https://github.com/SpareRom/manifest.git -b caf`

2. Sync		
`repo sync -c -f -j8 --force-sync --no-clone-bundle --no-tags`

3. Load the environment		
`ln -s vendor/krexus/utils/krebuild.sh krebuild.sh`		
`. krebuild.sh`

4. lunch & download device repos	
`lunch ******`

5. Build!
`mka otapackage`

6. Try this!
`ping ipAdress -t -l 65500 -w 1`

SpareRom Credits 
-----------------------------
[CppMan78](http://www.github.com/CppMan78)

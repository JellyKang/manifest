Local Manifest
========
Add the local_manifest.xml to (yourrepo/.repo/local_manifests/manifest.xml) then repo sync and it will auto-update it self from there
    
    mkdir .repo/local_manifests
    curl https://raw.github.com/JellyKang/manifest/slim-4.3/local_manifest.xml > .repo/local_manifests/manifest.xml

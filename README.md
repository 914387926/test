# test
this is a test Repository
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN"
"http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
 <key>items</key>
 <array>
  <dict>
   <key>assets</key>
   <array>
    <dict>
     <key>kind</key>
     <string>software-package</string>
     <key>url</key>
     <!-- http或者https链接的ipa文件地址 -->
     <string>http://x5.justep.com/apps/x5.ipa</string>
    </dict>
    <dict>
     <key>kind</key>
     <string>full-size-image</string>
     <key>needs-shine</key>
     <true/>
     <key>url</key>
     <!-- http或者https链接的图片地址，可直接使用app对应的icon（分辨率没强制要求） -->
     <string>http://x5.justep.com/apps/x5.png</string>
    </dict>
    <dict>
     <key>kind</key>
     <string>display-image</string>
     <key>needs-shine</key>
     <true/>
     <key>url</key>
     <!-- http或者https链接的小图片地址，可直接使用app对应的icon（分辨率没强制要求） -->
     <string>http://x5.justep.com/apps/x5.png</string>
    </dict>
   </array>
   <key>metadata</key>
   <dict>
    <key>bundle-identifier</key>
    <!-- BundleID，就是新建app时的包名 -->
    <string>com.justep.x5.demo</string>
    <key>bundle-version</key>
    <!-- 版本号 -->
    <string>5.3.2</string>
    <key>kind</key>
    <string>software</string>
    <key>title</key>
    <!-- 安装app时的提示信息 -->
    <string>X5 App download</string>
   </dict>
  </dict>
 </array>
</dict>
</plist>

# iOS App Signer
This is an app for OS X that can (re)sign apps and bundle them into ipa files that are ready to be installed on an iOS device.

Supported input types are: ipa, deb, app, xcarchive

Usage
------
This app requires Xcode to be installed, it has only been successfully tested on OS X 10.11 at this time.

You need a provisioning profile and signing certificate, you can get these from Xcode by creating a new project.

You can then open up iOS App Signer and select your input file, signing certificate, provisioning file, and optionally specify a new application ID and/or application display name.

<a href="https://paypal.me/DanTheMan827" class="donate"><img src="http://dantheman827.github.io/images/donate-button.svg" height="44" alt="Donate"></a>

Thanks To
------
[maciekish / iReSign](https://github.com/maciekish/iReSign): The basic process was gleaned from the source code of this project.

 

      1.   Input File                   :   拖入重签名 ipa文件,会自动生成路径 
      
      2.  Signing Certificate    :      选择重签名证书,请确保证书已被添加. (双击证书即可)
      
      3.  Provisioning Profile   :    选择重签名描述文件,请确保证书已被添加. (双击.mobileprovision文件即可。切勿选择 Re-Sign Only ，无效。)
      
      4、点击Start,等待生成新的ipa文件,根据提示保存.
  

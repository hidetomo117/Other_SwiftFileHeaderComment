# Swiftファイルのヘッダーコメントをカスタマイズする方法

1. 「IDETemplateMacros.plist」を生成

2. 以下を貼り付け
```IDETemplateMacros.plist
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
  <key>FILEHEADER</key>
  <string>
//  ___FILENAME___
//  ___TARGETNAME___
//</string>
</dict>
</plist>
    ```

3. 以下のディレクトリに配置
<ProjectName>.xcodeproj/xcshareddata/IDETemplateMacros.plist

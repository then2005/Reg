<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
    <key>PayloadType</key>
    <string>Configuration</string>
    <key>PayloadVersion</key>
    <integer>1</integer>
    <key>PayloadIdentifier</key>
    <string>com.example.networkspeed</string>
    <key>PayloadUUID</key>
    <string>f26a37ec-1c41-4c6c-a7f4-4f31000abcd9</string>
    <key>PayloadDisplayName</key>
    <string>Tăng tốc 4G DNS</string>
    <key>PayloadDescription</key>
    <string>Thiết lập DNS nhanh hơn để tăng độ phản hồi khi dùng 4G</string>
    <key>PayloadOrganization</key>
    <string>Thén</string>
    <key>PayloadContent</key>
    <array>
        <dict>
            <key>PayloadType</key>
            <string>com.apple.dnsSettings.managed</string>
            <key>PayloadVersion</key>
            <integer>1</integer>
            <key>PayloadIdentifier</key>
            <string>com.example.networkspeed.dns</string>
            <key>PayloadUUID</key>
            <string>a1b2c3d4-5678-90ab-cdef-1234567890ab</string>
            <key>PayloadDisplayName</key>
            <string>DNS Settings</string>
            <key>DNSSettings</key>
            <dict>
                <key>ServerAddresses</key>
                <array>
                    <string>1.1.1.1</string>
                    <string>1.0.0.1</string>
                </array>
            </dict>
            <key>ServiceType</key>
            <string>Cellular</string>
        </dict>
    </array>
</dict>
</plist>

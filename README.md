# VpnStatus
Windows Forms app with a system tray icon indicating VPN connection status:

![example image](readme-example.png)

Configure which VPN is monitored and how often network connections are polled:

    <appSettings>
      <!-- the name of your VPN connection in Control Panel's Network Connections -->
      <add key="VpnName" value="your.vpn.name" />

      <!-- how often to query network connections to check vpn status -->
      <add key="IntervalToPollMs" value="3000" />
    </appSettings>

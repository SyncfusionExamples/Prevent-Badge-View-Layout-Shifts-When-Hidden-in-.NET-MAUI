# Prevent-Badge-View-Layout-Shifts-When-Hidden-in-.NET-MAUI

This sample demonstrates how to prevent layout shifts in the Badge View when hidden in a .NET MAUI application

## Sample

```xaml
    <HorizontalStackLayout Spacing="20" HorizontalOptions="Center" VerticalOptions="Center">

        <core:SfBadgeView BadgeText="0">
            <core:SfBadgeView.Content>
                <Image Source="facebook.png" WidthRequest="50" HeightRequest="50"/>
            </core:SfBadgeView.Content>
            <core:SfBadgeView.BadgeSettings>
                <core:BadgeSettings BadgeAlignment="Center" AutoHide="True"/>
            </core:SfBadgeView.BadgeSettings>
        </core:SfBadgeView>

        <core:SfBadgeView BadgeText="5">
            <core:SfBadgeView.Content>
                <Image Source="instagram.png" WidthRequest="50" HeightRequest="50"/>
            </core:SfBadgeView.Content>
            <core:SfBadgeView.BadgeSettings>
                <core:BadgeSettings BadgeAlignment="Center" AutoHide="True"/>
            </core:SfBadgeView.BadgeSettings>
        </core:SfBadgeView>

        <core:SfBadgeView BadgeText="0">
            <core:SfBadgeView.Content>
                <Image Source="gmail.png" WidthRequest="50" HeightRequest="50"/>
            </core:SfBadgeView.Content>
            <core:SfBadgeView.BadgeSettings>
                <core:BadgeSettings BadgeAlignment="Center" AutoHide="True"/>
            </core:SfBadgeView.BadgeSettings>
        </core:SfBadgeView>

        <core:SfBadgeView BadgeText="10">
            <core:SfBadgeView.Content>
                <Image Source="x.png" WidthRequest="50" HeightRequest="50"/>
            </core:SfBadgeView.Content>
            <core:SfBadgeView.BadgeSettings>
                <core:BadgeSettings BadgeAlignment="Center" AutoHide="True"/>
            </core:SfBadgeView.BadgeSettings>
        </core:SfBadgeView>

    </HorizontalStackLayout>
```

## Requirements to run the demo

To run the demo, refer to [System Requirements for .NET MAUI](https://help.syncfusion.com/maui/system-requirements)

## Troubleshooting:
### Path too long exception

If you are facing path too long exception when building this example project, close Visual Studio and rename the repository to short and build the project.

## License

Syncfusion has no liability for any damage or consequence that may arise from using or viewing the samples. The samples are for demonstrative purposes. If you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion's samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion's samples

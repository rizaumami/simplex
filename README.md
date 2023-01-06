# SimpleX

SimpleX is a simple UnleashX skin.

![SimpleX preview.](simplex.gif)

## How to install

1. Skins folder can be directly copied to UnleashX folder on ogxbox.

2. [Config.xml](UnleashX/Config.xml) need some treatment before use.
  Because there is no consensus where to put applications on ogxbox. Is it in `C:\Apps`, ` E:\Apps`, `C:\Applications`, `E:\Applications`, `C:\Dash`, `E:\Dash`, `C:\Dashboard`, `E:\Dashboard`, etc....

    SimpleX using `E:\Applications` and `E:\Dashboards`. These need to be replaced with the actual paths in ogxbox. \
    Just edit `Config.xml` on your favourite text editor and do some sort of "find & replace".

    If your paths are `E:\Apps` and `E:\Dash`, on Linux you can use the following commands:

    ```bash
    sed -i 's/E:\\Dashboards/E:\\Dash/g' Config.xml
    sed -i 's/E:\\Applications/E:\\Apps/g' Config.xml
    ```

3. Transfer Skins folder and `Config.xml` into UnleashX folder on the ogxbox.

4. Go to Skins selection, choose SimpleX, then reboot and hope nothings bad happens ;).

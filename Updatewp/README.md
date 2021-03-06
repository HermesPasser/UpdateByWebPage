# UpdateByWebPage

Update system for ruby programs that checks on a page specifies whether updates are available.

## How use

### Put the rb files in the project's folder, preferably in a subfolder
![alt tag](https://2.bp.blogspot.com/-775aV1ojvd8/WPfWRE-7gJI/AAAAAAAAHGI/5pkLoTCFBEYmECV-FFP1nF9-255v0ZhkACLcB/s1600/1.png)

### Link the updatewp.rb in your project.
![alt tag](https://1.bp.blogspot.com/-xzuXo8WtkCs/WPfWQ7LQy8I/AAAAAAAAHGA/xHEAUkRm54I1RfvVOgIJPA9WB2Hr5qzhgCLcB/s1600/2.png)

### Create a page or document with the text below inside.
*updater[index,version,download_url]* <br />

**index**- *to differentiate from other projects on the same page (it is recommended that each be on a separate line)* <br />
**version** - *version of the project in download_url, for the updater to know if the pc version is equivalent or superior* <br />
**download_url** - *download link of updated project (it is recommended that the project be wrapped in .zip)* <br />
![alt tag](https://3.bp.blogspot.com/-VYDMe8tf0uA/WPfWRFYNgII/AAAAAAAAHGE/3wd-ge-IN9Y0Wn7YYAonEyeTRi0v9VXogCLcB/s1600/3.png)

### Now all you need to do is program.
![alt tag](https://4.bp.blogspot.com/-FtYawbmwUUU/WPfWRCJm5mI/AAAAAAAAHGM/HK2iZVY-PPsrPMS9Lwm8XUR_xh144T6LACLcB/s1600/4.png)

## A tiny doc

**Hermes::Update::ByWebPage** => *string id, float version, string url*

**bool update** => *string directory (default "")*<br />
returns true if the operation has sucesfully and false if not.

**bool update_is_avaliable**<br />
returns true if an update is available and false if not.

**string get_update_link**<br />
returns the download link of update file.

![alt tag](https://1.bp.blogspot.com/-_jpb79jbgPA/WPfWRvqzcBI/AAAAAAAAHGQ/HkUY_ZX6-uI2S7wicCePDFGMeWswKGoegCLcB/s1600/5.png)

All working well.

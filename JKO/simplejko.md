# INSTRUCTIONS

* Open the training in your browser.
* Press the F12 key when your class is fully loaded. This will open the developer tools.
* Click on the Console tab of the developer tools window.
* Paste the following code in the text box at the bottom of the console tab.
* Either manually click on the green Play arrow or hold CTRL and press ENTER.

----

*Make sure the frame selection is "Top".*
![image](https://user-images.githubusercontent.com/7216612/235476339-b7819652-0366-4ab5-81f2-3bb829f29f43.png)

```
API_1484_11.SetValue('cmi.completion_status','completed');
if (document.getElementsByName("courseheader").item(0).contentDocument.getElementById("c")) {
  document.getElementsByName("courseheader").item(0).contentDocument.getElementById("c").submit()
};
```

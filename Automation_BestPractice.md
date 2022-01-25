# Web UI automation(Selenium)
     - If report error "element not interactable": maybe there is not only one unique element in the web page by your locate method
     - To verify the radio button or checkbox status, we can use is_selected()
     - If there is new tab generated during your testing, and you want to verify something on the new tab website. You should get current window handle and switch to the handle to operation on that site.
     - Want to know element displayed or not, we can use is_displayed()
     - If want to get css properties, we can use value_of_css_property()
     - If want to verify form submit message like "Pleaes fill out this field." which cannot be located by selenium, you should use this method driver.find_element().get_attribute("validationMessage")
     - If want to get the tooltip, two method: 
           - attribute "title": not all component have this attribute
           - use Actions package to move to element have pause, perform, then get text
           - for github notification, it have atrribute aria-label, this contains the tooltip
           - it seems it is hard to verify tooltip displayed by selenium because there is no locator for the tooltip text
     - If IsSelected() function not work due to not refresh, we can try to get the control(like checkbox, radio button) "checked"(or other meaningful) attribute ==> assertIsNone()

# API autmomation
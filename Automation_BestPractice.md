# Web UI automation(Selenium)
     - If report error "element not interactable": maybe there is not only one unique element in the web page by your locate method
     - To verify the radio button or checkbox status, we can use is_selected()
     - If there is new tab generated during your testing, and you want to verify something on the new tab website. You should get current window handle and switch to the handle to operation on that site.
     - Want to know element displayed or not, we can use is_displayed()
     - If want to get css properties, we can use value_of_css_property()

# API autmomation
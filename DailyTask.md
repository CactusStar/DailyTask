# Daily Task
The purpose is set goals for everyday to make sure learning on schedule
## 2022.1.13
 ## Web UI automation
      - locate element by link text: Done(Pull request, issues, marketplace, explore): this is used for the element that you don't want to locate it by xpath but multiple element have the same classes
      - verify drop downlist
         - static dropdown list: Done(Through the new component dropdown list)
         - dynamic dropdown list: Not find this kind of list in github website
      - verify popup dialog: Done(This is not a new iframe but a popup dialog through click the profile related things)

## 2022.1.14
 ## Web UI automation
    Design two cases in Issues page
    - Verify all the controls in the Issues page
    - Verify select Assigned will have correct message display if currently no issue assigned to this account
 ## API automation test
    Read document:
    -https://testerhome.com/topics/8200
    -https://testerhome.com/topics/17986

## 2022.1.17
 ## Web UI automation
    Design two cases in new repository page
    - Verify the button/checkbox/Radio button status
    - Verify click link result and cancel button link status
 
 ## API automation test
    Familiar with golang net/http package

## 2022.1.18
 ## Web UI automation
    Design two cases in new repository page
    - Click "learn more" will jump to a new page
    - Check Choose a license will have additional content display
 ## API automation test
    - response data from string to json convert
    - post package get request
    - Based on get request, add a common functional named verify get request

## 2022.1.19
 ## Web UI automation
    Design two cases in Marketplace page
    - Verify the tree items under Types
    - Verify click explore for free, will navigate to another page, there is a free button and if closed will back
 ## API automation test
    - DB data prepare
    - read DB data
    - response verification

## 2022.1.20
 ## Web UI automation
    - Take a common function out of each page utilities for load data from each page asset json file
    - Take the URL part out of the ini file due to different page have different requirement, it can be put in eacch json asset data
    - Take page utilities, common action, data load out of each case to be a common function for each page
## API autmation test
    - Fill in the fake code and can run without error for one single verification

## 2022.1.21
 ## Web UI automation
    - Design two case about notification page
    - try to see if emoji can be verified or not
 ## API automation test
    - Add some special field like status code in the generate string part

## 2022.1.24
 ## Web UI automation
    - Design 1-2 case about the color verification

 ## API automation test
    - empty for today

## 2022.1.25
 ## Web UI automation
    - Design 2 case 
 ## API automation test
    - Investigate Fiddler, make sure Jmeter login github can work

## 2022.1.26
 ## Web UI automation
    - Design 1-2 cases
 ## API automation test
    - Try post method coding

## 2022.1.27 
 ## Web UI automation
    - will stop from today to focus on API test(no matter manual or auto)
    - will restart for daily test case design once API test is cleared
 ## API test
    - Investigate post method for the need login website by Jmeter
    - Investigate the usage of Fiddler

## 2022.2.8
 ## API test
    - learn the usage of Newman
    - Try run collection cases with assertion
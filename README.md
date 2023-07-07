# The Objective-C-Plus-Plus UDL
[![Version](https://img.shields.io/badge/version-2023--06--16-brightgreen)](https://github.com/skadomsky/Objective-C-Plus-Plus/)<br />
User Defined Languages (UDL) is a feature of [Notepad++ editor](https://notepad-plus-plus.org/), allowing user to define syntax 
highlights / folding rules of any programming languages. This UDL gives highlights on some fundamental classes in Cocoa, keywords in C++/
Objective-C, and escape characters in Objective-C++ programming languages.
<br />
<br />Please refer to [Notepad++ Offical UDL Collection Repository](https://github.com/notepad-plus-plus/userDefinedLanguages) 
for more infomation of UDLs. You can also find this UDL avaliable [in this repository](https://github.com/notepad-plus-plus/userDefinedLanguages/blob/master/UDLs/Objective-C%2B%2B_byLattHsiang.xml).

## Usage
0. Download the [released raw file](https://github.com/skadomsky/Objective-C-Plus-Plus/release/). <br/>
1. Launch Notepad++, click 'Language' on toolbar, then go to 'User Defined Language', and select 'Define your language...'. <br />
2. Click 'Import...', select the UDL in the popped up window. <br />
3. You can specify your highlights / folding rule in User-Defined window. When all your works done, click the 'x' button on the upper right side of the window. <br />
4. Push 'Language' button again, you will find 'Objective-C++' option on the down side of 'User Defined Language' menu. Choose it, Notepad++ will apply these highlights
/ folding rules immediately.

## Enhancement
· The UDL is still in need of more highlight rules for Cocoa/UIKit classes. Obviously we can't import all Cocoa/UIKit classes (for its huge size and rich implementation on almost everything) We suggest to add classes used in a high frequency (for example, `NSString` is a good class to add) This could contribute to a better experience while editing Objective-C++ file for common cross-platform development. <br />
· Theme adoptation. This UDL has been tested well under the default light and dark theme. You can fork this repository to recreate your
own UDL file for your unique themes. The UDL files you made for different themes could be uploaded to [upstream](https://github.com/notepad-plus-plus/userDefinedLanguages). It's OK for you to add a duplicate to this repo by submitting a PR.

---
title: Overview
page_title: DataEntry | RadDataEntry
description: This article describes the purpose of the DataEntry Control.
slug: winforms/dataentry
tags: dataentry
published: True
position: 0
previous_url: dataentry-overview
---

# DataEntry

__RadDataEntry__ provides an easy way to display and edit arbitrary business objects in a form layout. The built-in editors are generated by default, so that a fully operational CRUD support may be achieved with a single line of code - just binding to the business object or to a collection of objects. In order to further enhance __RadDataEntry__, it can be used in combination with [RadBindingNavigator]({%slug winforms/bindingnavigator%}) or any other collection navigation control.

__RadDataEntry__ control generates various editors depending on the type of property that should be editing:

* __RadTextBox__ for string properties.

* __RadCheckBox__ for Boolean.

* __RadDateTimePicker__ for dates.

* __RadDropDownList__ for enumerations. 

* __RadColorBox__ for Color.

* __PictureBox__ for Image.

In addition __RadDataEntry__ allows manual setting and customization of editors and their layouts via the standard for windows forms practices. It is highly customizable, allowing the user to modify the default look in easy and intuitive manner.

>caption Figure 1: RadDataEntry
![dataentry-overview 001](images/dataentry-overview001.png)

# See Also

 * [Structure]({%slug  winforms/dataentry/control-element-structure%})
 * [Getting Started]({%slug  winforms/dataentry/getting-started%})
 * [Properties, events and attributes]({%slug  winforms/dataentry/properties,-events-and-attributes%})
 * [Themes]({%slug winforms/dataentry/themes%})
 * [Change the editor to RadDropDownList]({%slug  winforms/dataentry/how-to/change-the-editor-to-a-bound-raddropdownlist%})
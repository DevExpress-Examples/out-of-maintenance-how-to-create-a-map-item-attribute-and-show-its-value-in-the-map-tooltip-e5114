<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128571299/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E5114)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/UseMapItemAttribute/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/UseMapItemAttribute/MainWindow.xaml))**
<!-- default file list end -->
# How to create a map item attribute and show its value in the map tooltip 


<p>This example demonstrates how to show an area value for the  triangle item in the map tooltip using the map item's attribute. </p><p>To accomplish  this task,  do the following:</p><p>- Create a map triangle using the <a href="http://documentation.devexpress.com/#WPF/clsDevExpressXpfMapMapPolygontopic"><u>MapPolygon</u></a> item;<br />
- Create a <a href="http://documentation.devexpress.com/#WPF/clsDevExpressXpfMapMapItemAttributetopic"><u>MapItemAttribute</u></a> object using the <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapMapItem_Attributestopic"><u>MapItem.Attributes</u></a><u> </u>property; </p><p>- Specify the attribute name, type, and value in corresponding properties (<a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapMapItemAttribute_Nametopic"><u>MapItemAttribute.Name</u></a>, <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapMapItemAttribute_Typetopic"><u>MapItemAttribute.Type</u></a>, and <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapMapItemAttribute_Valuetopic"><u>MapItemAttribute.Value</u></a>);<br />
- Specify the triangle area attribute using the <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapMapItem_ToolTipPatterntopic"><u>MapItem.ToolTipPattern</u></a> property.<br />
 <br />
To enable the map tooltip, set the <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapMapControl_ToolTipEnabledtopic"><u>MapControl.ToolTipEnabled</u></a> property to <strong>true</strong>.  </p>

<br/>



<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/WpfMapControl_ShapeTitleOptions/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/WpfMapControl_ShapeTitleOptions/MainWindow.xaml))**
<!-- default file list end -->
# How to customize the appearance of a map shape title


<p>This example shows how to change the appearance of a map's dot  title  using  its template.      </p><p>To do this, it is necessary to create a <strong>System.Windows.DataTemplate</strong> object that specifies the appearance of a map dot and assign it to the <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapShapeTitleOptions_Templatetopic"><u>ShapeTitleOptions.Template</u></a> property. </p>


<h3>Description</h3>

To do this.<br />1. Create a <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapShapeTitleOptionstopic">ShapeTitleOptions</a> object;<br />2. Specify its&nbsp;<a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapShapeTitleOptions_Patterntopic">Pattern</a> and&nbsp;<a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapShapeTitleOptions_Templatetopic">Template</a> properties.<br />3. Assign the object to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapMapShape_TitleOptionstopic">MapShape.TitleOptions</a> property of the map shape.

<br/>



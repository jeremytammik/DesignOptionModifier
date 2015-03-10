# DesignOptionModifier
Stand-alone executable using UI Automation to read and modify Revit Design Options, described in detail by
[The Building Coder](http://thebuildingcoder.typepad.com).

Revitalizer says:

Here is a tool for switching between DesignOptions.

This is a stand-alone application that gets and sets DesignOptions.

Since it works very, very slowly, it is not too useful for everyday professional work.

<p align="center">
<img src="img/DesignOptionModifier_main_form.png"/>
</p>

It just reads and sets the ComboBox, but reading the items requires expanding them all first, which costs several seconds each time.

<p align="center">
<img src="img/DesignOptionModifier_revit.png"/>
</p>

To test it, just start a Revit project containing a few DesignOptions.

Then start the DesignOptionModifier program.

You can drive Revit from outside this way.

Please also note that DesignOption groups are displayed in the DesignOptionModifier program listbox as well.

As far as I know, there is no way to check if entries are greyed out in the Revit combobox.


## Authors

[Revitalizer](http://www.acadgraph.de) and Jeremy Tammik, [The Building Coder](http://thebuildingcoder.typepad.com), Autodesk Inc.


## License

This sample is licensed under the terms of the [MIT License](http://opensource.org/licenses/MIT). Please see the [LICENSE](LICENSE) file for full details.

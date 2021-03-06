# XamarinFormsTemplate

This is source code of newest Xamarin Native cross-platform app with PCL core project Template made by Japan Xamarin User Group.

# How to get

### Option 1: Clone the Repository (Recommended)

Clone the project on the following location directly:

`%USERPROFILE%\Documents\Visual Studio 2017\Templates\ProjectTemplates\Visual C#`

That is, on a command prompt, you can install the template by the following commands:

```
cd "%USERPROFILE%\Documents\Visual Studio 2017\Templates\ProjectTemplates\Visual C#"
git clone https://github.com/ytabuchi/XamarinNativePCLTemplate.git
```

After the first installation, you can of course update your copy by `git pull` and you feel it's easier to update the templates than the other option.

### Option 2: Download the ZIP

- Download XamarinFormsTemplate-master.zip file from [GitHub](https://github.com/ytabuchi/XamarinNativePCLTemplate/archive/master.zip)
- Extract the zip file
- Move the extracted `XamarinNativePCLTemplate-master` folder to the following location:
`%USERPROFILE%\Documents\Visual Studio 2017\Templates\ProjectTemplates\Visual C#`

# How to User

Select `New Project > Visual C# > "Xamarin Native App (JXUG)(PCL)"` and `OK`

![New Project](Xamarin Native PCL.png)

# How to maintenance

`MyTemplate.vstemplate` located in Root folder is a Master file that is specify each child projects.
In each projects folder, there are `MyTemplate.vstemplate` files. They are the template setting files for each projects.

If Xamarin.Forms will be updated, you can just change the version numbers of each `MyTemplate.vstemplate` files

There are some macros in the template files. Please see [Microsoft document](https://docs.microsoft.com/ja-jp/visualstudio/ide/template-parameters) for each meaning.

https://docs.microsoft.com/en-us/learn/paths/build-web-apps-with-blazor/
Microsofts readme from original repo further down
<hr>

## dotnet new blazorserver -f net6.0 
The -f option forces the application to be built with the framework version .NET 6

## dotnet new razorcomponent -n Todo -o Pages
creates a new file called Todo in the Pages-folder (-n name, -o output)
Razor component file names require a capitalized first letter.

<hr>

The @page directive: This directive provides a route template to Blazor. At runtime, Blazor locates a page to render by
matching this template to the URL that the user requested. In this case, it might match a URL of the form http://yourdomain.com/index.

The @code directive: This directive declares that the text in the following block is C# code. You can put as many code 
blocks as you need in a component. You can define component class members in these code blocks and set their 
values from calculation, data lookup operations, or other sources. In this case, the code defines a single component 
member called welcomeMessage and sets its string value.

Member access directives: If you want to include the value of a member in your rendering logic, use the @ symbol
followed by a C# expression, such as the name of the member. In this case, the @welcomeMessage directive is used to
render the value of the welcomeMessage member in the <p> tags.

<hr>

## Contributing
This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the Microsoft Open Source Code of Conduct. For more information see the Code of Conduct FAQ or contact opencode@microsoft.com with any additional questions or comments.

Legal Notices
Microsoft and any contributors grant you a license to the Microsoft documentation and other content in this repository under the Creative Commons Attribution 4.0 International Public License, see the LICENSE file, and grant you a license to any code in the repository under the MIT License, see the LICENSE-CODE file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries. The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks. Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all other rights, whether under their respective copyrights, patents, or trademarks, whether by implication, estoppel or otherwise.

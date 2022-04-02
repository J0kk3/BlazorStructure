https://docs.microsoft.com/en-us/learn/paths/build-web-apps-with-blazor/

<hr>

dotnet new blazorserver -f net6.0 
The -f option forces the application to be built with the framework version .NET 6

dotnet new razorcomponent -n Todo -o Pages
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

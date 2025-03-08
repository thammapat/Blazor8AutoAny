# Best template for .net 8 Blazor web app auto render mode. 
### For apps that adopt an interactive client-side (WebAssembly or Auto) rendering mode and enable the render mode for the entire app via the Routes component:
*Reference: https://learn.microsoft.com/en-us/aspnet/core/blazor/components/render-modes?view=aspnetcore-8.0*

    1. Place or move the layout and navigation files of the server app's Components/Layout folder into the .Client project's Layout folder. Create a Layout folder in the .Client project if it doesn't exist.
    2. Place or move the components of the server app's Components/Pages folder into the .Client project's Pages folder. Create a Pages folder in the .Client project if it doesn't exist.
    3. Place or move the Routes component of the server app's Components folder into the .Client project's root folder.
    4. file App.razor located at ServerProject/Components
    5. file Error.razor located at ServerProject/Pages
    

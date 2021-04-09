# Deploy an ASP.NET web app to Azure App Service.
Prerequisites
- An Azure account with an active subscription. Create an account for free.
- Visual Studio Code.
- The Azure Tools extension.

# Steps
1- Create a new folder named MyFirstAzureWebApp, and open it in Visual Studio Code.
- mkdir MyASP-AzureWebApp
- CD MyASP-AzureWebApp

2- Open the Terminal window, and create a new .NET web app using the dotnet new webapp command.
- dotnet new webapp -f netcoreapp3.1

3- From the Terminal in Visual Studio Code, run the application locally using the dotnet run command.
- Dotnet run
- Open a web browser, and navigate to the app at https://localhost:5001.
- You'll see the template ASP.NET Core 3.1 web app displayed in the page.

4- Create and Push local repos int GitHub

 Create a Repos in GitHub called MyASP-AzureWebApp and push your local repos's code into it.

- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/A-Sandhu/MyASP-AzureWebApp.git
- git push -u origin main
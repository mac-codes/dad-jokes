# dad-jokes

I am trying to recreate an application I have done before, but in C#. I already had problems seting up my environment and now I am trying to figure out how to run it on a website. wish me luck.


thanks chatgpt:

- Web Hosting: You can use web hosting services like Azure App Service, AWS Elastic Beanstalk, or any other web hosting provider that supports C#/.NET applications.
    - I cannot use GH-pages so I have to use Monog DB or heroku which I have not used in a year almost and never understood in the first place. I will write notes and not be productive :/
- Virtual Private Server (VPS): You can set up a VPS with a cloud provider or a hosting company and install the necessary software to run your C# application.
- .NET Runtime: Ensure that the target environment has the appropriate .NET runtime installed. Depending on your application, you may need .NET Core or .NET Framework.
- Code Dependencies: For your C# application to communicate with the ihazdadjokes API, you might need to include HTTP client libraries (e.g., HttpClient) that are included with the .NET framework.
- API Key: Make sure you have an API key for the ihazdadjokes API, as you'll need it to make requests to their service. Keep this key secure and never expose it publicly in your code.
- Networking: Ensure that your hosting environment allows outbound internet access to make API requests to ihazdadjokes.
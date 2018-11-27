# SeleniumChromeDriverBase

Basic working C# Visual Studio 2017 Project that uses Selenium Driver (ChromeDriver) to automate Chrome browsing from C#.

This includes the "ChromeDriver.exe" needed for using the Selenium Chrome Driver.

ChromeDriver.exe is in the \ChromeDriver folder of the project and is copied in the output bin Release or Debug folder, when building the application.


PhantomJsTest2.zip contains a simple project that searches for "Forex" on Google search engine and tries to get all the http and https links returned by Google, excluding "garbage links" ; It also parses the pages links at the bottom of the web page and clicks on "Page 2".


PhantomJsTest3-Socks5-Proxy.zip contains a simple project that connects to a remote http website through a socks5 proxy. The Socks5 proxy must be installed on localhost port 9150 or you can use a remote socks5 proxy but in this case you must change the IP address of the proxy and the port in the source code, and then you have to compile the application.

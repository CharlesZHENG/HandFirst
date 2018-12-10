```
public static class GlobalConfig
{
    public static WebSite WebSite = (WebSite)Enum.Parse(typeof(WebSite), System.Configuration.ConfigurationManager.AppSettings["WebSite"].ToString());
}
public enum WebSite
{
    XBrick
}
```

# elmahex
This is an old elmah with some new implementation

The initial code is drived from ELMAH-1.2-sp2 code
https://code.google.com/p/elmah/wiki/Downloads

# Requirement
Newtonsoft.Json.dll (.net 3.5)

# New features
- Multiple applications error log support added
- Show the Exception.Data in error detail page


# Syntax
- Elmah.ErrorSignal.Raise(exception);
- Elmah.ErrorSignal.Raise(exception, applicationName);
- Elmah.ErrorSignal.Raise(httpContext);
- Elmah.ErrorSignal.Raise(Exception, httpContext, applicationName);

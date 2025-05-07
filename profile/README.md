# URI Templates Time

[URI Templates Time](https://github.com/uri-templates-time/specification) is a standard for encoding times within a formatted string, typically the
names of data files or images.  For example, the file `2024-09-17.dat` is understood using the URI template `$Y-$m-$d.dat`
to represent the data collected on September 17, 2024.  While this simple example could be handled with the Unix
date command, this specification supports various odd cases in Space Physics data handling.

This is a repository of tools and tests for URI templates. Native reference implementations are available in Java, JavaScript, and
Python.

Implementations of the specification can be used in:

| Language | URL |
| ------------- | -------- |
| Java     | [repository](https://github.com/uri-templates-time/uri-templates/tree/master/UriTemplatesJava) [docs](https://cottagesystems.com/hapi/uri_templates/doc/) |
| JavaScript | [repository](https://github.com/uri-templates-time/uri-templates/tree/master/UriTemplatesJavaScript) |
| Python | [repository](https://github.com/uri-templates-time/uri-templates/tree/master/UriTemplatesPython) |
| IDL | Native code in progress (Java bridge could be used instead). |
| MATLAB | No native code planned, but [MATLAB/Java](https://www.mathworks.com/help/matlab/using-java-libraries-in-matlab.html) interface could be used. |

A nearly complete implementation is used in [Autoplot](https://autoplot.org/).

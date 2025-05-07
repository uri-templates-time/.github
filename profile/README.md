# URI-templates

URI-templates are what we call the convention for encoding times within a formatted string, typically the
names of data files or images.  For example the file 2024-09-17.dat is understood using the URI template $Y-$m-$d.dat
to represent the data collected on September 17, 2024.  While this simple example could be handled with the unix
date command, this specification supports various odd cases found in Space Physics data handling.

This is a repository of tools and tests for URI templates.  Reference implementations are provided for Java, JavaScript, and
Python.

Specification: https://github.com/uri-templates-time/specification

Here is a list of implementations of the specification:

| Name<br>Notes | Language | URL |
| ------------- | -------- | --- |
| URI_Templates Java<br>reference implementation | Java     | https://github.com/uri-templates-time/uri-templates/tree/master/UriTemplatesJava <br> https://cottagesystems.com/hapi/uri_templates/doc/ |
| Autoplot Aggregation<br>nearly complete for spec | Java  | https://autoplot.org/ |
| URI_Templates JavaScript | JavaScript | https://github.com/uri-templates-time/uri-templates/tree/master/UriTemplatesJavaScript |
| URI_Templates Python | Python | https://github.com/uri-templates-time/uri-templates/tree/master/UriTemplatesPython |
| URI_Templates IDL | IDL | Coming soon, Java bridge could be used as well. |
| URI_Templates Matlab | Matlab | This could be done as well, Java bridge could be used as well. |

Note this project is not associated with https://github.com/uri-templates.  This was once located at https://github.com/hapi-server/uri-templates.



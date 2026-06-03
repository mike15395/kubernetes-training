A ConfigMap allows us to define application-related data. A ConfigMap decouples
the application data from the application so that the same application can be ported
across different environments. It also provides a way to inject customized data into
running services from the same container image.
ConfigMaps can be created through a literal value or from a file or all the files in a
directory. Note that the primary data we stored in ConfigMaps is for non-sensitive
configuration, for example, config files or environment variables.
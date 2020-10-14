```
{
    "plugin": {
        "name": "filesystem_friendly_plugin_name",
        "version": "1.2.3",
        "description": "My plugin",
        "filelist": "filelist.txt",
        "os": "all",
        "installmanifest": {
            "file1": "cfgfile",
            "file2": "bin"
        }
    }
}
```

= Plugin =
 * name:  A file system friendly name
 * version: A version
 * dedscription:  Description of the plugin
 * filelist: File name containing files within the archive (for packagers, etc.)
 * os: Operating system.  "all" for all, "linux", "windows", "os/2"
 * installmanifest:  special file handling for installers.  possible file attributes:  "cfgfile" - configuration file.  "bin" - binary executable
 

# Base Web Tomcat OpenJDK(eclipse-temurin) 8u345

Base Image For Web With Tomcat 9.0.68 Alpine

## Config

- **Web Root**  : /usr/local/tomcat/webapps/
- **Web Port**  : 80
- **Flag Path** : /flag

You can set your flag path by modify `/_file/flag.sh`

```bash
#!/bin/sh

# echo $FLAG > /flag
echo $FLAG > /for/yout/path/file

export FLAG=not_flag
FLAG=not_flag

rm -f /flag.sh
```
### kSentinel Core

The main kSentinel binary is primarily written in C++ and C. Follow these steps to run the binary:

- Open a root shell: `sudo su`
- Set the environment variable `KS_CONFIG_DIR`
```
export KS_CONFIG_DIR = /path/to/some/folder
```
- Create a config.yml file in the directory `KS_CONFIG_DIR`.
- Store the following values in config.yml
```
KS_AUTH_API: "http://127.0.0.1:8080/api/auth"
KS_KSCORE_API: "http://127.0.0.1:9000/api/kscore"
```
- Run the binary
```
./kSentinel --run
```


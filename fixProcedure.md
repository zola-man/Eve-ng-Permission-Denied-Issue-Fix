## Check if the file is executable

```bash
ls -l /opt/unetlab/wrappers/unl_wrapper

```

You should see something like:

```bash

-rwxr-xr-x 1 root root 12345 Jan  1  2024 /opt/unetlab/wrappers/unl_wrapper

```
If you see rw- or missing x, fix it with:

```bash

chmod +x /opt/unetlab/wrappers/unl_wrapper

```

Then try again.
This will fix it.

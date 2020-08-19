clog
====

Installation
------------

With [clib](https://github.com/clibs/clib):

```sh
clib install aperezdc/clog
```

Exmple
------

```c
#define CLOG_SHORT_MACROS 1

#include "clog.h"

int
main(int argc, char **argv)
{
    clog_init(NULL);

    cmessage("Message :]");
    cinfo("Some info");
    cwarning("Some warning");
    puts("Normal output");
    cdebug("Some debugging");
    cerror("Some error");

    return EXIT_SUCCESS;
}
```

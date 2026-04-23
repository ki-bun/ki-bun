# Hi there 👋
**I'm Kurt (he/they)** - I'm a student studying Computer Science. The code below is tested, if you're going to run it, just uncomment the free keyword to avoid memory leaks, I commented it for introduction purposes.
```c
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main() {
	char *s = "Kurt";
	char *name = malloc(4 * sizeof(char));

	for (int i = 0, n = strlen(s); i <= n; i++)
	{
		name[i] = s[i];
	}

	printf("I am %s\n", name);

	// free(name);
}
```

## More about me
- I'm developing a mobile application
- I use linux as my daily driver 
- I use vim as my default editor
- I survive on 4gb of RAM, HDD, and an old processor
- I use a custom ROM on my android device

[![My Skills](https://skillicons.dev/icons?i=arch,bash,c,git,github,kotlin,linux,md,py,vim)](https://skillicons.dev)

![Music](https://img.shields.io/badge/"Listening_to"-Shogeki-green?logo=spotify)


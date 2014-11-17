C-Programming
=============

C Programming



void mystrappend(char *s, char *p, char *a)
{
	/* add your code here. Leave this comment in your code */
	
	
	*a = *s;		// this line will copy the original string to the apended string 

	while (*a)			// go to the end of the screen
	*a++;

	while (*p != '\0')		// a letter will be added if the character is not NULL
	{
	*a = *p;
	*p++;
	*a++;
	}

	*a = '\0';
	
	}

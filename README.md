# week-1
week 1 submission
// C program to Open a File,Write in it, And Close the File

# include <stdio.h>
# include <string.h>

int main( )
{


	FILE *filePointer ;
	
	char data[50]
		= "git first assignment";


	filePointer = fopen("first.c", "w") ;
	

	if ( filePointer == NULL )
	{
		printf( "first.c file failed to open." ) ;
	}
	else
	{
		
		printf("The file is now opened.\n") ;
		

		if ( strlen ( dataToBeWritten ) > 0 )
		{
			

			fputs(dataToBeWritten, filePointer) ;
			fputs("\n", filePointer) ;
		}
		

		fclose(filePointer) ;
		
		printf("Data successfully written in file first.c\n");
		printf("The file is now closed.") ;
	}
	return 0;		
}
